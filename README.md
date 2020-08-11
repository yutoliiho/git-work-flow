# Phase 0: build an app plan
- pick an app and component;
- Define your API, pick a DB and design your Data Shape;
  For each service:
    Pick your features (base + stretch)
    Define your API
    Choose a DB and develop a schema

# Phase 1: build your service
- Generate "realistic" mock data (for 100 primary records) and load it into your DB with faker;
- Build a server that can serve an index.html file which then loads the app and renders it to the page (using react and webpack-dev [development] and webpack [production]);
- PORT 2046;
- Build an API that the React component will use to fetch data based on an item's ID and/or name.
  - Your server must be able to serve up the correct content by an item's ID and by that item's name. Note: this requirement has considerations for both your API design and your url decisions.
- Write tests to ensure your API works correctly and your component(s) render correctly
  - Jest will help you measure code coverage of your tests.


<!-- Required Tech START: -->
Express
Database (MongoDB or MySQL)
Webpack (production)
Webpack-dev (development)
React using Styled Components or CSS Modules
You must style your components use Style Components or CSS Modules
Do not use any jQuery UI components: instead opt for using React Libraries for subordinate UI components
Enzyme (for React) + Jest
Travis or Circle CI
<!-- Required Tech END: -->

