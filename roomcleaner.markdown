I was eager to have some fun with Spring Boot, after my latest project with Spring Cloud.
I was busy with housecleaning the other day, as my roommate asked (for the 100th time in a week): "So, which room do I have to clean this time? Is it the bathroom or the kitchen?"
Suddenly, it came to me that we have no calendar or plan to organize our shifts when cleaning, and I thought: "what if I built a simple application to handle shifts assignments for our house?".
Yeah, I know there's probably some kind of app which is the perfect solution for our needs, but I wanted to write some code. Well, that's what I'm doing right now. 
[RoomCleaner](https://github.com/valgh/room-cleaner) is a web application built with Spring Boot and Spring Data which lets you define users (cleaners), houses and rooms.
Each user can be assigned to a house and then to one or more of its rooms - and he is supposed to clean such rooms. A house is marked as "clean" if all of its rooms are clean - there should be some kind of weekly check or reset, I think.

So yeah, my goal was actually to have some fun with Spring Boot, Spring data and MongoDB. I wrote some Unit Tests to check my repository and some REST APIs which makes use of it and unit-tested them.
I was amazed by how easily the Spring framework lets you define the model, repository and controllers for your application: it simplifies the whole flow, letting the software engineer focus on the design of the APIs - easing the implementation process lets you a lot more time to think about the desing and user experience!

The project is currently ongoing: I defined a few APIs and CRUD actions which might be useful in the future, but I am yet to define much more logic about room and user handling.
I'd also like to implement a light-weight Web UI to interact with the backend, to finally let us define our shifts appropriately.

**UPDATE**: well, I managed to make some time to build and unit-test the core endpoints of the application. There's still a lot to do and improve, but in the meantime, I also added a Swagger UI to describe, document and even test the APIs.
You can find some more details in the README of the repository, as well as some clues on the next steps and activities.
