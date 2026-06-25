# TheGamingRoom

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The client was The Gaming Room. They wanted to take their game, Draw It or Lose It, from an Android-only app and turn it into a web-based game that could work on several platforms. The design needed to support teams, multiple players, unique game and team names, timed rounds, drawings, guessing, and a server-based setup so the game state stays consistent for all users. 

What did you do particularly well in developing this documentation?
I think I did well explaining the main requirements in a clear way and connecting them to the design. I also think the client-server setup made sense because it keeps the main game logic on the server while users can play from different devices through a browser. 

What about the process of working through a design document did you find helpful when developing the code?
The design document helped me slow down and think through the structure before coding. It made it easier to understand what classes were needed, like Game, Team, Player, Entity, and GameService. It also helped show where inheritance, encapsulation, and the singleton pattern fit into the program. 

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would revise the evaluation section and make it a little more detailed. I would add more specific examples about cost, user traffic, testing, and how the system would handle a large number of players. That would make the recommendations stronger and easier for the client to understand.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I looked at what the users needed from the game and turned that into design choices. Since users may be on different devices, browsers, and network speeds, the design uses a responsive web application with the game state managed on the server. It is important to consider user needs because the software has to work well for real people, not just meet the basic technical requirements. 

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
My approach was to start with the requirements first, then build the design around them. I used the domain model, system architecture, and recommendations to make sure each part of the application had a purpose. In the future, I would keep using UML diagrams, requirement lists, client-server planning, and security planning early in the process so the design is easier to build and update later.
