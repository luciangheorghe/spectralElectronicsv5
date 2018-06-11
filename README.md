# spectralElectronics - New Stuff Everyday - Project for Stream 3 - Code Institute

[![Build Status](https://travis-ci.org/luciangheorghe/spectralElectronicsv5.svg?branch=master)](https://travis-ci.org/luciangheorghe/spectralElectronicsv5)

This project is a Full Stack Web Application - It is a Ecommerce Platform that lets you buy the latest technology.
Users need to access the shop filter what they need and at to cart. Payment is taken securely using Paypal. The users don't need to waste
time loging in. They can buy their products in seconds.

It has been created using Atom IDE and:

-   Django Framework 1.11
-   Includes modules for:

    -   Accounts,
    -   Cart,
    -   Orders,
    -   PayPal e-commerce,
    -   Coupons,

-   Uses media queries for responsiveness
-   WeasyPrint for generating PDF invoices
-   Deployed to Heroku

The design is simple and flat, responsive and easy to understand.

The users have a categories filter that shows the main categories of the products that they can find on spectralElectronics.

The users choose their products after that add them to the Cart. In the next page if there is available a coupon it can be applied.

The last step is the Paypal Payment. If the users have a paypal account ones can pay for the chosen products. They will be delivered together with the invoice.

"Accounts" is not yet fully implemented. The need of logging in for users will be when they will have products to sell on spectralElectronics platform. For the moment they only can buy products without the need of registering. 
"Shop" is the e-commerce page that shows a table of products the user can buy using a one time payment through PayPal.
"Payment" redirects you to Paypal Page where the user can pay.
"Orders" here is where the users create the order with all the products that they love.
"Coupons" if there is an available coupon the users can apply it and get a discount.
"Cart" all the chosen products are stored here until the users decide to go for paymant.
