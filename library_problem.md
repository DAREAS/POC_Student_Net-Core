# Library of the Antom City - Beginner

 The library of the Antom City need a API to catalog your books.
 This API have to follow any requisits:
 
 1 - One channel for registration of:
   a - actors;
   b - publishing company;
   c - books
 
 2 - One channel to update data of:
   a - actors;
   b - publishing company;
   c - books
   
 3 - One channel to list data of:
   a - books;
   b - actors;
   c - publishing company;
   d - all books by actor name;
   e - all books by publishing company;
   
   
 ## Observations
  
  Use .NET Core.
  No need use database. Use memory chache, memory database or object with data
  The library has a system that consumes data of an API.
  The new API only needs provider links for the actual system to consume new data.
  No necessary forms of input.
  In your push branch you have an archive to specify an API contract to POST, GET and PUT.
