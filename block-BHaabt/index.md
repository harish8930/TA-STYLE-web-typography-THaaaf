html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>      
<div class="container">
  <div class="brandname"><p>ProInsure</p></div>

  <div class="navbar"><nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Contact</a>
  
  <button>View Plan</button></nav></div>
</div>
  </header>


  <section>
    <div class="container2">
      <div class="content">
    <h1>HUMANIZING</h1>
    <h2>YOUR INSURANCE</h2>
    <p class="para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat expedita placeat voluptatibus vel a officia, magni accusamus aspernatur error eveniet. Consequatur quidem vel nulla provident architecto unde, inventore distinctio optio?</p>
    <button>View Plan</button></div>

<div><img class="image" src="insure1.png"></div>
    </div>
  </section>

  <article>
<div class="container3">

 <img class="img2"  src="insure2.png" alt="error">
<div><h2 class="article-head">About the Insure </h2>
<p class="text-art">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam, ullam iste adipisci facere odio rerum!</p> 
<button class="btn">Know More</button>
</div>
</div>
  </article><hr>

<h3>We Are Different</h3>

<div class="row">

<div>,<img class="png" src="setting.png" alt="setting">
  <h4 class="col1">Easy Process</h4>
<p>Lorem ipsum dolor sit amet.</p></div>

<div><img class="png" src="setting.png" alt="setting">
  <h4 class="col2">Affordable Price</h4>
<p>Lorem ipsum dolor sit, amet </p></div>

<div><img class="png" src="setting.png" alt="setting"><h4 class="col3">You Come First</h4>
<P>Lorem ipsum dolor sit amet.</P></div>
</div>


<div class="container4">
<div><H2 class="foot-head">Find About More </H2>
<h2 class="foot-head2">How We Work</h2></div>


<div><button class="btn2">Know More</button>

</div>


</div>
  
  style.css
  
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;}



	/*start*/


body{
	font-family: url(DM_Serif_Display.zip);
}


.container{display: flex;
justify-content: space-between;
margin-top: 14px;
}


.brandname {font-size: 16px;
	font-weight: 900;
	margin-left: 20px;
	
}
.navbar, a, button{flex-wrap: wrap;
	text-transform: uppercase;
	text-decoration: none;
	margin-left: 10px;

}
section{width: 100%;
	height: 300px;
	margin-top: 10px;
	background-color: rgb(17, 17, 75);
}

.container2{font-size: 32px;
	color: white;
	margin-left: 50px;
display: flex;
justify-content: space-between;
}
.image{width: 300px;
height: 400px;
float: right;
margin-right: 50px;
padding-top: 50px;
}

.para{font-size: 16px;
}

.content{padding-top: 60px;
width: 30%;

}
.container3{display: flex;
	width: 70%;
flex-direction: row;
font-family: url(Karla.zip);

}
.img2{width: 300px;
height: 300px;
margin: 30px 0px 0px 30px;
border-radius: 10px;

}
.article-head{ 
	font-size: 24px;
	font-weight: 700;
margin-left: 40px;
margin-top: 50px;
}
.text-art{width: 300px;
margin-left: 30px;
margin-top: 20px;
}
.btn{margin: 30px 0px 0px 70px;}

h3{font-size: 20px;
font-weight: 700;
margin: 30px 0px 0px 50px;
}

.row{ display: flex; 
flex-direction: row;
justify-content: space-between;
margin-top: 30px;

}

hr{width: 200px;
float: left;}

.container4{width: 100%;
	height: 200px;
background-color:  rgb(17, 17, 75);
display: flex;

font-family: url(DM_Serif_Display.zip);
margin-top: 50px;
}
.row{display: flex;  
justify-content: space-around;
}
.png{width: 20px;
height: 20px;
}


.foot-head, .foot-head{color: white;
	font-size: 24px;
	font-weight: 900;
	
	padding-top: 50px;
	line-height: 1.7;

}

.foot-head2{font-size: 24px;
	font-weight: 900;
	font-family: url(Karla.zip);
	color: white;
}
.foot-head, .foot-head2{margin-left: 30px; }

.btn2{margin-top: 100px;
margin-right: 60px;}
  
  ................
  
  
  
  
  
  

