I. General Qs:
----

**Which repository setup will we use?**
- github

***

**Which branching model will we use?**
- Branch per feature
- Fast fixes or Initial base code are done directly on a Develop / Master branch

***

**Which distributed development workflow will we use?** --D
- We decided to follow the Centralized Workflow because we are all familiar with it - it is clear and easy, but more importantly, it help us achieve our goal - to constantly push new code and pull changes. The Centralized Workflow is the typical flow where there is one repository and all developers push and pull from it. If two people work at the same time and the first developer pushes, the second developer should first pull the changes and then can push to the repository.

***

**How do we expect contributions to look like?**
- Equal contribution between group members

***

**Who is responsible for integrating/reviewing contributions?**
- Diyana

**************************************************************************

II. Technology 
----

**Why did we choose Java?** --F
```...```

***

**Why did we choose Mongo?** --F
```...```

***

**Why did we choose React?**
- Things we considered when choosing a script language for the web app: Time & Resources and Popularity & Support.
1. Time & Resources: We have only one week to refactor a web application that has Register and Login, Profile page and functions to Add Tweets, Follow and Unfollow users .. meaning sending/receiving requests and managing State. The resources was two of us had previously worked with React. Naturally, React was preferred. We considered using Angular or Vue.JS but Angular is not a library, it is an entire framework, meaning everything is done in a specific way rather than flexible (like in React) and thus is very difficult to learn. We do not have the time to learn how to use a new web framework because that is not even the goal of the course / project. We didn't choose Vue.JS because that is a language designed to mostly develop sole web components rather than a full web application, managing state etc. .. Moreover, nobody has any experience with it.
2. Popularity & Support: React has been used and developed for many years and has huge online communities, courses and tutorials meaning we can find all what we may need. We were tempted to try new technology stack such as Go & Gorilla or Elixir & Phoenix or Ruby & Sinatra but given we wouldn't physically have the time to explore it (plus those frameworks are anyway not very rich, nor used), we didn't see any point on spending time on programming logic but rather, as we said before, focus on the Dev Ops part. Either way, if we wanted to focus on the programming logic, we would dive into better security (OAuth service, tokens etc.), Input validation and Testing which we consider way more important for a quality software. Often what makes good / quality software isn't that much the language but the way it is build. And knowing the language and its strengths / weaknesses makes it better.

***

**Why did we choose Azure?** --S&L
```...```

***

**Why did we choose Vagrant?** --V&L
```...```
