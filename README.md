
<div style="color: #44AEFB" align="center">
 <a  href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noreferrer">
      <img  alt="HTML" height="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank" rel="noreferrer">
      <img  alt="CSS" height="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>
  </a>
  <a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer">
      <img  alt="vscode" height="50px" style="padding-right:10px;"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"/>
  </a>
</div><br>
<h2 align="center">Membuat responsif  website Menggunakan framework materialize</h2>
<br> <img src="MacBook Air - 1.png"> <br> <hr>

# Cara install materialize
<h2>1. NPM</h2>
<p>You can find all the versions of the CDN at cdnjs.</p>
  
   ```
     npm install materialize-css@next
   ```

<h2>2. Download</h2>

  ```sh
  https://github.com/Dogfalo/materialize/releases/download/1.0.0/materialize-v1.0.0.zip
  ```

<h2>3. CDN</h2>
<p>You can find all the versions of the CDN at cdnjs.</p>

```sh
   <!-- Compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

    <!-- Compiled and minified JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script> 
    
```


<h2>4. HTML Setup<h2>
<h4>Next you just have to make sure you link the files properly in your webpage. Generally it is wise to import javascript files at the end of the body to reduce page load time. Follow the example below on how to import Materialize into your webpage.</h4>

```sh
<!DOCTYPE html>
  <html>
    <head>
      <!--Import Google Icon Font-->
      <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
      <!--Import materialize.css-->
      <link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>

      <!--Let browser know website is optimized for mobile-->
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    </head>

    <body>

      <!--JavaScript at end of body for optimized loading-->
      <script type="text/javascript" src="js/materialize.min.js"></script>
    </body>
  </html> 
```

<p align="center">Create by andri❤️ </p>
