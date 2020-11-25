# Matriz Foward-Form

## Introdução

A rastreabilidade de requisitos pode ser vista como a habilidade de acompanhar e descrever a vida de um requisito, em ambas as direções.  
A técnica de Pós-Rastreabilidade Forward-Form visa ligar documentos obtidos no processo de elicitação no plano de negócio a requisitos relevantes, ou seja, ao usarmos o método de Forward-Form, vinculamos os requisitos a artefatos de desenho do sistema e sua implementação.  

## Metodologia

A metodologia escolhida para o desenvolvimento da matriz é a proposta de Toranzo para a rastreabilidade. As informações a serem rastreadas serão classificadas em quatro níveis: ambiental, organizacional, gerencial e desenvolvimento. Essa classificação é definida como:

- Ambiental: informações de contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido;
- Organizacional: informações pertencentes à organização (missão, objetivos e estratégias);
- Gerencial: informações que auxiliam a gerência do projeto; e,
- Desenvolvimento: informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste e outros).  

Além disso, avaliamos também o suporte à rastreabilidade identificando os seguintes tipos de elos:

- Satisfação: classe origem tem dependência de satisfação com a classe
destino.
- Recurso: classe origem tem dependência de recurso com a classe
destino.
- Responsabilidade: registra a participação, responsabilidade e ação de
pessoas sobre artefatos.
- Representação: captura a representação ou modelagem dos requisitos
em outras linguagens.
- Alocado: classe origem está relacionada à classe destino, que
representa um subsistema.
- Agregação: indica “composição” de elementos.

## Matriz

### Legendas

|Sigla|Descrição|
|:-|:-|
|RF|Requisito Funcional|
|RNF|Requisito Não Funcional|
|EF|Elo Funcional|
|ENF|Elo Não Funcional|

<br>

### Forward-Form

### Matriz de Requisitos Funcionais

