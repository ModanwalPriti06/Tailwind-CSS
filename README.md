# Tailwind-CSS

# How to use Tailwind
- Node should be install your system: node -v
- go to this website: http://tailwindcss.com/docs/installation/tailwind-cli
- open terminal:
    -  npm init -y
    -  npm install -D tailwindcss@3
    -   px tailwindcss init (tailwind-config file created)
- Make folder src -index.html and index.css
- copy and paste config.js file inside content ["./src/**/*.{html,js}"] // ["./src/*.html"]
- paste in src/index.css file
    - @tailwind base;
    - @tailwind components;
    - @tailwind utilities;
- Run CLI in terminal - npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
 (Here this terminal commond define run input from src/input.css and output in output.css which is creating file automatic based on cli path. watch work like nodeman no need to run terminal again and again)
- add package.json and run npm run build
```
   "scripts": {
    "build" : "npx tailwindcss -i ./src/input.css -o ./public/style.css --watch"
  },
```


## How Tailwind CSS Work:
- Tailwind CSS is a utility-first CSS framework that provides pre-built utility classes instead of predefined components. It allows you to style elements directly in your HTML using small, reusable classes.
- It processes CSS dynamically using JavaScript and generates only the necessary styles at build time.
- Tailwind doesn’t work like vanilla CSS; it generates CSS dynamically.

## @tailwind base; @tailwind components; @tailwind utilities; what is this?
- These three lines are Tailwind CSS directives that tell Tailwind how to process styles when building your CSS. Here’s what each one does:

## How Tailwind Generates CSS
- When you add utility classes in your HTML, Tailwind processes and compiles them into a final CSS file using its CLI.

## Advanced Features
- Tailwind’s Responsive Design
- Dark Mode Support (💡 Use dark: for dark mode styling.)
  
## Note:
Whenever we changing anything in index.html or input.css file the we have to rerun this script(thing added 3 line in input.css file) again and again. for that what we can do it, we can instead add a watch flag.

---
# Classes

1. bg-slate-900
2. 
