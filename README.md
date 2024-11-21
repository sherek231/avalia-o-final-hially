Estrutura do Projeto:
index.html:
A página principal da loja virtual. Apresenta os produtos em destaque em uma grade visual, com botões para acessar mais detalhes sobre cada item.

produto.html:
Página de detalhes dos produtos. Mostra informações específicas de um produto, como nome, descrição, imagem e preço, baseado no ID passado pela URL.

contato.html:
Página de contato da loja. Inclui um formulário simples para os usuários enviarem mensagens com seus dados (nome, e-mail e mensagem).

style.css:
Arquivo de estilos que define o design e a aparência das páginas. Utiliza uma paleta de cores predominante em tons de laranja e branco.

Imagens de produtos (produto 1.png, produto 2.png, etc.)
Arquivos visuais correspondentes aos produtos exibidos no site.

Funcionalidades:
Páginas
Início (index.html):

Apresenta um cabeçalho fixo com links de navegação.
Seção de produtos em destaque exibida em formato de grade.
Botão "Ver Detalhes" para cada produto, que redireciona para a página de detalhes com base no ID do produto.
Detalhes do Produto (produto.html):

Exibe informações detalhadas de um produto específico.
Obtém os dados do produto através de um script que interpreta o ID fornecido pela URL.
Estrutura da página:
Nome do produto.
Imagem do produto.
Descrição detalhada.
Preço.
Botão "Comprar Agora" (sem funcionalidade adicional implementada).
Contato (contato.html):

Inclui um formulário para o envio de mensagens.
Campos: Nome, E-mail, Mensagem.
Botão para submissão do formulário (sem back-end integrado).

Estilos:
Layout responsivo definido no style.css.
Paleta de cores:
Laranja (#ff6600) como cor primária.
Branco (#fff) e cinza claro (#f3f4f6) para contrastes.
Preto (#2d2d2d) para textos.
Design limpo com botões arredondados e sombreamento leve para elementos destacados.

JavaScript:
Utilizado para dinamizar a página de detalhes do produto (produto.html):
Um objeto produtos armazena as informações (nome, descrição, imagem e preço) de cada produto.
O ID do produto é extraído da URL para determinar qual item será exibido.
Uso
Configuração Inicial

Certifique-se de que todos os arquivos HTML, CSS e imagens de produtos estejam no mesmo diretório.
Abra o arquivo index.html em um navegador para visualizar a página principal.
Visualizar Detalhes do Produto

Clique em "Ver Detalhes" em qualquer produto na página inicial para ser redirecionado à página de detalhes.
Contato

Acesse a página de contato através do menu para preencher e enviar o formulário.
