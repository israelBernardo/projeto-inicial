🎯 Jogo do Número Secreto

Este é um jogo simples de adivinhação desenvolvido em JavaScript, onde o jogador tenta descobrir um número secreto gerado aleatoriamente entre 1 e 50. O jogo fornece dicas se o número chutado é maior ou menor que o número secreto e utiliza síntese de voz para tornar a experiência mais interativa.

🚀 Funcionalidades

- Geração aleatória de número secreto entre 1 e 50.
- Validação de tentativas do jogador.
- Feedback interativo com voz (via ResponsiveVoice).
- Controle de números já sorteados para evitar repetições.
- Reinício do jogo com novo número secreto.

🧠 Lógica do Jogo

1. Um número secreto é gerado aleatoriamente.
2. O jogador insere um palpite.
3. O jogo informa se o palpite está correto, ou se o número secreto é maior ou menor.
4. O número de tentativas é contabilizado.
5. Ao acertar, o botão de reinício é habilitado para jogar novamente.

📁 Estrutura do Código

- listaDeNumerosSorteados: Armazena os números já utilizados para evitar repetições.
- numeroLimite: Define o limite superior do intervalo de números.
- numeroSecreto: Armazena o número atual a ser adivinhado.
- tentativas: Conta o número de palpites feitos.

🔊 Requisitos

- Navegador com suporte a JavaScript.
- Conexão com a internet para utilizar a API do ResponsiveVoice.

🖥️ Como usar

1. Abra o arquivo HTML no navegador.
2. Digite um número entre 1 e 50 no campo de entrada.
3. Clique no botão para verificar o palpite.
4. Receba feedback visual e por voz.
5. Ao acertar, clique em "Reiniciar" para jogar novamente.

📌 Observações

- O jogo evita repetir números já sorteados até que todos os números do intervalo tenham sido utilizados.
- A voz utilizada é a "Brazilian Portuguese Female" com velocidade ajustada para melhor compreensão.
