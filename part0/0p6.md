```mermaid
sequenceDiagram
    participant browser
    participant server

    Note over browser: Creates new note from form
    Note over browser: Adds new note to notes list
    Note over browser: Re-render notes list

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    
```