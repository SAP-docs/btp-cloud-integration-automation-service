<!-- loio1508b4908a8f497fb3a34e97595aceec -->

# Identity Provider and Identity Management

For identity management and authentication, Cloud Integration Automation service relies on Identity Provider \(IdP\). Ensure that your IdP is configured in the customer subaccount that its subscriptions.

All requests handled by Cloud Integration Automation service subscriptions are authenticated against the identity provider of the consumer subaccount. Further, for Cloud Integration Automation service in the customer subaccount authorized against the role assignments specified.

You can interact with various features of the Cloud Integration Automation service by being available in the respective identity provider. You can replace the default SAP Cloud Platform Identity Authentication service with your corporate identity provider.

The users used in destinations of the target systems from consumer subaccount must be authenticated and authorized by the IdP configured in the target systems.

For more information about the concepts and the necessary configuration steps in the SAP BTP subaccount, see [Security Administration: Managing Authentication and Authorization](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/1ff47b2d980e43a6b2ce294352333708.html) in the SAP Business Technology Platform documentation.



