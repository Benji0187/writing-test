# Create and manage a Checkout Session

This topic outlines the process for making payments through a Checkout Session. To start a payment, you must create a Checkout Session, which you can open through various methods. This topic details the steps for creating a Checkout Session, including recipient selection, payer information, and order numbers.

## Create a Checkout Session

This section describes the steps you must complete the create a Checkout Session. 

The steps are:

1. [Gather the information needed to create a Checkout Session](#gather-information-for-payment-creation).
1. [Start the Checkout Session](#start-the-checkout-session). 
1. [Confirm the payment details with the payer](#confirm-payment-details-with-the-payer).


### Gather information for payment creation

You need to provide the system with certain information during the Checkout Session creation process. Some of the information is mandatory and some is optional. The information that you can provide includes:

- Recipient identifier (mandatory)
- Order number (mandatory)
- Payer information (optional)

#### Recipient identifier

The recipient identifier that you provide when creating a Checkout Session defines which  recipient receives the payment. A recipient identifier is unique three-letter value, such as "FWU." You can retrieve recipient identifiers by searching for the recipient's name in the system. You must provide the recipient identifier during the Checkout Session creation process.

> **Note**: Recipients may also be referred to as portals. Both terms refer to the same thing. <! --- Why do we have two terms for the same concept? --->

#### Order number

Order numbers are unique to each order and serve as identifiers. You can retrieve order numbers by querying available orders in the system. You must provide the order number when you create the Checkout Session.

> **Note**: Not all portals can use every order number; compatibility depends on the portal's country and must match the order. <! --- I need to clarify what this point means. --->
#### Payer information

You can optionally include payer information. If payer information has been provided, we recommend that you include it when creating the Checkout Session. During the payment process, the payer can change this information.

### Start the Checkout Session

#### What happens when I start a Checkout Session?
Starting a Checkout Session initiates the payment session, and invites the payer to review their payer information via a sent link. The payer can make changes to their payer information if necessary.

Starting a Checkout Session initiates the payment session, and invites the payer to review their payer information via a sent link. The payer can make changes if necessary.

#### What happens after a payer confirms their payment details?

Once a payer has confirmed their payment details you can create the payment
After your payer confirms their payment details you can create the payment, and the payer will be charged and funds will be transferred from them to Flywire.

#### How do I start a Checkout Session?
You create a Checkout Session using the system's user interface (UI) by following these steps:

1. Enter the recipient's recipient identifier.
1. Enter the order's order identifier.
1. Enter the payer's payer information (optional)/
1. Select the **Create Session** button.
1. *Result*: The system starts the Checkout Session and prompts the payer to confirm their payment details.

### Confirm payment details with the payer

#### What happens when a payer confirms their payment details?

After your payer confirms their payment details you can create the payment, and the payer will be charged and funds will be transferred from them to Flywire.

### Recipient selection

A crucial step in Checkout Session creation is selecting the recipient for the session. Recipients, also referred to as portals, are identified by unique three-letter IDs, such as "FWU." This ID code is essential for the Checkout Session. You can retrieve recipient IDs by searching for the recipient's name in the system.

### Payer information (optional)

Payer information is an optional component of the Checkout Session and can be modified later by the payer. While not mandatory, providing payer information can be useful for payment tracking and communication.

## Required information for payment creation

To complete a payment and charge a payer, you need the following information:

- Recipient ID
- Payer information (optional)
- Order number

### Recipient identifier

The recipient identifier, obtained as described in section 2.1, is essential for specifying the recipient of the payment.

### Payer information

If provided, payer information should be included in the payment details.

### Order number

Order numbers are unique to each order and serve as identifiers. These numbers can be acquired by querying available orders in the system. It's important to note that not all portals can use every order number; compatibility depends on the portal's country and must match the order.

## Payment process

Once you have gathered the necessary information, you can proceed with creating the payment and charging the payer. This can be accomplished through the system's user interface (UI) by following these steps:

- Enter all the required information in the UI.
- Click on the "Create Session" button.

This action initiates the payment session, inviting the payer to review their payer information via a sent link. The payer can make changes if necessary.

### Payer confirmation

After the payer confirms the payment details, you can proceed to create the payment. The payer will be charged, and the funds will be transferred from them to Flywire.

## Order numbers and refund identifiers

- Order numbers are unique identifiers for each order and can be retrieved by searching for available orders in the system. The compatibility of order numbers depends on the portal's country.
- Refund IDs are unique to each payment and are only generated after a refund is initiated.

## Payment dashboard

You can monitor and manage all the payments you've created through your Payment Dashboard

| Information | Mandatory or optional | Where to find the information |
|------------------|------------------|------------------|
| Recipient identifier          | Mandatory           | Search for the recipient's name in the system.           |
| Order number           | Mandatory           | Query the available orders in the system.           |
| Payer information          | Optional           | Data 9           |