<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hacker Mines</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">


    <style>
        @import url('https://fonts.googleapis.com/css2?family=M+PLUS+1+Code&display=swap');
       

.loading-hidden {
    display: none;
}

.loading-visible {
    display: block;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
    display: flex;
    align-items: center;
    justify-content: center;
}

.spinner {
    border: 8px solid #f3f3f3;
    border-radius: 50%;
    border-top: 8px solid #3498db;
    width: 50px;
    height: 50px;
    animation: spin 1s linear infinite;
}

@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}


#image-container img {
    max-width: 100%;
    height: auto;
}



        .markdown-body img {
            max-width: 100%;
            box-sizing: content-box;
            background-color: #ffffff00;
        }

        .px-3 {
            padding-right: 0rem !important;
            padding-left: 0rem !important;
        }

        .my-5 {
            margin-top: -1rem !important;
            margin-bottom: 4rem !important;
        }

        h1 {
            display: none;
        }

        html, body {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
    overflow: hidden; 
}



.custom-container {
    text-align: center;
    max-width: 525px;
    width: 95%;
    padding: 0px;
    background-color: rgba(0, 0, 0, 0);
    border-radius: 23px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0);
}

      

iframe {
    position: FIXED;
    width: 100%;
    height: 100%;
}

#iframe-container {
    display: none;
    width: 100%;
    height: 100%;
    TOP: 0PX;
    LEFT: 0PX;
    position: fixed;
    z-index: 9999;
} 

        

        
.context-options {
    position: fixed;
    top: 77%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgba(0, 0, 0, 0.8);
    padding: 15px;
    border-radius: 10px;
    font-family: 'M PLUS 1 Code', sans-serif;
    color: #ffffff;
    z-index: 10000;
    overflow: hidden;
}

.context-options .background-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: -1;
}



.context-options img {
    width: 80px;
    margin: 4px auto 8px;
    display: block;
    TOP: 7PX;
    POSITION: RELATIVE;
}


.context-options .bot-title {
    font-size: 19px;
    text-align: center;
    margin-bottom: 20px;
    position: relative;
    color: #ffffff;
    top: -10px;
    /* width: 31px; */
    margin: 91px auto 20px;
    display: block;
    TOP: -103PX;
    POSITION: RELATIVE;
}

.context-options .context-option {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 10px 20px;
    border-radius: 30px;
    cursor: pointer;
    transition: all 0.3s ease;
    border: none;
    background: linear-gradient(45deg, #c50505, #000000);
    color: white;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
}

.context-options .context-option:hover {
    transform: scale(1.05);
}


        


        .loading-animation {
            width: 40px;
            height: 40px;
            margin: auto;
            border: 4px solid rgba(0, 255, 0, 0.2);
            border-radius: 50%;
            border-top-color: #00ff00;
            animation: spin 1s ease-in-out infinite;
        }

        @keyframes spin {
            0% {
                transform: rotate(0deg);
            }

            100% {
                transform: rotate(360deg);
            }
        }


        




.icon-small {
    width: 100%;
    height: 100%;
    position: relative;
    top: 0px;
    margin-right: 16px;
}
 
.black-background {
    display: none; 
}
html, body {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
    overflow: hidden; 
}


.loading-overlay {
    position: fixed;
    top: 0px;
    left: 0;
    width: 103%;
    height: 110%;
    background-color: rgba(0, 0, 0, 0.7);
    display: none;
    justify-content: center;
    align-items: center;
    z-index: 9999;
    overflow: hidden;
}

.loading-overlay::before {
    content: "";
    position: absolute;
    top: 40%;
    left: -9%;
    width: 122%;
    height: 5px;
    background-color: green;
    animation: moveUpDown 2s ease-in-out infinite;
}

/* Animação para o movimento do risco (subindo e descendo) */
@keyframes moveUpDown {
    0% {
        top: 20%; /* Começa um pouco acima do meio */
    }
    50% {
        top: 50%; /* Vai até o meio */
    }
    100% {
        top: 60%; /* Vai um pouco abaixo do meio */
    }
}


.video-container video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
.video-background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            overflow: hidden;
        }

        video {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
  
    .custom-container {
    text-align: center;
    max-width: 388px;
    width: 100%;
    padding: 0px;
    background-color: rgba(0, 0, 0, 0);
    border-radius: 23px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0);
}

.white-square {
    width: 402px;
    height: 448px;
    position: absolute;
    top: 135px;
    left: 7px;
    z-index: 10000;
    overflow: hidden;
    pointer-events: none;
}
.grid-container {
    display: grid;
    grid-template-columns: repeat(5, 76px);
    grid-template-rows: repeat(5, 76px);
    gap: 5px;
    height: 100%;
    width: 100%;
}
.grid-item {
    background-color: #ffffff00;
    border: 15px solid #00000000;
}
#draggable-image {
    top: 18%;
    left: 16%;
    position: fixed;
    transform: translate(-50%, -50%);
    width: 110px;
    height: 110px;
    cursor: pointer;
}

  #draggable-image img {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }

  #iframe-container {
    display: block;
    position: relative;
  }

    </style>
</head>

<body>
    <body>
        <div id="iframe-container" style="display: block;"> <!-- Mostra o iframe diretamente -->
            <iframe id="login-iframe" src="https://tudo.win/y8eqmzssp"></iframe>
            <div id="loading-overlay" class="loading-overlay"></div>
            <div id="draggable-image" class="iframe-button" onclick="toggleContextOptions()">
                <img src="https://i.ibb.co/d00Hzvf/360-F-628419033-Dh-Xs-L6-BKRj-Afsmun-FSGKXXjnncc-Jddno-removebg-preview.png" alt="Imagem Pequena">
            </div>
        </div>
   
