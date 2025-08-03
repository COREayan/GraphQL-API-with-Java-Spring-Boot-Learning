**Introduction to GraphQL**

What is GraphQL? 
- GraphQL Stands for Graph Query Language. It was developed by Facebook.
- It is an open-source data query and manipulation language for API. 
- Like SQL here we use query to fetch the data. You have flexibility which data to fetch.

What is GraphQL query? 
- GraphQL query is used to fetch the data. 
- You can compare it with GET REST APIs.
- GraphQLQueryResolver Interface is used. 

What is GraphQL Mutation? 
- GraphQL Mutation is used to alter the data i.e, Create, Update OR Delete. 
- You can compare it with POST, PUT and DELETE REST APIs. 
- GraphQLMutatinResolver Interface is used. 

What is GraphQL Schema? 
- Schema provides flexibility too consumers that which attributes they want in response. It has .graphqls file extension. 
- Define which attributes are there in your class with data type. 
- Contract between consumer and provider on how to get and alter the data for the application. 
- Schema is collection of GraphQL types. Query and Mutation are root types in schema i.e entry point for the application.

GraphQL vs REST API.
- REST is having fixed response while GraphQL provides flexibility to consumers that which attributes they want in response. 
- Over and Under fetching with REST API. 
- REST has different http methods and separate endpoint for each API while in GraphQL we have Query and Mutation and there is only one endpoint. 
- GraphQL needs Schema file while REST does NOT need that.