[Back](README.md)

# GraphQL Diagram

```mermaid
flowchart LR
  element
  elementCombo
  user

  infiniteQuery --> element
  infiniteQuery --> elementCombo
  infiniteQuery --> user

  element --> elementId 
  element --> elementName
  element --> elemenetEmoji
  element --> createdAt
  element --> createdBy

  elementCombo --> e1
  elementCombo --> e2
  elementCombo --> e3

  user --> userName
```