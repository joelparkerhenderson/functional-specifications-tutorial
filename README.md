# Functional specifications tutorial

Functional specifications are the blueprint of how a web project or application looks and works. 

Contents:

* [Introduction](#introduction)
* [Why write a functional spec?](#why-write-a-functional-spec)
* [Who writes a functional spec?](#who-writes-a-functional-spec)
* [Define the application](#define-the-application)
  * [What is the application supposed to be?](#what-is-the-application-supposed-to-be)
  * [What is the application supposed to do?](#what-is-the-application-supposed-to-do)
  * [Who is going to be using this application?](#who-is-going-to-be-using-this-application)
  * [What are the metrics?](#what-are-the-metrics)
  * [What are similar applications?](#what-are-similar-applications)
* [Develop models](#develop-models)
  * [User's conceptual model](#user-s-conceptual-model)
  * [Designer's model](#designer-s-model)
  * [Programmer's model](#programmer-s-model)
* [Define the information flow](#define-the-information-flow)
  * [Define the navigational elements](#define-the-navigational-elements)
  * [Diagram the organization of the information (i.e., create flowcharts)](#diagram-the-organization-of-the-information-i-e-create-flowcharts)
* [Create a prototype](#create-a-prototype)
  * [Prototype now or later?](#prototype-now-or-later)
* [Create wireframes and mockups](#create-wireframes-and-mockups)
  * [Patience and diligence](#patience-and-diligence)
* [Crete mockups](#crete-mockups)
  * [Create wireframes for your key pages](#create-wireframes-for-your-key-pages)
  * [Why create wireframes and mockups if we have already have a prototype?](#why-create-wireframes-and-mockups-if-we-have-already-have-a-prototype)
  * [Leave out detail](#leave-out-detail)
* [Create a design document](#create-a-design-document)
  * [Say very little about...](#say-very-little-about)
* [Write the spec](#write-the-spec)
  * [Cover everything](#cover-everything)
  * [Use lots of screen shots](#use-lots-of-screen-shots)
  * [Write concisely, correctly, and consistently](#write-concisely-correctly-and-consistently)
  * [Use the tools and format most comfortable for you](#use-the-tools-and-format-most-comfortable-for-you)


## Introduction

Functional specifications explain in detail what the finished product will do, how a user will interact with it, and what it will look like.

This tutorial on functional specifications is adapted from work by [Allen Smith](https://twitter.com/mojofat)

When you create functional specifications at the start of a project, then you can save time and increase productivity during the development of the project, because your developers can focus on development, instead of also trying to work out the logic of the user-experience. 

Functional specifications also help manage the expectations of stakeholders, such as your clients or your managers. This is because the stakeholders will know more about what to expect. 


## Why write a functional spec?

A key benefit of writing up a Functional Spec is to streamline the development process. 

The developer working from the spec has, ideally, all of their questions answered about the application and can start building it. And since this is a spec that was approved by the client, they are building nothing less than what the client is expecting.

There should be nothing left to guess or interpret when the spec is completed.


## Who writes a functional spec?

You want somebody who is familiar with user-interface issues and web design, familiar enough with technology to know its limitations and capabilities, and someone who is a very skilled and detailed writer. While writing a spec, you will spend much of your time imagining how a user might use a certain feature and how they may navigate their way through the information. 

You need to map this world out visually, and you also have to write out in great detail what this world does; all the while, balancing everything within the current technological limitations and business demands.

The functional spec writer's sole concern is marrying the user-experience with the various departmental, business, and technical requirements of the project.


## Define the application

The information gathering process is the critical step of any successful functional spec. Just as important as the finished document is the thinking process you have to force yourself through in order to begin writing. It makes everyone think about what they are building, why they're building it, who will be using it, how they'll be using it, and what it will end up doing.

At this early stage, everyone may have various shades of ambiguity about what they're getting ready to build and it's unlikely that anyone is in total agreement about what exactly the finished product will do. 

Here is a quick checklist of the general questions you should be asking (and depending on what the project is, you'll probably come up with more specific questions) at this early stage: 


### What is the application supposed to be?

Make sure you have a strong grasp on what the product is before you start anything. Make sure 
the team you're working with, and the management team ultimately responsible for the product, 
also have a strong grasp on what you are all doing. Expect lots of arguing and discussion during 
this stage! 


### What is the application supposed to do?

Identify the main objectives of this project based on its mission critical factors. Typically, there are one or two core pieces of functionality that make up the bulk of the final product with a bunch of other smaller items thrown in. 

Identify the core pieces and make them a priority. A good way to do this is to simply create a list of all the functions you want the application to perform and then rank them based on priority. Do not allow the smaller items to get in the way, but make sure you've made a note of them. 


### Who is going to be using this application?

Find out who the audience is (i.e., who is going to be using this product). Knowing your audience is important in understanding why and how they are going to be using the final application...which is important in defining the scope of the project.

Better yet, create use cases and develop user personas. User personas can be a great tool for allowing you, as the writer, to enter the world of your users and see everything from their perspective.


### What are the metrics?

Most projects have a performance metric attached to them somewhere; e.g., revenue, page views, new members, etc. Make sure this is clearly known from the beginning. It will help focus your approach and the approach of the team as well, because even if you develop a great product it can still be a failure if it doesn't meet its metrics.


### What are similar applications?

If what you're developing is similar to other products out there, it can make your learning curve much easier by researching those applications and discovering what works and what doesn't. 

Make it a point to perform a very thorough competitive analysis. It help you gain speed faster, and give you an idea of what your competition is like and how to do it better.


## Develop models

Developing models is a good way to start distilling all of the information you have gathered so far. Models, by definition, are a good way to convey an understanding of the components that make up a system. 

Teachers frequently use models as aids to explain complex ideas; physicists use atomic models, automobile designers frequently build many models of a new vehicle before creating a prototype. As the functional spec writer, you are responsible for creating information models to help convey the concepts of the application you are developing.

It may be useful to consider creating three different models: User's Conceptual Model, Designer's Model, and  Programmer's Model.


### User's conceptual model

Building this model will be helped greatly by your development of use cases and user personas. Here, you will build a model of your system based around the user's perceptions of the system: not what the system actually is, but how it will be perceived by the user. 

A good example of this is take an e-mail list or a "Clubs" application (like Yahoo! Clubs). The user does not really care whether it is an e-mail list, a club, a web page, or anything. All they care about is the subject: whether that be baseball, german polkas, or Mad magazines.


### Designer's model

The designer's model is really the nuts and bolts model for the functional spec writer. This is where the interface components and relationships to be seen and experienced by the user are defined. It details the available objects in the user's universe and how they can use them to accomplish certain tasks. 

It's easier to try and break things out into objects and classes at this point. I find that when I start doing this, the whole system becomes simpler and less complex. Although this topic is much larger than the scope of this tutorial, we can briefly take a look at an example designer's model. 


### Programmer's model

The programmer's model is typically only relevant to the programmer. Ideally, we would create user and designer models, and then pass those off to the programmer who would then build the application. However, every programming environment has inherent limitations and that those constraints must be 
incorporated into the designer's model. 

What typically works for me is to have a meeting with the programmer assigned to the project and go over the designer's model with them. From that, I can 
usually walk away with a good idea of what we need to change, what we can work around, and what I need to watch out for as we move forward. 


## Define the information flow

To start this process, try and make an outline of everything you currently know. Since this tutorial is geared towards web projects, make a list of all the pages you know will be included at this point. 

Underneath your pages, start listing all of the elements, to date, to be included. For example, you could start listing search fields, login buttons, dynamic and static content, etc. Then make this your beginning table of contents. A lot of this should be easy after creating your models for the application. 

	
### Define the navigational elements

Start creating the "buckets" in which your application is going to be divided up and then identify what is going to be filling up those buckets. Do this from the user's perspective. Seek out what will be your global navigation and how the sub-navigation will work under that to support your user's goals. 


### Diagram the organization of the information (i.e., create flowcharts)

Creating flowcharts can be very handy when trying to work through a lot of information or a very deep navigation set. Anything you develop now will change over time, but ultimately you'll want a thorough flowchart of the application included with your spec. 

Also include the navigational path through the information on this diagram (e.g., parent-child directories, where the user can jump to from each page, etc.). Visio is a good tool for developing technical diagrams and flow charts such as these. 


## Create a prototype

A prototype of a web application is just a set of static html pages put together to show the key pages of the application and the user interface. It allows the functional spec writer to have something close to a working model to test their ideas out on, start focusing on the layout, and 
begin gathering input about the look and feel.

It is debatable in some circles whether you want to create a prototype at this stage or not. For me, I prefer to have one at this point. In the iterative 
process, I believe it helps to have this big picture look at a potential finished product while also seeing how the components of the system affect the overall product.


### Prototype now or later?

Whether you create a prototype now or later, you should definitely have one before you start writing the actual spec. Aside from being a convenience for you and allowing you to possibly iterate your design much faster, it allows your colleagues and stakeholders the opportunity to look at the application and deliver much more specific and useful input about what you are doing. 


## Create wireframes and mockups

The amount of time it takes for you to get to this point is totally dependent on the scope of your project and your team. So far, you've had to spend a lot of time talking to a lot of different people to get input on the various requirements for the application. Don't get frustrated if it seems like it's taking a long time or if it becomes tedious (which it will!). 


### Patience and diligence

Writing the functional spec imposes a lot of discipline on the whole web development cycle and, in turn, can require a good deal of 
patience and diligence upfront to make it through. The time spent now, though, will reap multiple dividends later. In terms of development time, frustration, and money saved by having a document that spells out exactly what the application is and how it should work, it's a small price to pay at 
the beginning to avoid a death march. 


## Create mockups

Now that we have defined our application and mapped out the functionality and information, we're ready to create some mockups. At this point, it is recommended you bring in a graphic designer to develop these for you. Even if you're capable of putting them together, it can be beneficial to have someone else looking through your document and creating these. They'll spot holes in your logic and raise good questions; plus, it will free you up to continue focus on the writing and any final requirements gathering you need to do. A basic process you may want to follow: 


### Create wireframes for your key pages

A wireframe is a mockup of the page that only addresses the layout, not aesthetics. Think of it as the skeleton of your page, and the mockup will add the skin. A wireframe is useful because, at this point, you're still dealing with pure information and flow but you're also starting to understand the relationship of that information as it applies to your application. The spec writer should be creating these. 

Design for the functional requirements, business requirements, and user requirements. Lay your user's needs over the functional and business requirements. If it's not usable, then it's completely worthless to everyone involved. Address the user first and then work in the other 
requirements. Perhaps the hardest part is finding this common ground between the business needs and user accessibility, so do not be deterred. 


### Why create wireframes and mockups if we have already have a prototype?

That is a great question! Actually, what we want to accomplish at this stage (as opposed to the previous one) is a major commitment to the look and feel. The prototype should be created with the thought of being able to throw it away at a moment's notice. It is just there for you to have something to put in your hands, so to speak.

This is the stage where we want to define the look and feel, make critical design decisions (like color scheme, layout, branding, etc.), and get ready to create the design document.

Also, as a designer it can be useful to see your prototype in order to generate ideas faster (i.e., some of the thinking about how everything works 
together has been done) and it can provide a nice starting point from which to work from. Just don't allow yourself to become married to your own work at this point: be open to change and different ideas. 

Now, that's why we create the mockups. The wireframes should simply follow the mockups, and here's why we create them. We are going to be drafting a design document in the next section. As you will see, one of the aims of this document is to allow all stakeholders in the project to see a kind of "Sneak Preview" of the upcoming functional spec.


### Leave out detail

The best way to elicit useful and impartial feedback is to leave as much detail out as possible. Ideally, what you want to do is convey the application and the functionality without bogging the conversations down in discussions of color or branding. This is best done with wireframes. Wireframes are all about getting the right kind of feedback at the right time. So in order to gain useful comments about the layout, navigation, and functionality of the application, we want to strip out as much of the design and visual design as possible. 

If it seems confusing to you to have a designer working on the look and feel while you are putting together a design document with only the wireframes, it may be useful to view this process as a spiral, or iterative, development cycle and not a linear, or waterfall, methodology. 

It has been my experience that I work faster and end up with a better product when I follow this sort of organic approach: letting several facets of the application design process run in parallel and gradually allow the application to sort of rise up on its own through the requirements gathering process. 

The key for all of this working is having a good team and keeping the communication open.


## Create a design document

As stated in the previous section, a design document serves to collect everything we know about 
the application at this point into a kind of pre-functional spec document and allow people the opportunity to review it and give their feedback. You will want to use this document as a tool for building consensus and, simultaneously, managing the expectations of people about what is coming.


### Say very little about...

The key thing about design documents that you want to keep in mind is that they say very little (if anything) about the visual appearance of the application (aside from layout), and they say very little about the specifics of the user experience. If our models from Step 2 are at the 50,000 foot view and our finished spec will be at ground level, then this is somewhere in the neighborhood of 10,000 feet. 

We want to slowly bring the application into focus, reveal some details about the layout and overall structure of the site, and broadly highlight what functionality will be available to the user to do what. Beyond that, you are risking bogging down the project with frivolous discussions that do not matter at this point.


## Write the spec

Certainly, this is the most daunting task of the whole process. You've asked the questions, done the preliminary work, made a few mockups, and now it's just you with a blank Word document (or Framemaker, an XML editor, or whatever your preference may be) and a head full of ideas. 

Throughout the first five steps, you've ideally been taking notes, developed a working outline, and maybe even started writing a few sections as they come up. Although each writer will invariably have their own style, I would like to pass on a few general tips that you may find useful in structuring your document: 


### Cover everything

By this, I mean make sure you've written about every single interaction point that exists in the application. Don't leave anything to guess or assume. It's quite likely that you'll come to a point where you believe you have included everything, only to find you have left out something very obvious. Every link, text field, button, etc. should have a detailed description of what it does and how the user experiences it. 


### Use lots of screen shots

It's usually helpful to slice up your mockups and insert screenshots of the individual elements you may be writing about. And always include a screen shot of the entire page at the end of its section. 


### Write concisely, correctly, and consistently

An economy of words will be appreciated by those who have to read your document and make sense of it all. Additionally, try and break things out into logical components or steps as much as possible. Use proper grammar and consistent terms (e.g., if you use "drop down menu" in one part of your document, don't start using "pull down menu" in another part to mean the same thing). 


### Use the tools and format most comfortable for you

As a spec writer, you still have quite a few decisions make. What tools do you use? What format? What sort of style should you adopt? Etc. Also, you need to take into account how your documents will be used: will they need to be online, will they frequently be merged with other documents (e.g., large technical libraries), do they need to be in a particular format or follow a certain style? 

Really, there is no single correct path for all of this, and it depends on you: the writer. I have frequently used Word, PhotoShop, and Visio to create my specs. This setup has its pros and cons, but I have also found myself in a position where I needed to adopt the system of my employer.or one of their clients, etc.

