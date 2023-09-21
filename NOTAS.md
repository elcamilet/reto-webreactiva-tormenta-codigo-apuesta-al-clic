
ASTRO
=====
Se crea la app con: 
```
  npm create astro@latest
```
Se ejecuta localmente con:
```
  npm run dev
```
Se añade Netlify con:
```
  npx astro add netlify
```
` `  
` `  
NETLIFY
==
Se ha de añadir al **Build command** lo siguiente:
```
astro build
```
Y al **Publish directory** esto:
```
/src/dist
```