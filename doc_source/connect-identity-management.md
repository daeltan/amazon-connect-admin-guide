# Identity Management in Amazon Connect<a name="connect-identity-management"></a>

Before you set up your Amazon Connect instance, you should decide how you want to manage your Amazon Connect users\. You cannot change the option you select for identity management after you create the instance\. If you decide to change the option or directory you selected, you can delete the instance and create a new one\. When you delete an instance, you lose all configuration settings and metrics data for it\.

You can choose from one of the following supported identity management solutions supported in Amazon Connect:
+ **Store users with Amazon Connect**—Choose this option if you want to create and manage user accounts within Amazon Connect\. When you manage users in Amazon Connect, the user name and password for each user is specific to Amazon Connect\. Users must remember a separate user name and password to log in to Amazon Connect\.
+ **Link to an existing directory**—Choose this option to use an existing directory\. The directory must be associated with your account, set up in AWS Directory Service, and be active in the same Region in which you create your instance\. If you plan to choose this option, you should prepare your directory before you create your Amazon Connect instance\. For more information, see [Use an Existing Directory for Identity Management](directory-service.md)\.
+ **SAML 2\.0\-based authentication**—Choose this option if you want to use your existing network identity provider to federate users with Amazon Connect\. Users can only log in to Amazon Connect by using the link configured through your identity provider\. If you plan to choose this option, you should configure your environment for SAML before you create your Amazon Connect instance\. For more information, see [Configure SAML for Identity Management in Amazon Connect](configure-saml.md)\.