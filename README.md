## 🚀 Features

- **RESTful APIs** for managing books and users.
- **Real-time updates** with WebSocket using `socket.io`.
- **Modular architecture** for scalability and maintenance.
- **Error handling** and **input validation**.
- **Test coverage** for critical application components.
- **In-memory database support** for testing.
- **Uses-Redis** for cache database.
- **fetchAndAggregateData** written in utils folder 

## 🛠 Setup and Run
1.http://localhost:4000- for Application
2.ws://localhost:4000- for socket connection

### Api Endpoints
1.http://localhost:4000/api/books - create(POST)

2.http://localhost:4000/api/books - getAll(GET)  -  **With pagination and filter**
3.http://localhost:4000/api/books/87fecfea-0e8f-4820-b1dc-34ebacf1426b - getByID(GET)
4.http://localhost:4000/api/books/ab9f7753-4b0f-4b0b-a481-09a5ec43b4a7 - delete(DELETE)


### Command
**npm start** -for application running
**npm test** -for check test case
### Prerequisites

- **Node.js** (v16+)
- **npm**
- **MongoDB** (Local or Cloud)
