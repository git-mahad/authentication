# NestJS Authentication Example

This project is a simple authentication system built with 
* [![Nest][Nest.js]][Nest-url], 
TypeORM, and JWT. It demonstrates user registration, login, and profile retrieval using local and JWT strategies.

## Table of Contents

- [Installation](#installation)
- [Creation .env file](#creation)
- [Project Structure](#project-structure)
- [Stay in touch](#Stay-in-touch)

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/git-mahad/authentication.git
cd authentication
npm install
```
## creation
### Use your own data
``` bash
DB_HOST=your_database_host
DB_PORT=your_database_port
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
DB_NAME=your_database_name
JWT_SECRET=your_jwt_secret
```
## project-structure
```bash
src/
├── app.module.ts
├── main.ts
├── auth/
│   ├── auth.module.ts
│   ├── auth.service.ts
│   ├── auth.controller.ts
│   ├── local.strategy.ts
│   └── jwt.strategy.ts
├── user/
│   ├── user.module.ts
│   ├── user.service.ts
│   └── user.entity.ts
└── profile.controller.ts
.evn
```
## Stay in touch

- Author - [M Mahad](https://www.linkedin.com/in/mahad-dev)
## Run the application:
```bash
  npm run start
```