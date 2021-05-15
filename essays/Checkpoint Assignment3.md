---
layout: essay
type: essay
title: Checkpoint Assignment #3
# All dates must be YYYY-MM-DD format!
date: 2021-05-05
labels:
  - E7
  - ITM
---
https://youtu.be/0dtfIXmW4pg


Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype
	
Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.


Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.
I will store user’s input to the to the session, and make the user’s input sticky on the textbox. So the user can easily modify the quantity that they desire. 
	
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
I will use assign a cookie to the user when the user logged on, and everything then the user request the invoice page, I can use a server function to see if the cookie is defined or not in order to check if they already login or expired.
Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)
I will try to make some customize greeting to the user once they logged in, and by accessing the user_data.json.
If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
I am completing Assignment 3 by myself, and I don’t have a partner.
How are you approaching Assignment 3 differently than Assignment 2?
I think Assignment 3 is more difficult than the Assignment 2 because I need to have really good understanding on working on the Assignment3. I am afraid I will not be able to complete my assignment due to the confusion of the session and cookies.
