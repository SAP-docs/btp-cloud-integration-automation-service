<!-- loio35fbf2ab8a844217b3486f85a2bd9ab2 -->

# What is Cloud Integration Automation Service?

**Cloud Integration Automation** service provides you a guided workflow to integrate SAP cloud solutions to on-premise and other SAP cloud solutions. The guided workflow contains instructions for manual and automated tasks to enable an easy and quick integration configuration setup.

<a name="loioc2a43f6ac5f6471eae8063e7470bd404"/>

<!-- loioc2a43f6ac5f6471eae8063e7470bd404 -->

## Advantages

-   User and task-centric approach using guided workflows in integration configuration scenarios.

-   Planning capabilities to plan an integration scenario.

-   A guided workflow that covers an integration setup for a specific scenario.

-   Instructions provided in task format, which can be assigned to a dedicated role.

-   Instructions provided based on your landscape and chosen integration scenario.

-   Automated technical configuration steps available and enabled on selected targets.

-   Monitoring capabilities for an integration scenario guided workflow.


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





### SAP Business Technology Platform \(BTP\) Services

-   SAP Business Network Asset Collaboration Setup on BTP
-   SAP Asset Performance Management
-   SAP Group Reporting Data Collection



### SAP Business Technology Platform \(BTP\) ABAP Environment

-   Configuring the ABAP Environment to Use the Custom Code Migration App
-   SAP BTP, ABAP Environment, and SAP S/4HANA Cloud: Integration



### Intelligent Enterprise - Design to Operate - Plan to Fulfill

-   Subcontracting with SAP Business Network \(5I2\)



### Intelligent Enterprise - Lead to Cash - Contact to Lead

-   Onboard Company: Integration Commerce Cloud with S/4 Cloud \(S4HC\)
-   Capture Interaction: Integrate SAP Commerce Cloud with SAP Marketing Cloud
-   SAP Customer Data Cloud Integration with SAP S/4HANA Cloud



### Intelligent Enterprise - Lead to Cash - Lead to Opportunity

-   SAP Marketing Cloud Integration with SAP Cloud for Customer \(1J9\)



### Intelligent Enterprise - Lead to Cash - Master Data

-   MDM Business Partner Integration with Marketing Cloud \(MDM MC\)
-   MDI Business Partner Integration with SAP Cloud for Customer\(MDI C4C\)
-   MDI Business Partner Integration with S/4HANA Cloud \(MDI BP\)
-   SAP Master Data Service for Business Partners Integration with SAP Commerce Cloud
-   MDM Business Partner Integration with Field Service Management \(MDM FSM\)
-   SAP Customer Data Cloud Integration with SAP Master Data Service for Business Partners
-   SAP Configure Price Quote with SAP Master Data Service for Business Partners
-   SAP Customer Data Cloud Integration with SAP Commerce Cloud \(B2B Scenario\)
-   SAP Customer Data Cloud Integration with SAP Commerce Cloud \(B2C Scenario\)



### Intelligent Enterprise - Lead to Cash - Order to Cash

-   Service Order Processing with SAP Field Service Management \(49X\)
-   Orchestrate Fulfillment Process: Order Management Data Replication to SAP Marketing Cloud \(1UG\)
-   Orchestrate Fulfillment Process: Integration Commerce Cloud with Subscription Billing \(SB\)
-   Subscription Management with Convergent Invoicing \(5IK\)
-   Subscription Management with Sales Billing \(BP SB\)
-   On-Premise: B2B Order Fulfillment with SAP Commerce Cloud \(2TY\) 2021
-   On-Premise: B2B Order Fulfillment with SAP Commerce Cloud \(2TY\) 2022



### Intelligent Enterprise - Lead to Cash - Opportunity to Quote

-   SAP Marketing Cloud Integration with SAP Cloud for Customer \(1J9\)
-   Opportunity-to-Order with SAP Cloud for Customer \(1VP\)
-   Integration SAP CPQ Quote 2.0 - SAP Cloud for Customer



### Intelligent Enterprise - Lead to Cash - Quote to Order

-   SAP Commerce Cloud Integration with SAP CPQ for Quote 2.0
-   Automation of Order-to-Invoice with SAP Business Network \(4A1\)



### Intelligent Enterprise - Recruit to Retire - Hire to Retire

-   Payroll Processing with SAP SuccessFactors Employee Central Payroll \(1NL\)
-   Payroll Processing with SAP ERP HCM Payroll \(3UP\)
-   Workforce Management with SAP Master Data Integration \(Inbound\)
-   On-Premise: Setting up Payroll Processing with SAP SuccessFactors Employee Central Payroll 2020
-   On-Premise: Setting up Payroll Processing with SAP SuccessFactors Employee Central Payroll 2021
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
-   On-Premise: Contract for Central Procurement with SAP Ariba Contracts \(4B0\) 2021
-   Contract for Central Procurement with SAP Ariba Contracts \(4B0\)



### Intelligent Enterprise - Source to Pay - Guided Buying

