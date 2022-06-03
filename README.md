# websites-com-HTML5-CSS3
Introdução a criação de websites  com HTML5 e CSS3.

Seguido conforme orientações exemplificadas.

Utilizei o editor de texto "Sublime Text"

HTML5

Alterei o simbolo < pelo -, eu ainda não sei outro método sem que ele converta para fórmulas.

-!DOCTYPE html>

-html>

-head>
	
	-meta charset="utf-8">
	
	-title>Everton Ribeiro</title>
	
	-link rel="stylesheet" href="style.css">
	
-/head>

-body>

	-header>
	
		
		-img src="Everton.jpg" alt="Minha foto" class="photo">
	
	-h1 id="title" >Everton Ribeiro</h1>	
	
	-/header>
	
	-section>
		-header>
			-h2 class="subtitle">Posts</h2>
		-/header>
		-article class="post">
			-header>
				
				-h3 class="post_title">Post #1</h3>
				
				-img src="Everton2.jpg" alt="Ironman" class="post_image">
			
			-/header>
		
		-/article>
		
	-/section>
	
	-footer>
	
		-ol>
		
			-ul class="contacts_list">
			
				-a href="mailto:everton.oribeiro@outlook.com" target="_blank">everton.oribeiro@outlook.com</a>
				
				-/li>
				
				-li>
				
					-a href="https://www.linkedin.com/in/evertonribeiro82/" target="_blank">LinkedIn</a>
				-/li>
				
				-li>
				
					-a href="https://github.com/EvertonRib">GitHub</a>
				
				-/ul>
				
	-/footer>
	
-/body>

-/html>


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

