# What are API's - Day33

Hello there!! 👋

[Marc](https://twitter.com/MrMarcFletcher) here.

Congratulations on progressing so far with your 100 days of no-code challenge. Today we're going to be familiarising ourselves with what APIs are, what they do and why they are important for us as no-code builders.


# Task for today 🚀

📝 **Task type(s)**: Reading this article and take a look at the additional reading items

⏲️ **Estimated time**: 45 mins

🛠️ **Tools**: None

👇 **Steps...**

Get ready to learn about the amazing, but sometimes intimidating, backbone of computer communications. The API.

### What is an API?

An API is a set of rules that software programmes use when they talk to each other. There are lots of computer programming languages (JavaScript, Python, Go, PHP etc.) and communication between software built with different languages is the foundation the internet and other computer-based systems. The rules of APIs facilitate this communication.

The three letters ‘API’ are an acronym for the name “Application Programming Interface”. Take a moment to think about what ‘Application Programming Interface’ means, focusing on the individual words and compare your thoughts with some dictionary definitions and my own supplementary explanations.

### What does API stand for? 

**Application**:  “A computer program used for a particular type of job or problem”. Software, like a desktop web browser (Chrome, Firefox etc.) or a smartphone app (Weather, Reddit, Facebook etc.)

**Programming**: “the act or process of planning or writing a program.” Creating the instructions given to a computer or software to facilitate specific actions.

**Interface**: “a surface regarded as the common boundary of two bodies, spaces, or phases”, “to bring together; connect or mesh:” A good, relatable interface example is this: Humans use an operating system (MacOS, Windows, Linux) to communicate with a computer. The operating system, along with a screen and input devices, is an interface; namely, a user interface (UI).

All APIs are not the same. The specific rules of an API are defined by whomever builds the API. Decisions such as the scope of what data is made available, what the format of a request to the API should look like, who can access the data, whether or not new records can be created and how frequent the API can be contacted are decisions made by the API builder. The API rule book that explains these decisions is called the API documentation.

### What does an API do?

Take the scenario of signing up to an Amazon account using a web browser. You navigate to Amazon’s website and click “sign-up”. Amazon will display a form on their website which has empty inputs ready to receive your name, password and other information. When you’ve filled in the inputs, you push the send button. The browser prepares the information you provided and sends it to an API on Amazon’s servers. In this scenario, the API is the rule-book for creating new users. Depending on the rules defined in the API, the API will either accept or reject this request to create a new user. The API evaluates the request and decides if it complies with the API rules. If the request is compliant, a new user will be made. If the request is not compliant, a new user will not be made. The API will always send back a response confirming what has happened. All this happens very, very fast.

### Why are APIs important?

Consider your average daily internet browsing activity for a moment. Every time you visit a news site an API request and response takes place to get the latest headlines. Every time you visit a social media service an API request and response takes place to obtain the most recent posts for your feed. Every time you log in to an e-commerce site an API request and response takes place to validate your username and password. Quite simply APIs are a core feature of computers functioning in a connected globe.

### API Waiter analogy.

A popular, but slightly loose abstraction to explain APIs is one that relates to a typical restaurant experience. Imagine you visit a restaurant with the intention of ordering food to eat. The waiter who works at the restaurant is called, Api. When you arrive, Api checks to see that you’ve made a reservation by asking for your name. You tell him your name. He looks at the reservations book and sees that you previously called and booked a table under the same name so Api shows you to your seat and hands you a menu. You order some food and drinks from the menu by asking Api for a burger and lemonade. Api writes your order down on his notepad and takes the order to the kitchen. A short time later, Api returns with your food and drink which you can then eat.

In this scenario, You are the Client who would like some data (food and drink). With the help of Api and his menu (an API) you obtain authorisation (reservation check) to access the Server’s database (restaurant) and order (request) some data (food and drink). The API’s (Api the waiter’s) behaviour (response) is to bring you the food and drink you ordered.

With a stretch of the imagination, hopefully you can see the relation in communication actions.

### Key API jargon
As you'll be working with API's over the coming days, make sure to get yourself comfortable with the key jargon. Read [this Notion](https://narrow-ixora-7de.notion.site/API-jargon-4aa674b99c13409fa135fe6193e88718) doc to do just tha, plus access some further resources. 


# Sneak Peek 👀
Tomorrow we’ll start a 3-part project to build a waitlist landing page which collects user data and sends it to a database. 