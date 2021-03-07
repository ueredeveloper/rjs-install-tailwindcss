


Install: 

```
@tailwindcss/postcss7-compat@2.0.3
autoprefixer@9.8.6
@tailwindcss/postcss7-compat@2.0.3
postcss@7.0.35

@craco/craco@6.1.1

```

Change:

```
"start": "react-scripts start",
"build": "react-scripts build",
"test": "react-scripts test --env=jsdom",
  
```
To:

```
"start": "craco start",
"build": "craco build",
"test": "craco test",

```



 

