# srlemos
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login</title>
    <link rel="stylesheet" href="css/estilo.css">
</head>
<body>
    <div class="container">
    <div class="wrapper">
        <div class="title" >
            <span>faça seu login</span>
            </div>
            <form action="">
            <div class="row">
                <div class="i"><i class="fa-solid fa-user" style="color:white"></i></div>
                <input type= "text" placeholder = "Email" id="email" required>                
            </div>
            <div class="row">
                <div class="fa- solid fa-lock" style="color: white;">
                    <input type="password" placeholder="senha" id="senha" required>
            </div>
            <div class="row button">

            <div class="pass"><p>Esqueceu a Senha?</p></div>
            <input type="submit" value="Login" onclick="Logar(); return false">
            </div>





            </form>
</body>
</html>



CSS

/*tira toda fomatação padrão de css */
*{
margin: 0;
padding: 0;
box-sizing: border-box;
}

/*fonte do css3 serve para importar fontes(tipografias)
externa para toda página*/
@font-face {
    font-family: 'Montebello';
    src: url(Montebello-regular.ttf)format("truetype"), url("Montebello-Light.otf")format("opentype");
    font-weight: normals;
    font-style: normal;
}

/*corpo da página*/
body{
    width: 100%;
    height: 100%;
    background: red;
    overflow: hidden;
}

/* regra div container */
.container{
    max-width: 400px;
    padding: 0 20px;
    margin: 170px auto;
}

/* a regra para div wrapper essa regra afeta tudo e cria uma caixa para a tela de login */
.wrapper{
    width: 400px;
    height: 340px;
    background: whitesmoke;
    border-radius: 7px;
    box-shadow: 0 6px 4px -4px rgba(0,0,0,0,0.25);
}

/* faixa superior para a tela de login */
.wrapper .title{
    line-height: 80px;
    background: gray;
    padding-left: 20px;
    border-radius: 7px 7px 0 0;
    font-size: 25px;
    color: rgb(243, 241, 241);
    font-weight: 600;
    font-family: 'Montebello', Times, serif;   
}

/* regra de movimento do formulario */

.wrapper form{
    padding: 30px 20px 25px 20px;
}

/* posicionamento dos elementos do formulario  */
.wrapper form .row{
height: 45px;
margin-bottom: 15px;
position: relative;
}
