<!-- loio35fbf2ab8a844217b3486f85a2bd9ab2 -->

# What is Cloud Integration Automation Service?

**Cloud Integration Automation** service provides you a guided workflow to integrate SAP cloud solutions to on-premise and other SAP cloud solutions. The guided workflow contains instructions for manual and automated tasks to enable an easy and quick integration configuration setup.

<a name="loioc2a43f6ac5f6471eae8063e7470bd404"/>

<!-- loioc2a43f6ac5f6471eae8063e7470bd404 -->

## Advantages

-   User and task centric approach in integration configuration scenarios, using guided workflows.

-   Planning capabilities to plan an integration scenario.

-   The guided workflow covers an integration setup for a specific scenario.

-   Instructions are provided in a task format and can be assigned to a dedicated role.

-   Instructions are provided based on your landscape and the chosen integration scenario.

-   Automated technical configuration steps on selected targets are available and enabled.

-   Monitoring capabilities for the integration scenario guided workflow.


<a name="loio58b9975587304c659e28c9eea8e89500"/>

<!-- loio58b9975587304c659e28c9eea8e89500 -->

## Important Disclaimers

-   User ID, email ID, SAP Business Technology Platform \(SAP BTP\) subaccount/subdomain name, and landscape-related data \(system ID, host\) will be persisted into the Cloud Integration Automation service database tables to enable guided workflow execution.
-   It is expected that you follow the instructions as described in the guided workflows and acknowledge the same upon completion.
-   For automation APIs, destinations to the respective system needs to be created in the SAP BTP subaccount.

<a name="loioafa0202d036d4c4c94edc3d08e5f261a"/>

<!-- loioafa0202d036d4c4c94edc3d08e5f261a -->

## Limitations

-   The number of active workflows supported for an SAP BTP subaccount/subdomain is currently limited to 15.
-   Explicit deletion of user ID, email ID, or transactional data as a self-service from the Cloud Integration Automation service consumer subaccount is not offered in the current release of Cloud Integration Automation service. Hence, you need to raise a support request to the component *BC-INS-CIT-RT* to remove the complete transactional data \(status should be completed or terminated\) including user IDs or email IDs.

    The ticket must contain the user ID or email ID that needs to be removed, as well as the SAP BTP consumer subaccount/subdomain name.

