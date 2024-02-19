<!-- loio9ec06845ddd44209a0540322df63a948 -->

# Task

A task contains its details and execution instructions for a scenario to the assigned users.

> ### Note:  
> While executing a scenario, you can view manual or automation tasks depending on the selected execution scope in the previous [task](selecting-execution-scope-444db93.md).



<a name="loio9ec06845ddd44209a0540322df63a948__section_rcl_3dw_p5b"/>

## Task Instructions

This tab provides instructions to the assigned user to execute and complete the selected task.

> ### Note:  
> -   Automation instructions are displayed for a task if added in the scenario. By default, manual instructions are displayed for all the tasks, irrespective of manual or automation task.
> -   When multiple users are assigned to a task, click *Claim* to lock the task. Once locked, the task is marked as *Reserved* for all the assigned users.

For manual tasks, follow the instructions on the screen and execute all the tasks on the target system. Once all the instructions are executed successfully, click *Task Completed*.

For automation tasks, configure the parameter details. Enter the parameter details in their respective fields and review the predefined parameters.

The following options are available on the screen:

-   *Refresh* - Updates the status of the automations. Hover on the icon to view the time of the last status update.
-   *Expand All* - Displays parameters of all the automations. By default, all the parameters of automations are expanded and displayed.
-   *Collapse All* - Collapses parameters of all the automations.
-   *Show/Hide Read-Only Parameters* - Displays or hides read-only parameters of all the automations. By default, the read-only parameters are hidden.
-   *Save Parameters* - Saves the changes made to the parameters.
-   *Automation Status* - Displays the progress of the automation while being executed via the statuses - Not Executed, To be Executed, In Progress, Success, Error, and Warning.
-   *Logs* - Displays the execution log for each automation.

    > ### Note:  
    > To view the execution log for the selected task, click *Logs* placed at the top-right corner of the screen.

-   *Information* - Displays a short description for each parameter.

Click *Execute Step* to process and execute the automations for this task.

> ### Note:  
> For any error during the execution, rectify the incorrect parameters of that automation and click *Execute Step* again. If few automations have failed from the list, select one from the following options:
> 
> -   *Only Failed Automations* - Executes the automations with Error status only.
> -   *All Automations* - Executes all the automations in the task, irrespective of their statuses.



<a name="loio9ec06845ddd44209a0540322df63a948__section_hcw_kfw_p5b"/>

## Overview

This tab displays a list of all the tasks in the sequence of execution in a scenario. Manual instructions for the selected task are displayed next to the list and comments for each task are displayed at the beginning.

Hover on the tasks to identify its type, for example:

-   Concept Task - This task provides an overview of the selected scenario and its tasks.
-   Topic - This is a header that contains the tasks to be executed.
-   User Task - This is a manual task.
-   User Service Task - This is an automation task.

> ### Note:  
> The list doesn't display admin-related tasks such as disclaimer and other initialization tasks.

You can perform the following actions on the list:

-   *Expand All* - Displays all the tasks to be executed in a scenario. By default, all the tasks are expanded and displayed.
-   *Collapse All* - Collapses all the tasks in the list.
-   *Current Task Instruction* - Displays manual instructions of the current task to be executed from the list.

    > ### Note:  
    > -   The current task in execution is indicated with an arrow at the beginning.
    > -   Click the *Comments* icon is displayed if the assigned user has added any comments for that task. Click the icon to view the comments.




<a name="loio9ec06845ddd44209a0540322df63a948__section_ocg_jlp_h3b"/>

## Comments

This tab displays the comments added for all the tasks in the scenario. These comments are displayed to all the assigned users and admins of that scenario.

To search for a comment, enter relevant keywords in the search bar. You can also refresh the list of comments using the *Refresh* icon.

To add a comment, enter the information in the field and click the *Submit* icon.



<a name="loio9ec06845ddd44209a0540322df63a948__section_f1z_flp_h3b"/>

## System Access

This tab displays the system access details for the selected task, if any. It also provides you an access link to the system.



<a name="loio9ec06845ddd44209a0540322df63a948__section_nvb_glp_h3b"/>

## Assigned To

This tab displays all the users assigned to the selected task.

> ### Note:  
> You can only view the assigned users for the task. You can't change the assigned user or their role from this tab.



<a name="loio9ec06845ddd44209a0540322df63a948__section_zvc_glp_h3b"/>

## Support Information

This tab displays all the support information for your assistance if an error occurs.

Once you've successfully executed all the instructions and automations and reviewed all the other tabs, go back to the Task Instructions tab and click *Task Completed*.

