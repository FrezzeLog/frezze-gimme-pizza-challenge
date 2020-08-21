# "GIMME PIZZA!" Project #
***

Welcome, **DEV**!

We expect to address all your concerns and doubts in this document, but if you need any assistance, take a look at **Who do I talk to?** section.

We wish you a great journey and we hope you enjoy this project like we do, cause we lo__<3__ pizza! LOL

***
## What kind of features should this project contain? ##

1. Create configurable Order registration
	* Pizza Size (Defined options: P, M, G)
	* Whole pizza or Half'n'Half
	* Thin-Crust or Thick-Crust pizza dough
	* Extra sauce
	* Pizza flavors (Defined options: MARGUETIRA, CALABRESA, PEPPERONI, FRANGO_COM_CATUPIRY, PORTUGUES, QUATRO_QUEIJOS)
	* Observation ("Send message to client prior to delivery", "Exchange black olives for green ones", etc)
2. Create basic client registration
	* Full name
	* ID (CPF)
	* Contacts (email and phone)
	* Client address
3. Allow delivery to be customizable
	* Scheduled Order (Mon~Sat, from 6PM to 12AM)
	* Delivery address can be different from the registered client address
4. Import pizza Order from a XML or a JSON file
5. Create Order workflow (Defined statuses: ABERTO, CONTATAR_CLIENTE, PREPARANDO, SAIU_PARA_ENTREGA, CANCELADO, FINALIZADO)
	* Allow Order configuration by the system owner in ABERTO and CONTATAR_CLIENTE statuses
6. Provide list and bucket (by status) views of Orders (should consider pagination)
7. Provide Order details view (must be separated in client data, pizza data and delivery data sections)
8. Enable Orders filtering by Order number and by client ID (CPF)
9. Enable batch changes to Orders status
10. Export Orders to a file (preferably to a sheet)

Now, if you have **ninja skills** and you are like this guy:

![Alt text](https://media1.tenor.com/images/071073537a1f211c0fe4fa680a836bfb/tenor.gif?itemid=4996013 "Challenge Accepted")

## Here are some extra stuff you can do to show your commitment and your "AWESOMENESS": ##

1. Create a dashboard with a few informations:
	* Number of Orders in PREPARANDO status
	* Number of the last delivered Order
	* Number of scheduled Orders for the day
	* Most ordered pizza flavor historically
2. Provide "Orders of the day" view
3. Provide Order history view by client
4. Export client Order history to a sheet

***
## What you don't need to consider ##

YOU **SHOULD NOT** CONSIDER:

1. Shopping cart view (although it's recommended to think about a checkt-out feature)
2. Pizza prices or anything related to products value

***
## So, what's the idea behind this project? ##

Well, basically, what we expect is that you are able to create a project which allows the attendant to register pizza Orders and to be able to follow these Orders workflow through facilitated and comfortable views. 

In this way, they will be able to have a well organized environment that helps them on their business decision making.

This is specially important, because, in short, the tasks described here reflect what you will do in a daily basis at Frezze and this is essential so our business can thrive!

***
## What guidelines do I need to follow? ##

1. There are no restrictions regarding frontend development frameworks used in this project
	* Feel free to choose the technology that most suits you. Yet, it's important for you to know that Frezze's applicatons are currently developed in Angular + Spring Boot
2. The source code must be available through a public project in any Git repository hosting service of your preference
3. The provided repository must contain a README with a brief explanation about the project and with the steps in order to run the project successfully
	* Include any details if needed
	* Docker images are welcome
4. The frontend application must be accessible through the cloud
	* You may use any cloud service of your preference (Firebase, Heroku, DO, AWS, etc)
5. For the evaluation process, we will consider the following:
	* Developed features
	* Applied principles regarding frontend technologies (HTML, CSS, JS)
	* Clean code and code maintainability
	* Best practices
	* Componentization
	* Developed tests
	* Frontend application design
	* User experience

***
## Right, so where's the API that I'll use? ##

In order to let you focus on what matters - create an amazing frontend application - we rolled out an initial version of our own Gimme Pizza API.

The API is being hosted [here](https://gimme-pizza-api.herokuapp.com).

For more details and informations on how to consume the API, access the [documentation](https://documenter.getpostman.com/view/12428975/T1LV83UP?version=latest).

If you have any doubts or issues related to the API, let us know.

***
## Who do I talk to? ##

If you have any concerns, doubts or requests, please, feel free to reach us out through:

- [Elton's Email](elton@frezze.com.br) || [Elton's LinkedIn](https://www.linkedin.com/in/elton-a-soares/)
- [Felipe's Email](felipe@frezze.com.br) || [Felipe's LinkedIn](https://www.linkedin.com/in/felipemantovanello/)

***

**Now, off to work!!!**

![Alt text](https://media1.tenor.com/images/44826c0ff7a64db5896ad728237d8ecd/tenor.gif?itemid=4903969 "Crazy Typing")


**PS: If you prefer to develop a similar project related to another subject, let us know. We are opened to any ideas!**

