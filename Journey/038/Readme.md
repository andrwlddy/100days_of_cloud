Create an Azure website using the CLI 

☁️☁️☁️ Signing in using Az Login and creating a resource group 

    This is usually the first two steps, but for this sandboxed excercise, these were already done for us. So we will move past this. 
    
    
☁️☁️☁️ Creating variables for later commands (using export command)

    export RESOURCE_GROUP=learn-4161ebd3-0555-468b-963b-b36dce69b6c8
    export AZURE_REGION=centralus
    export AZURE_APP_PLAN=popupappplan-$RANDOM
    export AZURE_WEB_APP=popupwebapp-$RANDOM
    
    
  ![1](https://user-images.githubusercontent.com/102994059/217664392-b76896c6-1975-40ea-a437-c47a83756ba2.jpg)

    
☁️☁️☁️ Creating a appservice plan 

Appservice plans in azure -- Azure App Service enables you to build and host web apps, mobile back ends, and RESTful APIs in the programming language of your choice without managing infrastructure. It offers auto-scaling and high availability, supports both Windows and Linux, and enables automated deployments from GitHub, Azure DevOps, or any Git repo. Learn how to use Azure App Service with our quickstarts, tutorials, and samples.


   TO create an appservice plan, we used the az appservice plan create command with some extra options ... See the full command below
      
      az appservice plan create --name $AZURE_APP_PLAN --resource-group $RESOURCE_GROUP --location $AZURE_REGION --sku FREE
      
      
☁️☁️☁️ creating a web app 

    az webapp create --name $AZURE_WEB_APP --resource-group $RESOURCE_GROUP --plan $AZURE_APP_PLAN
    
    
☁️☁️☁️ Help from Github!

The final step is to deploy code from a GitHub repository to the web app. Let's use a basic PHP page available in the Azure Samples GitHub repository that displays "Hello World!" when it executes. Make sure to use the web app name you created.


    az webapp deployment source config --name $AZURE_WEB_APP --resource-group $RESOURCE_GROUP --repo-url "https://github.com/Azure-Samples/php-docs-hello-world" --branch master --manual-integration
    
    
☁️☁️☁️ View website contents with Curl command 

    curl $AZURE_WEB_APP.azurewebsites.net


![2](https://user-images.githubusercontent.com/102994059/217664407-d5553dde-181e-4c16-957a-d8f05256f916.jpg)

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
