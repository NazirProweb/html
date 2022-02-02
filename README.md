<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width, initial-scale=1.0">
    <title>Document</title>
    <link rel="shortcut icon" href="images/logo.png" type="images/png"/>
    <style>
        div.head{
          background-color: aqua;  
          padding: 12px;
        }
        div.one{
            background: yellow;
            padding: 12px;
            border-radius: 100px 100px;
        }
        h1{
            color: blue;
            text-align: center;
            text-transform: capitalize;
        }
        button{
            background-color: blue);
            border-style: solid;
            border-color: aqua;
            /* border: 1px solid blue; */
            border-radius: 10px 10px 10px 10px;
            padding: 5px;
            cursor: pointer;
            color: blue;
        }
        body{
  background-image: url(coll.jpg);  
}
a{
    color: blue;
}
    </style>
</head>
<body>
    <div class="head">
        <h1>Bienvenu dans mon site!</h1>
    </div>
    <div class="one">
        <h2 style="text-align: center;">veuillez cliquer sur l'introduction pour voir l'introduction</h2>
    </div>
    <div>
        <p style="text-align: center;">
            <button><a href="intro.html">Introduction</a></button>
            <button><a href="dev.html">Developpement</a></button>
            <button><a href="conclu.html">Conclusion</a></button>
        </p>
    </div>
    <!-- <footer>
    <img src="images/logo.png" style="font-size: 10px;" class="">
</footer> -->
</body>
</html>
