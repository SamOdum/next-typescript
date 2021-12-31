# Next-TypeScript

> A starter project that brings Nextjs and TypeScript together and makes them play nice with each other.

---

## Overview

This project bootstraps the technologies I usually use in building fast frontends and preconfigures them to interact seamlessly right out of the box. These technologies include.

- Nextjs
- TypeScript
- Framer-motion
- Jotai
- Eslint
- Prettier
- Husky
- Lint-staged
- Nodemon

Nextjs handles rendering my frontends as SSG or SSR pages while Framer motion provides fluid client-side animations. Jotai is my minimalistic global state powerhouse. And Typescript ensures far less bugs, if any, are pushed to production.
Eslint and Prettier enforce code consistency which means your code style and presentation will be uniform throughtout the project - regardless of whether you're working solo or in a team.

Lint-staged ensures that all your code is linted and checked by Prettier and Eslint. Husky is there to guarantee that each time you try to commit your code, it is meticulously squeezed through Lint-staged. This means you'll have an opportunity to address any errors or inconsistencies in your code _before_ it is commited. Nodemon provides a better developer experience with hot module reloading. It also provides a simpler way to deal with enviroment variables.

## Get started

This project includes an empty `.env.local` file to store environment variables. Should any development aspect require setting up environment variables, simply create them in this file. Once that is sorted, you're ready to go. Just run the following commands in order.

```bash
# Install dependencies
yarn

# Enable Husky
yarn husky install

# Start dev server
yarn dev
```

## Production

Remember to build your typescript files into javascript before deployment. Just run the following command.

```bash
# Build production files
yarn build
```

After your TypeScript compiles into JavaScript, you're ready to deploy everything in your build folder. Just go ahead and start your server.

```bash
# Start production Server
yarn start
```
