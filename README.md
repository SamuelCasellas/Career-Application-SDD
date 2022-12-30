# Career-Application-UML

Contained within this repository is a collection of various UML diagrams that
I have created as part of my database team's deliverable for our SDD to fulfull
the requirements of a comprehensive web application similar to LinkedIn.

These diagrams showcase my expertise in creating UML diagrams commonly used in the tech industry.
These include:
- Class Diagrams
- Component Diagrams
- API Endpoint Table
- Flowcharts
- Pseudocode

# Authorship

Authors are included in the pdf embedded in this repository.

I was one of the four (4) team leaders involved in designing a comprehensive web application.

# Personal Insights

The backend consists of different service layers for different entites.
The different services that can correspond to our application can include job postings, users, companies, etc. 
They each consist of the following:

- Entity
- Controller 
- Repository

The controller is mainly responsible for application flow control logic. Bound to the handler's path,
the controller can call specific methods in specific classes with said path.

The repository for the corresponding entity will then find the information requested for the specific inquiry.
The inquiry is held in a Data Transfer Object (DTO).

For example, in the case of profile service, the repository will find for the student by their id.

[More info on controllers in service layers](https://learn.microsoft.com/en-us/aspnet/mvc/overview/older-versions-1/models-data/validating-with-a-service-layer-cs)

# My diagrams

| Diagram | Diagram Name | Diagram Type | Purpose |
| ----------- | ----------- | ----------- | ----------- |
|  |  |  |  |
|  | CompanyMessagesInterface.studentUpdateMessage() | Pseudocode | Describe the algorithm of studentUpdateMessage() |
