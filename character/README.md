# Character Queries

This directory contains GraphQL queries to fetch specific characters by their IDs from the Rick and Morty API.

## Endpoint
https://rickandmortyapi.com/graphql

## Files
| File | Description |
|------|--------------|
| character-id-1.graphql | Query to fetch character with ID 1 |
| character-id-1-output.json | Output of character ID 1 query |
| character-id-2.graphql | Query to fetch character with ID 2 |
| character-id-2-output.json | Output of character ID 2 query |
| character-id-3.graphql | Query to fetch character with ID 3 |
| character-id-3-output.json | Output of character ID 3 query |
| character-id-4.graphql | Query to fetch character with ID 4 |
| character-id-4-output.json | Output of character ID 4 query |

## Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
