---
layout: post
title: "Lab 6 Reflection"
categories: misc
comments: false
author: Sam CT
---


This lab was an interestin one. Some parts were definatly easier than others. I had to look at the specifications of what the client wanted to narrow down and focus on what actually is needed. I had to make some assumtions of what the client was doing with their database outside of customer function. Wether or not the this would be used just on the custormer side but also for the owner to be able to view stock of their items. I also made assumtions that clients could have multiple phone numbers and delivery address. The biggest assumption that I made was how the order fucntion would work. In my sketch each item in the order is in veiwed as an indiviual item in a larger order. So sub-orders that make up a total order.

Here are the user stories I came up with:
<ul>
<li>An owner can view how much of specific food items are in stock. This is a 5 size project. It connects to the customers ability to add items to carts.
</li>

<li>A customer can add a food item to their cart, choosing the quantity desired, special instructions, and substitutes. This is a size 13 project. It connects to the customer purchasing items and how many of the items are in stock. 
</li>
<li>An owner can add a new food item to the items available in the store. This is a size 3 project. It connects to customer purchasing and owner viewing of items in stock.
</li>

<li>A customer can view the items available for sell in the store. This is a size 3 project. It connects to the customer adding the item to their cart. 
</li>
<li>A customer can submit an order with a specific time and date for pick up. This is a size 13 project. It connects to the customer viewing and adding items to cart.
</li>
</ul>

<div align = "center">
<img src="/assets/GrocerySchema.png" width="400" >
</div>



<div align="center">
<img src="/assets/GroceryStoreLucidChart.png" width="400" >
</div>

I do like how the data models turned out. The Lucid Chart was designed based on how I believe the system would work. I had issues with the Schema just labeling and assigning primary and foreign keys but after some trial and error I am happy with how it turned out.