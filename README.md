# Semantic Folder web-ui

This is a self-hosted web UI for [Semantic Folder](https://github.com/WashingtonGT/sf-web-ui) Vector Search Engine.

This UI is supposed to be served by connect the Semantic Folder services.

Main goal of this UI is to provide a simple way to view and manage your knowledge graph.

Similar to [Kibana](https://www.elastic.co/kibana) for Elasticsearch, but does not require any additional services.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

Development mode expects that Qdrant is running on [http://localhost:6333](http://localhost:6333).

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Stack used

- [React](https://reactjs.org/)
- [MUI](https://mui.com/core/)
- [Axios](https://axios-http.com/)
