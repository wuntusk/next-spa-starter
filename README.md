# NextJS TypeScript Starter with ESLint/Prettier for VSCode

## How to use

Fork/clone copy... 

```
npm i
npm run dev
```

Debugging is enabled for VSCode just run the Next:Chrome to debug


## How this Starter was Built

Create a nextjs starter
```
npx create-next-app next-spa-starter
```

Add Typescript

```
touch tsconfig.json
npm install --save-dev typescript @types/react @types/node
```

Start the dev server

```
npm run dev
```

It will populate the `tsconfig.json` with the default typescript config and create `next-env.d.ts`

Convert the project to typescript

rename `pages/api/hello.js` to `pages/api/hello.ts`
rename `pages/_app.js` to `pages/_app.tsx`
rename `pages/index.js` to `pages/index.tsx`

Edit `tsconfig.json` and Turn on strict mode

```
    "strict": true,
```

Setup our dev environment

Add the following files:
`.prettierrc`,`.gitignore`,`.eslintrc.js`


ESLint

```
npm install eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser --save-dev
```

Prettier

```
npm install prettier eslint-config-prettier eslint-plugin-prettier --save-dev
```