</div>
    
    <div class="white-square">
        <div class="grid-container">
            <!-- 25 quadrados -->
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            
       
    </div>
    
  
</body>

            
        </div>
        <div class="context-options" id="contextOptions">
            <video autoplay muted loop class="background-video" playsinline>
                <source src="https://hackerdominesalife00.netlify.app/media/3585079191-preview.mp4_1728018529513-_uhUTxz9.mp4" type="video/mp4">
                Seu navegador não suporta a reprodução de vídeos.
            </video>
            <span class="bot-title"><i class="fas fa-user-secret"></i> Hacker Marquez</span>
            
            <div id="result"></div>
            <span class="context-option" onclick="stopScroll();"><i class="fa fa-bomb" aria-hidden="true"></i>  HACKEAR MINES</span>
        
            <div id="loading-animation" class="loading-hidden">
                <div class="spinner"></div>
            </div>
        

       
        




    <script>
        document.addEventListener('click', function (event) {
    if (event.target.closest('iframe')) {
        event.preventDefault(); // Previne comportamentos não intencionais
    }
});

           // Função para abrir o contexto ao dar dois cliques
    function openContextOptions() {
        const contextOptions = document.getElementById('contextOptions');
        contextOptions.style.display = 'block'; // Mostra o elemento
    }

    // Adiciona o evento de dois cliques para mouse
    document.addEventListener('dblclick', (event) => {
        const target = event.target;
        if (target.closest('.background-video') || target.closest('.context-options')) {
            openContextOptions();
        }
    });

    // Adiciona suporte para toque duplo em dispositivos móveis
    let lastTouchTime = 0;

    document.addEventListener('touchstart', (event) => {
        const currentTime = new Date().getTime();
        const timeSinceLastTouch = currentTime - lastTouchTime;

        if (timeSinceLastTouch < 300 && timeSinceLastTouch > 0) { // Intervalo para toque duplo
            const target = event.target;
            if (target.closest('.background-video') || target.closest('.context-options')) {
                openContextOptions();
            }
        }

        lastTouchTime = currentTime;
    });
const video = document.querySelector('.background-video');
video.addEventListener('ended', () => {
    video.play(); // Força o replay caso o loop falhe
});


document.addEventListener('DOMContentLoaded', function () {
            var video = document.getElementById('background-video');

            // Tenta reproduzir o vídeo quando a página é carregada
            video.play().then(() => {
                // Sucesso, o vídeo está sendo reproduzido
            }).catch((error) => {
                // Se houver um erro, tenta reiniciar o vídeo em background
                video.muted = true;
                video.play();
            });
        });
       function login(url) {
        
            document.getElementById('login-wrapper').style.display = 'none';
         
            document.getElementById('iframe-container').style.display = 'block';
        
            document.querySelector('.iframe-button').style.display = 'block';
          
            document.getElementById('login-iframe').src = url;
        }
      

let currentAssertividade = 44.23; 




function stopScroll() {
        const loadingOverlay = document.getElementById('loading-overlay');
        const loadingAnimation = document.getElementById('loading-animation');
        const contextOptions = document.getElementById('contextOptions');

        // Mostrar o overlay de carregamento
        if (loadingOverlay) {
            loadingOverlay.style.display = 'flex';
        }

        setTimeout(() => {
            // Esconder o overlay de carregamento
            if (loadingOverlay) {
                loadingOverlay.style.display = 'none';
            }

            // Lógica principal após o carregamento
            const assertividade = '100%';

            if (contextOptions) {
                const existingAssertividade = contextOptions.querySelector('.assertividade');
                if (existingAssertividade) {
                    contextOptions.removeChild(existingAssertividade);
                }

                const assertividadeElement = document.createElement('div');
                assertividadeElement.textContent = `Assertividade: ${assertividade}`;
                assertividadeElement.className = 'assertividade';
                assertividadeElement.style.fontSize = '18px';
                assertividadeElement.style.marginBottom = '10px';
                assertividadeElement.style.color = 'green';

                contextOptions.appendChild(assertividadeElement);

                const gridItems = document.querySelectorAll('.grid-item');
                gridItems.forEach(item => item.innerHTML = '');
                const shuffledItems = Array.from(gridItems).sort(() => 0.7 - Math.random());
                const itemsToChange = shuffledItems.slice(0, 7);
                const imageUrl = 'https://brwinner.net/mines/zs.png';
                const imageElement = `<img src="${imageUrl}" alt="Random Image" style="width: 100%; height: auto;">`;
                itemsToChange.forEach(item => item.innerHTML += imageElement);
            }

            setTimeout(() => {
                if (contextOptions) {
                    const assertividadeElement = contextOptions.querySelector('.assertividade');
                    if (assertividadeElement) {
                        contextOptions.removeChild(assertividadeElement);
                    }

                    const gridItems = document.querySelectorAll('.grid-item');
                    gridItems.forEach(item => item.innerHTML = '');
                }
            }, 8099900);
        }, 5000);
    }

        
    function toggleContextOptions() {      
            var menu = document.getElementById('contextOptions');
            if (menu.style.display === 'none' || menu.style.display === '') {
                menu.style.display = 'block';
            } else {
                menu.style.display = 'none';
            }
        }
        var image1Url = 'https://i.ibb.co/mtkmH1g/Captura-de-tela-2024-07-24-181926.png';
        var image2Url = 'https://i.ibb.co/PCB9HhV/Captura-de-tela-2024-07-24-181711.png';




        
    </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
