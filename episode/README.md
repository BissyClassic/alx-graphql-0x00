# Episode Queries

This directory contains GraphQL queries that fetch specific episodes from the Rick and Morty API using their IDs.

## Endpoint
https://rickandmortyapi.com/graphql

## Files
| File | Description |
|------|--------------|
| episode-id-1.graphql | Query to fetch episode with ID 1 |
| episode-id-1-output.json | Output for episode ID 1 |
| episode-id-2.graphql | Query to fetch episode with ID 2 |
| episode-id-2-output.json | Output for episode ID 2 |
| episode-id-3.graphql | Query to fetch episode with ID 3 |
| episode-id-3-output.json | Output for episode ID 3 |
| episode-id-4.graphql | Query to fetch episode with ID 4 |
| episode-id-4-output.json | Output for episode ID 4 |

## Example Query
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}

