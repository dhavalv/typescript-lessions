#### Typescript Lession

(1)Typescript Javascript Install typescript with npm
```
npm install -g typescript
```
(2) create ```app.ts``` in your directory
```
class person{
}
```
(3) compile from command line: "tsc app.ts", It'll create new file your "app.js"
``` tsc --out bundle.js app.ts ```
same out like ```tsc app.ts```
```tsc --watch --out bundle.js app.js```

(4) Configure typescript project:
```
"scripts": {
    "build": "tsc -p ./src"
},
```
(5) Apply command below command, It'll generate new directory in your folder.
```npm run build```