-   Guided Buying Capability with SAP Ariba Buying \(2NV\)
-   On-Premise: Guided Buying Capability with SAP Ariba Buying \(2NV\) 2021
-   Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\)
-   On-Premise: Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\) 2021
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2020
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2021



### Intelligent Enterprise - Source to Pay - Sourcing

-   Sourcing with SAP Ariba Sourcing \(4BL\)
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2020
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2021
-   Central Sourcing with Ariba Sourcing \(4QN\)
-   On-Premise: Central Sourcing with Ariba Sourcing \(4QN\) 2021



### Intelligent Enterprise - Source to Pay - Supplier Collaboration/Network

-   Automation of Central Procurement Quotes with Ariba Net \(5JT\)
-   On-Premise: Automation of Central Procurement Quotes with Ariba Net \(5JT\) 2021
-   Automation of Source-to-Pay with SAP Business Network \(42K\)
-   On-Premise: Automation of Source-to-Pay with SAP Business Network \(42K\) 2020
-   On-Premise: Automation of Source-to-Pay with SAP Business Network \(42K\) 2021
-   Subcontracting with SAP Business Network \(5I2\)
-   Services Procurement with SAP Business Network and SAP Fieldglass \(4R2\)



### Communication Management Migration from 2SL to 3SL

-   Migrate Communication Management Entities from 2SL to 3SL
-   3SL Migration Precheck of S/4 - CIAS Connection



### SAP Cloud Connector

-   Configuration of SAP Cloud Connector with Principal Propagation



### SAP Integrated Business Planning \(IBP\)

-   Configuring Real-Time Integration \(RTI\) in SAP IBP



### SAP Build

-   Provision SAP Build on SAP BTP
-   Provision SAP Build on SAP BTP with S/4HANA Cloud Private Edition Integration



### SAP Build Work Zone Integration

-   SAP Build Work Zone Standard Edition Integration with SAP S/4HANA
-   SAP Build Work Zone Standard Edition Integration with SAP S/4HANA Cloud



### SAP S/4HANA Cloud Private Edition Integration

-   Solution Quotation Management with SAP CPQ \(7HB\)



### SAP S/4HANA Cloud Integration

-   Travel Expense Processing with SAP Concur Expense Professional \(1M1\)
-   Automatic Market Rates Management \(1S4\)
-   Payroll Processing with SAP SuccessFactors Employee Central Payroll \(1NL\)
-   Credit Agency Integration \(1RY\)
-   Customer Payments \(1S0\)
-   Digital Payments \(1S2\)
-   Opportunity-to-Order with SAP Cloud for Customer \(1VP\)
-   Restricted Party Screening with SAP Watch List Screening \(1WE\)
-   SAP S/4HANA for Enterprise Contract Management \(1XV\)
-   Import Connection setup with SAP Analytics Cloud \(1YB\)
-   Digital Payments Sales \(1Z1\)
-   External Billing \(1Z6\)
-   Logistics with Third-Party Warehouse Management \(1ZQ\)
-   External Workforce Procurement via SAP Fieldglass \(22K\)
-   Integration of Procurement with External Suppliers \(2EJ\)
-   Integration of Sales with External Buyers \(2EL\)
-   Integration of Payment Advice with Buyers and Suppliers \(2MB\)
-   Guided Buying Capability with SAP Ariba Buying \(2NV\)
-   Continuous Control Monitoring with SAP Process Control \(2OH\)
-   Integration to SAP S/4HANA Cloud for Enterprise Contract Assembly \(2OQ\)
-   International Trade Management with SAP GTS
-   Key Risk Indicator Monitoring with SAP Risk Management \(2U2\)
-   Automated Provisioning via SAP Cloud Identity Access Governance \(3AB\)
-   Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\)
-   Payroll Processing with SAP ERP HCM Payroll \(3UP\)
-   Third-Party Shop Floor Execution - Process Industry \(3W3\)
-   Third-Party Shop Floor Execution - Discrete Industry \(3W4\)
-   Service Order Processing with SAP Field Service Management \(49X\)
-   Automation of Source-to-Pay with SAP Business Network \(42K\)
-   Automation of Order-to-Invoice with SAP Business Network \(4A1\)
-   Workforce Management with SAP Master Data Integration \(Inbound\)
-   Setting Up SAP Ariba Buying \(4AI\)
-   Contract Management with SAP Ariba Contracts \(4AZ\)
-   Contract for Central Procurement with Ariba Contracts \(4B0\)
-   Sourcing with SAP Ariba Sourcing \(4BL\)
-   SAP Central Invoice Management \(4N6\)
-   Central Procurement with SAP Ariba Sourcing \(4QN\)
-   Services Procurement with SAP Business Network and SAP Fieldglass \(4R2\)
-   Digital Payments Foundation \(53V\)
-   ABAP Core Data Services Extraction for SAP Datasphere \(53L\)
-   Subscription Management with Sales Billing \(57Z\)
-   Subcontracting with SAP Business Network \(5I2\)
-   Subscription Management with Convergent Invoicing \(5IK\)
-   Automation of Central Procurement Quotes with Ariba Network \(5JT\)
-   Real Estate Integration between S/4HANA cloud with C4RE \(5VX\)
-   Core HR with SAP SuccessFactors Employee Central \(JB1\)
-   MRP Change Request Integration with SAP Business Network \(65D\)
-   Solution Order Quotation Management with SAP CPQ \(6BV\)
-   Resource Management capability in SAP Project and Resource Management \(6JO\)
-   Integrate SAP S/4HCE with SAP Sales and Service Cloud \(6KO\)
-   S/4HANA Cloud for Projects, Collaborative Project Management \(6JN\)
-   Integration to Icertis for Contract Assembly \(6V2\)
-   3SL Migration Precheck of S/4 - CIAS Connection



