# Anna-s-page
<html lang="en">
<head>
  <title>This is Anna's Page!</title> 
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="styles/styles.css">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
    }

    /* Style the header */
    header {
      background-color: #666;
      padding: 30px;
      text-align: center;
      font-size: 35px;
      color: white;
      margin: 0;
    }

    /* Create two columns/boxes that float next to each other */
    nav {
      float: left;
      width: 30%;
      background: #ccc;
      padding: 20px;
      margin: 0;
      min-height: 100vh;
    }

    /* Style the list inside the menu */
    nav ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
    }


	nav li {
 	 color: white;
 	 font-size: 20px;
 	 margin-bottom: 10px;
 	 transition: color 0.3s;
 	 padding: 10px; /* Added padding for better visual effect */
 	 background-color: #ccc; /* Added background color */
	}

	nav li:hover {
	  background-color: grey; /* Change background color on hover */
	  color: white; /* Change text color on hover */
 	 cursor: pointer; /* Change cursor to indicate clickable item */
	}
  
    article {
      float: left;
      padding: 20px;
      width: 70%;
      background-color: #f1f1f1;
      height: 100%;
      margin: 0;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    article img {
      max-width: 100%;
      max-height: 100%;
      height: auto;
      width: auto;
    }

    /* Clear floats after the columns */
    section::after {
      content: "";
      display: table;
      clear: both;
    }

    /* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
    @media (max-width: 600px) {
      nav, article {
        width: 100%;
      }
    }
    
    #whiteBox {
	background-color:rgba(255,255,255,0.75)
	width:85%;
	margin:auto;
	padding:50px;
	border:15px groove bule;
	}
  </style>
</head>
<body>

<header>
  <h1> Welcome to <big>Anna's</big> Page </h1>
  <p> A little about me~ </p>
</header>

<section>
  <nav>
    <ul>
      <li><a href="hometown.html">Hometown</a></li>
      <li><a href="travel.html">Favorite Travel Spot</a></li>
      <li><a href="food.html">Favorite Restaurant in New York</a></li>
    </ul>
  </nav>
  
  <article>
    <img src="img/welcome p.JPG" alt="Welcome Image" />
  </article>
</section>
<footer>
<p><a href="https://i6.cims.nyu.edu/~zc2403/AssignmentPage.html">Go back</a> to my assignment page.</p>
</footer>

</body>
</html>
