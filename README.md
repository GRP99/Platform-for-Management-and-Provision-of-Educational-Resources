# Information Processing and Representation
<div align="center">
    <img src="view/public/images/favicon.png">
    <h1>Platform for Management and Provision of Educational Resources</h1>
    <br>
</div>

### Goals
* Provide educational resources of various types: books, articles, applications, student work, monographs, reports, ...
* Allow to add new types of features and new features;
* Have the resources sorted by year, type, theme, ... (use of hashtags or a classifying taxonomy);
* Allow a user to make a Post about a resource;
* Allow other users to comment Posts;
* Create a ranking system for resources (stars attribution by users);
---
### How to run
1. Start MongoDB
    1. Create a database with the name "myFiles";
    2. With the help of mongoimport import the files present in this [file](_examples_/_users_/users.json);
    3. Make sure MongoDB is listening on port 27017.
2. Start Authorization-Server
    1. Open terminal and access the following directory "[authorization-server](authorization-server/)";
    2. Run <code>npm i</code>;
    3. Run <code>npm start</code>;
    4. Check if Authorization-Server is listening at the port 3000.
3. Start API-Server
    1. Open terminal and access the following directory "[api-server](api-server)";
    2. Run <code>npm i</code>;
    3. Run <code>npm start</code>;
    4. Check if API-Server is listening at the port 3001.
4. Start View-Server
    1. Open terminal and access the following directory "[view-server](App/view-server)";
    2. Run <code>npm i</code>;
    3. Run <code>npm start</code>;
    4. Check if API-Server is listening at the port 3002.
---
### Dependencies
* **[Node](https://nodejs.org/en/)**
* **[Mongo](https://www.mongodb.com/)**
---
### Team
![Gonçalo Pinto][grp-pic] | ![Diogo Pereira][diogo-pic] | ![Francisco Lopes][chico-pic] | ![Luís Ribeiro][luis-pic]
:---: | :---: | :---: | :---:
[Gonçalo Pinto][grp] | [Diogo Pereira][diogo] | [Francisco Lopes][chico] | [Luís Ribeiro][luis]

[grp]: https://github.com/GRP99
[grp-pic]: https://github.com/GRP99.png?size=120
[diogo]: https://github.com/dpereira7
[diogo-pic]: https://github.com/dpereira7.png?size=120
[chico]: https://github.com/chico2911
[chico-pic]: https://github.com/chico2911.png?size=120
[luis]: https://github.com/luis1ribeiro
[luis-pic]: https://github.com/luis1ribeiro.png?size=120

<div align="center">
  <sub>September 2020 - January 2021</sub>
</div>