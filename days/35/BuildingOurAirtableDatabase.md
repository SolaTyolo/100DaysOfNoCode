# Building Our Airtable Database - Day35

Hello there!! 👋

[Harold](https://twitter.com/hdkstr) here again. 

Today we're going to finish our database scheme and implement it in Airtable 🙂!

# Task for today 🚀

📝 **Task type**: Planning & Building

🧱 **No-Code Learning Sprint**: Research & Building

⏲️ **Estimated time**: 30 mins

🛠️ **Tools**: [Whimsical](https://whimsical.com/signup), [Airtable](https://www.airtable.com/)

👇 **Steps...**

**1. Finish the database scheme in Whimsical**

In order to set up your Airtable base in a structured and efficient way, we are first going to complete our overview in Whimsical. To do so, we are going to add the [field types](https://support.airtable.com/hc/en-us/articles/203229705-Guide-to-the-basic-field-types) we'll need to use in Airtable, in the third column of the tables we added yesterday.

+ To create a unique identified for the primary keys (like Tool ID, Product ID), use the [Autonumber](https://support.airtable.com/hc/en-us/articles/360042807273) field type
+ For the foreign keys (the connected tables), use [Linked Record](https://support.airtable.com/hc/en-us/articles/206452848)
+ Depending on the rest of the attributes in your tables, you can add whatever field types you'll need ([reference list](https://support.airtable.com/hc/en-us/articles/360055885353-Field-types-reference))


💡 **Tip**

Linked Record's won't shop up on the pages we are going to build on Softr later. If you want to be able to show information from another table on a subject's page, then you can add [Lookup-fields](https://support.airtable.com/hc/en-us/articles/360042312194) for this. For example, to show the name of the Maker on a product's page.

Since this data lives in the other table(s), I'd recommend giving the lookup fields another color in your database scheme, so you can easily spot them.

![](https://ci6.googleusercontent.com/proxy/Ppx2MrxsA4GTmcC9v9azvDG18OKSzAadG3PX8sOWg-J-UvSIhTg3vWnuVi1LgaCOo35Dr_1kouFRqIbooeGfeOJeQhSdU6-a5RXJ2oVMofcZbeRR-DkerK5SF_bGGQPQevlgBfxkgwKnuxtEV2E=s0-d-e1-ft#https://bucket.mlcdn.com/a/2070/2070180/images/abf19c0c3f3cf79f52a8f789d2db80e1a28a718b.png)


2. **Implementing in Airtable**

    Now you can easily implement this in Airtable:

+ Create your tables
+ Then just copy the field names from the overview we created, and select the field types you have already chosen. 
+ When you add a Linked Record, Airtable asks you whether you want to link it to multiple records or not. Set this according to the relationship you've drafted in your database scheme. Read this article to get further clarity. 
3. That's it for today. We're now ready to build the frontend with Softr, to show this information to our end users


# Sneak Peek 👀

Tomorrow we are going to add some data into Airtable and start building the frontend. 