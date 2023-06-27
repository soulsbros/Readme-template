# Project name

## ℹ️ Description

This app does things, so that other people are able to do things.

The frontend is exposed at https://myapp.example.org.

## 🔗 Dependencies

- database X
- external service

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
