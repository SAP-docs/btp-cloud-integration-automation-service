<!-- loio3538ec51b1c84d1f8c564b339b60d9d1 -->

# Security Restrictions

-   The SAP BTP subaccount name provided in maintenance planner to invoke Cloud Integration Automation service must exist and must be subscribed to Cloud Integration Automation service already.

-   The user ID provided in maintenance planner or in Cloud Integration Automation service planning application to invoke Cloud Integration Automation service workflow must exist in the SAP BTP subaccount specified during the planning.
-   The number of running transactions \(workflows\) for a Cloud Integration Automation service consumer in SAP Cloud Platform subaccount is limited to 15.

-   Deleting a transaction in maintenance planner does not automatically delete its associated data in Cloud Integration Automation service and needs to be manually deleted in Cloud Integration Automation service.


