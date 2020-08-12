# "GIMME PIZZA!" Project #
***

Welcome, **DEV**!

We expect to address all your concerns and doubts in this document, but if you need any assistance, take a look at **Who do I talk to?** section.

We wish you a great journey and we hope you enjoy this project like we do, cause we lo__<3__ pizza! LOL

***
## What kind of features should this project contain? ##

1. Create configurable Order registration
	* Auto-generated Order number
	* Whole pizza or Half'n'Half
	* Thin-Crust or Thick-Crust pizza dough
	* Extra sauce
	* Pizza flavors (consider six options of your preference)
	* Observation ("Send message to client prior to delivery", "Exchange black olives for green ones", etc)
2. Create basic client registration
	* Full name
	* ID (CPF)
	* Contacts (email, phones)
	* Client address
	* Delivery address
3. Allow delivery to be customizable
	* Scheduled Order (Mon~Sat, from 6PM to 12AM with a 2H window)
	* Delivery address can be different from the registered client address
4. Import pizza Order from a XML or a JSON file (feel free to define the message format)
5. Create Order workflow (suggested statuses: OPEN, CONTACT CLIENT, PREPARING, OUT FOR DELIVERY, CANCELED, DONE)
	* Allow Order configuration by the system owner in OPEN and CONTACT CLIENT statuses
6. Provide list and bucket (by status) views of Orders (consider pagination)
7. Provide Order details view (must be separated in client data, pizza data and delivery data sections)
8. Enable Orders filtering by Order number and by ID (CPF)
9. Enable batch changes to Orders status
10. Export Orders to a file (preferably to a sheet)

Now, if you have **ninja skills** and you are like this guy:

![Alt text](https://media1.tenor.com/images/071073537a1f211c0fe4fa680a836bfb/tenor.gif?itemid=4996013 "Challenge Accepted")

## Here are some extra stuff you can do to show your commitment and your "AWESOMENESS": ##

1. Create a dashboard with a few informations:
	* Number of Orders in PREPARING status
	* Number of the last delivered Order
	* Number of scheduled Orders for the day
	* Most ordered pizza flavor historically
2. Provide "Orders of the day" view
3. Provide Order history view by client
4. Export client Order history to a sheet

***
## What you don't need to consider ##

YOU **SHOULD NOT** CONSIDER:

1. Shopping cart view
2. Pizza prices or anything related to products value
3. Architectural concepts and complexity related to the back-end API
	* All you need to do is expose a simple API to serve the data to your front-end (resource endpoints)
	* If you prefer, the data can be mocked or saved in a file or in an in-memory structure. There is no need to create a database or to worry about data modeling concepts

***
## So, what's the idea behind this project? ##

Well, basically, what we expect is that you are able to create a project which allows the system owners to register pizza Orders and to be able to follow these Orders workflow through facilitated and comfortable views. 

In this way, they will be able to have a well organized environment that helps them on their business decision making.

This is specially important, because, in short, the tasks described here reflect what you will do in a daily basis at Frezze and this is essential so our business can thrive!

***
## What guidelines do I need to follow? ##

1. There are no restrictions regarding any frontend or backend development frameworks used in this project
	* Feel free to choose the stack that most suits you. Yet, it's important for you to know that Frezze's applicatons are currently developed in Angular + Spring Boot
2. The source code must be available through a public project in any Git repository hosting service of your preference
3. The provided repository must contain a README with a brief explanation about the project and with the steps in order to run the project successfully
	* Include any details if needed
	* Docker images are welcome
4. Both application (frontend and backend) must be accessible through the cloud
	* You may use any cloud service of your preference (Firebase, Heroku, DO, AWS, etc)
5. For the evaluation process, we will consider the following:
	* Developed features
	* Applied principles regarding frontend technologies (HTML, CSS, JS)
	* Clean code and code maintainability
	* Best practices
	* Componentization
	* Developed tests
	* Frontend application design
	* Applied concepts in the backend development (be it a REST or GraphQL API)

***
## Who do I talk to? ##

If you have any concerns, doubts or requests, please, feel free to reach us out through:

- [Elton's Email](elton@frezze.com.br) || [Elton's LinkedIn](https://www.linkedin.com/in/elton-a-soares/)
- [Felipe's Email](felipe@frezze.com.br) || [Felipe's LinkedIn](https://www.linkedin.com/in/felipemantovanello/)

***

**Now, off to work!!!**

![Alt text](https://media1.tenor.com/images/44826c0ff7a64db5896ad728237d8ecd/tenor.gif?itemid=4903969 "Crazy Typing")


**PS: If you prefer to develop a similar project related to another subject, let us know. We are opened to any ideas!**

