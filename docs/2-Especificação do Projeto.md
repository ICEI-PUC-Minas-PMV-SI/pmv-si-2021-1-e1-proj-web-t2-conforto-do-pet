# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

<b>Nathalia Amorim</b>

Nathalia Amorim tem 24 anos, mora em Passa Tempo MG, é recem formada em direito pela universidade Feol. Nathalia é uma pessoa que gosta muito de animais, ela possui 2 cachorros, e acredita que um aplicativo que possa agilizar o serviço de marcação de consultas para seus pets poderia otimizar sua rotina. Ela foi perguntada sobre o que consideraria essencial para que o aplicativo a atendesse da melhor maneira. Em resposta, ela mencionou que o aplicativo precisa ser simples, ágil, seguro. Disse também que anúncios dentro de um aplicativo podem poluir a visualização além de ser algo incômodo para usuários finais. Por fim, foi levantado algumas das suas principais características listadas no quadro abaixo.

![alt text](https://user-images.githubusercontent.com/80352124/114281443-c7f9ea80-9a14-11eb-970e-b2d33d3cb4ef.jpg)| Nathalia Amorim | 24 Anos | Advogada
:--------- | :------: | -------: | -------: 
<b>Hobbies</b> | Ler | Dançar | Cantar 
<b>Motivações</b> | Fámilia | Deus | Amigos
<b>Aplicativos</b> | WhatsApp | Instagram | Facebook


<b>Lucas Jhony</b>

Lucas Jhony tem 20 anos, mora atualmente em Desterro de Entre Rios MG, Estudante na universade Puc Minas! Lucas também é uma pessoa que gosta muito de animais, possui muitos. Aproximadamente 12 cachorros. E acredita que seria excelente a ideia de um aplicativo pet, que ajudaria muito na facilidade de encontrar produtos e também na praticidade de comprar online. Acha também que pela praticidade de encontrar o aplicativo, usaria sem dúvidas. Segundo Lucas, acharia legal encontrar no Aplicativo Diversidade de produtos e de serviços para o seu pet. E também, consultas online, caso o pet não esteja muito bem. Lucas teria em principal objetivo no uso do app, comprar rações para seu pet. Que segundo ele, tem preguiça para deslocar até o local de venda do produto. Acha que para um aplicativo passar uma boa visão ao seus usuários deve ter uma interface bonita porém sem muito detalhes, e que seja fácil de usar. Acha que taxas abusivas em um aplicativo nunca deve existir, pois torna inviável para o público. Por fim, Foi levantado algumas das suas principais características no quadro abaixo.


![alt text](https://user-images.githubusercontent.com/80352124/114282433-663c7f00-9a1a-11eb-8ab3-77b6281b4097.jpg)| Lucas Jhony | 20 Anos | Estudante
:--------- | :------: | -------: | -------: 
<b>Hobbies</b> | Jogar | Sair | Estudar 
<b>Motivações</b> | Família | Amigos | Fé
<b>Aplicativos</b> | Instagram | Facebook | Twitter

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |
|RF-003| Cadastro de Pet   | MÉDIA |
|RF-004| Gravar as preferências do usuário   | MÉDIA |
|RF-005| Permitir que o úsuário encontre pet shops mais próximos à sua residência através da sua localização   | MÉDIA |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|RNF-003| O sistema deve ser restrito ao lançamento de produtos e serviços pet | ALTA | 
|RNF-004| Não é autorizado o uso de Pop-up's,banner's ou qualquer tipo de propaganda monetizável |  MÉDIA | 
|RNF-005| O sistema deve ser simples e minimalista | MÉDIA | 
|RNF-006| O site deve ser compatível com os navegadores mais populares do mercado | ALTA | 
|RNF-007| O site deve ter um sistema de classificação de satisfação por nota baseado na quantidade de estrelas(0 a 5 estrelas) | ALTA | 


Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend       
|03| As especificações do projeto deverão ser entregues até o dia 19/04/21
|04| Não é necessário que o usuário instale nenhum programa para utilização do produto


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.


> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
