index.html

<html>
	<head>
		<title>Starbucks Coffe</title>
		<link href="css/style.css" rel="stylesheet"/>
		<meta nome="viewport" content="width=device-width, initial-scale=1.0,maximum-scale=1.0">
	</head>
	<body>
		<header>
			<div class="center">
				<div class="logo"><img src="istockphoto.png" /></div><!--logo-->
				<div class="menu">
					<a href="#">Home</a>
					<a href="#">About</a>
					<a href="#">Menu</a>
					<a href="#">What's New</a>
				</div><!--menu-->
			</div><!--center-->
		</header>
        <section class="sobre">
            <div class="extras">
                 
            </div><!--extras-->
        </section>

        <div class="texto-sobre">
            <h1>Olá<br/>seja bem vindo ao meu novo site <span style="color: rgb(255, 4, 150)">Me chamo Gabrielly</span></h1>
            <buttom>Saiba Mais</buttom>
        </div>
	</body>
</html>

style.css
{
   margin:0;
    padding:0;
    box-sizing: border-box;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.center{
    display:flex;
    flex-wrap:wrap;
    max-width:1280px;
    margin:0 auto;
    padding:0 2%;
}

html.body{
    height:50%;
    overflow-y: hidden;
    overflow-x:hidden;
}

header{
    height:200px;
    padding:20px 0;
}

.logo{
    width:50%;
}

.menu{
    padding-top:30px;
    width:50%;
    text-align: right;
}

.menu a{
    color:black;
    text-decoration: none;
    font-weight: bold;
    margin-right: 15px;
}

section.sobre{
    height: calc(100% - 200px);
    position: relative;
}

.extras{
    position:absolute;
    bottom:-150px;
    right:-300px;
    width:800px;
    height:600px;
    border-radius:50%;
    background-color: rgb(255, 0, 119);
    
}

.texto-sobre{
    margin-top: 100px;
}

.texto-sobre h1{
    font-size: 50px; 
}

.texto-sobre p{
    margin:20px 0;
    color:black;
    font-size: 14px;
    font-weight: bold;
    max-width: 800px;
}

.texto-sobre button{
    border:0;
    background-color:rgb(253, 86, 189);
    color: white;
    border-radius: 10px;
    width:80px;
    height:30px;
    cursor:pointer;
    
}
