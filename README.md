# Daisy FastApi

Hands on repo to learn about Daisy UI

## Setup

Start installing dependencies for tailwind.

```bash
npm init
npm install -D tailwindcss
npx tailwindcss init
npm i -D daisyui@latest
```

Next add the file in styles/app.css and generate tailwindcss file.

```bash
npx tailwindcss -i ./styles/app.css -o ./static/css/app.css --watch
```


## Starting the app

```bash
fastapi dev main.py
```
