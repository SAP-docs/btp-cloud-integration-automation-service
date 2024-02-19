<!-- loio5ccb2ce04baa447282e76e7e95e4b36c -->

<link rel="stylesheet" type="text/css" href="css/sap-icons.css"/>

# Using Cloud Integration Automation Service

You can plan for an integration scenario in Cloud Integration Automation service using the *Plan for Integration* tile.



<a name="loio5ccb2ce04baa447282e76e7e95e4b36c__section_krr_5pt_mxb"/>

## Procedure

1.  Launch the Cloud Integration Automation service.

    > ### Note:  
    > The Cloud Integration Automation service link is available in the *Instances and Subscription* tab of the SAP BTP subaccount where Cloud Integration Automation service is subscribed. Choose the link to launch the Cloud Integration Automation service and obtain its URL. To find the link, either select the subscription row to open more details about the subscription or click on the <span class="SAP-icons"></span> \(Go to Application\) icon in the *Application* column.

2.  Select the *Plan for Integration* tile.
3.  Select one of the available solutions from the *Solutions* tab.
4.  Select one of the available scenarios in the solution.

    Alternatively, you can also add a scenario in the search box. This will restrict the number of solutions where the scenario is available.

5.  From the available options, select a scenario option.
6.  Select the systems for integration.

    The systems and tenants are listed according to the customer number to which the SAP BTP global account is assigned to where Cloud Integration Automation service is subscribed.

    In case a system or tenant is not visible, proceed with the next steps. You can enter the landscape data manually. To enter the data, navigate to the *Confirm System Components* task in the *My Inbox* tile of Cloud Integration Automation service.

7.  Invoke the workflow.

    > ### Note:  
    > The selected systems may belong to different landscapes. For such instances, you are prompted to confirm with the integration between such systems. If yes, click *Proceed*. Click *Cancel* to choose different systems.
    > 
    > To invoke the workflow, enter the following:
    > 
    > 1.  The subaccount where Cloud Integration Automation service workflow will be generated defaults to subaccount where Cloud Integration Automation service is currently accessed.
    > 2.  In the input field for SAP BTP Workflow Users: provide the list of users who receives the first task. Ensure that these users can access the SAP BTP subaccount.
    > 3.  Provide the Cloud Integration Automation Service Transaction Name, which will be referred to *My Inbox* and *Scenario Execution Monitoring* tiles in Cloud Integration Automation service.

8.  Upon successful workflow generation, a link is generated to view the task in the *My Inbox* tile.

