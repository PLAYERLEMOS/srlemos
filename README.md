# srlemos
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login</title>
    <link rel="stylesheet" href="css/estilo.css">
</head>

<style>

</style>
<body>
    <div class="container">
    <div class="wrapper">
        <div class="title" >
            <span>Faça seu Login</span>
            </div>
            <form action="">
            <div class="row">
                <div class="i"><i class="fa-solid fa-user" style="color:white"></i></div>
                <input type= "text" placeholder = "Email" id="email" required> 
                               
            </div>
            <div class="row">
                <div class="i"><i  class="fa- solid fa-lock" style="color: white;"></i></div>
                    <input type="password" placeholder="Senha" id="senha" required>
            </div>
<br>
            <div class="row button">
            <div class="pass"><p>Esqueceu a Senha?</p></div><br>
            <input type="submit" value="Login" onclick="Logar(); return false">
            </div>

            </form>
</body>
</html>



#CSS

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
        background: rgb(27, 127, 251);
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
        background: rgb(7, 172, 255);
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
    
    /*Posicionamento dos elementos do formulario*/
    .wrapper form .row{
    height: 45px;
    margin-bottom: 15px;
    position: relative;
    }

    /*Personaliza as bordas e utiliza a fonte baixada*/
    .wrapper form .row input{
        height: 100%;
        width: 100%;
        outline: none;
        padding-left: 60px;
        border-radius: 5px;
        border: 1px solid rgb(0, 0, 0);

    }

    /*Elementos, Efeitos, Sombras e etc*/
    .wrapper form .row .i{
        position: absolute;
        width: 47px;
        height: 100%;
        font-size: 20px;
        background: gray;
        box-shadow: 0 4px 2px -2px rgba(0,0,0,0,0.25);
        border-radius: 5px 0 0 5px;
        display: flex;
        align-items: center;
        justify-content: center;
}

    .wrapper form .pass{
        margin: -8px 0 20px 0;
    }

    .wrapper form .pass p{
        color: rgb(239, 37, 6);
        font-size: 17px;
        text-decoration: url(Montebello-regular.ttf)format("truetype"), url("Montebello-Light.otf")format("opentype");
    }

    .wrapper form .pass p :hover{
        text-decoration: none;

    }
    /*Configuração do botão*/
    .wrapper form .button input{
        color: white;
        height: 30px;
        width: 50px;
        font-size: 10px;
        font-weight: 500;
        padding-left: 0;
        background: rgb(70, 192, 13);
        border: 1px solid rgb(0, 0, 0);
        cursor: pointer;
    }
    
    

