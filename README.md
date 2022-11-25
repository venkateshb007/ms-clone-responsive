# ms-clone-responsive

MS-clone

A brief description of what this project does and who it's for

```npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch

if some how above project showing error
try the below process

deploy this project using tailwindcss postCssmethod

in details follow this link
https://tailwindcss.com/docs/installation/using-postcss

Terminal
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
(run these two npm and npx in terminal)

postcss.config.js(add given codes in postcss.config.js file)
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  }
}


tailwind.config.js(add below code in tailwind.config.js file)
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}


main.css(add below components to main.css file)
@tailwind base;
@tailwind components;
@tailwind utilities;



## Documentation

[tailwindcss](https://tailwindcss.com/docs/installation/using-postcss)

https://tailwindcss.com/docs/installation/play-cdn
