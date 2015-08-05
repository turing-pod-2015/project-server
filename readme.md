# Backend team

This is the codebase for the backend team.

You have the largest job: create a database, make it scale well, provide useful
APIs for access to the database, and work with the algorithms team to get
appropriate data to provide the frontend team. Your first priority should be to
get a dummy server set up so the frontend team can start building with (fake)
  test data; after that, get it right.

The other big responsibility you have is to design a secure accounts system.
Data should follow its owner around securely, and under no circumstances should
data leak. Think carefully about this -- security involves a lot of lateral
thinking to outsmart your exploiters.

Things to think about:
* Does it scale?
* Does this feature have a sensible API?
* Does everything need a function call? What should and shouldn't be made
  public?
* What do you need to store? How should you store it? When retrieving data, what
  would work best for the receiving team, raw data or a more advanced data
  structure?
* Is it secure?
