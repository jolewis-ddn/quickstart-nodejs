[![CircleCI](https://circleci.com/gh/jolewis-ddn/quickstart-nodejs/tree/master.svg?style=svg&circle-token=cfcf617dad74100b6dbb3a84078ed4ea760f6c78)](https://circleci.com/gh/jolewis-ddn/quickstart-nodejs/tree/master)

# quickstart-nodejs

Node.js sample application for Screwdriver

## Pipeline

### Fail to Publish

The `publish` job is properly defined in the `screwdriver.yaml`. The package is purposely configured to fail.

Given that this package is basic, we don't want to flood the NPM Registry with quickstart modules. The included `package.json` file contains a `private: true` flag to safeguard against publishing to the NPM Registry.

## Dev

### Requirements

* [NodeJS](https://nodejs.org/en/)
* NPM (included in the NodeJS package)

### Install dependencies

```
$ npm install
```

### Run tests

```
$ npm test
```

