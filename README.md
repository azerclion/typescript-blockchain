```
npm init -y
npm i -D typescript
```

```
md src
cd src
touch index.ts
```

```
touch tsconfig.json
{
  "include": ["src"],
  "compilerOptions": {
    "outDir": "build"
  }
}

```

```
  "scripts": {
    "build": "tsc"
  },

npm run build
```

```
npm run build && npm start
```

```
npm i -D ts-node
```

nodejs를 위한 타입설치

```
npm i @types/node -D
```

예)axon을 위한 타입 설치

```
npm i @types/axon
```
