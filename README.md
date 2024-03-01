# CS230 - Operating Systems Summary

- *Briefly summarize The Gaming Room client and their software  requirements. Who was the client? What type of software did they want  you to design?*

  The Gaming Room, a client, wanted CTS to design a web-based game based on their existing Android application, "Draw It or Lose It". This web-based game should be accessible across various platforms and allow for multiple users to play simultaneously. The key requirements include cross-platform compatibility, user registration and authentication, game instance management, unique names for teams and players, scalability, tech stack compatibility, responsive user experience, and data storage. Aside from transitioning an Android app into a web-based game, the aim was to utilize best practices in software design and architecture to meet the outlined requirements effectively.

  

- *What did you do particularly well in developing this documentation?*

  I clearly outlined the client's requirements and the projects design constraints, making it easy for developers to understand the project's goals. The requirements section is thorough, covering cross-platform compatibility, user registration and authentication, unique naming for teams and players, scalability, tech stack compatibility, responsive user experience, and data persistence. This shows a deep understanding of both the technical and user experience needs for the project.

  

- *What about the process of working through a design document did you find helpful when developing the code?*

  The Domain Model and UML diagram severed as a blueprint when writing the code. By clearly expressing the functionality of each class, and the design patterns, I was able to write the code as effoertless as I am writing this summary. Before this class, it was tempting to get the code right and document it later since I wanted to make sure I was documenting something that works to submit it on time. This time, with the help of the courses structure, I was able to take it step by step and experience the documentation side doing a lot of the ground work when finally sitting down to code.

  

- *If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?*

  I would improve the Evaluation section. It mainly focuses on general advantages and disadvantages without presenting a clear comparison or specific criteria used for evaluation. I would expand on specific resource requirements and add detailed cost comparisons to help the client make an informed decision, regardless of my recommendation.

  

- *How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs  when designing?*

  I used software design patterns to answer the clients needs. They wanted a sole instance of a game, team, and player at any given time, so I implemented the singleton pattern to encapsulate each entity. They wanted unique names for players and teams, so I implemented the iterator pattern to check for existing data. The iterator pattern also traversed through the list of games to ensure only one game instance was active at any given time.

  

- *How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?*

  My initial approach was to utilize various independent algorithms to solve one problem at a time, maybe 2. The technique I will use moving forward is to think in terms of patterns. Understanding the 3 types of design patterns will help me stack patterns to solve common problems. Here, I was able to insert a behavioral pattern (iterator) within a creational pattern (singleton) for the client to encapsulate each entity and provide list iterators to the ones requiring a unique identifier attached to their sole instance.

