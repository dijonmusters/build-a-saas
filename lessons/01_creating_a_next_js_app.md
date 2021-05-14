# 01 Creating a Next.js app

Create folder and cd into folder

```
mkdir eggfoot && cd eggfoot
```

Initialize as NPM project

```
npm init -y
```

Install next.js and dependencies

```
npm i next react react-dom
```

Create pages directory and index file

```
mkdir pages && touch pages/index.js
```

```
const IndexPage = () => {
  return <p>welcome</p>;
};

export default IndexPage;
```

Add scripts to `package.json`

```
"scripts": {
  "dev": "next dev",
  "build": "next build",
  "start": "next start",
  "export": "next export"
},
```

Run app

```
npm run dev
```

Add a gitignore

```
node_modules/
.next/
.DS_Store
out/
.env
.vercel
```

Creating a `.prettierrc` config file

```
{
  "endOfLine": "lf",
  "semi": false,
  "singleQuote": true,
  "tabWidth": 2,
  "trailingComma": "es5"
}
```

Create a `.prettierignore` file

```
.next
package.json
package-lock.json
public
node_modules
```

jsconfig.json

```
{
  "compilerOptions": {
    "baseUrl": "."
  }
}
```
