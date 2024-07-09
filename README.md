1. npm init

2. npm i express

3. npm i typescript ts-node @types/node @types/express -D

4. npx tsc --init

5. create nodemon.json
  ```
  {
    "watch": ["src"],
    "ext": ".ts,.js",
    "exec": "ts-node src/server.ts"
  }
  ```

6. add start and dev scripts
  ```
  "start": "npx ts-node src/server.ts",
  "dev": "npx nodemon"
  ```
