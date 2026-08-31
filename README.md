Operação Consumidor — Multiplayer 20
O que é
Projeto único que junta os dois modos:
Vários jogadores no mesmo celular: 3–20 jogadores.
Online: cada jogador usa seu próprio celular/dispositivo; 3–20 jogadores por sala.
PWA instalável: em navegador compatível, use “Adicionar à tela inicial/Instalar aplicativo”.
Rodar no computador
Instale Node.js 18 ou mais recente.
Abra um terminal nesta pasta.
Execute npm install.
Execute npm start.
Abra http://localhost:3000.
Colocar online
Hospede esta pasta em um serviço que aceite Node.js e WebSocket. O comando de inicialização é npm start. O serviço precisa permitir WebSocket. Depois de publicado, compartilhe o endereço HTTPS com os jogadores.
Observação
O servidor mantém as salas em memória. Se o servidor reiniciar, as salas e partidas em andamento são encerradas.
