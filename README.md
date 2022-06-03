# websites-com-HTML5-CSS3
Introdução a criação de websites  com HTML5 e CSS3.

Seguido conforme orientações exemplificadas.

HTML5

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Everton Ribeiro</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<img src="Everton.jpg" alt="Minha foto" class="photo">
	<h1 id="title" >Everton Ribeiro</h1>	
	</header>
	<section>
		<header>
			<h2 class="subtitle">Posts</h2>
		</header>
		<article class="post">
			<header>
				<h3 class="post_title">Post #1</h3>
				<img src="Everton2.jpg" alt="Ironman" class="post_image">
			</header>
			<p class="post_content">
			Lorem ipsum dolor sit amet, <a href="https://linkedin.com/in/evertonribeiro82/"target="_blank">consectetur adipiscing elit</a>, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, <a href="mailto:everton@email.com">quis nostrud</a>  exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</p>
		</article>
	</section>
	<footer>
		<ol>
			<ul class="contacts_list">
				<a href="mailto:everton.oribeiro@outlook.com" target="_blank">everton.oribeiro@outlook.com</a>
				</li>
				<li>
					<a href="https://www.linkedin.com/in/evertonribeiro82/" target="_blank">LinkedIn</a>
				</li>
				<li>
					<a href="https://github.com/EvertonRib">GitHub</a>
				</ul>
	</footer>
</body>
</html>


CSS3

body {
	background:#f7f7f7;
	font-family: Verdana;
	max-width: 900px;
	margin: auto;
}

.photo {
	border: 1px solid #505050;
	border-radius:50%;
}

#title, .subtitle, .post_title {
color:  #505050;
}

#title {
	font-size: 40px;
	text-transform: uppercase;
}

# {
	text-decoration: line-through;
	color: #505050;
}

.post_title {
 font-size: 16px;
 font-style: italic;
 margin: 0;
 margin-bottom: 15px;
}

.post {
	background:#FFF;
	padding: 15px;
	border: 3px solid #505050;
	margin-bottom: 15px;
	border-radius: 5px;
	}

	.post_content {
		margin: 0;
		margin-bottom: 15px;
		text-transform: capitalize;
		text-align: justify;
	}

	.post_image{
		margin-bottom: 15px;
		width: 100%;

	}

	.contacts_list {
		list-style-type: none;
		padding-left: 15px;
	}
	.contacts_list li a {
	text-decoration: none;
}

