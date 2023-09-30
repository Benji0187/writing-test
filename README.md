# Create and manage a Checkout Session

## About Checkout Sessions

This topic outlines the process for making payments through a Checkout Session. To start a payment, you must create a Checkout Session, which you can open through various methods. This topic details the steps for creating a payment session, including recipient selection, payer information, and order numbers.

## Checkout Session creation

Before initiating a payment, you must create a Checkout Session. This session serves as the foundation for the payment process and can be initiated in multiple ways.

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
