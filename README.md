# Create and manage a Checkout Session

This topic outlines the process for making payments through a Checkout Session. To start a payment, you must create a Checkout Session, which you can open through various methods. This topic details the steps for creating a Checkout Session, including recipient selection, payer information, and order numbers.

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

#### What happens when the payer confirms their payment details?

When the payer confirms their payment details you can create the payment and transfer the funds from the payer to Flywire.
#### How do I start a Checkout Session?
You create a Checkout Session using the system's user interface (UI) by following these steps:

1. Enter the recipient's recipient identifier.
1. Enter the order's order identifier.
1. Enter the payer's payer information (optional)/
1. Select the **Create Session** button.
1. *Result*: The system starts the Checkout Session and prompts the payer to confirm their payment details.


## Order numbers and refund identifiers

- Order numbers are unique identifiers for each order and can be retrieved by searching for available orders in the system. The compatibility of order numbers depends on the portal's country.
- Refund IDs are unique to each payment and are only generated after a refund is initiated.

## Payment dashboard

You can monitor and manage all the payments you've created through your Payment Dashboard.