|RF|Requisito|Cenários|Léxicos|Casos de Uso|Histórias de Usuários|Categoria|Elo
|:-:|:-:|:-|:-|:-|:-|:-|:-|
|01|O usuário deve ser capaz de escolher sua localização no mapa| - | - | - | US02 | 
|02|O usuário deve ser capaz de pedir ajuda para outros usuários| C1, C10, C11. | Ajudas abertas;<br>Ajudas finalizadas;<br>Ajudas em Andamento. | [Criar Pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=criar-pedido-de-ajuda)<br> []()  | US11 ||
|03|O usuário deve ser capaz de oferecer ajuda a outros usuários| C3, C4, C5, C7, C8, C9, C11, C12.|| [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US19 |
|04|O usuário deve ser capaz de finalizar uma ajuda quando quiser| C11. ||||
|05|O usuário deve ser capaz de escolher o usuário que vai lhe ajudar| C4, C5, C7, C8, C9.||| US14 |
|06|O usuário deve ser capaz de entrar em contato com o usuário que lhe ofereceu ajuda| C4, C5, C7, C9.||| US06, US15, US24 |
|07|O usuário deve ser capaz de finalizar um pedido de ajuda depois de ter sido ajudado| C4, C7.||| US16 |
|08|O usuário deve ser capaz de finalizar uma oferta de ajuda após ajudar um usuário| C4, C7.|| [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US20 |
|10|O usuário deve ser capaz de visualizar seus pedidos de ajuda| C1, C10, C11.||| US18 |
|11|O usuário deve ser capaz de visualizar suas ofertas de ajuda|C3, C4, C5, C7, C8, C9.|| [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US21 |
|12|O usuário deve ser capaz de visualizar os pedidos de ajuda de outros usuários no mapa|C3, C4, C5, C7, C8, C9.||| US12 |
|13|O usuário deve ser capaz de dar um título ao pedido de ajuda| C1.||
|14|O usuário deve ser capaz de adicionar uma breve descrição ao pedido de ajuda| C1, C4, C5, C7, C8, C9, C10.||| US06 |
|15|O usuário pode editar seu telefone|C2.|| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US08 |
|16|O usuário pode editar seu endereço|C2.|| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US09 |
|17|O usuário pode editar sua foto de perfil|C2.|| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US07 |
|18|O usuário deve ser capaz de logar e deslogar de sua conta quando quiser|C6, C13.||

### Matriz de Requisitos não Funcionais

|RNF|Requisito|Cenários|Léxicos|Casos de Uso|Histórias de Usuários|Categoria|Elo
|:-:|:-:|:-|:-|:-|:-|:-|:-|
|01|O usuário deve ser capaz de criar diversos pedidos de ajuda|C1.||
|02|O usuário deve ser capaz de ver as informações básicas de quem lhe ofereceu ajuda| C3, C4, C5, C7, C8, C9.||
|03|O usuário deve ser capaz de visualizar seu histórico de ajudas| -||Histórico||US17, US26|
|04|O usuário deve ser capaz de trocar sua senha quando solicitado| - |||US10|
|05|O usuário deve ser capaz de informar se faz parte do grupo de risco da COVID-19| C4|||US05|
|06|O usuário deve ser capaz de informar que é um profissional da saúde mental|C7|||US03|
|07|O usuário deve ser capaz de selecionar a categoria de sua ajuda para que a mesma possa ser filtrada por outros usuários|C5|||US27|
|08|O E-mail do usuário não pode se repetir| C2 ||
|09|O CPF do usuário não pode se repetir| C2 ||
|10|O usuário deve receber notificações quando tiver uma oferta de ajuda aceita|C11|||US22|
|11|O usuário deve ter um limite de pedidos de ajuda abertos simultaneamente| - ||
|12|O E-mail do usuário deve ser validado ao criar uma nova conta| C2||
|13|As ajudas do usuário devem ser apagadas depois de um tempo limite| - ||
|14|Um usuários só pode ajudar outros usuários que estiverem dentro do seu raio de distância| C2, C12||
|15|Se deve avisar ao usuário caso o sistema esteja offline e ter uma estimativa de volta.| - ||

## Detalhamento

## Login

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![Login](./images/login.jpg ':size=200') | Requisitos do Sistema: RF-17<br>Cenário(s): [C6 - Logar no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c6-logar-no-aplicativo), <br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Pedir ajuda

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![PrimeiroPedido](./images/pedirAjuda.jpg ':size=200') | **Requisitos do Sistema:**<br>RF-02, RF-12, RF-13<br>**Cenário(s):**<br>[C1 - Primeiro pedido de ajuda,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c1-primeiro-pedido-de-ajuda) <br> [C10 - Emergência com itens de proteção,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c10-emerg%c3%aancia-com-itens-de-prote%c3%a7%c3%a3o) <br> [C11 - Pedido de ajuda confirmado](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c11-pedido-de-ajuda-confirmado)<br>**Léxico(s):**<br> [Ajudas abertas,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-abertas)<br>[Ajudas em Andamento](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-em-andamento)<br>[Ajudas finalizadas,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-finalizadas)<br>**Caso(s) de Uso:**<br>[Criar Pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=criar-pedido-de-ajuda)<br>**História(s) de Usuário:**<br>**Softgoal(s) Relacionados:** 

## Marcar localização

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![AdicionarLocalização](./images/loc.jpg ':size=200') | Requisito do Sistema: RF-01, <br>Cenário(s): [C2 - Cadastro no aplicativo,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo) [C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco) [C12 - Procurar pedido de ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c12-procurar-pedido-de-ajuda)<br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Localização inicial

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![LocalizaçãoCadastro](./images/cadastroLoc.jpg ':size=200') | Requisito do Sistema: <br>Cenário(s): [C2 - Cadastro no aplicativo,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo) Login<br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Cadastro

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![Cadastro](./images/cadastro.jpg ':size=200') | Requisito do Sistema: RF-14, RF-15, RF-16, RNF-08, RNF-09, RNF-12, RNF-14<br>Cenários: [C2 - Cadastro no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo) <br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados: 

## Pedidos em andamento

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![PedidoemAndamento](./images/pedidosAndamento.jpg ':size=200') | Requisito do Sistema: <br>- Cenários: <br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Filtro de Itens de Proteção

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![GrupodeRisco](./images/itensProtecao.jpg ':size=200') | - Requisito do Sistema: <br>- Cenários: Login<br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Filtro de Pequenos Serviços

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![PequenosServiços](./images/pequenosServicos.jpg ':size=200') | - Requisito do Sistema: <br>- Cenários: Login<br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Filtro de Ajuda psicológica

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![AjudaPsicológica](./images/apoioPsicologico.jpg ':size=200') | - Requisito do Sistema: <br>- Cenários: Login<br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Filtro de Transporte de Emerência

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![TransportedeEmergência](./images/transporte.jpg ':size=200') | Requisito do Sistema: <br>Cenário(s): [C8 - Auxílio com transporte de emergência](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c8-aux%c3%adlio-com-transporte-de-emerg%c3%aancia)<br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Filtro de Apoio Social

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![ApoioSocial](./images/apoioSocial.jpg ':size=200') | **Requisito do Sistema:**<br>RF-03, RF-05, RF-06, RF-10, RF-11, RF-13<br>**Cenário(s):**<br>[C9 - Apoio Social](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c9-apoio-social)<br>Léxico(s):  <br>Caso(s) de Uso: <br>História(s) de Usuário: <br>Softgoal(s) Relacionados:

## Pedidos Finalizados

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![MeusPedidos](./images/meusPedidos.jpg ':size=200') | **Requisito do Sistema:**<br>RF-04, RF-07, RF-08 <br>**Cenário(s):** [C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br>[C7 - Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%c3%a7%c3%a3o-psicol%c3%b3gicao)<br> [C11 - Pedido de ajuda confirmado](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c11-pedido-de-ajuda-confirmado)<br>**Léxico(s):** <br>**Caso(s) de Uso:**<br>**História(s) de Usuário:** <br>**Softgoal(s) Relacionados:**

## Logout

| Funcionalidade | Rastreabilidade
|:-:|:-
| ![LogOut](./images/logout.jpg ':size=200') | **Requisito do Sistema:**<br> RF-17 <br>**Cenário(s):**<br>[C13 - Sair do aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c13-sair-do-aplicativo) <br>**Léxico(s):**<br>**Caso(s) de Uso:** <br>**História(s) de Usuário:** <br>**Softgoal(s) Relacionados:**

---

## Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|19/11/2020|0.1|Criação do documento|Pedro Vítor de Salles Cella|
|21/11/2020|0.2|Descrição dos tópicos de Introdução, Metodologia e Matriz|Ailamar Alves Guimarães|
|22/11/2020|0.3|Forward-Form versão 0.1|Ailamar Alves Guimarães|
|23/11/2020|0.4|Adição do detalhamento|Ailamar Alves Guimarães|

<br>

## Referências

- Requisitos - Aula 26. Milene Serrano e Maurício Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/426777/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf> . Acesso em: nov, 2020.

- LSAYÃO, Miriam; DO PRADO LEITE, Julio Cesar Sampaio. Rastreabilidade de requisitos. RITA, v. 13, n. 1, p. 57-86, 2006. Disponível em: <http://www-di.inf.puc-rio.br/~julio/rastreabilidade5.pdf>. Acesso em: nov, 2020.

- Matriz Forward-From. Grupo Audible - 2019.2. Disponível em: <https://requisitos-de-software.github.io/2019.2-Audible/matrizforwardfrom/>. Acesso em: nov, 2020.
