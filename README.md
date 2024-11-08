# CRUD React Project

This is a simple CRUD (Create, Read, Update, Delete) application built with React. It uses `json-server` to simulate a backend, serving `db.json` on localhost port `3500`.

## Prerequisites

Ensure you have the following installed:
- [Node.js and npm](https://nodejs.org/)
- [json-server](https://www.npmjs.com/package/json-server) (for running `db.json` as a REST API)

## Getting Started

Follow these steps to set up and run the project:

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/YourRepoName.git
cd YourRepoName

npm install -g json-server

json-server --watch db.json --port 3500

npm start