-   Deleting a transaction in maintenance planner does not automatically delete its associated data in Cloud Integration Automation service, and must be deleted manually.

    Refer [SAP Note 2608492](https://launchpad.support.sap.com/#/notes/2608492).

-   Cloud Integration Automation service currently does not perform checks on connecting inter-landscape tenants. Hence, check explicitly if the landscape chosen for integration is valid.

-   The following browsers are supported on *Microsoft Windows* PCs:


    <table>
    <tr>
    <th valign="top">

    Browser
    
    </th>
    <th valign="top">

    Versions
    
    </th>
    </tr>
    <tr>
    <td valign="top">
    
    Mozilla Firefox
    
    </td>
    <td valign="top">
    
    Extended Support Release \(ESR\) and latest version
    
    </td>
    </tr>
    <tr>
    <td valign="top">
    
    Google Chrome
    
    </td>
    <td valign="top">
    
    Latest version
    
    </td>
    </tr>
    </table>
    

<a name="loiob38977dd690e492e895b7013ac9721c2"/>

<!-- loiob38977dd690e492e895b7013ac9721c2 -->

## Supported Scenarios

The following integration scenarios are currently supported:





### Intelligent Enterprise - Lead to Cash - Contact to Lead

-   Onboard Company: Integration Commerce Cloud with S/4 Cloud \(S4HC\)
-   Capture Interaction: Integrate SAP Commerce Cloud with SAP Marketing Cloud
-   SAP Customer Data Cloud Integration with SAP S/4HANA Cloud



### Intelligent Enterprise - Lead to Cash - Lead to Opportunity

-   SAP Marketing Cloud Integration with SAP Cloud for Customer \(1J9\)



### Intelligent Enterprise - Lead to Cash - Master Data

-   SAP Master Data Service for Business Partners Integration with SAP Commerce Cloud
-   SAP Customer Data Cloud Integration with SAP Commerce Cloud \(B2B Scenario\)
-   SAP Customer Data Cloud Integration with SAP Commerce Cloud \(B2C Scenario\)
-   SAP Customer Data Cloud Integration with SAP Master Data Service for Business Partners
-   SAP Configure Price Quote with SAP Master Data Service for Business Partners
-   MDM Business Partner Integration with Field Service Management \(MDM FSM\)
-   MDI Business Partner Integration with S/4HANA Cloud \(MDI BP\)
-   MDI Business Partner Integration with SAP Cloud for Customer\(MDI C4C\)
-   MDM Business Partner Integration with Marketing Cloud \(MDM MC\)



### Intelligent Enterprise - Lead to Cash - Order to Cash

-   Orchestrate Fulfilment Process: Order Management Data Replication to SAP Marketing Cloud \(1UG\)
-   On-Premise: B2B Order Fulfillment with SAP Commerce Cloud \(2TY\) 2021
-   On-Premise: B2B Order Fulfillment with SAP Commerce Cloud \(2TY\) 2022
-   Subscription Management with Convergent Invoicing \(5IK\)
-   Subscription Management with Sales Billing \(BP SB\)
-   Orchestrate Fulfillment Process: Integration Commerce Cloud with Subscription Billing \(SB\)



### Intelligent Enterprise - Lead to Cash - Opportunity to Quote

-   SAP Marketing Cloud Integration with SAP Cloud for Customer \(1J9\)
-   Opportunity-to-Order with SAP Cloud for Customer \(1VP\)
-   Integration SAP CPQ Quote 2.0 - SAP Cloud for Customer



### Intelligent Enterprise - Lead to Cash - Quote to Order

-   SAP Commerce Cloud Integration with SAP CPQ for Quote 2.0
-   Automation of Order-to-Invoice with Ariba Network \(4A1\)





### Intelligent Enterprise - Recruit to Retire - Hire to Retire

-   Payroll Processing with SAP SuccessFactors Employee Central Payroll \(1NL\)
-   On-Premise: Setting up Payroll Processing with SAP SuccessFactors Employee Central Payroll 2020
-   On-Premise: Setting up Payroll Processing with SAP SuccessFactors Employee Central Payroll 2021
-   Payroll Processing with SAP ERP HCM Payroll \(3UP\)
-   Workforce Management with SAP Master Data Integration \(Inbound\)
-   On-Premise: Workforce Integration in SAP S/4HANA 2020
-   On-Premise: Workforce Integration in SAP S/4HANA 2021
-   On-Premise: Workforce Integration in SAP S/4HANA 2022
-   Core HR with SAP SuccessFactors Employee Central \(JB1\)



### Intelligent Enterprise - Recruit to Retire - Travel to Reimburse

-   Travel Expense Processing with SAP Concur Expense Professional \(1M1\)
-   Payroll Processing with SAP SuccessFactors Employee Central Payroll \(1NL\)
-   On-Premise: Setting up Payroll Processing with SAP SuccessFactors Employee Central Payroll 2021
-   On-Premise: External Workforce Procurement via SAP Fieldglass \(22K\) 2021
-   Workforce Management with SAP Master Data Integration \(Inbound\)
-   On-Premise: Workforce Integration in SAP S/4HANA 2021
-   On-Premise: Workforce Integration in SAP S/4HANA 2022
-   SAP S/4HANA-Concur-Payroll Integration



### Intelligent Enterprise - Recruit to Retire - External Workforce

-   External Workforce Procurement via SAP Fieldglass \(22K\)
-   On-Premise: External Workforce Procurement via SAP Fieldglass \(22K\) 2021
-   On-Premise: External Workforce Procurement via SAP Fieldglass \(22K\) 2022
-   Workforce Management with SAP Master Data Integration \(Inbound\)
-   On-Premise: Workforce Integration in SAP S/4HANA 2021
-   On-Premise: Workforce Integration in SAP S/4HANA 2022





### Intelligent Enterprise - Source to Pay - Contract

-   Contract Management with SAP Ariba Contracts \(4AZ\)
-   On-Premise: Contract Management with SAP Ariba Contracts \(4AZ\) 2020
-   On-Premise: Contract Management with SAP Ariba Contracts \(4AZ\) 2021
-   On-Premise: Contract Management with SAP Ariba Contracts \(4AZ\) 2022
-   Contract for Central Procurement with SAP Ariba Contracts \(4B0\)
-   On-Premise: Contract for Central Procurement with SAP Ariba Contracts \(4B0\) 2021
-   On-Premise: Contract for Central Procurement with SAP Ariba Contracts \(4B0\) 2022



### Intelligent Enterprise - Source to Pay - Guided Buying

-   Guided Buying Capability with SAP Ariba Buying \(2NV\)
-   On-Premise: Guided Buying Capability with SAP Ariba Buying \(2NV\) 2021
-   On-Premise: Guided Buying Capability with SAP Ariba Buying \(2NV\) 2022
-   Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\)
-   On-Premise: Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\) 2021
-   On-Premise: Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\) 2022
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2020
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2021
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2022



### Intelligent Enterprise - Source to Pay - Sourcing

-   Sourcing with SAP Ariba Sourcing \(4BL\)
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2020
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2021
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2022
-   Central Sourcing with Ariba Sourcing \(4QN\)
-   On-Premise: Central Sourcing with Ariba Sourcing \(4QN\) 2021
-   On-Premise: Central Procurement with SAP Ariba Sourcing \(4QN\) 2022



