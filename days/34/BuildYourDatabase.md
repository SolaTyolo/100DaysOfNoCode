# Build your Database - Day34


Hello there!! 👋

Lachlan here again.

In today’s learning path, we’re going to build out the database for our custom CRM in Bubble.

When you’re creating a product with Bubble, I personally recommend taking the time to first start by structuring your database. The database structure will ultimately determine how the rest of your application is built and performs.


# Task for today 🚀

📝 **Task type(s)**: Building

⏲️ **Estimated time**: 30 mins

🛠️ **Tools**: Bubble

👇 **Steps...**

### 1. Preparation

Throughout my last email, we’d not only registered our own Bubble account, but I’d also given you free access to my video course - How to build a Salesforce clone using Bubble.

Throughout this course, I have a dedicated module ([module 2](https://lachlankirkwood1.podia.com/view/courses/how-to-build-a-salesforce-crm-clone-with-no-code-using-bubble-video-course/884914-2-configuring-your-database)) that walks you through the exact database structure you’ll need to build a custom CRM.

### 2. Identifiying your data types & fields

When creating your own custom database, you’ll first need to identify what things you’d like to store as a data type, as well as what information you’ll need to add within each data type as data fields.

**Data types**: A data type is an overarching thing you’d like to display within your app. If a user ever needs to create something (e.g. an account, a post, an activity), this should be listed as a data type.

**Data fields**: Within each overarching data type, you’ll then need to identify what specific information should be stored inside this. For example, if you’re creating a data type for a customer, you’ll need to store information such as their contact name, their email, phone number, etc.

![](https://ci3.googleusercontent.com/proxy/mrhW7S9iszpcHLUSeaePC7BNfZO4fTYVAB6Th8pjPZnoto4-52L5HRcom_l7rR03VoC-ZfsFo3RW208hqyiti_64C2jXCAlVHJxz1ZFu6V_z1vWG-3MYIQGC-OkHzvUmgTFtrn5gf5lEFEQDS4w=s0-d-e1-ft#https://bucket.mlcdn.com/a/2070/2070180/images/bd0d5d33f2c4641efbeb87bf07eef0e0687f2a59.png)

### 3. Linking data types

What I love about Bubble is its ability to create truly relational databases. In short, this means that you can connect different data types together in order to cross-reference information.

For example, under our activity data type, I’d like to reference which customer this activity event should be associated with. By creating a data field called ‘customer’, I can reference the existing customer data type. This would allow me to then access all of the data fields within this data entry to retrieve information like the customers name.

![](https://ci6.googleusercontent.com/proxy/8A_QPRrAfTIB6mmphEU1LpIpnwoCbXx3ZqA3aFhjGjQGenVj8v0qzl7Gq2z3ZUiAqsFhAYKVBRSDR8_iHodY_UoMr9RJBbAPYmve7tUNEBIuACJydAORsiQWw4mWpXe0FVRULu0gXKxnpgmqkqQ=s0-d-e1-ft#https://bucket.mlcdn.com/a/2070/2070180/images/7afd0d65eda4877656253861becd29dd4deb927e.png)


# Sneak Peek 👀
Tomorrow we’ll create a way to register team member accounts within our CRM.