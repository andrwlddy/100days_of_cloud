Azure SSPR 

How SSPR works...

The user initiates a password reset either by going directly to the password reset portal or by selecting the Can't access your account link on a sign-in page. The reset portal takes these steps:

Localization: The portal checks the browser's locale setting and renders the SSPR page in the appropriate language.
Verification: The user enters their username and passes a captcha to ensure that it's a user and not a bot.
Authentication: The user enters the required data to authenticate their identity. They might, for example, enter a code or answer security questions.
Password reset: If the user passes the authentication tests, they can enter a new password and confirm it.
Notification: A message is sent to the user to confirm the reset.
There are several ways you can customize the SSPR user experience. For example, you can add your company logo to the sign-in page so users know that they're in the right place to reset their password.



Recommendations
Enable two or more of the authentication reset request methods.
Use the mobile app notification or code as the primary method, but also enable the email or office phone methods to support users without mobile devices.
The mobile phone method isn't a recommended method because it's possible to send fraudulent SMS messages.
The security question option is the least recommended method because the answers to the security questions might be known to other people. Only use the security question method in combination with at least one other method.

Accounts associated with administrator roles
A strong, two-method authentication policy is always applied to accounts with an administrator role, regardless of your configuration for other users.
The security questions method isn't available to accounts that are associated with an administrator role.







## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
