# animation-with-css
Übungen zum Thema Animationen mit CSS aus dem Studium Multimedia Production August 2018
<html lang="de"><!-- Ziel ist es, dass der rechte Button sanft vergrössert wird -->
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Transition Button</title>
    <style type="text/css">
        .wrap {
        margin: 50px;
        }
        .container {
          display: inline-block;
          width: 300px;
        }
        h1 {
          color: lightgray;
          font-family: lato;
          font-size: 20px;
          font-weight: 200;
          padding: 20px;
          text-align: center;
          text-transform: uppercase;
        }
        .box {
          border-radius: 5px;
          height: 40px;
          margin: 50px auto;
          width: 80px;
        }
        .wrap:hover .box {
          transform: scale(2);  /* button doppelt so gross */ 
        }
        .box1 {
          background: mediumturquoise;
        }
        .box2 {
          background: #2b3f53;
          transition: all 1s; /* transition von 1s */ 
        }
    </style>
</head>
 
<body>
    <div class="wrap">
        <div class="container">
            <h1>Ohne transition</h1>
            <div class="box1 box"></div>
    </div>
    <div class="container">
        <h1>Mit transition</h1>
        <div class="box2 box"></div>
    </div>
    </div>


</body>
</html>