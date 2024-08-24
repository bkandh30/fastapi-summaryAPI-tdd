# fastapi-summaryAPI-tdd

An Asynchronous text summarization API with Test-Driven Development.

## API Routes

| METHOD | ROUTE            | FUNCTIONALITY        | CRUD Method |
| ------ | ---------------- | -------------------- | ----------- |
| GET    | `/summaries`     | get all summaries    | READ        |
| GET    | `/summaries/:id` | get a single summary | READ        |
| POST   | `/summaries`     | add a summary        | CREATE      |
| PUT    | `/summaries/:id` | update a summary     | UPDATE      |
| DELETE | `/summaries/:id` | delete a summary     | DELETE      |
