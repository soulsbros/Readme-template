# Project name

[![pipeline](https://github.com/USER/REPO/actions/workflows/WORKFLOW/badge.svg)](https://github.com/USER/REPO/actions/workflows/WORKFLOW)

## ℹ️ Description

This app does things, so that other people are able to do things.

The frontend is exposed at https://myapp.example.org.

## 🔗 Related projects

Fancy opensource project: https://github.com/things

### Dependencies

- [Stuff API](https://example.org/stuff/api)
- ElasticDB

## 📚 Documentation

https://myapp.example.org/api/swagger

https://wiki.stuff.com/thing

## 🏡 Local development

### ⚙️ Prerequisites

- thing version 2
- otherThing version 99

### 🔧 Installation

```bash
# get the key from cyberark
./deploy-cluster.sh <secret_key>

kubectl helm upgrade install-and-fail --namespace thing

npm install-all-the-things
```

### 🚀 Run locally

```bash
npm run-thing
```

Then open your browser and head to http://localhost:6969

### 🌲 Test locally

Automated tests can be run with:

```bash
npm run-tests --ignore-results
```

If you need to test thing ingestion manually, go to the `Things` tab in the web UI,
create a new thing, and ingest the thing. If you get a green checkmark, it worked!

## 📝 Additional information

### Project-specific thing

This project uses SpecialThing, therefore we do that thing in a different way.

The folder foo contains the mock data for tests.
