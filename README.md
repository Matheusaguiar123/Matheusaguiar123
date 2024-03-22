V<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="width=device-width" content="width=, initial-scale=1.0">
    <!-- google fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <!-- fim google fonts -->
    <!-- icones -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <!-- icones -->
    <title>VALGANI FARMÁCIA DE MANIPULAÇÃO</title>
    <link rel="stylesheet" href="tema-claro.css">
    <link rel="stylesheet" href="tema.js">

    <style>
        body {
            background-color: #fff; /* Fundo branco */
            color: #000; /* Texto preto */
        }
    </style>
</head>

<body>
    <header>
        <style>
            /* Estilos para o alerta */
            #alerta {
                display: none;
                position: fixed;
                bottom: 100px;
                left: 50%;
                transform: translateX(-50%);
                background-color: #fa2a1b;
                color: white;
                padding: 15px;
                border-radius: 10px;
                z-index: 9999;
            }
        </style>
       <div id="alerta">
        Pagamentos e orçamentos somente em nosso WhatsApp. 
    </div>
    
    <script>
        // Função para mostrar o alerta
        function mostrarAlerta() {
            document.getElementById("alerta").style.display = "block";
        }
    
        // Função para esconder o alerta após 5 segundos
        function esconderAlerta() {
            document.getElementById("alerta").style.display = "none";
        }
    
        // Mostrar o alerta quando a página carregar
        mostrarAlerta();
    
        // Esconder o alerta após 5 segundos
        setTimeout(esconderAlerta, 5000); // Tempo em milissegundos (5 segundos)
    </script>
    
        <div class="interface">
            <div class="logo">
                <a href="#"></a>
                <img src="./img/logo-removebg-preview.png" width="200" height="200" alt="logo">
            </div><!-- fim de class logo -->
         
            <nav class="menu">
                <ul>

                    <style>
                        /* Estilo para aumentar o tamanho do botão */
                        .bi-sun-fill {
                            font-size: 34px; /* Defina o tamanho desejado para o ícone */
                        }
                    </style>

                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#proje">Informátivos</a></li>
                    <li><a href="#fim">Contatos</a></li>
                    <li><a href="ValganiP.html"><i class="bi bi-sun-fill"></i></a></li>
                </ul>
            </nav><!-- fim de class menu -->

            <div class="btn-contato">
                <a href="https://api.whatsapp.com/send?phone=5531983238772&text=Oi%20Farmácia%20Valgani"><button><i class="bi bi-whatsapp"></i></button></a>
            </div>
        </div> <!-- fim de class interface -->
  
            
    </header>
    <main>
        <section class="topo-site">
            <div class="interface">
                <div class="flex">

                    <div class="txt-topo">
                        <h1>Valgani Farmácia de <span>Manipulação</span></h1>

                        <p><strong>Valgani Farmácia de Manipulação é uma empresa dedicada à saúde e ao bem-estar, que tem como objetivo oferecer soluções personalizadas e de alta qualidade para seus clientes. Fundada em <span>01 de Agosto de 2001</span>, na cidade de <span> Belo Horizonte</span> a Valgani se destaca pelo seu compromisso com a excelência, tanto na seleção de matérias-primas quanto na elaboração de formulações sob medida.</p></strong> 

                        <div class="btn-contato">
                            <a href="https://www.google.com/maps/@-19.923792,-43.9233214,3a,67.5y,102.81h,87.2t/data=!3m6!1e1!3m4!1sRtpESp5kMQeD7JL4MaPOZw!2e0!7i16384!8i8192?entry=ttu">
                                <button>Localização</button>
                            </a>
                            <div class="img-topo-site">
                                <img src="./img/remedio.jpg" width="250" height="250" alt="">
                            </div> <!-- txt topo -->
                        </div><!-- btn contato -->

                    </div> <!-- flex -->
                </div> <!-- img topo site -->
            </div><!-- interface -->
        </section><!-- topo site -->
        <section class="especialidades">
            <div class="interface">
                <a id="remedio"></a>
                <h2 class="titulo"> O que tem em um remédio de  <span> manipulação?</span></h2>
                <a id="remedio"></a>
            </div>
            <div class="flex">
                <div class="especialidades-box">
                    <i class="bi bi-capsule"></i>
                    <h3>Personalização</h3>
                </div>

                <div class="especialidades-box">
                    <i class="bi bi-hospital"></i>
                    <h3>Acessibilidade</h3>
                </div>
                <div class="especialidades-box">
                    <i class="bi bi-capsule-pill"></i>
                    <h3>Evita ingredientes desnecessários</h3>
                </div>
                <div class="especialidades-box">
                    <i class="bi bi-bandaid"></i>
                    <h3>Saudavel</h3>
                </div>

        </section>
        <section> <!-- sobre -->
            <div class="sobre">
                <div class="interface">
                    <div class="flex">
                        <style>
                            .img-sobre img {
                                border-radius: 0px;
                                width: 500px;
                                height: 500px;

                            }
                        </style>
                        <div class="img-sobre">
                            <img src="./img/1.jpeg" alt="">
                        </div><!-- class img-sobre-->
                        
                        <script>
                            // Lista de URLs das imagens que você deseja alternar
                            var imagens = [
                            "./img/1.jpeg",
                                "./img/2.jpeg",
                                "./img/3.jpeg"
                            ];
                        
                            // Índice da imagem atual
                            var indiceAtual = 0;
                        
                            // Função para alternar para a próxima imagem
                            function proximaImagem() {
                                indiceAtual = (indiceAtual + 1) % imagens.length;
                                document.querySelector('.img-sobre img').src = imagens[indiceAtual];
                            }
                        
                            // Chamada da função para iniciar a troca de imagens (pode ser chamada em um evento, como clique em um botão)
                            // Aqui, é chamada após um intervalo de tempo (por exemplo, 5 segundos)
                            setInterval(proximaImagem, 3000); // Alterna a imagem a cada 5 segundos (5000 milissegundos)
                        </script>
                        <div class="txt-sobre">
                            <a id="sobre"></a>
                            <h2> Quem nós <span>somos:</span></h2>



                            <p><strong> Desde de <span>primerio de Agosto de 2001 </span>, com o passar dos anos, a Valgani conquistou reconhecimento e credibilidade no mercado, tornando-se uma referência em qualidade e confiabilidade. Seja na formulação de medicamentos, cosméticos ou suplementos nutricionais, a Valgani se compromete a oferecer produtos seguros e eficazes, contribuindo para a saúde e o bem-estar de seus clientes.

                                Com uma visão de futuro voltada para a expansão e aprimoramento de seus serviços, a Valgani Farmácia de Manipulação continua firme em seu propósito de proporcionar saúde e qualidade de vida através da manipulação de produtos farmacêuticos personalizados e inovadores.
                            </p></strong>

                            <div class="btn-social">
                                <a href="https://www.instagram.com/farmaciavalgani/"><button><i class="bi bi-instagram"></i></button></a>
                                <a href="https://br.linkedin.com/in/valgani"><button><i class="bi bi-linkedin"></i></button></a>
                                <a href="https://api.whatsapp.com/send?phone=5531983238772&text=Oi%20Farmacia%20Valgani"><button><i class="bi bi-whatsapp"></i></button></a>
                                <a href="https://www.youtube.com/watch?v=Mj4zClpFmrI"><button><i class="bi bi-youtube"></i></button></a>
                            </div>
                        </div><!-- class txt-sobre -->
                    </div><!-- class flex -->
                </div><!-- class txt-sobre -->
            </div>
        </section>
        <section class="projeto">
            <div class="interface">
                <a id="proje"></a>

                <h2 class="titulo"><span>Serviços</span></h2>

                <div class="flex">

                    <div class="img-proj" style="background-image: url(img/imagem.png);">
                        <a href="explicação.html">
                        <div class="escurecer">O que tem em um remédio de manipulação?</div></a>
                    </div><!-- img-proj -->

                    <div class="img-proj" style="background-image: url(img/t2.JPG);">
                        <a href="modo de preparo.html">
                            <div class="escurecer"></div></a>
                    </div><!-- img-proj -->

                    <div class="img-proj" style="background-image: url(img/t3.JPG);">
                        <div class="escurecer"></div>
                    </div><!-- img-proj -->

                </div><!-- flex -->
            </div><!-- interface -->
        </section><!-- projeto -->
    </main>
    <footer>
        <div class="interface">
            <div class="rodape">
                <div class="flex">
                    <div class="logo-rodape">
                        <img src="img/logo-removebg-preview.png" width="200" height="200" alt="logo rodape">
                    </div>
                    <div class="btn-social">
                        <a href="https://www.instagram.com/farmaciavalgani/"><button><i class="bi bi-instagram"></i></button></a>
                        <a href="https://br.linkedin.com/in/valgani"><button><i class="bi bi-linkedin"></i></button></a>
                        <a href="https://api.whatsapp.com/send?phone=5531983238772&text=Oi%20Fármacia%20Valgani"><button><i class="bi bi-whatsapp"></i></button></a>
                    </div><!-- btn-social -->
                </div>
            </div>

            <div class="rodape borda">
                <p><i class="bi bi-envelope"></i><a href="mailto:valgani@valgani.com.br">valgani@valgani.com.br</a></p>
            </div><!-- rodape -->
            <div>
                <div class="rodape borda">
                    <p><i class="bi bi-info-square-fill"></i><a href="https://cnpj.biz/04659619000163">CNPJ: 04.659.619/0001-63</a></p>
                </div><!-- rodape -->
                <div>
        </div><!-- interface -->
        <a id="fim"></a>
    </footer>

    <style>
        /* Estilos para telas menores, como smartphones */
    @media only screen and (max-width: 200px) {
        /* Adicione estilos específicos para telas menores aqui */
    }
    
    </style>
</body>

</html>
