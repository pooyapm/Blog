---
title: "How to Design Software Products"
date: 2022-08-06T13:00:22+02:00
---

Identify functionality and use cases

This is the complete functionality of your SW system. This is what the system is built for. At this step all the functionalities and use cases of the system must be clarified. Normally, a SW system takes some inputs and then it performs some processing on it and then it returns some output or takes action as the result. 


<figure>
  <img src="/images/competitor-analysis-1.PNG" alt="Competitor analysis" style="margin-left: 15%; width:70%">
  <figcaption style="text-align:center">Competitor analysis based on two features. The first feature is the
  specializing in clothing. The second feature is free/easy return.</figcaption>
</figure> 

Example of static website generator

Identify characteristics of your product and system

<figure>
  <img src="/images/competitor-analysis-1.PNG" alt="Competitor analysis" style="margin-left: 15%; width:70%">
  <figcaption style="text-align:center">Competitor analysis based on two features. The first feature is the
  specializing in clothing. The second feature is free/easy return.</figcaption>
</figure>

Characteristics of the system include attributes such as resiliency, reliability, capacity to handle requests, traffic loads to handle, request handling delays, etc.

Break down the system level functionalities to functions that can be handled by smaller SW components

Now the higher level functions of the system must be broken down to smaller pieces. It is likely there will be many ways to do this. This process must be iterated many times to achieve the desirable design. 

Add building blocks to fulfill the functionalities

Now, add components that can perform these broken down functions

<figure>
  <img src="/images/competitor-analysis-1.PNG" alt="Competitor analysis" style="margin-left: 15%; width:70%">
  <figcaption style="text-align:center">Competitor analysis based on two features. The first feature is the
  specializing in clothing. The second feature is free/easy return.</figcaption>
</figure>

Identify information blocks and data structures
So internal operations of building blocks know where 

Identify interface requirements
Interfaces are operations between entities

<figure>
  <img src="/images/competitor-analysis-1.PNG" alt="Competitor analysis" style="margin-left: 15%; width:70%">
  <figcaption style="text-align:center">Competitor analysis based on two features. The first feature is the
  specializing in clothing. The second feature is free/easy return.</figcaption>
</figure>

Now, for these components to be able to perform their functions and the system to achieve its use cases and functions the components need to communicate with each other. At this step, the requirements on the interfaces for communication between these components must be identified. 

Identify building blocks requirements

Now, identify requirements of the components. Treat these components like your higher level system and do what you did in previous steps. 

<figure>
  <img src="/images/competitor-analysis-1.PNG" alt="Competitor analysis" style="margin-left: 15%; width:70%">
  <figcaption style="text-align:center">Competitor analysis based on two features. The first feature is the
  specializing in clothing. The second feature is free/easy return.</figcaption>
</figure>

Repeat the process for each building block

If needed you can even break down these components and do all previous steps for the new smaller components.

Iterate the whole process to meet the functionality and characteristics requirements

Depending on the functionalities, priorities, specific technologies to use, etc. there must be many ways to design your system. You must reiterate through all these processes to achieve the best design to fulfill the functionalities and characteristics of the system.


