# DAT250 Assignment 2

## Experiment 1

The first challenge I encountered was how to open a project in IntelliJ as a maven project, but I found out quickly that I only 
needed to open the "pom.xml" to correctly get a maven project. After I changed the path in * persistance.xml * the main method ran without any errors. 
I struggled a little bit about how to inspect the database tables but I first installed the * Derby database server * locally and used the SQL scripting tool "ij" 
that came together with Derby. I did not really like ij so I connected to the database using DBeaver instead ( I also found out that IntelliJ has an integrated database tool, 
but I still prefer DBeaver).


### First database
![Test](https://user-images.githubusercontent.com/42749439/132532968-e4fc3bd2-29af-4f49-a4bf-2f3e2ec4b65c.png)


### Second database
![Experiment 1](https://user-images.githubusercontent.com/42749439/132533518-991a2a77-41d0-4da9-bf24-3171e831e2d6.png)


## Experiment 2

In the second experiment I had some problems with remembering the details around ownership of associations but after I rewatched the video I managed to create the
correct correct database. 


### First try
This was the result of my first try, here there was something wrong with the ownership between Person and Address and I also thought it would make more sense to have
the bank as the owner over the creditcards relationship. 

![Screenshot 2021-09-08 171827](https://user-images.githubusercontent.com/42749439/132537349-b43b1ddc-69e5-4a3a-9d71-ab4622791c1f.png)


### Second try
Here I made Person the owner over Address and Bank the owner over Creditcards so that a join table between creditcard and bank was generated. 

![Screenshot 2021-09-08 171845](https://user-images.githubusercontent.com/42749439/132537394-52b14dc0-38fc-4ae7-8959-45a93324e1a2.png)


## Link to Code

#### Experiment 1

https://github.com/h578031/DAT250Assignment2Ex1

#### Experiment 2

https://github.com/h578031/DAT250Assignment2Ex2







