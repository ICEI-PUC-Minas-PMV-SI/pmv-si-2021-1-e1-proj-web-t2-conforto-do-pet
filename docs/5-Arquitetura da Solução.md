# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>


A arquitetura da solução para o site Conforto do Pet apresenta o servidor Hostinger para que atenda à um dos requisitos do projeto de poder ser acessado pelos navegadores mais populares, as linguagens usadas para a programação do site são HTML, CSS e JavaScript. 
O usuário acessará o site por meio do endereço www.confortodopet.com.br, sendo que o usuário pode ser um prestador de serviço que queira cadastrar seu petshop ou um consumidor final em busca de serviços de cuidados para seu pet
Ao acessar o site o usúario terá acesso às seguintes páginas:

Main page: Página principal do site que contem um menu com as páginas secundárias contendo também campo de login caso o usuário seja cadastrado e um campo de cadastro para quem acessa pela primeira vez

Produtos: Nessa página o usuário acessa os produtos ofertados pelos PetShops cadastrados

Banho e Tosa: O dono do pet poderá encontrar serviços de cuidados com o pet de banho e ou tosa

Hotel: O proprietário do PetShop encontrará nessa página o campo para cadastrar seu serviço de hospedagem para seu animal, e o dono do pet poderá localizar um PetShop queofereça esse seviço

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
     - **SAC/CHAT** - seções de serviços de atendimento ao cliente e chatbox 
     - **produtos** - registro de produtos listados nos anúncios
     - **Preferidas** - registro de serviços listados nos anúncios
 - **News API** - plataforma que permite o acesso às notícias exibidas no site.
 - **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 


## Tecnologias Utilizadas

**Github**
**Bootstrap**
**Figma**
**Adobe Photoshop**
**Adobe Ilustrator**
**HTML**
**CSS**
**Python**
**Visio** 

## Hospedagem

O site terá o domínio registrado em https://registro.br, terá o endereço www.confortodopet.com.br e a hospedagem será realizada em https://www.hostinger.com.br/

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
