# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>


A arquitetura da solução para o site Conforto do Pet apresenta o servidor Hostinger para que atenda à um dos requisitos do projeto de poder ser acessado pelos navegadores mais populares, as linguagens usadas para a programação do site são HTML, CSS e JavaScript. 
O usuário acessará o site por meio do endereço www.confortodopet.com.br, sendo que o usuário pode ser um prestador de serviço que queira cadastrar seu petshop ou um consumidor final em busca de serviços de cuidados para seu pet
Ao acessar o site o usúario terá acesso às seguintes páginas:

Main page: Página principal do site que contem um menu com as páginas secundárias contendo também campo de login caso o usuário seja cadastrado e um campo de cadastro para quem acessa pela primeira vez

Produtos:

Banho e Tosa:

Hotel: O proprietário do PetShop encontrará nessa páginao campo para cadastrar seu serviço de hospedagem para seu animal, e o dono do pet poderá localizar um PetShop queofereça esse seviço

Passeio: Nessa página um passeador pode se cadastrar oferecendo serviços de passeador ou o usuuário poderá agendar um passeio para seu animal tendo a opção de marcar semanalmente 

Consulta: O dono do pet poderá marcar consulta online ou presencial nessa página



## Diagrama de componentes

Diagrama que permite a modelagem física de um sistema, através da visão dos seus componentes e relacionamentos entre os mesmos.

Exemplo: 

Os componentes que fazem parte da solução são apresentados na Figura XX.

![DIAGRAMA](https://user-images.githubusercontent.com/81272141/118564932-a690ca80-b747-11eb-8215-f65bcbc35b6d.png)


A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
     - **Canais** - seções de notícias apresentadas 
     - **Comentários** - registro de opiniões dos usuários sobre as notícias
     - **Preferidas** - lista de notícias mantidas para leitura e acesso posterior
 - **News API** - plataforma que permite o acesso às notícias exibidas no site.
 - **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 

> **Links Úteis**:
>
> - [Whimsical](https://whimsical.com/)

Inclua um diagrama da solução e descreva os módulos e as tecnologias que fazem parte da solução. Discorra sobre o diagrama.

A imagem a seguir ilustra a o fluxo do usuário em nossa solução. Assim
que o usuário entra na plataforma, ele é apresentado à tela inicial
(Tela 1) onde ele é confrontado com as opões de editar seu perfil ou
então visualizar sua galeria.

Caso ele opte por seguir pelo primeiro caminho (Editar Perfil), ele é
redirecionado para a tela de edição de perfil (Tela 2), onde pode
atualizar seus dados cadastrais. Nessa tela, o usuário também pode
escolher para editar sua foto de perfil. Ao selecionar essa opção, ele é
redirecionado para a Tela 3, onde ele a imagem expandida do perfil do
usuário é mostrado. Ao selecionar a opção para atualizar a imagem, uma
nova janela abre pedindo para o usuário fazer o upload da nova foto.
Assim que o processo termina um pop-up exibe o status para o usuário
(Tela 4) e o usuário é redirecionado para a Tela 2.

Caso o usuário opte seguir pelo segundo caminho (Visualizar Galeria) ele
é redirecionado para a Tela 5 com todas as fotos que o usuário possui. O
usuário pode clicar em um post qualquer para visualizar os detalhes do
post (Tela 6). Nessa tela, ele pode então escolher editar o post, sendo
redirecionado para a Tela 7. Ao editar as informações, o usuário pode
escolher salvar ou deletar o post. Em ambos os casos o status é
notificado para o usuário (Tela 8) e em seguida ele é redirecionado
para a Tela 2.

![Exemplo de UserFlow](img/userflow.jpg)


## Tecnologias Utilizadas

Github
Bootstrap
Figma
Adobe Photoshop
Adobe Ilustrator
HTML
CSS
Python

## Hospedagem

O site terá o domínio registrado em https://registro.br, terá o endereço www.confortodopet.com.br e a hospedagem será realizada em https://www.hostinger.com.br/

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
