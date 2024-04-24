[Back](README.md)

# Infinite Craft Plus High Level Architecture

```mermaid
graph TD
  subgraph " "
    userInterface[User Interface]
    gqlApi[GraphQL API]
    sqlServer[PostgreSQL Server]
    sqLite[SQLite Cache]

    userInterface <--> gqlApi
    userInterface <--> sqLite 

    gqlApi <--> sqlServer
  end
```