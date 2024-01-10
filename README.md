# NFD Web Development Project

## create react app
```
 npx create-react-app myproject_name;
```
### Download required assets for this project

There are assets for this project that has been used here :- [click here for Assets](https://github.com/sanjaraiy/NFD_Project/tree/main/src/Components/assets).

## Using install the Tailwind CSS
```
 npm install -D tailwindcss
 npx tailwindcss init
```
## Configuration of Tailwind CSS

/** @type {import('tailwindcss').Config} */
module.exports = {
  content:` ["./src/**/*.{html,js}"]`,
  theme: {
    extend: {},
  },
  plugins: [],
}

## Add the Tailwind directives to your CSS

@tailwind base;
@tailwind components;
@tailwind utilities;

### Project Description 

