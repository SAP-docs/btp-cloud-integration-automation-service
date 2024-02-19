<!-- loio9ad530a11cc7412e897552078908807d -->

# Assigning Roles to the Users



Cloud Integration Automation service application requires certain roles to be fulfilled at the subscription level. This section describes them in detail and the steps to add a user to a group from the SAP BTP subaccount.



### Pre-Requisites

Your subaccount is subscribed to Cloud Integration Automation service in the Cloud Foundry environment. To learn more, see [Subscription to Standard Plan](subscription-to-standard-plan-c8ed936.md).



### Roles

The following table describes the various roles, the role collection that they are assigned to by default, and their privileges:

**Pre-Defined Roles**


<table>
<tr>
<th valign="top">

Roles

</th>
<th valign="top">

Assigned to Role Collection

</th>
<th valign="top">

Privileges

</th>
</tr>
<tr>
<td valign="top">

Integration Monitor

</td>
<td valign="top">

CIASIntegration Monitor

</td>
<td valign="top">

-   Read-only access to *Scenario Execution Monitoring* application.
-   Work on assigned tasks.



</td>
</tr>
<tr>
<td valign="top">

Integration Expert

</td>
<td valign="top">

CIASIntegrationExpert

</td>
<td valign="top">

-   Access to *My Inbox* application.
-   Work on assigned tasks.




</td>
</tr>
<tr>
<td valign="top">

Integration Administrator

</td>
<td valign="top">

CIASIntegrationAdministrator

</td>
<td valign="top">

-   Access to *My Inbox* application.

-   Access to *Plan for Integration*.
-   Access to *Scenario Execution Monitoring*.

-   Review the workflow execution plan like confirm landscape, role assignment, and scope selection.

-   Monitor the workflow execution and terminate a scenario.

-   Plan a new integration scenario.



</td>
</tr>
</table>



### Assign users to groups

As part of the subscription process, three role collections are created by default. You can add one or more users to these role collections to assign the roles associated with them:

-   CIASIntegrationExpert
-   CIASIntegration Monitor
-   CIASIntegrationAdministrator



### Procedure

1.  From the left navigation menu, choose *Security* \> *Role Collections*.
2.  *Choose an appropriate role* \> *Edit* \> *Users* tab and add user using their email ID or user ID which is used to login to the subaccount.
3.  Else, *Trust configuration* \> *Add a user* using SAP IDP or custom IDP or IAS tenant.

> ### Note:  
> 1.  The users you assign to the role collections are managed by the identity provider currently configured for the subaccount which runs Cloud Integration Automation service. In case you configure the subaccount to use a different identity provider afterward, the My Inbox and Scenario Execution Overview applications will not be accessible anymore unless the assigned users are also managed by the new identity provider.
> 2.  Cloud Integration Automation service currently supports any SAML assertion Name ID attribute. Once Cloud Integration Automation service is active with this Name ID attribute, if identity provider uses a different Name ID attribute, the My Inbox and Scenario Execution Overview applications will not be accessible.
> 3.  To avoid issues resulting from the conditions described above, we strongly recommend that you subscribe to Cloud Integration Automation service in a separate subaccount which is configured to use an identity provider with the SAML assertion Name ID attribute.

