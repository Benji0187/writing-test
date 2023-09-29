# Create a checkout session

To make a payment you have to create a checkout session. A Checkout Session can be opened in many different ways. Before you can create a session you have to decide which recipient you want to use for the session. Recipients (or portals) have a three-letter ID like “FWU”. This is the code you need for the checkout session. You can look up those codes by searching for the name of the recipient in the system You also need to provide payer information (optional). This payer information can be changed later by the payer. 

In total you need the recipient ID, the payer information, and an order number. From all of this you can create a payment and charge a payer, either charging their bank account or credit card. You enter all the information in the UI and click on “Create Session”. This session invites your payer to look at their payer information (they will be sent a link) and change it if needed. 

After your payer confirms the payment details you can create the payment, and the payer will be charged and funds will be transferred from them to Flywire. 

Order numbers are unique to each order and can be obtained by looking up available orders in the system. Not every portal can use every order number, it depends on the country of the portal and Unset the order, they need to match. Refund IDs are unique to each payment and are only available after a refund is initiated. 

You can see all the payments you have created in your Payment Dashboard.