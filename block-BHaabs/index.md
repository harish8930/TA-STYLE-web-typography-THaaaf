html

!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, corrupti!</h1>

<section><div class="para">
  <p class="p1"> Tagged: Design Typography</p>
  <p class="p2">28April,2023</p></div> 

<p class="main-para">
Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis consequuntur molestias aperiam nemo a, vel, excepturi praesentium iste blanditiis saepe quis officia laborum vero, quibusdam similique illum atque officiis tempore expedita nobis. Ducimus aspernatur veritatis iste odio, recusandae doloribus soluta praesentium itaque,<quote> inventore debitis suscipit assumenda veniam fuga reprehenderit</quote> neque sequi quo molestiae officia? Modi, incidunt asperiores. Explicabo, beatae veniam.
Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis consequuntur molestias aperiam nemo a, vel, excepturi praesentium iste blanditiis saepe quis officia laborum vero, quibusdam similique illum atque officiis tempore expedita nobis. Ducimus aspernatur veritatis iste odio, recusandae doloribus soluta praesentium itaque, inventore debitis suscipit assumenda veniam fuga reprehenderit neque sequi quo molestiae officia? Modi, incidunt asperiores. Explicabo, beatae Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis consequuntur molestias aperiam nemo a, vel, excepturi praesentium iste blanditiis saepe quis officia laborum vero, quibusdam similique illum atque officiis tempore expedita nobis. Ducimus aspernatur veritatis iste odio, recusandae doloribus soluta praesentium itaque,<quote> inventore debitis suscipit assumenda veniam fuga reprehenderit</quote> neque sequi quo molestiae officia? Modi, incidunt asperiores. Explicabo, beatae veniam.
Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis consequuntur molestias aperiam nemo a, vel, excepturi praesentium iste blanditiis saepe quis officia laborum vero, quibusdam similique illum atque officiis tempore expedita nobis. Ducimus aspernatur veritatis iste odio, recusandae doloribus soluta praesentium itaque, inventore debitis suscipit assumenda veniam fuga reprehenderit neque sequi quo molestiae officia? Modi, incidunt asperiores. Explicabo, beatae 
</p>

<h2>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptatem, harum.</h2>
<p class="main-para2">
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod repellendus, distinctio illum, exercitationem deserunt libero fugiat perferendis earum fugit illo iure totam vel consequuntur ratione rem blanditiis eos saepe ipsum atque facere, eum laboriosam necessitatibus. Quos at cupiditate fuga. Pariatur quaerat illum architecto iste, atque odio fugit, aut, tempora ut sunt quae illo sed voluptate neque molestiae ea? Ad, numquam. Laborum quam unde eum odit, natus temporibus animi mollitia, assumenda placeat dignissimos qui. Nisi itaque sapiente, eaque deleniti, vero eligendi, qui quibusdam obcaecati voluptatem nihil ea maiores. Molestiae dolore ea modi repudiandae accusantium incidunt vitae eveniet numquam, dolor quod sint pariatur debitis sequi voluptatum amet nobis dignissimos tenetur delectus neque sapiente non alias? Ducimus doloremque quam soluta neque, accusamus sequi.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod repellendus, distinctio illum, exercitationem deserunt libero fugiat perferendis earum fugit illo iure totam vel consequuntur ratione rem blanditiis eos saepe ipsum atque facere, eum laboriosam necessitatibus. Quos at cupiditate fuga. Pariatur quaerat illum architecto iste, atque odio fugit, aut, tempora ut sunt quae illo sed voluptate neque molestiae ea? Ad, numquam. Laborum quam unde eum odit, natus temporibus animi mollitia, assumenda placeat dignissimos qui. Nisi itaque sapiente, eaque deleniti, vero eligendi, qui quibusdam obcaecati voluptatem nihil ea maiores. Molestiae dolore ea modi repudiandae accusantium incidunt vitae eveniet numquam, dolor quod sint pariatur debitis sequi voluptatum amet nobis dignissimos tenetur delectus neque sapiente non alias? Ducimus doloremque quam soluta neque, accusamus sequi.




</p>




</section>

</body>
</html>


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


body{background-color: rgb(32, 29, 29);
}
h1{font-family: url(Open_Sans.zip);
	font-size: 32px;
	color: white;
	text-align: center;
	line-height: 1.7;
}


.para{ color: red;
	display: flex;
	justify-content: space-between;
	 margin: 40px 0px 40px 0px;

}
.p2{color: white;
}


.main-para{font-family: url(Ubuntu.zip);
	font-size: 14px;
	color: white;
	font-weight: lighter;
text-decoration: underline  rgb(131, 216, 228);
line-height: 1.2;
letter-spacing: 3px;
}

h2{font-size: 30px;
	text-align: center;
	color: white;
	margin-top: 40px;
	text-shadow: 5px 5px 5px cornflowerblue;
}

.main-para2{font-size: 14px;
	color: white;
	font-weight: lighter;
	line-height: 1.7;
	margin-top: 20px;

}
section{margin: 0px 200px 0px 200px;

}




























