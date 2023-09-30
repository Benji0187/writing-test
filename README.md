# Technical Document: Creating a Payment and Managing Payment Sessions

## 1. Introduction

This technical document outlines the process for making payments through a checkout session in a system. To initiate a payment, you must create a checkout session, which can be opened through various methods. This document details the necessary steps and requirements for creating a payment session, including recipient selection, payer information, and order numbers.

## 2. Checkout Session Creation

Before initiating a payment, a checkout session must be created. This session serves as the foundation for the payment process and can be initiated in multiple ways.

### 2.1. Recipient Selection

A crucial step in checkout session creation is selecting the recipient for the session. Recipients, also referred to as portals, are identified by unique three-letter IDs, such as "FWU." This ID code is essential for the checkout session. You can retrieve recipient IDs by searching for the recipient's name in the system.

### 2.2. Payer Information (Optional)

Payer information is an optional component of the checkout session and can be modified later by the payer. While not mandatory, providing payer information can be useful for payment tracking and communication.

## 3. Required Information for Payment Creation

To complete a payment and charge a payer, you need the following information:

- Recipient ID
- Payer information (optional)
- Order number

### 3.1. Recipient ID

The recipient ID, obtained as described in section 2.1, is essential for specifying the recipient of the payment.

### 3.2. Payer Information

If provided, payer information should be included in the payment details.

### 3.3. Order Number

Order numbers are unique to each order and serve as identifiers. These numbers can be acquired by querying available orders in the system. It's important to note that not all portals can use every order number; compatibility depends on the portal's country and must match the order.

## 4. Payment Process

Once you have gathered the necessary information, you can proceed with creating the payment and charging the payer. This can be accomplished through the system's user interface (UI) by following these steps:

- Enter all the required information in the UI.
- Click on the "Create Session" button.

This action initiates the payment session, inviting the payer to review their payer information via a sent link. The payer can make changes if necessary.

### 4.1. Payer Confirmation

After the payer confirms the payment details, you can proceed to create the payment. The payer will be charged, and the funds will be transferred from them to Flywire.

## 5. Order Numbers and Refund IDs

- Order numbers are unique identifiers for each order and can be retrieved by searching for available orders in the system. The compatibility of order numbers depends on the portal's country.
- Refund IDs are unique to each payment and are only generated after a refund is initiated.

## 6. Payment Dashboard

You can monitor and manage all the payments you've created through your Payment Dashboard
