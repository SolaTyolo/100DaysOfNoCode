# Database Design - Day34

Hello there!! 👋

[Harold](https://twitter.com/hdkstr) here again. 

Welcome back - today we're going to be doing some prep before we start building in the coming days. 

# Task for today 🚀

The ultimate goal of this path is to build a directory site: a page that lists information you've stored, for example with restaurants, hotels, books or no-code tools.

We will show this to our visitors who come to our site built with Softr. Before we can do that, we first have to create a database that stores all data we need for our project, which is what we'll be planning for today.

📝 **Task type**: Planning

🧱 **No-Code Learning Sprint**: Research / prep

⏲️ **Estimated time**: 30 mins

🛠️ **Tools**: [Whimsical](https://whimsical.com/)

👇 **Steps...**

1. Read [this article](https://blog.airtable.com/what-is-a-relational-database/) to get to grips with the basics of databases. 

But before you dive into Airtable to set this up right away, we'll first create a visual overview of the information we need. This will help you set up your Airtable database in a structured and efficient way, and prevents you from getting lost between all tables and fields. It serves as your blueprint.

Make sure to open up [this template](https://whimsical.com/entity-relationship-diagram-RBkRErQpeqx343tTnLktqo) in Whimisical before moving forward. 

2.  Preparation

  + Clear the tables and remove the connections between them
U+ se one seperate table for every subject you'd like to show on your site. Remove redundant tables, or add extra tables when needed.
+ Put the subjects (title) on the first row in the middle column of the table. For example:
  
    - **Tools** for a table with a list of No-code tools
       
    - **Products** for a seperate table with products built with those tools (Products)

+ Add an extra colum to all tables


3. Add attributes to tables

+ Now list all attributes you want to use to describe those subjects below the titles. For example: Tool Name, Tool Website, Tool Logo etc.
    - In doing so, always start with a unique identifier, for example Tool ID, Product ID or Creator ID. This is the primary key of a table (PK)
+ Do this for all tables you have
+ Only list attributes in a table that are related to that specific subject.


4. Connect tables

+ When you have more than one table, you can now connect them to eachother to show the relationships
+ Then also specify the type of relationship, like you've read in the article above (one-to-one, one-to-many, or many-to-many). For example:
    - A tool can be used to build multiple products, and products can be built using multiple tools (Many-to-many)
    - When focusing on indie creator (solo), this creator can make several products, but each product only has one creator (one-to-many).
+ Finally add the subjects of the connected tables as foreign keys (FK) at the bottom of the other tables. Checkout the example below...

![](https://ci3.googleusercontent.com/proxy/LYJuFkwJzJg4ATvZh5AfPm3Kc6lOLS-yheO63ZVRY-2PsnalBgOsL10l0wWtEbnkzTyynfB0FXREMwctNz31xWNBShkiL3ZZY9cbCxieFeJP8xoQgL0HjWB1W-CgtTE5lpEXD3qX9gUh_FDN9yM=s0-d-e1-ft#https://bucket.mlcdn.com/a/2070/2070180/images/84a0eb0c4ab9798f85395496dcd84b757634f8d0.png)


5. That's it for today. We already have a nice overview of the structure of our database now

# Sneak Peek 👀
Tomorrow we are going to add the third columns of the tables as we are prepare to implement in Airtable.