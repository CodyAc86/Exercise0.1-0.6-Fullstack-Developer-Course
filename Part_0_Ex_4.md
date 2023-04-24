# Exercise0.1-0.6-Fullstack-Developer-Course
Exercises for Fullstack Developer course part 0
```mermaid
sequenceDiagram  
  browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note;
  activate server;
  server-->>browser: URL redirect;
  deactivate server;
  
  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/notes;
  activate server;
  server-->>browser: HTML document;
  deactivate server;
  
  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.css;
  activate server;
  server-->>browser: CSS file;
  deactivate server;
  
  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.js;
  activate server;
  server-->>browser: JavaScript file;
  deactivate server;
  
  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/data.json;
  activate server;
  server-->>browser: application/json file;
  deactivate server;
  
  browser->>server: GET https://studies.cs.helsinki.fi/favicon.ico;
  activate server;
  server-->>browser: text/html file
  deactivate server;
 ``` 
  
