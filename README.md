# Projeto-Bike Montai
Site com HTML e CSS
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/estilo.css">
    <title>Bike Montai</title>
</head>
<body>
  
        </div>
       <navbar class="navbar">
           <div class="Logo">
            <img src="ciclista-da-bicicleta-do-atleta-98731628.jpg" style="height: 80px;">

           </div>
         <br><br>
         <div class="menu">
            <a href="#">Home</a>
            &nbsp; &nbsp;
            <a href="#">contatos</a>
            &nbsp; &nbsp;
            <a href="#">Quem somos?</a>
         </div>
     
       </navbar>
       <br><br>
       <header>
          <h1>Eco Projects-Bike Montai</h1>
          <img src="Bike-no sol.jpg" style="height: 700px;">
          
       </header>
       <br><br>
       <header>
       <h2>Quem somos?</h2>
       <p>
         <b>Somos uma coperativa de ciclistas logalizadas no bairro da Costeira do Pirajubaé .</b>
       </p>
        <br><br>
        <h2>projerto</h2>
        <p><b>O projeto visa o lazer , a saúde mental e fisíca. com o crescimento da anciedade nas pessoas resolvemos criar um grupo aberto ao público todos os finais de semana , nosso objetivo é trazer terápia para as pessoas que lidam com a rotina estressante do dia a dia , dando a oportunidade de fazer novas amizades e contribuindo para o meio ambiente.</b></p>
        <br><br>
        <img src="imagem-bike.jpeg">
        <br><br>

        
       </form>
        <footer>
         <h3>Desenvolvedor</h3>
         <p>
            
               Marco Antonio Fernandes da Silva ,
               <br>
               (48)985008662,
              <br>
               
               marcoantoniof668@gmail.com,
              <br>
               
               Costeira do Pirajubaé,
              
               
               Servidão carioca do Rio 199,
              
               
               Florianopólis SC
            
         </p>
         <br><br>
         <h3>Apoiadores:</h3>
         <img src="logo-pasta.png" style="height: 40px;">
         &nbsp;&nbsp;&nbsp;&nbsp;
         <img src="LOGO-NETCOM-2.jpg" style="height: 40px;">
      </footer>
       </header>
       
</body>
</html>

.navbar{
    display: flex;
    flex-flow: row wrap;
    height: 100px;
    background-color: rgb(250, 255, 253);
    justify-content: center;
    align-items: center;
    border-radius: 1%;   
}
 
.logo{
    flex: 20%;
    margin-left: 10%;
    border: 1px solid rgb(252, 243, 243);
    text-align: center;
    font-family: 'Inconsolata', monospace;
font-family: 'Roboto', sans-serif;
}

h1{
    text-align: center;
    color: rgb(21, 22, 21);
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.menu{
    flex: 70%;
    text-align: right;
    padding: 20px;
   /* border: 1px solid black;*/
}

 
.menu a{
    color: rgb(20, 20, 20);
    text-decoration: none;
    font-size: 20px;
    pad: 15px 16px;
    margin-bottom: 10%;
}

.menu a:hover{
    color: rgb(143, 10, 99);
    border-top: 4px solid , rgb(141, 18, 49);
    margin-top: 20%;
}

body{
    background-color: rgb(253, 251, 251);
    text-align: center;
}
h2{
    text-align: center;
    font-size: 30px;
}
p{
    text-align: center;
}
header{
    background-color: rgb(246, 252, 250);
}
