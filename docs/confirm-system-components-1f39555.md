<!-- loio1f395552f4d04481a4de55574d554e6f -->

# Confirm System Components

This section describes the steps to confirm system components.

The system components are populated based on your selection during planning with maintenance planner.

> ### Note:  
> -   Only users with Admin role can view and complete this task.
> -   When multiple users are assigned to a task, click *Claim* to lock the task. Once locked, the task is marked as *Reserved* for all the assigned users.

Review the components and choose *Confirm Systems* button.

Assign destination to the possible system components. For missing destinations, create a destination in the SAP BTP subaccount and refresh the list.

> ### Note:  
> Destination selection is optional. In case a destination isn't assigned, the respective automation isn't available during task execution.

Currently, you need to specify the Account Name and Host for SAP BTP Account Cockpit, which you've already specified in maintenance planner.

For more details, see [Destination Creation](destination-creation-b2cd7e9.md).

Review the components and choose *Confirm System*.

> ### Note:  
> Tenant information like *Name* and *Host* can't be changed.

Some scenarios support manually entering system properties if they aren't already displayed from the management system.

In such cases, enter the following properties in the text field:

**Multiple Workflow Execution Handling**

If there's more than one integration setup workflow within the same system components, an execution lock is implemented. When such a situation occurs, select from the following options:

-   **Proceed**: Proceed without resolving conflicts. You can resolve these later manually.

-   **Terminate**: Terminate the selected instances.

-   **Terminate Current Instance**

-   **Cancel**


