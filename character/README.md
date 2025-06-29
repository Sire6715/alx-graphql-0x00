# Character Info Queries – GraphQL

This directory contains individual GraphQL queries that fetch information about specific characters from the Rick and Morty API.

## Objective

Use the `character(id: ID!)` field to fetch data for character IDs 1 through 4. The fields included in the queries are:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## Files

Each query file (`.graphql`) corresponds to a specific character ID and has a matching output file (`.json`) with the API response.

## Running the Queries

Use any GraphQL client (like [GraphiQL](https://rickandmortyapi.com/graphql), Postman, or Apollo Studio) to run the queries.

Endpoint:
