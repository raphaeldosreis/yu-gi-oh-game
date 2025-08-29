Yu-Gi-Oh! Master Duel (Web)
Este é um projeto de jogo de cartas Yu-Gi-Oh! para navegador, desenvolvido com HTML, CSS e JavaScript puro. O jogo simula as mecânicas básicas de um duelo, permitindo a interação entre o jogador e um oponente 

Funcionalidades
Tabuleiro de Duelo 3D: Uma representação visual do campo de duelo com efeito 3D.

Gerenciamento de Pontos de Vida: Contadores de LP para o jogador e o oponente.

Decks e Cemitérios: Gerenciamento de cartas nos decks e no cemitério para ambos os jogadores.

Invocação de Monstros: Capacidade de invocar monstros do deck na sua zona de campo.

Posições de Batalha: Invocações em posição de ataque ou defesa.

Inteligência Artificial (IA): Um oponente básico que saca cartas, invoca monstros e ataca.

Log de Duelo: Um painel que registra as ações do jogo.

Animações: Animações básicas para sacar e mover cartas.

Tecnologias Utilizadas
HTML5: Estrutura da página e elementos do jogo.

CSS3: Estilização do tabuleiro, cartas e interfaces.

Tailwind CSS: Utilizado para estilização e responsividade da interface.

JavaScript ES6+: Lógica do jogo, gerenciamento do estado, manipulação do DOM e a inteligência artificial do oponente.

Como Jogar
Abra o arquivo index.html em qualquer navegador moderno.

O duelo se inicia automaticamente.

Arraste uma carta da sua mão para uma das zonas de monstro no campo.

Escolha a posição de invocação (Ataque ou Defesa).

Clique no botão "Passar Turno" para que o oponente jogue.

O jogo continua até que um dos jogadores tenha seus Pontos de Vida reduzidos a 0.

Estrutura do Código
index.html: Arquivo principal que contém a estrutura HTML, os estilos CSS e toda a lógica JavaScript.

Estilização: O CSS embutido no <style> define o layout e o visual do jogo.

Lógica do Jogo: O JavaScript no <script> no final do <body> gerencia o estado do jogo (gameState), a interação do usuário (arrastar e soltar), as ações da IA e a renderização do campo.

