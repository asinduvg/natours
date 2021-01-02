# Natours
This is the landing page for the fictional company 'Natours'.
### The site is live 👉 [natours](https://asinduvg.gitlab.io/natours-landing)

## Installation

Use the package manager [npm](https://www.npmjs.com/) to get started.

```npm
npm install 
```

## Usage
You have to use only auto or custom. No need to try them both.
### auto 🤘

Before you get started, you should use the **style.css** instead of **style.min.css** to see the changes at the development phase. So change the following line in **index.html**.
```html
<link rel="stylesheet" href="css/style.min.css" />
```
into,
```html
<link rel="stylesheet" href="css/style.css" />
```
Then use the following command.
```npm
npm start
```
or,
```npm
npm run start
```
This will start the live server and watch the sass folder for changes. When a change determined, it automatically convert SCSS code into CSS (css/style.css).

After development ended, use the following command,
```npm
npm run build:css
```
Make sure to change the css href back to **css/style.min.css** in index.html before the production.

### custom 🤘
After every change you need to do following commands,
```npm
npm run compile:css
npm run build:css
```
## License
[MIT](https://choosealicense.com/licenses/mit/)