### Intelligent Enterprise - Source to Pay - Supplier Collaboration/Network

-   Automation of Source-to-Pay with Ariba Network \(42K\)
-   On-Premise: Automation of Source-to-Pay with SAP Business Network \(42K\) 2020
-   On-Premise: Automation of Source-to-Pay with SAP Business Network \(42K\) 2021
-   On-Premise: Automation of Source-to-Pay with SAP Business Network \(42K\) 2022
-   Services Procurement with Ariba Network and SAP Fieldglass \(4R2\)
-   On-Premise: Services Procurement with SAP Business Network and SAP Fieldglass \(4R2\) 2022
-   Subcontracting with SAP Business Network \(5I2\)
-   On-Premise: Subcontracting with SAP Business Network \(5I2\) 2022
-   Automation of Central Procurement Quotes with Ariba Net \(5JT\)
-   On-Premise: Automation of Central Procurement Quotes with Ariba Net \(5JT\) 2021
-   On-Premise: Automation of Central Procurement Quotes with Ariba Net \(5JT\) 2022
-   MRP Change Request Integration with Ariba Network \(65D\)
-   On-Premise: MRP Change Request Integration with Ariba Network \(65D\) 2022





### SAP Business Technology Platform \(BTP\) ABAP Environment

-   Configuring the ABAP Environment to Use the Custom Code Migration App
-   SAP BTP, ABAP Environment, and SAP S/4HANA Cloud: Integration





### SAP Cloud for Projects

-   SAP S/4HANA Cloud for Project - Project Collaboration





### SAP Business Technology Platform \(BTP\) Services

-   SAP Business Network Asset Collaboration Setup on BTP
-   SAP Asset Performance Management
-   SAP Group Reporting Data Collection





### SAP Cloud Connector

-   Configuration of SAP Cloud Connector with Principal Propagation





### SAP Integrated Business Planning \(IBP\)

-   Configuring Real-Time Integration \(RTI\) in SAP IBP



### SAP Launchpad Service Integration

-   SAP Launchpad Service Integration with SAP S/4HANA
-   SAP Launchpad Service Integration with SAP S/4HANA Cloud



### SAP S/4HANA Cloud Integration

-   Travel Expense Processing with SAP Concur Expense Professional \(1M1\)
-   Payroll Processing with SAP SuccessFactors Employee Central Payroll \(1NL\)
-   Credit Agency Integration \(1RY\)
-   Customer Payments \(1S0\)
-   Digital Payments \(1S2\)
-   Automatic Market Rates Management \(1S4\)
-   Opportunity-to-Order with SAP Cloud for Customer \(1VP\)
-   Restricted Party Screening with SAP Watch List Screening \(1WE\)
-   SAP S/4HANA for Enterprise Contract Management \(1XV\)
-   Import Connection setup with SAP Analytics Cloud \(1YB\)
-   Digital Payments - Sales \(1Z1\)
-   External Billing \(1Z6\)
-   Logistics with Third-Party Warehouse Management \(1ZQ\)
-   External Workforce Procurement via SAP Fieldglass \(22K\)
-   Integration of Procurement with External Suppliers \(2EJ\)
-   Integration of Sales with External Buyers \(2EL\)
-   Integration of Payment Advice with Buyers and Suppliers \(2MB\)
-   Guided Buying Capability with SAP Ariba Buying \(2NV\)
-   Continuous Control Monitoring with SAP Process Control \(2OH\)
-   Integration to SAP S/4HANA Cloud for Enterprise Contract Assembly \(2OQ\)
-   Customs Management with SAP Global Trade Services \(2U1\)
-   Key Risk Indicator Monitoring with SAP Risk Management \(2U2\)
-   Automated Provisioning via SAP Cloud Identity Access Governance \(3AB\)
-   Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\)
-   Payroll Processing with SAP ERP HCM Payroll \(3UP\)
-   Third-Party Shop Floor Execution - Process Industry \(3W3\)
-   Third-Party Shop Floor Execution - Discrete Industry \(3W4\)
-   Automation of Source-to-Pay with SAP Business Network \(42K\)
-   Service Order Processing with SAP Field Service Management \(49X\)
-   Automation of Order-to-Invoice with SAP Business Network \(4A1\)
-   Workforce Management with SAP Master Data Integration \(Inbound\)
-   Financial Master Data for SAP SuccessFactors Employee Central \(4AJ\)
-   Contract Management with SAP Ariba Contracts \(4AZ\)
-   Contract for Central Procurement with Ariba Contracts\(4B0\)
-   Sourcing with SAP Ariba Sourcing \(4BL\)
-   SAP Central Invoice Management \(4N6\)
-   Central Procurement with SAP Ariba Sourcing \(4QN\)
-   Services Procurement with SAP Business Network and SAP Fieldglass \(4R2\)
-   ABAP Core Data Services Extraction for SAP Datasphere \(53L\)
-   Digital Payments Foundation \(53V\)
-   Subscription Management with Sales Billing \(57Z\)
-   Subcontracting with SAP Business Network \(5I2\)
-   Subscription Management with Convergent Invoicing \(5IK\)
-   Automation of Central Procurement Quotes with Ariba Network \(5JT\)
-   Real Estate Integration between S/4HANA cloud with C4RE \(5VX\)
-   MRP Change Request Integration with SAP Business Network \(65D\)
-   Solution Order Quotation Management with SAP CPQ \(6BV\)
-   S/4HANA Cloud for Projects, Collaborative Project Management \(6JN\)
-   Resource Management for Projects \(6JO\)
-   Integrate SAP S/4HCE with SAP Sales and Service Cloud \(6KO\)
-   Core HR with SAP SuccessFactors Employee Central \(JB1\)





