# LMS Frontend

### Setup instruction

1. Clone the project

```
    https://github.com/Ksarang26/LMS-Frontend-.git
```

2. Move into the directory

```
    cd lms-frontend
```

3. intall dependencies

```
    npm i
```

4. run the server

```
    npm run dev
```

### Setup for tailwind CSS

[Tailwind official instruction docs](https://tailwindcss.com/docs/installation)

1. Install Tailwind CSS

```
    npm install -D tailwindcss
```

2. Create tailwind config file

```
    npx tailwindcss init
```

3. Add file extension in tailwind config file

```
    "./src/**/*.{html,js,jsx,ts,tsx}"
```

4. Add tailwind directives
 
```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```

### Adding plugins and dependencies

```
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
```

###configure auto import sort esline 

1. Install simple import sort
```
npm i -D esline-plugin-simole-import-sort
```

2. Add rule in `.esline.cjs`

```
'simple-import-sort/imports':'error',
```

3. Add simple-import sort plugin in `.esline.cjs`

```
plugins: [ ... ,'simple-import-sort'],
```
