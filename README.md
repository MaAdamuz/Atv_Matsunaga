Lista Interativa.

Integrantes: Vinicius Martins, Matheus Adamuz, Gustavo Almirão

Tecnologias/Linguagens: Visual Studio Code, HTML/CSS/JS/JQUERY e Tailwind CSS.

Este é um projeto web simples de uma lista interativa, desenvolvido com HTML, CSS e JavaScript puro. O sistema simula uma aplicação com autenticação básica, manipulação de itens (CRUD), visualização de detalhes e persistência local usando localStorage.

🔧 Funcionalidades
Login Simulado:
A página index.html apresenta uma tela de login simples. A autenticação é validada diretamente no JavaScript com credenciais fixas.

Home (home.html):
Após o login, o usuário é redirecionado para a tela principal onde pode:

Adicionar novos itens à lista;

Editar título e descrição dos itens;

Marcar ou desmarcar como concluído;

Remover itens da lista;

Compartilhar um item (redirecionamento para detalhes.html com base no ID do item).

Detalhes (detalhes.html):
Página que exibe os detalhes completos de um item da lista. A navegação é feita ao clicar em “compartilhar” em um item da home.

Persistência Local com localStorage:
Todos os itens da lista são armazenados no navegador por meio do localStorage, garantindo que as informações não se percam ao recarregar a página.

🛠️ Tecnologias Utilizadas
HTML5

CSS3

JavaScript Puro (Vanilla JS)

▶️ Como Usar:
Abra o arquivo index.html em um navegador.

Faça login com as credenciais simuladas(usuario, 1234).

Gerencie sua lista interativa na home.html.

Visualize os detalhes dos itens clicando em “compartilhar”.

