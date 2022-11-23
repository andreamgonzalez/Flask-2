### Conceptual Exercise

Answer the following questions below:

- What is RESTful routing?
-- Is a standard used in crud applications in order interact with servers via resuable and efficient routes. It uses a set of standard directives or "ways" to interact with a server such as Post, Put, Patch, Delete, Get.

- What is a resource?
  -- A resource is a given database table you are trying to access through a server from a database or API. So for example, a Users table with users in it could be considered a resource as it pertains to application and server interaction.

- When building a JSON API why do you not include routes to render a form that when submitted creates a new user?
 -- The intention of json api's is to return data in a json format based on the request. Typically this API will not care how the request is sent so the request can simply be sent as a json object once collected from a form in the front end/client side upon submission.

- What does idempotent mean? Which HTTP verbs are idempotent?
-- A request directive that can be made multiple times that each time results the same result/data as if it were done once. Examples of directives that have idempotence are PUT, PATCH, DELETE, GET.

- What is the difference between PUT and PATCH?
-- Put updates the entire resource while PATCH only updates part of the resource.

- What is one way encryption?
-- One way encryption is essentially encryption that takes place in a manner that cannot be reversed or backwards engineered in order to determine or uncover the original input. This is useful when dealing with sensitive data being stored in a database such as passwords. This is used to protect sensitive data in the case of a security breach or security attack from bad actors.

- What is the purpose of a `salt` when hashing a password?
--To introduce a simple string before hashing an input with the sole purpose of adding complexity to a hashed field/input.

- What is the purpose of the Bcrypt module?
-- Bcrypt is a hashing technology that performs cryptographic hashing, or in other words, non-reversible unique output for a given input such as a password. It adds a factor of randomization to the password hashing because the output generated is enitely unpredictable therefore making it safe to be stored somewhere such as a database.

- What is the difference between authorization and authentication?
-- Authorization as it pertains to applications is the process of confirming that a given user has the permission to make changes or see special details within an application. An example of this is having permission to delete your own images or posts on twitter where as you wont have any authority or permission to delete someone else pictures and posts. Autheticating a user is the process of confirming that the user attemtping to access the application is an actual real user in the systems records/database. This is essentially what is happening when one logs on to any website. 
s
