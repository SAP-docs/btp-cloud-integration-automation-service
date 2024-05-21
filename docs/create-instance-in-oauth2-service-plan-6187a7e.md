<!-- loio6187a7e05c484249a4dcd011812f21b1 -->

# Create Instance in OAuth2 Service Plan

You can create an instance of Cloud Integration Automation service in the OAuth2 service plan using SAP BTP cockpit.



## Context

To enable services in SAP BTP, Cloud Foundry environment, you can create a service instance using either the SAP BTP cockpit or the Cloud Foundry command-line interface \(CLI\), and bind that instance to your application. A service instance is a single instantiation of a service running on SAP BTP. For more information, see [About Services](https://help.sap.com/docs/btp/sap-business-technology-platform/about-services).

The service instance of Cloud Integration Automation service scales dynamically according to usage; creating additional service instances that has no impact on the available resources. All service instances within the same organization share the same data.



## Procedure

1.  Navigate to your space in the SAP BTP cockpit.

2.  Choose *Service Marketplace* displayed under *Services*.

3.  Choose the *Cloud Integration Automation Service* tile.

4.  Choose *Create*.

5.  In the pop-up, choose plan *OAuth2*.

6.  Choose *Other* or *Cloud Foundry* as Runtime Environment.

    > ### Note:  
    > Cloud Foundry is displayed in the drop-down only if Cloud Foundry is enabled.

7.  Enter a suitable name for the instance.

8.  Choose *Create*. The newly created instance is displayed on the *Instances* page.

9.  You need a service key if you want to call the service API standalone without a UI, for example, from Postman. Follow the below steps to create a service key. This is an optional step.

    1.  On the *Instances* page, click the *Actions* icon of the created service instance.

    2.  Choose *Create Service Key*. You can create a service key with or without a certificate. A certificate is required when setting up an mTLS communication.

        -   Create a service key with certificate
            1.  In the *New Service Key* wizard, choose a name for your service key and specify the following parameters in JSON format:

                > ### Sample Code:  
                > ```
                > {
                >     "xsuaa": {
                >         "credential-type": "x509",
                >         "x509": {
                >             "key-length": 2048,
                >             "validity": 1,
                >             "validity-type": "YEARS"
                >         }
                >     }
                > }
                > ```

                > ### Note:  
                > The maximum validity of this certificate is one year \(defined in years, months, days, and so on\).

            2.  Choose *Create*.

        -   Create a service key without certificate
            1.  In the *New Service Key* wizard, enter a name for your service key.
            2.  Choose *Create*.


    3.  Using the fetched client id and client secret, generate an OAuth JWT token and connect to Cloud Integration Automation service. For more information, see [Creating Service Keys](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/4514a14ab6424d9f84f1b8650df609ce.html).



