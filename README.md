<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form contato</title>
    <!-- ---- CSS ---- -->
    <style>
        *{ margin: 0; padding: 0; box-sizing: border-box;}
        body{
            background-color: #BDB76B;
        }

        form{
            background-color: #FFFFE0;
            max-width: 500px;
            width: 70%;
            padding: 20px;
            position: absolute;
            left:50%;
            top: 50%;
            transform: translate(-50%, -50%);
        }
        form h3{
            text-align: center;
            color:	#BDB76B;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }
        form input[type=text],
        form input[type=password]{
            width: 100%;
            height: 45px;
            border: 1px solid #ccc;
            padding-left: 10px;
            margin: 10px 0;

        }
        form input[type=submit]{
            width: 100%;
            height: 40px;
            cursor: pointer;
            background-color:#BDB76B;
            color: white;
            border:0;
            border-radius: 20px;
        }
        form input[type=submit]:hover{
            background-color: #B8860B;
            transition: 1s;
        }
        form input[type=text]:focus{
            outline:0;
        }
        form input[type=password]:focus{
            outline:0;
        }
    </style>
</head>
<body>
    <!-- ---- HTML ---- -->
    <form>
        <h3>Entrar em contato</h3>
        <input id="email" type="text" name="e-mail" placeholder='Seu email...'/>
        <input id='password' type="password" name=" senha " placeholder="Sua senha...">
        <input type="submit" name="acao" value="Enviar"/>
    </form>
   
</body>
</html>

