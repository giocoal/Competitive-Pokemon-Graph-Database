# Competitive Pokémon Graph Database
## Project for the Data Management course

The idea behind the project is to create a database containing all information related to competitive Pokémon videogame, with particular reference to the Video Game Championship Series 12 rules, the official format in effect for official tournaments and events during the period February - August 2022 and valid for the Pokémon World Championship in London in August 2022. The goal is to obtain a useful tool as a support for competitive play, both for novice and experienced players. The different Pokémon are placed in relation to the teammates, moves, tools, skills the basic statistics with which they are most frequently matched within teams in competitive matches. For this reason, the choice on the type of database to be implemented fell on a graph database, implemented through Neo4J. The choice of the graph database allowed us to take advantage of its characteristic of being schema less, which allows us to create nodes, to model the different entities, and arcs, to model the various relationships, without following a predefined schema. The database was populated through data obtained through API and Web Scraping, appropriately integrated and processed.

![PokemonCopertina](https://user-images.githubusercontent.com/80491610/177854097-0d5a62c7-6b56-497f-b2d7-6a467a46ce80.png)
