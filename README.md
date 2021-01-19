# Node.js tests using TDD with Jest

### **Tech:** Node.js, Jest, Sequelize ORM, Docker

### Databases:

- **PostgreSQL** for Development
- **SQLite** for Tests

### **Concepts:** TDD, Authentication

- Rocketseat tutorial: https://www.youtube.com/watch?v=2G_mWfG0DZE

## Initialization

- Clone the repository, install the dependencies and set up .env file:

```bash
    git clone https://github.com/GabrielCC163/node-auth-tdd.git
    cd node-auth-tdd
    yarn install
```

- Start the database:

```bash
    docker-compose up -d
```

- Run migrations:

```bash
    yarn sequelize db:migrate
```

- Start the API (localhost:3333)

```bash
    yarn start
```

- Run tests

```bash
    yarn test
```
