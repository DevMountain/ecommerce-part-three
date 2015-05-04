eCommerce Project - Part III
=================

## Objectives

The purpose of this application is to build a simple backend using Node, Express, and MongoDB and connect it to a simple front-end Angular application.

During this project you will use Mongoose to create relationships between multiple sets of data.

## Resources
* [Mongoose] (http://mongoosejs.com/)

## The Domain

Most companies sell some sort of product and service. For this project we will simulate buidling an eCommerce application. We will finish this project over the next two days.

Today you are going to create two new schemas, one for Orders and one for Carts.  You are also going to create a relationship between Carts and Products using a reference, a relationship betwen Orders and Products using embedding, and a relationship between Orders and Users using reference.

Use this README for instructions today, but use your codebase and push to your repository from days one and two.

### Step 1: Create new Schemas

Create a schema for orders.  Add whatever fields you feel it might need.  Remember, orders will have two relationships: a reference to a user, and embedded products.

Create the Order model with the schema and export it.

Create a schema for cards.  Add whatever fields you feel it might need.  Remember, carts will have one relationship: a reference to products.

Once you've created your schema, export it (NOT as a model).  Then go to your User model and use the cart schema for the User's cart field.

*Note*:  This may seem confusing.  Technically, you could just define the new fields in the User's schema.  But it's important to know that a schema is just a pattern or blueprint to follow.  It can be used in multiple models.  For clarification on the difference between a schema and a model see [this SO post](http://stackoverflow.com/questions/22950282/schema-vs-model).

**Breakpoint**: You should be able to spin up your server without any errors.  You should also be able to test that your new Order model and new cart schema are working.  You can either create a dummy endpoint and hook it up to your models, or write a script in your server.js file and run it on server load.  Test and make sure that you can create new Orders and add items to a user's cart.

If you've passed this breakpoint, then you have essentially set up your relationships.  Good work!  Let's walk through how you are going to reason about these relationships.

### Step 2: 

### Step 3: 

### Step 4: 

### Step 5: 
