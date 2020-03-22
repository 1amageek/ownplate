# OwnPlate Project

## Overview
This is an open source project for a take-out order service, which allows restaurants to create their own menu + order page. Unlike Caviar or UberEats (which charges 12% to 30% + credit card transaction fee), it costs only the credit card transaction fee (via Stripe, 2.9% + 30cents). 

It is built with Firebase + Vue + Stripe, for productivity and scalability.

## Minimum Viable Product
Restaurants can
 - login using e-mail
 - create its own page, with restaurant name, banner, address, phone number, homepage url
 - enter the menu with prices and tax (and available time)
 - associate a Stripe account (to receive payment)
 - be notified for a new order
 - see the list of pending orders
 - remove orders that have been picked up
Customers can
 - log in using Phone SMS
 - see the menu
 - order items (shopping cart) and pay
 - let the service remember the credit card (via Stripe)
 
## Additional Features
Restaurant can
 - add the theme (colors and font)
 - verify the identity of customer on pick-up
 - send coupons and specials
 - offer royalty program
 - be notified when the customer has arrived 
Customers can
 - specify the pickup time
 - see the status of the order
 - be notified the status of the order
 - give feedback (stars and text)
 - pay tips beforer or after pick-up
 - search Restaurants using text or from map or current location
 - click the address to start the navigation