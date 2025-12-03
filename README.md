# .gitignore
Explicação:
O projeto "Portal de Notícias Dinâmico" é um exercício prático de Programação Back-End (PBE) que visa transformar um website estático em uma aplicação viva e atualizada utilizando a plataforma Node.js.
O objetivo central é conectar um layout (a parte visual que o usuário vê) com uma API (Interface de Programação de Aplicações) real de notícias, a NewsAPI.org, para que o conteúdo (títulos, imagens e descrições) seja carregado dinamicamente a cada acesso, em vez de ser fixo no código HTML.

Como Rodar:

1. Configurar a chave API 
Certifique-se de que o arquivo .env na raiz do projeto está preenchido com a sua chave da NewsAPI e a porta:
API_KEY=sua_chave_obtida_no_passo_1_aqui
PORT=3000

2. Iniciar o Servidor
Abra o terminal na pasta portal-backend/ (onde estão os arquivos app.js e package.json) e execute o comando:
node app.js
Dica: O servidor iniciará e você verá a mensagem: Servidor rodando em http://localhost:3000

3. Acessar no Navegador
Abra o seu navegador web (Chrome, Firefox, etc.) e acesse o endereço:
http://localhost:3000








