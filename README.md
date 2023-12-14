# FrontendDevTest

This is a React project made with Vite.
First run npm install to get all dependencies.
Then npm run dev will fire up the project.

index.css contains a css reset.
App.jsx contains the parent wrapper and the table component.
The table component has most of the features. It calls the API, renders the table and data, in addition to but not limited to the Error component and loading message.
Currency is formatted.
The header component is also located in here. It receives the payload and contains the search bar.
Each component has it's own css module with basic classes.
Moreover, there's a css variables file with global color variables.
When the API is first called, the payload is stored in Local Storage. Upon entering in a search query, the payload is modified, and restored via Local Storage.
