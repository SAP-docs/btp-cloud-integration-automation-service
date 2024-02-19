<!-- loio484ec5f0a46e448a97c95fa83b4f6914 -->

# Create Instance in OAuth2 Service Plan

To create an instance in OAuth2 service plan for Cloud Integration Automation service:

1.  **Enable Cloud Foundry -** Ensure that you have enabled the Cloud Foundry. Else, choose your subaccount → *Enable Cloud Foundry* under *Cloud Foundry Environment*.
2.  **Create Space -** After Cloud Foundry is enabled, create space by choosing *Create Space* under the Cloud Foundry Environment tab or choose *Spaces* from left-side menu.
3.  **Create Instance -** 
    -   Choose *Service Marketplace* → *Cloud Integration Automation Service* → *Create*
    -   In the pop-up, choose plan *OAuth2*
    -   Choose *Cloud Foundry* as *Runtime Environment*

        > ### Note:  
        > Cloud Foundry in the dropdown would be witnessed only if Cloud Foundry is enabled.

    -   Provide an appropriate instance name and choose *Create*
    -   Choose *View Instance* from the pop-up or choose *Instances and Subscriptions* from the left-side menu

4.  **Create Service Key -** Choose *Create* under *Service Keys* and give an appropriate name in the Service Key Name field
    -   Choose *Create*
    -   Choose the options icon against the appropriate service key
    -   Choose view to get the credential details such as client ID and client secret

5.  Using the fetched client id and client secret, you can generate an OAuth JWT token and connect to Cloud Integration Automation service. To learn more, see [creating service keys](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/4514a14ab6424d9f84f1b8650df609ce.html).

