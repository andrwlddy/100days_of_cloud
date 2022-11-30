Security Layers in a cloud environment


![defense-in-depth](https://user-images.githubusercontent.com/102994059/204687331-8c6efb81-8cb8-48c4-bec0-fe09ca1bdd7f.jpg)

## Introduction

☁️☁️☁️ (Why) A quick intro to azure security starts with the security layers. Below are specific examples with each layer!

At each layer, there are some common attacks that you'll want to protect against. The following list isn't all-inclusive, but it can give you an idea of how each layer can be attacked and what types of protections you might need.
•	Data layer: Exposing an encryption key or using weak encryption can leave your data vulnerable if unauthorized access occurs.

•	Application layer: Malicious code injection and execution are the hallmarks of application-layer attacks. Common attacks include SQL injection and cross-site scripting (XSS).

•	VM/compute layer: Malware is a common method of attacking an environment, which involves executing malicious code to compromise a system. After malware is present on a system, further attacks that lead to credential exposure and lateral movement throughout the environment can occur.

•	Networking layer: Unnecessary open ports to the internet are a common method of attack. These might include leaving SSH or RDP open to virtual machines. When these protocols are open, they can allow brute-force attacks against your systems as attackers attempt to gain access.

•	Perimeter layer: Denial-of-service (DoS) attacks often happen at this layer. These attacks try to overwhelm network resources, forcing them to go offline or making them incapable of responding to legitimate requests.

•	Policies and access layer: This layer is where authentication occurs for your application. This layer might include modern authentication protocols such as OpenID Connect, OAuth, or Kerberos-based authentication such as Active Directory. The exposure of credentials is a risk at this layer, and it's important to limit the permissions of identities. You also want to have monitoring in place to look for possible compromised accounts, such as logins coming from unusual places.

•	Physical layer: Unauthorized access to facilities through methods, such as door drafting and theft of security badges, can happen at this layer.





☁️☁️☁️ Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](https://www.linkedin.com/feed/update/urn:li:share:7003536077625901056/)