### SAP S/4HANA On-Premise Integration

-   Configuration for Connectivity S/4HANA to SAP Digital Manufacturing Cloud
-   Asset Intelligence Network integration with S/4HANA On-Premise
-   On-Premise: Integration of Sales with External Buyers \(2EL\) 2022
-   On-Premise: Integration of Sales with External Buyers \(2EL\) 2023
-   On-Premise: Integration of Procurement with External Suppliers \(2EJ\) 2022
-   On-Premise: Integration of Procurement with External Suppliers \(2EJ\) 2023
-   On-Premise: External Workforce Procurement via SAP Fieldglass \(22K\) 2022
-   On-Premise: External Workforce Procurement via SAP Fieldglass \(22K\) 2023
-   On-Premise: B2B Order Fulfillment with SAP Commerce Cloud \(2TY\) 2022
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2022
-   On-Premise: Automation of Order-to-Invoice with SAP Business Network \(4A1\) 2023
-   On-Premise: Set Up Automation of Source-to-Pay with SAP Business Network \(42K\) 2022
-   On-Premise: Set Up Automation of Source-to-Pay with SAP Business Network \(42K\) 2023
-   On-Premise: Subcontracting with SAP Business Network \(5I2\) 2022
-   On-Premise: Subcontracting with SAP Business Network \(5I2\) 2023
-   On-Premise: Central Procurement with SAP Ariba Sourcing \(4QN\) 2022
-   On-Premise: Central Procurement with SAP Ariba Sourcing \(4QN\) 2023
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2022
-   On-Premise: Sourcing with SAP Ariba Sourcing \(4BL\) 2023
-   On-Premise: Services Procurement with SAP Business Network and SAP Fieldglass \(4R2\) 2022
-   On-Premise: Services Procurement with SAP Business Network and SAP Fieldglass \(4R2\) 2023
-   On-Premise: Contract Management with SAP Ariba Contracts \(4AZ\) 2022
-   On-Premise: Contract Management with SAP Ariba Contracts \(4AZ\) 2023
-   On-Premise: MRP Change Request Integration with SAP Business Network \(65D\) 2022
-   On-Premise: MRP Change Request Integration with SAP Business Network \(65D\) 2023
-   On-Premise: Contract for Central Procurement with SAP Ariba Contracts \(4B0\) 2022
-   On-Premise: Contract for Central Procurement with SAP Ariba Contracts \(4B0\) 2023
-   On-Premise: Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\) 2022
-   On-Premise: Guided Buying for Central Procurement with SAP Ariba Buying \(3EN\) 2023
-   On-Premise: Automation of Central Procurement Quotes with Ariba Net \(5JT\) 2022
-   On-Premise: Automation of Central Procurement Quotes with Ariba Net \(5JT\) 2023
-   On-Premise: Guided Buying Capability with SAP Ariba Buying \(2NV\) 2022
-   On-Premise: Guided Buying Capability with SAP Ariba Buying \(2NV\) 2023
-   On-Premise: Workforce Integration in SAP S/4HANA 2022
-   On-Premise: Workforce Integration in SAP S/4HANA 2023
-   On-Premise: Workforce Integration in SAP S/4HANA as Producer 2022
-   On-Premise: Workforce Integration in SAP S/4HANA as Producer 2023
-   On-Premise: SAP Business Network Asset Collaboration Integration with S/4HANA



### SAP SuccessFactors Employee Central with SAP S/4HANA On-Premise Integration

-   Replicating Cost Centers from SAP S/4HANA On-Premise to SAP SuccessFactors Employee Central
-   Migrating Employee and Organizational Data from SAP S/4HANA On-Premise to SAP SuccessFactors Employee Central
-   Basic System Setup for Data Replication from SAP SuccessFactors Employee Central to SAP S/4HANA On-Premise



### SAP SuccessFactors Employee Central Payroll

-   Configure Pay Statement \(Direct\) Integration in SFEC and ECP



### Two-Tier Accelerator

-   Integration of S/4HANA Cloud Public Edition with S/4HANA On-Premise using BTP



### Business Transformation Center

-   Setup Integration of Business Transformation Center with ECC and S/4HANA On-Premise

