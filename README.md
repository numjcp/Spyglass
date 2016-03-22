![Spyglass](branding/spyglass-sm.png)

Spyglass provides a simple search interface for your search engine.

# Overview

## Supported search engines

- Elasticsearch
- Solr

## Functionality

- Search input
- Search result lists
- Autocomplete
- Filter groups

- Ability to have multiple inputs or result lists
- Extensible data model allows adding more search engine endpoints.

For a little more background until we get a project page up [go here](http://www.opensourceconnections.com/2013/08/28/investing-in-client-side-search/).

# Trying Spyglass


# Developing Spyglass

Install NPM dependancies

```bash
npm install typings webpack-dev-server rimraf webpack -g
npm install
npm start
```

Navigate to [http://localhost:3000](http://localhost:3000)

To run tests:

```bash
npm run test
```

continuous tests:

```bash
npm run watch:test
```
