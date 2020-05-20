# ts-hello

## setup

```
mkdir test-app
cd test-app
npm init -y
npm install --save-dev typescript
npx tsc --init
mkdir src dist
vim tsconfig.json
```

Edit package.json
Add index.ts under src

```
npm run build:dev
```

open another terminal
```
npm start
```

Here you will get the following
```
$ npm start

> ts-hello@1.0.0 start /Users/hl/pub/ts-hello
> node dist/index.js

hello
```

## another way to set up

```
npx create-react-app my-app --template typescript
```
or

```
yarn create react-app my-app --template typescript
```

## Reference

* [from JavaScript to TypeScript](https://medium.com/better-programming/going-from-javascript-to-typescript-dde6d016917e)

