# RESTfulAPI-Toolbox
Quick-start toolbox for RESTful APIs

## REST (Representational State Transfer) Refresher 
In order to qualify as  RESTful and API has to comply with the following rules:
1. Client-server: Separation of data and user interface e.g. logics and presentation
2. Statelessness: No client state is stored on server side. Each request has to be complete in the sense that it cannot draw on any prior client specific information. 
3. Uniformed Interface:
 a. Resource identification in requests
 b. Self-descriptive messages
 c. Hypermedia / Hyperlinks to resources
 d. Enables resource manipulation through representations of of them
4. Layered System: Hierarchical layers constrain component behaviour
5. Cacheability: Response has to specify whether a response is cacheable, i.e. to be used for subsequent requests
6. Code on demand: Server may return optionally executable code, which helps to implement more complex client functions with minimal implementation effort necessary.

Practical Problem: cross origin-sharing, cross site scripting

Template is located [here](template/).

Development tools for API client interfaces are: 
1. Atom: editing JavaScript and html code
2. Postman: To quickly send requests and inspect response, including JSON parse