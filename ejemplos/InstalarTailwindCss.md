 npm install -D tailwindcss postcss autoprefixer  
 npx tailwindcss init -p  
 nano tailwind.config.js  
```` 
    /** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
````

nano src/index.css  
````
@tailwind base;
@tailwind components;
@tailwind utilities;
````
