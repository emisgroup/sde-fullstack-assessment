# SDE - Full Stack - Technical Assessment

As Software Development Engineers at EMIS;

> We connect patients and healthcare professionals through integrated, ground-breaking technology, helping people live longer, healthier lives.

## How can I demonstrate my technical ability?

We'd like you to create a simple Single Page Application (SPA).

The application should meet our [user driven requirements](/requirements/) and showcase your approach to software engineering.

### Bonus

To support your web application, we have provided a mock API.

Replacing this mock API with an actual API would help demonstrate your skills across the full web stack. Your API can still use our [data/data.json](data/data.json) file as its datastore.

## Where do I start?

We have provided the following resources:

- [/application](./application) - an base application generated using `npx create-react-app --template=typescript`
- [/data](/data) - a [JSON Server](https://github.com/typicode/json-server) Mock API, which serves patient data. The Mock API serves the following endpoints:
  - `GET /patients`
  - `GET /patients/{id}`
  - `POST /patients/{id}`
  - `PATCH /patients/{id}`
  - `DELETE /patients/{id}`

Use these resources as a starting point for developing your application.

## Do I need to use specific technologies?

Your solution should use the following technology as it aligns well with our team and projects:

- Single page application - Typescript, React
- API (Bonus) - Typescript / Golang

Beyond this, the world is your oyster! Go as far as you like!

## How do I submit my solution?

Create a public GitHub repository and push your solution including any documentation you feel necessary. Commit often - we would rather see a history of trial and error than a single monolithic commit. When you're finished, please send us the URL to the repository.

We suggest you do not fork this repo, as your fork will be easily visible to other candidates.

## What are you looking for in my solution?

We will use the following criteria to assess your solutions:

1. How effectively does the solution meet our user requirements?
2. Is the solution engineered with a strong attention to detail?
3. How does the solution implement open source software effectively?
4. How does the solution ensure a high level of engineering quality?
