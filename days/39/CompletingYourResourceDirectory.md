# Completing your Resource Directory - Day39


Hello there!! 👋

[Harold](https://twitter.com/hdkstr) here again. 

We're ready to finish our directory site today!

We started with a database scheme in Whimsical and then built it in Airtable. After that, we drafted our sitemap in Whimsical and implemented this in Softr. Yesterday we connected our list blocks from Softr to Airtable, and today we'll wrap this up by linking our list detail blocks to Airtable.

I'm curious what you've built, so feel free to [share your directory site](https://twitter.com/hdkstr/status/1468342989466607617) here with me and let me know what you think of this learning pack 🙂


# Task for today 🚀
📝 **Task type**: Building

🧱 **No-Code Learning Sprint**: Building

⏲️ **Estimated time**: 30 mins

🛠️ **Tools**: [Softr](https://www.softr.io/), [Airtable](https://www.airtable.com/)

👇 **Steps...**

### 1. Why a List Details Block is Useful

When presenting a list of records to your users, there's often not enough space in the list to show all relevant information. In that case, you can connect your list pages to detail pages with more information by means of [list detail blocks](https://docs.softr.io/building-blocks/listing-details). And the beauty of this is that you only have to set this up once and then it automatically creates a detail page for all records on the concerning list page ⚡️

Watch [this mini video](https://www.youtube.com/watch?v=ZDWEV38CE1s) for context, before following the below steps. 

### 2. Connect List Block to a List Details Block

+ Open your list detail page in Softr and click on the list detail block you've added on day 5
+ Since you already connected your account to Airtable yesterday, you don't have to do this again and you can immediately connect it to the right table in Airtable
+ Next, you can map the block to the right fields from Airtable, just like we did with the list block yesterday. Ask yourself what are the additional bits of information I want to show users that I wasn't able to in the list block. 

**⚡ Do you want to show relevant data from other tables here as well?**

Make sure the tables are linked via a Linked Record first. After that you can show the relevant information in the following ways:

+  Add the concerning information in Airtable as lookup fields to the table that is connected to the list detail page. Then map the relevant fields to these [lookup fields](https://support.airtable.com/hc/en-us/articles/360042312194) in your list detail block.
+  Add an extra list block to your list detail page and connect that to the other table you want to connect (for example the table with products that are built with the No-code tools):

    - Add a conditional filter to this new list block

     - Match the linked record from the table used for this extra list block, to the primary field of the table connected to your list detail page itself (the first column).

        + For example, my Tool detail page is connected to Tools table. But I also want to show all products built with a specific tool, so I add an extra list block on the tool detail page that I connect to my Products table. To make sure only the relevant products will appear, I'll add this conditional filter:
            - Tools (my linked record from the Products table) is Tools Tool ID (the primary field of my Tools table).

![](https://ci4.googleusercontent.com/proxy/Hjmq9P7Slk5ol6bsKYJ-BqCEPnDIB9JLVSFdzEPawRc6piwvKNziDR31dJQJvp4HDfXNlSWkaY8cZiX7h6gIgC7CHAdiwjqQMdbowX1GP_AvBic0IWofE3Tebouf4Xu2TXdlTvSRx-m5vdE5_Zc=s0-d-e1-ft#https://bucket.mlcdn.com/a/2070/2070180/images/f568a4fa74e82195502ad6e78d50e1f53f47daa9.png)

### 4. Customise your list details

Finally you can design all sections of your list details block by clicking on the 🎨 icon. 

Repeat the above steps for all list details blocks, if you have more than one. 

 💡 **Tip**: If you made any changes in your database (Airtable), pages or blocks in Softr, I'd recommend you to modify this in your database scheme and sitemap in Whimsical. That way, you'll have one source of truth that you can look back on. 

### 5. Share your progress

That's a wrap! Thanks for participating in this learning path. I hope you enjoyed it just as much as I did 🙂 I'm looking forward to see what you've built, so feel free to [share the result](https://twitter.com/hdkstr/status/1468342989466607617) here. Of course, you can always polish your product, but you'll learn a lot from sharing it early on by building it in public.

Thanks again, and I hope to see you around in the 100 Days Of No Code Community or bootcamps!


# Sneak Peek 👀
Tomorrow you'll be able to pick which learning path you want to take next! 