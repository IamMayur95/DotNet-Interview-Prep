# Cloud

1.	What are the types of azure functions?
2.	If an Azure Key Vault secret is used in a connection string and that secret reaches its expiration date, what happens to the application using it?
3.	Explain the process of white listing an ip using bastion and how connection from VM was established?explain the the VNET creation
4.	How will you trigger ADF pipeline
5.	Differentiate between azure topics and queues
6.	Differentiate between azure logic app and function app

# .NET Core Concepts

7.	EFcore DB context is scoped then why ? What if i make it singleton what will be the issues
8.	What is scoped , addsingleton and addtransient 
9.	What are different configuration providers in .net core
10.	IHosted and hosted services in .net core
11.	Grpc call in .net core
12.	How asp.net core handles DI internally
13.	Explain middleware 
14.	What is configure and configureservices
15.	Filters in .net core
16.	Localization and globalization
17.	Difference between useapp and runapp?
18.	What is DI?
19.	Different scopes?
20.	IQueryable and IEnumerable? 
21.	Exception handling globally in an API
22.	Custom middleware if any used in the application
23.	Async and await ? How does it differ from synchronous programming
24.	There is one method which is sync and same method is async then which one will work faster?
25.	Difference between scope and transient in .net core
26.	difference between filter and exception handling
27.	Dependency injection in .net core
28.	How we can define cross platform in .net core
29.	how to add swagger for documentation of API?
30.	.net core features
31.	Routing - Understand attribute vs conventional routing
32.	Custom Middleware - Design custom middleware
33.	Logging - Use built-in logging
34.	Dependency Injection - Explain DI basics
35.	Controllers - Build simple controllers
36.	Exception Handling - Configure global exception handling

# API
37.	How to optimize api
38.	Explain Versioning in API
39.	difference between POST and PUT
40.	Example HTTP PATCH request

# Microservices

41.	Scope of services
42.	Health checks of API
43.	Caching mechanism in api
44.	Event-driven - Kafka, RabbitMQ
45.	Service Discovery - Explain service registry
47.	Communication - REST vs gRPC basics
48.	Resilience - Circuit breaker pattern
49.	Basics - Explain microservices concept

# Authentication and Authorization

50.	Authentication and authorization , jwt?
51.	How does JWT token works?
52.	What happens when JWT is expired and what will be the result?
53.	What is the difference between authentication and authorization in .net core?
54.	different ways to authen and authorize users for a web api
55.	you give a simple code example in c# on how to implement oauth 2.0
56.	Authorization - Role-based authorization

# C-Sharp and concepts

57.	What is sealed class?
58.	Conepts of OOPS – Inheritence? – Coding question
59.	What is the difference between out and ref
60.	What is the difference between abstract class and interface?
61.	Improve the below code
public string GetData()
{
    HttpClient client = new HttpClient()	
    var result = await client.GetStringAsync("https://api.com").Result;
    return result;
}
62.	difference between finalize and dispose
63.	benefit of using Generic methods
64.	Async/Await - Implement async programming
65.	Generics - Apply generics for type safety
66.	Data Types & Variables - Understand basic types and usage
67.	Memory Management - Optimize GC usage
68.	Exception Handling - Handle runtime errors
69.	OOP Basics - Explain classes, objects, inheritance
70.	Collections - Use List, Dictionary
71.	LINQ-Query collections effectively
72.	Control Structures - Apply loops and conditionals

# SQL 

73.	Sql questions – 
Get second highest salary
Create table using check constraint
Where clause query
74.	What are indexes?
75.	Left and left outer join , is there a difference?
76.	If there is a query which is returning very time consuming then how to optimize it?
77.	If there is table and gender need to be swaped in single update query then how to do it?
In which situation can we them?
78.	2nd highest salary
select max(salary) 
from Emp
where salary < (select max(salary) from Emp);

# EF Core

79.	Add , Attach and Update of EFcore
80.	LINQ query to get emp which are having salary greater than avg salary of the group
81.	can you explain lambda expressions with example
82.	Write the code to count frequency of the char in a string
83.	how to write raw query in entity framework
84.	What are different Entity framework approaches?

# Design patterns

85.	What do I need to do make API scalable ? what design patterns is to be followed?
86.	Explain repository pattern in .net core
87.	solid principles in .NET with example.
88.	Singleton - Ensure single instance usage
89.	Factory - Encapsulate object creation
90.	CQRS - Command-query separation
92.	Factory - Encapsulate object creation
94.	Dependency Injection Pattern - Inversion of control

# CICD and Docker
95.	Database CI/CD in entity framework
96.	How we can deploy .net core app on linux
97.	how to deploy asp.net app in docker
98.	Explain Docker and Kubernetes

# .NET Framework concepts

99.	How to handle unhandled exception.
100.	explain .Net Framework components
101.	class libraries of .NET FW
102.	explain CLS and how it can help developers
103.	application state , session state and view state in .NET FW
104.	practical implementation of session state
105.	client side session state storage
106.	difference between normal web api and rest api
107.	how to cascade delete in SQL
108.	Reflection - Use reflection for metadata
109.	Performance - Caching basics

# Unit testing

110.	Mocking - Explain mocking frameworks
111.	Advanced Mocking - Complex dependency testing