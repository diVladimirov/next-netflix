# Fullstack Netflix Clone with NextJS, TailwindCSS

# Deployed on Vercel

https://next-netflix-rose.vercel.app/auth

Technologies:

- NextJS - React Framework
- Tailwind CSS - Css Framework
- MongoDB - Database creation
- Prisma - ORM for connections
- Authentication with NextAuth and Google & Github providers
- SWR for data fetching
- Zustand for state management
- bcrypt for safely store a password
- React-icons for icons

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/diVladimirov/next-netflix.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_JWT_SECRET=
NEXTAUTH_SECRET=
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
