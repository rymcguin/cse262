Ryan McGuiness

# Date: 8/29/19
## Maven 
* Helps us
	* structure our source code
	* compile our code and produce har
	* manage dependencies and plugins
		* pom.xml file: Project Object Model
* Dont push target folder to the remote repository
	* .gitignore

```
SELECT height FROM kids WHERE age BETWEEN 10 AND 11 AND race = 1
```
SQL
- 
- Declaritive language
	- create, retrieve/read, update, delete/drop

REST
-
- Representational State Transfer is a set of architectural principles by whicch you can design web services and web APIs that ficus on a systems resources and how resource states are addressed and transferred. 
-  4 principles
	1. addressable resources
	1. constrained interface
	1. **Resources with multiple representations**
	1. **communicate statelessly** - Web Service should not keep a client state on the server. It is the responsibility of the client to pass its context to the server and then the server can store this context to process the client's further request.
		- pros
			- Web services can treat each method request independently.
			- Web services need not maintain the client's previous interactions. It simplifies the application design.
		- Cons
			- Web services need to get extra information in each request and then interpret to get the client's state in case the client interactions are to be taken care of.
		https://www.tutorialspoint.com/restful/restful_statelessness.htm