@Repository is a Spring annotation that indicates that the decorated class is a repository. 
A repository is a mechanism for encapsulating storage, retrieval, and search behavior which emulates a collection of objects.
The following application demonstrates the usage of @Repository. 
src
├── main
│   ├── java
│   │   └── com
│   │       └── sample
│   │           ├── Application.java
│   │           ├── controller
│   │           │   └── MyController.java
│   │           ├── model
│   │           │   └── Customer.java
│   │           ├── repository
│   │           │   └── CustomerRepository.java
│   │           └── service
│   │               ├── CustomerService.java
│   └── resources
│       ├── application.yml
│       ├── import.sql
│       ├── static
│       │   └── index.html
└── test
    ├── java
    └── resources