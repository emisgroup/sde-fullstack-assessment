# SDE - Full Stack - Technical Assessment

We connect patients and healthcare professionals through integrated, ground-breaking technology, helping people live longer, healthier lives.

## Assessment

Create a frontend application that displays patients and their details.

As a stretch goal you could replace the mock API with an appropriate middleware solution. This can still use the `./data/data.json` file as a DB.

You will have 1 week to complete this task.

We are only looking for an MVP, but feel free to take this as far as you'd like.

## Provided Materials

We have provided the following resources:

- In the `/application` directory is the output of `npx create-react-app --template=typescript`.
  - You can run the current solution with a `npm run start` in the `/application` directory.
- In the `/data` directory is a mock API [JSON Server](https://github.com/typicode/json-server) that serves patient data. The Mock API serves the following endpoints:
  - You can run the current solution with a `npm run serve` in the `/data` directory.
  - `GET /patients`
  - `GET /patients/{id}`
  - `POST /patients/{id}`
  - `PATCH /patients/{id}`
  - `DELETE /patients/{id}`

## The Solution

Your MVP can use any of the following technologies along with any frameworks or libraries you feel appropriate:

- Frontend - Typescript, React
- Middleware (Stretch Goal) - Typescript / Golang

## Submit The Solution

Create a public GitHub repository and push your solution including any documentation you feel necessary. Commit often - we would rather see a history of trial and error than a single monolithic push. When you're finished, please send us the URL to the repository.

We suggest you do not fork this repo, as your fork will be easily visible to other candidates.
