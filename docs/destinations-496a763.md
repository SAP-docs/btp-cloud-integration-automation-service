<!-- loio496a7638dac4430abb033b7a8ce09d8e -->

# Destinations

The automation services to configure target systems make use of the destinations created in the consumer SAP BTP subaccount to which Cloud Integration Automation service is subscribed. SAP BTP subaccount administrator creates and manages these destinations. The destination configuration data is stored only in the consumer subaccount.

Cloud Integration Automation service accesses these configurations while executing automation services for a restricted period.

> ### Note:  
> 1.  By default, a ‘Cloud Integration Automation Service Integration Administrator’ has the authorization to create a destination \(delete or modify of destination not allowed\) in the SAP BTP subaccount where Cloud Integration Automation service is subscribed. Creation of destination in the subaccount can be done from the System Component task in the My Inbox application of Cloud Integration Automation service.
> 2.  Configure destinations to use secure communication protocols, such as HTTPS always!
> 3.  To know more about Destinations, see [Destination](https://help.sap.com/viewer/cca91383641e40ffbe03bdc78f00f681/Cloud/en-US/565fdb3dd19d4cda80864341dc5a0451.html) in the SAP Business Technology Platform documentation.

> ### Note:  
> **Disclaimer**: Cloud Integration Automation service uses SAP BTP destinations to access APIs of the systems to be integrated for automation. Therefore ensure that the users executing the automation are authorized to perform the configuration on the respective systems. Cloud Integration Automation service will instruct you to create respective destinations. Consider deleting those after the workflow has finished.