### SAP S/4HANA On-Premise Integration

-   Configuration for Connectivity S/4HANA to SAP Digital Manufacturing Cloud
-   On-Premise: External Workforce Procurement via SAP Fieldglass \(22K\) 2022
-   On-Premise: External Workforce Procurement via SAP Fieldglass \(22K\) 2023
-   On-Premise: Integration of Procurement with External Suppliers \(2EJ\) 2022
-   On-Premise: Integration of Procurement with External Suppliers \(2EJ\) 2023
-   On-Premise: Integration of Sales with External Buyers \(2EL\) 2022
-   On-Premise: Integration of Sales with External Buyers \(2EL\) 2023
-   On-Premise: Guided Buying Capability with SAP Ariba Buying \(2NV\) 2022
-   On-Premise: Guided Buying Capability with SAP Ariba Buying \(2NV\) 2023
-   On-Premise: B2B Order Fulfillment with SAP Commerce Cloud \(2TY\) 2022
-   On-Premise: Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\) 2022
-   On-Premise: Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\) 2023
-   On-Premise: Set Up Automation of Source-to-Pay with SAP Business Network \(42K\) 2022
-   On-Premise: Set Up Automation of Source-to-Pay with SAP Business Network \(42K\) 2023
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2022
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2023
-   On-Premise: Workforce Integration in SAP S/4HANA 2022
-   On-Premise: Workforce Integration in SAP S/4HANA 2023
-   On-Premise: Workforce Integration in SAP S/4HANA as Producer 2022
-   On-Premise: Workforce Integration in SAP S/4HANA as Producer 2023
-   On-Premise: Contract Management with SAP Ariba Contracts \(4AZ\) 2022
-   On-Premise: Contract Management with SAP Ariba Contracts \(4AZ\) 2023
-   On-Premise: Contract for Central Procurement with SAP Ariba Contracts \(4B0\) 2022
-   On-Premise: Contract for Central Procurement with SAP Ariba Contracts \(4B0\) 2023
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2022
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2023
-   On-Premise: Central Procurement with SAP Ariba Sourcing \(4QN\) 2022
-   On-Premise: Central Procurement with SAP Ariba Sourcing \(4QN\) 2023
-   On-Premise: Services Procurement with SAP Business Network and SAP Fieldglass \(4R2\) 2022
-   On-Premise: Services Procurement with SAP Business Network and SAP Fieldglass \(4R2\) 2023
-   On-Premise: Subcontracting with SAP Business Network \(5I2\) 2022
-   On-Premise: Subcontracting with SAP Business Network \(5I2\) 2023
-   On-Premise: Automation of Central Procurement Quotes with Ariba Net \(5JT\) 2022
-   On-Premise: Automation of Central Procurement Quotes with Ariba Net \(5JT\) 2023
-   On-Premise: MRP Change Request Integration with SAP Business Network \(65D\) 2022
-   On-Premise: MRP Change Request Integration with SAP Business Network \(65D\) 2023
-   SAP Business Network Asset Collaboration integration with S/4HANA On-Premise





### SAP SuccessFactors Employee Central with SAP S/4HANA On-Premise Integration

-   Replicating Cost Centers from SAP S/4HANA On-Premise to SAP SuccessFactors Employee Central
-   Migrating Employee and Organizational Data from SAP S/4HANA On-Premise to SAP SuccessFactors Employee Central
-   Basic System Setup for Data Replication from SAP SuccessFactors Employee Central to SAP S/4HANA On-Premise





### SAP SuccessFactors Employee Central Payroll

-   Configure Pay Statement \(Direct\) Integration in SFEC and ECP

