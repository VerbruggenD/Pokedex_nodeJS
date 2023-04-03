# Pokedex_nodeJS
Project for application to Wisemen using node JS. 

# The project

## Description
The client has always been a big fan of the original 151 Pokémon, and would like to have an app that can serve as their Pokédex. They’d like to browse through the Pokemon, search, manage their favourites, and more. The app needs a REST api which needs to be developed.
The’ve provided a list of things they want in the app (required), and also some extra’s (nice to have) if time allows it.
\
Additionally they want this API to:
- Be published in an online Git repository (Github, Bitbucket, …)
- Have clean commits
- Uses some open source packages (don’t reinvent the wheel), but be able to explain why.

## Requirements
A basic list of functionality the back-end should have:
- Implement the pre-defined OpenAPI spec. document (see attachment). This includes calls to:
  - Get a list of Pokémon
  - A Pokémon’s details
  - CRUD calls to manage a team (limited to 6)
- Store Pokémons' information in a database
  - Use an ORM with clearly defined models for each entity
  - Use migrations as needed
- Provide a command to import a dump / seed of Pokémon (see attachment).
  - You may need to transform this data before importing it into your database.
- Provide a command to import a Pokémon from an external service (see docs), given an external ID or name as parameter.

## Nice to have
There are some extra’s the client would like (in order of preference):
Relations in Database
Testing
Authorization for the team routes using a hardcoded token (in Authorization header)
Save images from import (local file storage, database or S3)
Run in Docker
