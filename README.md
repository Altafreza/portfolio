# altaf-portfolio
my portfolio

npm install --save gh-pages


  "scripts": {
+   "predeploy": "npm run build",
+   "deploy": "gh-pages -d build",
    "start": "react-scripts start",
    "build": "react-scripts build",
    
    
      "scripts": {
    "predeploy": "npm run build",
-   "deploy": "gh-pages -d build",
+   "deploy": "gh-pages -b master -d build",


npm run deploy


To do a manual deploy to Netlify’s CDN:

npm install netlify-cli -g
netlify deploy


--------------------------------------------------
cmd for netlify

npm install netlify -cli -g

netlify deploy
 select create & configure a new site
 
 ./build
  netlify deploy --prod
   ./build



https://create-react-app.dev/docs/deployment/#github-pages
