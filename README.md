<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css" integrity="sha512-10/jx2EXwxxWqCLX/hHth/vu2KY3jCF70dCQB8TSgNjbCVAC/8vai53GfMDrO2Emgwccf2pJqxct9ehpzG+MTw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Portfólio João</title>
</head>
<body>

    <div class="background">
        <header>
            <div class="logo">
                <i class="fa-regular fa-j"></i>
            </div>

            <div class="cabeçalho-link">

                <li>
                    <a href="#">Home</a>
                </li>

                <li>
                    <a href="#">Sobre</a>
                </li>

                <button><a href="https://wa.me/5527998400260">Meu Contato</a></button>

            </div>
        </header>

        <div class="container-text">
            <div class="text">
                    <h3>Olá, bem-vindo!</h3>
                    <h1>Eu sou <span>João Victor</span></h1>
                    <p>Tenho 21 anos, curso Análise e Desenvolvimento de Sistemas<br>na instituição FAESA.</p>
                    <p>Este é o meu site xD</p>
                <div class="redes-social"> 
                    <a href="https://wa.me/5527998400260" target="_blank"><i class="fa-brands fa-whatsapp"></i></a>
                    <a href="https://www.instagram.com/jvcrf1/" target="_blank"><i class="fa-brands fa-instagram"></i></a>                  
                    <a href="https://github.com/joaocrf1/" target="_blank"><i class="fa-brands fa-github"></i></i></a>
                </div>
                <button onclick="" class="btn">Sobre Mim<a href="#"></a></button>
            </div>
            <img src="/img/img_joao.jpeg" alt="João Victor">
        </div>
    </div>


    <script type="script.js"></script>    
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>



</body>
</html>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins" , sans-serif;
    text-decoration: none;
    list-style: none;
}

body{
    overflow: hidden;
}

.background{
    background: linear-gradient(rgba(0, 0, 0, 1), rgba(0, 0, 0, 0.5)),url();
    background-size: cover;
    background-position: center;
    width: 100%;
    height: 100vh;
   
}

header{
    display: flex;
    justify-content: space-around;
    max-width: 100%;
    align-items: center;
    text-align: center;
    padding-top: 1rem;   
}

.cabeçalho-link{
    display: flex;
    gap: 3rem;
    font-weight: 300;
    cursor: pointer;  
}

.cabeçalho-link a{
    color: #fff;
    font-size: 12px;
}

.cabeçalho-link a:hover{
    color:  #4c8df5;
    transition: 0.3s all;
}

.logo i{
    height: 40px;
    width: 40px;
    background: transparent;
    border: 1px solid #f54c4c;
    color: #f54c4c;
    border-radius: 50%;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    font-size: 13px;
    cursor: pointer;
}

.logo :hover{
    background-color: #f54c4c;
    color:#fff;
    transition: 0.5s;
}

button{
    color: #f54c4c;
    background: transparent;
    border:solid 1px #f54c4c;
    padding: 5px;
    border-radius: 15px;
    font-size: 12px;
    cursor: pointer;
    width: 150px;
}

button:hover{
    color: #fff;
    transition: 0.5s;
}

.container-text{
    padding: 150px 0 0 130px;
    display: flex;
    justify-content: space-around;

}

img{
    margin: -3%;
    width: 500px;
    height: 470px;
    border-radius: 55%;
}

.text h3{
    color: #fff;
    font-size: 15px;
}

.text h1{
    color: #fff;
    margin-top: 10px;
}

.text span{
    color: #f54c4c; 
}

.text p{
    color: #fff;
    font-weight: 500;
    margin-top: 10px;
    font-size: 13px;
}

.redes-social{
    margin-top: 10px;
}

.redes-social a{
    color: #f54c4c;
    padding: 10px;
    margin-top: 5px;
}

.btn{
    margin-top: 15px;
}

@media screen and (max-width:900px){
    .cabeçalho-link {
        display: none;
    }
    .header{
        display: flex;
        align-items: center;
        justify-content: left;
    }
    .container-text{
        display: flex;
        align-items: center;
        justify-content: left;
    }
    .container-text img{
        display: none;
    }
}
