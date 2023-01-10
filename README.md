Run ```npm start``` for creating build using parcel (parcel ./public/index.html") script.

Go to ./dist folder and use ```index.[random_number].js``` . 

This is the final file we are using as a widget in other application.

Include this file into other application and call renderDOM function. Which takes selector as an argument 

Example

  ```html
  <!doctype html>
  <html lang="en">
  <head><link rel="stylesheet" href="/index.34b7aba5.css">
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
   
    <title>React App</title>
  </head>
  <body>
    <div id="test"></div>

    <script src="/index.975ef6c8.js"></script>
    <script>
      renderDOM("#test");
    </script>
  </body>
</html>
  ```
  
  
