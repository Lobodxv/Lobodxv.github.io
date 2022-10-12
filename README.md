<!DOCTYPE html>
<html lang="en">
    <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>
                EEEP JG
            </title>
            <!--font-->
            <link rel="preconnect" href="https://fonts.googleapis.com">
            <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
            <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.css">


        <!-- Js -->
        <script type="text/javascript">
            function abrirWindow() {
                document.getElementById('modal').style.top = "0";
            }
            function fecharWindow() {
                document.getElementById('modal').style.top = "-100%";
            }
        </script>

        <!--Folha de estilo CSS-->
        <style>
/* KEYFRAMES */

/*@keyframes animacao{
    0% {border-color:rgb(253, 156, 65);}
    25% {border-color: rgb(51, 252, 33);}
    50% {border-color: green;}
    75% {border-color: rgb(253, 181, 47);}
    100% {border-color: rgb(255, 166, 0);}
} */
@keyframes animacaobt{
    0% {background-color: orange;}
    25% {background-color: rgb(95, 129, 2);}
    50% {background-color: yellow;}
    100% {background-color: green;} 
}
@keyframes animacaosimples{
    from {color: white;}
    to {color: rgb(185, 185, 185);}
}
@keyframes criador{
    from {color: rgb(187, 187, 187);}
    to {color: rgb(49, 49, 49)}
}
@keyframes arco-iris{

}
/*  Header  */
            * {
                margin: 0;
                padding: 0;
                background-color: rgb(20, 20, 20); 
            }
            .criador{
                cursor: pointer;
                font-family:'Arial Bold', sans-serif;
                font-style: italic;
                font-size: 13px;
                color: rgb(54, 54, 54);
                text-shadow:rgb(48, 48, 48);
                background-color: none;
                margin-right: 10px;
                text-align:center;
                width: 100%;
                height: 10px;
                margin-bottom: 0;
                padding: 5px;
                animation-name: criador;
                    animation-duration: 850ms;
                    animation-iteration-count: infinite;
                    animation-direction: alternate-reverse;
            }
            .nameCriador, .fa-code{
                animation-name: criador;
                    animation-duration: 850ms;
                    animation-iteration-count: infinite;
                    animation-direction: alternate-reverse;
            }
            .nameCriador .fa-code{
                cursor: pointer;
            }
            #header {
                background-color: rgb(46, 146, 0);
                color: white;
                width: 100%;
                height: 150px;
                position: relative;
            }
                #textHeader {
                    color: white;
                    background-color:rgb(46, 146, 0);
                    font-size: 30px;
                    width: 500px;
                    margin: 0 auto;
                    font-family: 'Rubik', sans-serif;
                    text-align: center;
                    cursor: pointer;
                    animation-name: animacaosimples;
                        animation-duration: 2s;
                        animation-iteration-count: infinite;
                        animation-direction: alternate-reverse; 

                }
                #textHeader:hover {
                    color: rgb(212, 212, 212);
                    transition: 350ms; 
                }
                #headerTwo {
                    background-color: white;
                    color: white;
                    width: 100%;
                    height: 10px;
                }
                    #headerThree {
                        background-color: rgb(255, 136, 0);
                        width: 100%;
                        height: 25px; 
                    }
                
/* end Header  */

            #info {
                color: white; 
                border-style:dotted;
                border-bottom-color: rgb(133, 87, 2);
                border-top-color: rgb(26, 87, 2);
                border-left-color: rgb(88, 88, 88);
                border-right-color: rgb(88, 88, 88);
                width:400px;
                height:250px;
                border-width:3px;
                padding: 5px;
                text-align:center;
                text-transform:initial;
                font-family: 'Rubik', sans-serif;
                display: inline-block; 
                margin-right:350px;
                margin-left: 20px;
                float:none;
                word-wrap:break-word; 
            }
            #info h2{
                color:white;
                transition: 350ms;
            }
            #info h2:hover{
                cursor: pointer;
                color: rgb(163, 106, 0);
                transition: 350ms; 
            }

            #info p {
                font-size: 17px;
                font-family: 'Poppins', sans-serif;
                margin-top: 20px;
            }

            /* Window buttom and buttom css */
            .bgWindow {
                width: 100%;
                height: 100%;
                background: rgba(0,0,0,0.75);
                position: fixed; 
                z-index: 2;
                top: -100%;
                display: block; 
                transition: 750ms;
            }

            .window {
                width: 50%;
                height: 60%;
                background-color: rgb(20, 20, 20);
                border: 1px solid #000;
                border-radius: 5px;   
                margin: 100px auto 0 auto;
                font-size: 40px; 
            }
            .window span {
                margin-left: 10px;
                margin-right: 10px; 
                color:rgb(133, 87, 2)
            }
            .window span:hover {
                color: rgb(26, 87, 2);
                transition: 350ms;
                cursor:pointer; 
            }
            .openWindow {
                background-color:rgb(255, 131, 0);
                cursor: pointer;
                color: rgb(255, 255, 255);
                width: 350px;
                height: 35px;
                text-align: center;
                font-family:Arial, Helvetica, sans-serif;
                font-size: 16px;
                font-weight: bold;
                border-radius: 15px;
                text-decoration-style: solid;
                border-style:none;
                margin-left: 37%;
                margin-top: 35px;
                margin-bottom: 20px;
                z-index: 2;
                animation-name: animacaobt;
                    animation-duration: 2s;
                    animation-iteration-count: infinite;
                    animation-direction: alternate-reverse;
            }
            .openWindow:hover {
                background-color: rgb(46, 146, 0);
                color: white;
                transition: 500ms;
            }

        </style>
    </head>
    <body>
        <!--HTML-->
        <div id="header">
            <br>
            <br>
            <br>
            <h1 id="textHeader">EEEP João Jackson Lobo Guerra</h1>
        </div>
        <div id="headerTwo"></div> 
        <div id="headerThree"></div><br>
        <br> 
        <div id="info">
            <h2 class="tituloInfo">Lorem ipsum</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam ac enim arcu. Vivamus quis neque sagittis.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam ac enim arcu.</p>
        </div>

        <!-- Button window -->
        <button class="openWindow" onclick="abrirWindow()">Saiba mais sobre nossa escola</button>
        <div class="bgWindow" id="modal">
            <div class="window">
                <span class="close" onclick="fecharWindow()">&times;</span>
            </div>
        </div>
        <!-- Tag do criador -->
        <div href="https://instagram.com/imanoellob/" class="criador">
          2022 © | Desenvolvido por <b class="nameCriador">Manoel Lobo </b><i class='fas fa-code'></i>
        </div>



                          <!--||| Código feito por Manoel Lobo |||-->

    </body>
</html>
