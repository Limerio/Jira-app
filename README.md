# Jira App

*The creation of this application isn't by **[Atlassian](https://atlassian.com)** or a copy of the project but **only for view my jira instance** in an app and not on a browser.
It's a **tool** 🛠️ to simplify my organisation to do my work and i want to share that to you if you have the same problem of me and you want that.*

## Software need :

- Node.js
- NPM (include by Node.js by default) or [Yarn](https://yarnpkg.com) or [PNPM](https://pnpm.io)

## Steps :

1. Execute ``npm i`` or ``yarn`` or ``pnpm i`` to install all of the dependencies
2. You need to update the name of the .env.sample file to .env
3. Open the file and add after URL= the url of your jira instance
4. Execute the setup task ⬇️ or the package task ⬇️
*note: when you execute the setup task, you generate 2 directories in the **out** directory the first is the package of the project and the second directory is a setup file to install your computer globaly*

### For start the project

Yarn:

```cmd
yarn start
```

NPM:

```cmd
npm start
```

PNPM:

```cmd
pnpm run start
```

### For package the project

Yarn:

```cmd
yarn package
```

NPM:

```cmd
npm run package
```

PNPM:

```cmd
pnpm run package
```

### For generate a setup and package the project

Yarn:

```cmd
yarn make
```

NPM:

```cmd
npm run make
```

PNPM:

```cmd
pnpm run make
```
