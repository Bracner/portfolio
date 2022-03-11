
<html lang="pt-br" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" type="text/css" href="style.css" media="screen" />

    <title>Luan Duarte - Portfolio</title>
  </head>
  <body>
    <style>
      body{
  background-color: #0f0f0f;
}

@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300;400&display=swap');




#menu1{
  position: absolute;
  height: 560px;
  width: 200px;
  left: 40px;
  top: 72px;
  background-color: #222222;
  transition: 0.3s;

}
#menu1:hover{
  height: 565px;
  width: 205px;
}
#menu1 img{
  position: absolute;
  left: 13px;
  top: 80px;
  width: 170px;
}
#menu1 h3{
  position: absolute;
  left: 45px;
  top: 240px;
  color: white;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

#menu1 p{
  position: absolute;
  left: 6px;
  top: 300px;
  text-align: center;
  color: white;
  font-size: 11px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

/** **/
#nav{
  position: absolute;
  height: 50px;
  width: 1050px;
  left: 280px;
  top: 72px;
  background-color: #222222;
}
#nav ul{
  list-style: none;
  left: 50%;
  position: absolute;
}
#nav ul li{
  display: inline;
}
#nav ul li a{
  color: white;
  text-decoration: none;
  font-family: segoe ui;
  padding: 15px;
  font-size: 17px;
}
#nav ul li a:hover{
  background-color: #0c9c9a;
}
/** Menu do meio */
#menu2{
  position: absolute;
  left: 280px;
  top: 132px;
  background-color: #222222;
  height: 500px;
  width: 1050px;
  color: white;
  font-family: Segoe UI;
  transition: 0.3s;
}
#menu2 h1{
  position: absolute;
  left: 30px;
}
#menu2:hover{
  height: 505px;
  width: 1055px;
  left: 275px;
}


#menu2 h2{
  top: 230px;
  left: 180px;
  position: absolute;
  font-size: 50px;

}
#menu2 h3{
  top: 310px;
  left: 180px;
  position: absolute;
  color: #c49b11;
  font-size: 25px;
}

#menu2 a{
  text-decoration: none;
  top: 390px;
  left: 190px;
  position: absolute;
  color: white;
  font-size: 20px;
  padding: 5px;
  padding-left: 10px;
  padding-right:10px;
  background-color: #0c9c9a;
}

#menu2 a:hover{
  background-color: #0b8e8c;
}

#menu2 img{
  position: absolute;
  left: 70%;
  top: 100px;
}
#ano1{
  position: absolute;
  left: 67%;
  top: 83px;

}
#ano1text{
  position: absolute;
  left: 75%;
  top: 80px;
  font-family:'Roboto Condensed' ;
  font-size: 20px;
}

    </style>
    <div id="menu1">
        <img src="profile.png">
        <h3>Luan Duarte</h3>
        <p>My name is Luan, I'm 19 years old 
          and I'm graduating from the 
          Systems Analysis and 
          Development course.
          I aim to be both a front-end 
          and a back-end developer.</p>
    </div>
    <div id="nav">
        <ul>
          <li> <a href="#"> Home</a></li>
          <li> <a href="#"> About</a></li>
          <li> <a href="#"> Portfolio</a></li>


        </ul>
    </div>
    <div id="menu2">
      <h1>Port<span style="color: #d6254d;">folio</span></h1>
      
      <h2>HELLO,</h2>
      <h3>My name is Luan</h3>

      <a href="#">GitHub</a>

      <img src="timeline.png" alt="">
      <p id="ano1">2002</p>
      <p id="ano1text">Nascimento</p>
    </div>
  </body>
</html>
