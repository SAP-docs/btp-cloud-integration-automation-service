<!-- loio2ad4326e15794abc8eac2de014c770f9 -->

# Using Maintenance Planner



## Context

An S-User assigned to the customer ID for access to maintenance planner. For more information, see the [Maintenance Planner User Guide](https://help.sap.com/viewer/62c8d2b1a71046a09b9c7ec745910ae4/latest/en-US).



## Procedure

1.  Launch maintenance planner.

    [https://maintenanceplanner.cfapps.eu10.hana.ondemand.com](https://maintenanceplanner.cfapps.eu10.hana.ondemand.com/)

2.  Click the *Plan for Cloud Integration Scenario* tile.

3.  Select one of the available solutions from the Solutions tab..

    Alternatively, you can enter the cloud integration solution in the search.

4.  Select one of the available scenarios.

5.  From the available options, select a **scenario option**.

6.  Select the systems for integration.

    The systems and tenants are listed according to the customer number based on the S-User.

    In case a system or tenant is not visible, proceed with the next steps. You can enter the landscape data manually. To enter the data, navigate to the Confirm System Components task in the My Inbox application of Cloud Integration Automation service.

    You can also search for systems using the Tenant URL.

7.  Invoke the workflow.

    > ### Note:  
    > The selected systems may belong to different landscapes. For such instances, you are prompted to confirm with the integration between such systems. If yes, click *Proceed*. Click *Cancel* to choose different systems.

    To invoke the workflow, enter the following:

    1.  In the input field for SAP BTP Region, select the data center region in which Cloud Integration Automation service is subscribed.

    2.  In the input field for SAP BTP Account Technical Name, provide a valid SAP BTP Account name in which Cloud Integration Automation service solution is subscribed.

        If not subscribed, follow the [Subscription to Cloud Integration Automation Service](subscription-to-cloud-integration-automation-service-b3a72d9.md) section.

    3.  In the input field for SAP BTP Account Workflow Users, provide the list of users who receives the first task.

        Ensure that these users can access the SAP BTP subaccount.

    4.  Provide the Cloud Integration Automation Service Transaction Name, which will be referred to My Inbox and Scenario Execution Monitoring applications of Cloud Integration Automation service.


8.  Upon successful workflow generation, a link is generated.

9.  Click the link to launch Cloud Integration Automation service.


