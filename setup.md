# React Portfolio App: next.js+tailwind



## 1. Install nextjs-app

open a terminal and run:

```
npx create-next-app@latest react-portfolio-tw
```

then select options as below:

​	TypeScript: No
​	ESLint:	Yes
​	Tailwind CSS:	Yes
​	`src/` directory:	No
​	App Router:	Yes
​	Import alias:	No



## 2. Install VS Code extension: Tailwind CSS IntelliSense



## 3. Install some node-modules

```
npm i react-icons
npm i -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```



## 4. Run the Dev

```shell
cd react-portfolio-tw
npm run dev
```



## 5. Setup in the app

**/app/globals.css**

```javascript
@tailwind base;
@tailwind components;
@tailwind utilities;

body {
  overflow-x:hidden;
}
```



