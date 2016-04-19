# SparkPost

Only needed when you need to send mails.

There are two options to set up SparkPost:
* With a domain for the project
* Without an exisiting domain ==> via renuoapp.ch subdomain

**Note:**  
With the second option, you are only able to send mails from %app_name%.renuoapp.ch

*There should only be one sparkpost account per project. That means, that the master, develop & testing all use the same one.*

1. Go to https://app.sparkpost.com/sign-up/ and create a *new* account
2. Use the email sparkpost+%app_name%@renuo.ch
3. Use ```renuo generate-password``` to generate a secure password
4. Fill in the domain you plan to use, otherwise fill in %app_name%.renuoapp.ch
5. Note down the API-key, because it's only shown once!
4. You can check your key under: https://app.sparkpost.com/account/credentials
5. Validate your sending domain under https://app.sparkpost.com/account/sending-domains  
(SPF text record recommended)


For DNS setup see [Go Live](go_live.md)