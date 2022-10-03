<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fight Club</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

    body {
      margin: 0;
      box-sizing: border-box;
    }

    .container {
      line-height: 150%;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px;
      background-color: #e9e9e9;
    }

    .header h1 {
      color: #E73936;
      font-size: 30px;
      font-family: 'Pacifico', cursive;
    }

    .header .social a {
      padding: 0 5px;
      color: #E73936;
    }

    .left {
      float: left;
      width: 180px;
      margin: 0;
      padding: 1em;
    }

    .content {
      margin-left: 190px;
      border-left: 1px solid #d4d4d4;
      padding: 1em;
      overflow: hidden;
    }

    ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      font-family: sans-serif;
    }

    li a {
      display: block;
      color: #000;
      padding: 8px 16px;
      text-decoration: none;
    }

    li a.active {
      background-color: #E73936;
      color: white;
    }

    li a:hover:not(.active) {
      background-color: #E73936;
      color: white;
    }

    table {
      font-family: arial, sans-serif;
      border-collapse: collapse;
      width: 100%;
      margin: 30px 0;
    }

    td,
    th {
      border: 1px solid #dddddd;
      padding: 8px;
    }

    tr:nth-child(1) {
      background-color: #E73936;
      color: white;
    }

    tr td i.fas {
      display: block;
      font-size: 35px;
      text-align: center;
    }

    .footer {
      padding: 55px 20px;
      background-color:#E73936;
      color: white;
      text-align: center;
    }
  </style>
</head>

<body>
  <div class="container">
    <header class="header">
      
      <h1>SFC</h1>
      <div class="social">
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
      </div>
    </header>
    <aside class="left">
      
      <ul>
        <li><a href="index.html">Fighters</a></li>
        <li><a href="Records.html">Records</a></li>
        <li><a class="active" href="#Rosters">Events</a></li>
        <li><a href="Videos.html">Videos</a></li>

      </ul>
     
    </aside>
    <main class="content">
      <hr><br>
      <h2><center>Events</center></h2>
      <table>
        <tr>
          <th>Fighters</th>
          <th>Date</th>
          <th>Location</th>
        </tr>
<tr>
          <td><center>Jesse Woolsey vs Luka Arapov</center></td>
           <td><center>October 7th</center></td>
                      <td><center>Saint Stevens</center></td>
        </tr>          
          
      </table>
      <a href="https://mail.google.com/mail/u/3/#inbox?compose=DmwnWrRrljTCbrdbCnsPDzrWBcccRPlnJqNvZzsGGCMhlGRmckrrGFRnsCxtCBMDFQtvXqgFTxsb"><center>Email Us</center></a>
    </main>
    <footer class="footer">&copy; Copyright SFC</footer>
  </div>
</body>

</html>
