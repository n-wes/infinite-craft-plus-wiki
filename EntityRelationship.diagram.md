[Back](README.md)

# Entity Relationships

```mermaid
  erDiagram
    Element {
        bigserial Id PK
        varchar(32) Name UK
        varchar(8) Emoji
        timestamp createdAt
        bigserial createdBy FK
    }
    User {
        bigserial Id PK
        varchar(32) Name
        varchar(100) EmailAddress UK
    }
    ElementCombo {
        bigserial Element1 FK
        bigserial Element2 FK
        bigserial Combo FK
    }
```
