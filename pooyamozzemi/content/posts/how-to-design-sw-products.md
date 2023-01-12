---
title: "How to Design Software Products?"
author: "Pooya Mozzemi"
categories: ["Technology", "Product Management"]
tags: ["pooya mozzemi","pooya moazzeni", "software desing", "system design"]
---

Designing large scope and complex software products can be very confusing even for highly competent and
experienced system designers. Also, understanding someone else's code or a product developed by many
developers over many years can be quite complicated and one can easily give up and never really learn and 
contribute to the code base in a meaningful way. Here, I try to explain on a very high level where to start
thinking about the design of a complex software product, and what to consider. It also helps to understand 
the existing products, since you know how it was originally desinged at first place.

I provide the steps of the process which can be followed to design a software system accompanied by a example
for better illustration. This will help you to have a clear understanding of where to start and which
steps to take until completion of your product design.

Where should we start? 

### Identify functionality and use cases

We build the software product to accomplish a functionality. That is our starting point in our product design.

This is the complete functionality of your SW system. This is what the system is built for. At this step all the functionalities and use cases of the system must be clarified. Normally, a SW system takes some inputs and then it performs some processing on it and then it returns some output or takes action as the result. 

I use Hugo static site generator as example in this blog to illustrate the process. What is Hugo? with
Hugo you can use markdown language to create static website fast. You do not need knowledge of html or css or web programming in
in general to create a website using Hugo. This blog is created using Hugo static site generator togteher
with Github pages!!!

<figure>
  <img src="/images/design-sw/sw1.png" alt="Convert functionality" style="margin-left: 40%; width:20%">
  <figcaption style="text-align:center">The highest level of functionality. Convert Markdown language (md 
  files) to statis html pages.</figcaption>
</figure>

<figure>
  <img src="/images/design-sw/sw2.png" alt="First move" style="margin-left: 15%; width:70%">
  <figcaption style="text-align:center">The first move.</figcaption>
</figure>

Knowing to start witht the functionality helps to avoid getting stuck with the first step os software design.
Also, if we want to understand already built complex large code bases we know that the starting point must
be the high level functionality.

Is the functionality of the product the only problem that we need to consider? Or should we take into account
other factors?

### Identify characteristics of your product and system

Handle large traffic. Make a reliable system?

Characteristics of the system include attributes such as resiliency, reliability, capacity to handle requests, traffic loads to handle, request handling delays, etc.

<figure>
  <img src="/images/design-sw/sw3.png" alt="First move" style="margin-left: 15%; width:70%">
  <figcaption style="text-align:center">The first move.</figcaption>
</figure>

Break down the system level functionalities to functions that can be handled by smaller SW components

Now the higher level functions of the system must be broken down to smaller pieces. It is likely there will be many ways to do this. This process must be iterated many times to achieve the desirable design. 


This summarizes the highest level of description for designing our software product. 

What we already have in most cases will be too high level to be implemented directly. So, what should
we do next?

### Add building blocks to fulfill the functionalities

Now, add components that can perform these broken down functions

Identify information blocks and data structures
So internal operations of building blocks know where 

### Identify interface requirements
Interfaces are operations between entities

<figure>
  <img src="/images/design-sw/sw5.png" alt="First move" style="margin-left: 15%; width:70%">
  <figcaption style="text-align:center">The first move.</figcaption>
</figure>

Now, for these components to be able to perform their functions and the system to achieve its use cases and functions the components need to communicate with each other. At this step, the requirements on the interfaces for communication between these components must be identified. 

Identify building blocks requirements

Now, identify requirements of the components. Treat these components like your higher level system and do what you did in previous steps. 

Repeat the process for each building block

If needed you can even break down these components and do all previous steps for the new smaller components.

### Identify and structure the data used by building blocks

### Iterate the whole process to meet the functionality and characteristics requirements

Depending on the functionalities, priorities, specific technologies to use, etc. there must be many ways to design your system. You must reiterate through all these processes to achieve the best design to fulfill the functionalities and characteristics of the system.

Summary

