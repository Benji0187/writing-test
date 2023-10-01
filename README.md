# Create a Checkout Session

This topic explains what Checkout Sessions are and describes the tasks you need to complete to create one.

> **Note**: You can create a Checkout Session using various methods. This document explains how to create one using the system's user interface (UI). 

## Understand Checkout Sessions

### What is a Checkout Session?
Before initiating a payment, you must create a Checkout Session. A Checkout Session forms the basis of the payment process. When you create a Checkout Session you must specify a recipient for the payment and the order number to which the payment is related.

### What happens when I start a Checkout Session?

Starting a Checkout Session causes the system to generate a link and share it with the payer. The system invites the payer to review and confirm their payer information. The payer can make changes to their payer information if necessary.

### What happens when the payer confirms their payment details?

When the payer confirms their payment details, you can proceed to create the payment. The payer will be charged, and the funds will be transferred from them to Flywire.

## Create a Checkout Session

This section describes the steps you must complete the create a Checkout Session. 

The steps are:

1. [Gather the information needed to create a Checkout Session](#gather-information-for-payment-creation).
1. [Start the Checkout Session](#start-the-checkout-session). 


### Gather information for payment creation

You need to provide the system with certain information during the Checkout Session creation process. Some of the information is mandatory and some is optional. The information that you can provide includes:

- Recipient identifier (mandatory)
- Order number (mandatory)
- Payer information (optional)

#### Recipient identifier

The recipient identifier that you provide when creating a Checkout Session defines which  recipient receives the payment. A recipient identifier is unique three-letter value, such as "FWU." You can retrieve recipient identifiers by searching for the recipient's name in the system. You must provide the recipient identifier during the Checkout Session creation process.

> **Note**: Recipients may also be referred to as portals. Both terms refer to the same thing.

#### Order number

Order numbers are unique to each order and serve as identifiers. You can retrieve order numbers by querying available orders in the system. You must provide the order number when you create the Checkout Session.

> **Note**: Not all portals can use every order number; compatibility depends on the portal's country and must match the order. 
#### Payer information

You can optionally include payer information. If payer information has been provided, we recommend that you include it when creating the Checkout Session. During the payment process, the payer can change this information.

### Start the Checkout Session

You start a Checkout Session using the system's UI by following these steps:

1. Enter the recipient's recipient identifier.
1. Enter the order's order identifier.
1. Enter the payer's payer information (optional)/
1. Select the **Create Session** button.
1. *Result*: The system starts the Checkout Session and prompts the payer to confirm their payment details.

## Monitor a Checkout Session 

You can monitor and manage all the payments you've created through your Payment Dashboard.