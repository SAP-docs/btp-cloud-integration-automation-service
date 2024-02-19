<!-- loio22abc396ccb84d9081cb19aa46ee1717 -->

# Data Protection and Privacy

-   User IDs and email IDs would be stored in the Cloud Integration Automation service provider database against the subscription of an SAP BTP consumer subaccount name.
-   System and Tenants selected for an integration setup would be stored in the Cloud Integration Automation service provider subaccount to execute the workflow.
-   The logs would not store any user-related personal data.

-   The logs would be stored for 30 days in the Cloud Integration Automation service provider subaccount and would be deleted after a specific time.

-   Explicit deletion of a user ID or a transactional data as a self-service from Cloud Integration Automation service consumer subaccount is not provided, currently. Hence, you need to raise an explicit support request to the component **BC-INS-CIT-RT** to remove the complete transactional data \(status should be completed or terminated\) including the user IDs.

    The ticket must contain the User ID that needs to be removed, as well as the SAP BTP consumer subaccount name.


