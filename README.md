# React Datta Able `full-stack`

Full-Stack Seed project generated by **[React App Generator](https://appseed.us/generator/react/)** top of *Datta Able* design. The backend logic is provided by a simple, `easy-to-extend` API Server that manages the Authentication flow (login, registration, logout) using `JSON Web Tokens` (JWT).

- 👉 [React Datta Able](https://react-node-js-datta-able.appseed-srv1.com/) - LIVE Demo (from a similar product)

- 🚀 Built with [React App Generator](https://appseed.us/generator/react/), timestamp `2022-11-12 07:35`

<br />

![React Datta Able - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/174488189-7bbb3e82-b319-487e-94ec-e295aca3f6d7.png)


<br >

## ✨ `React` Datta Able

- Modern aesthetics UI design - Designed by *[CodedThemes](https://bit.ly/37fF9RT)*
- React, Redux, Redux-persist

<br />

> `Tests` (compatibility matrix)

| NodeJS | NPM | YARN | 
| --- | --- | --- |  
| `v14.0.0` | ❌ | ✅ |
| `v16.0.0` | ✅ | ✅ | 
| `v18.0.0` | ❌ | ❌ | 


<br />

## ✨ `NodeJS API` Features

- Stack: `NodeJS` / `Express` / **SQLite** 
- `TypeScript`, Joy for validation
- **DB Layer**: `TypeORM`, `SQLite` persistence
- **Auth**: Passport / `passport-jwt` strategy
- [API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition) - the unified API structure implemented by this server

<br />

> `Tests` (compatibility matrix)

| NodeJS | NPM | YARN | 
| --- | --- | --- | 
| `v18.0.0`  | ❌ | ✅ |
| `v17.0.0`  | ❌ | ✅ |
| `v16.13.0` | ❌ | ✅ | 
| `v16.0.0`  | ❌ | ❌ | 


<br /> 

## ✨ How to use it

Being a full-stack product, the backend and the frontend should be compiled and started separately. 
Before starting to compile the product, make sure you have the following tools installed in the environment:

- [NodeJS](https://nodejs.org/en/) - version `14.x` or higher
- [GIT](https://git-scm.com/) - used to clone tjhe sources from Github
- [Python3](https://www.python.org/) - used in many tools

<br />

### 👉 Start the Frontend 

> **Step 1** - Once the project is downloaded, change the directory to `react-ui`. 

```bash
$ cd react-ui
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

At this point, the app is available in the browser `localhost:3000` (the default address).


<br /> 

### 👉 Start the Backend Server 

> **Step 1** - Change the directory to `api-server-nodejs`

```bash
$ cd api-server-nodejs
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Run the SQLite migration via TypeORM

```bash
$ npm run typeorm migration:run
// OR 
$ yarn typeorm migration:run
```

<br />

> **Step 4** - Start the API server (development mode)

```bash
$ npm run dev
// OR
$ yarn dev
```

The API server will start using the `PORT` specified in `.env` file (default 5000).

<br /> 

## 👉 Codebase Structure

```bash
< ROOT / src >
     | 
     |-- config/                              
     |    |-- config.ts             # Configuration       
     |    |-- passport.ts           # Define Passport Strategy             
     | 
     |-- migration/
     |    |-- some_migration.ts     # database migrations
     |
     |-- models/                              
     |    |-- activeSession.ts      # Sessions Model (Typeorm)              
     |    |-- user.ts               # User Model (Typeorm) 
     | 
     |-- routes/                              
     |    |-- users.ts              # Define Users API Routes
     | 
     | 
     |-- index.js                   # API Entry Point
     |-- .env                       # Specify the ENV variables
     |                        
     |-- ************************************************************************
```

<br />

## 👉 SQLite Path

The SQLite Path is set in `.env`, as `SQLITE_PATH`

<br />

## 👉 Database migration

> Generate migration:

```bash
$ yarn typeorm migration:generate -n your_migration_name
```

> run migration: 

```bash
$ yarn typeorm migration:run
```

<br />

<br />

## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Datta Able is a premium React Design now available for download as a full-stack app. Made of hundred of elements, designed blocks, and fully coded pages, Datta Able PRO is ready to help you create stunning websites and web apps.

- 👉 [React Datta Able PRO](https://appseed.us/product/datta-able-pro/full-stack/) - Product Page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![React Datta Able PRO - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/174492290-a581dc5f-6b4a-4f5e-822e-419a8b96a480.png)

<br />

---
**React Datta Able** - Full-Stack Seed project generated by **[App Generator](https://appseed.us/generator/)**.
