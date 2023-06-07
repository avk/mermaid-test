This should show a Mermaid diagram below.

```mermaid
erDiagram
    TITLE {
        int title_id PK
        int type_id FK
        string name
        datetime release_date
    }

    TITLE_TYPE {
        int type_id PK
        string type
    }

    TITLE }|--|| TITLE_TYPE: has
 ```
 
 All done with my Mermaid diagram.
