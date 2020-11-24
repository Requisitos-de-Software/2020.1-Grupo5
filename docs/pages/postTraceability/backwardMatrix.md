# Matriz Backward-Form

## Introdução
A Matriz Backward-Form tem como função ser uma ferramenta de rastreabilidade, ao usarmos o método de Backward-Form, fazemos a ligação dos requisitos levantados com seus respectivos métodos de elicitação e modelagem o qual forma utilizados durante a elicitação de requiitos na disciplina.

## Legenda

|Sigla|Descrição|
|:-:|:-:|
|RF|Requisito Funcional|
|RNF|Requisito Não Funcional|
|EF|Elo Funcional|
|ENF|Elo Não Funcional|

<br>

## Categorias do Meta-Modelo de Toranzo

|Categoria|Descrição|
|:-:|:-:|
|Ambiental|informações oriundas do contexto no qual a organização está inserida|
|Desenvolvimento|informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste e outros)|
|Gerencial|informações que auxiliam a gerência do projeto|
|Organizacional|informações pertencentes à organização (missão, objetivos e estratégias)|

<br>

## Associações usadas para elaborar um modelo de rastreamento

|Associação|Descrição|
|:-:|:-:|
|Agragação|Uma  associação  que  modela  um  relacionamento  todo-parte  entre  uma  classe, denominado todo,  e  uma  ou  mais  classes  que  são  denominadas  partes.|
|Aloca|Uma    associação    uni-direcional    de    uma    classe,    que    representa requisitos   funcionais,   para   uma   outra   classe   que   representa   um subsistema.|
|Generalização|Um  relacionamento  entre  um  elemento  geral  e  um   elemento   mais específico.  O  elemento  mais  específico  é  complemente  consistente com o elemento geral e contem informações adicionais.|
|Recurso|Uma associação que especifica que uma classe possui uma dependência de informação ou física com outra classe|
|Representação|Uma  associação  que  é  usada  para  mapear  um  elemento  em  um  outro elemento.|
|Responsabilidade|Uma  associação  que  visa    capturar  a  participação,  responsabilidade  e ação      das   pessoas   sobre   artefatos   ou   elementos   do   processo   de software.|
|Satisfação|A  associação  satisfação  é  uma  relação  de  dependência  que   especifica   que   a   classe   origem      tem   uma   dependência   de realização  com  a  classe  destino.  O  termo  realização    é  usado  para expressar  que  algo  deverá  ser  realizado  ou  feito  sobre  as  instâncias  da  classe  destino  para  satisfazer  as  instâncias  da  classe  origem  com  as quais estão conectadas.|



## Matriz de Requisitos Funcionais

|ID|Requisito|Origem|Elo|
|:-:|:-:|:-:|:-:|
|RF-01|O usuário deve ser capaz de escolher sua localização no mapa|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_4-quais-funcionalidades-seriam-essenciais-para-um-aplicativo-de-a%c3%a7%c3%a3o-social), [Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF01|
|RF-02|O usuário deve ser capaz de pedir ajuda para outros usuários|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_4-quais-funcionalidades-seriam-essenciais-para-um-aplicativo-de-a%c3%a7%c3%a3o-social), [Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF02|
|RF-03|O usuário deve ser capaz de oferecer ajuda a outros usuários|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_2-como-combinar-volunt%c3%a1rios-que-querem-ajudar-de-alguma-forma-com-as-pessoas-necessitadas), [Questionario](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/survey/survey?id=caso-a-pessoa-ache-interessante)|EF03|
|RF-04|O usuário deve ser capaz de finalizar uma ajuda quando quiser|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF04|
|RF-05|O usuário deve ser capaz de escolher o usuário que vai lhe ajudar|[Storytelling](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/storytelling/storytelling?id=hist%c3%b3ria-de-jos%c3%a9), [Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF05|
|RF-06|O usuário deve ser capaz de entrar em contato com o usuário que lhe ofereceu ajuda|[Storytelling](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/storytelling/storytelling?id=hist%c3%b3ria-de-jos%c3%a9), [Questionario](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_1-como-proporcionar-ajuda-a-pessoas-que-est%c3%a3o-passando-por-dificuldades-ou-limita%c3%a7%c3%b5es-de-forma-acess%c3%advel-e-solid%c3%a1ria)|EF06|
|RF-07|O usuário deve ser capaz de finalizar um pedido de ajuda depois de ter sido ajudado|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF07|
|RF-08|O usuário deve ser capaz de finalizar uma oferta de ajuda após ajudar um usuário|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_4-quais-funcionalidades-seriam-essenciais-para-um-aplicativo-de-a%c3%a7%c3%a3o-social)|EF08|
|RF-09|O usuário deve ser capaz de visualizar seus pedidos de ajuda|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF09|
|RF-10|O usuário deve ser capaz de visualizar suas ofertas de ajuda|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF10|
|RF-11|O usuário deve ser capaz de visualizar os pedidos de ajuda de outros usuários no mapa|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF11|
|RF-12|O usuário deve ser capaz de dar um título ao pedido de ajuda|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_4-quais-funcionalidades-seriam-essenciais-para-um-aplicativo-de-a%c3%a7%c3%a3o-social), [Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF12|
|RF-13|O usuário deve ser capaz de adicionar uma breve descrição ao pedido de ajuda|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_4-quais-funcionalidades-seriam-essenciais-para-um-aplicativo-de-a%c3%a7%c3%a3o-social)|EF13|
|RF-14|O usuário pode editar seu telefone|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF15|
|RF-15|O usuário pode editar seu endereço|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF16|
|RF-16|O usuário pode editar sua foto de perfil|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF17|
|RF-17|O usuário deve ser capaz de logar e deslogar de sua conta quando quiser|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|EF18|

## Matriz de Requisitos Não Funcionais

|ID|Requisito|Origem|Elo|
|:-:|:-:|:-:|:-:|
|RNF-01|O usuário deve ser capaz de criar diversos pedidos de ajuda|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF01|
|RNF-02|O usuário deve ser capaz de ver as informações básicas de quem lhe ofereceu ajuda|[Questionario](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/survey/survey?id=caso-a-pessoa-utilize-o-aplicativo)|ENF02|
|RNF-03|O usuário deve ser capaz de visualizar seu histórico de ajudas|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF03|
|RNF-04|O usuário deve ser capaz de trocar sua senha quando solicitado|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF04|
|RNF-05|O usuário deve ser capaz de informar se faz parte do grupo de risco da COVID-19|[Storytelling](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/storytelling/storytelling?id=hist%c3%b3ria-de-maria)|ENF05|
|RNF-06|O usuário deve ser capaz de informar que é um profissional da saúde mental|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF06|
|RNF-07|O usuário deve ser capaz de selecionar a categoria de sua ajuda para que a mesma possa ser filtrada por outros usuários|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_3-de-que-forma-as-pessoas-podem-ajudar), [Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF07|
|RNF-08|O E-mail do usuário não pode se repetir|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF08|
|RNF-09|O CPF do usuário não pode se repetir|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF09|
|RNF-10|O usuário deve receber notificações quando tiver uma oferta de ajuda aceita|[Questionario](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/survey/survey?id=caso-a-pessoa-n%c3%a3o-utilize-o-aplicativo), [Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_4-quais-funcionalidades-seriam-essenciais-para-um-aplicativo-de-a%c3%a7%c3%a3o-social)|ENF10|
|RNF-11|O usuário deve ter um limite de pedidos de ajuda abertos simultaneamente|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF11|
|RNF-12|O E-mail do usuário deve ser validado ao criar uma nova conta|[Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection?id=requisitos)|ENF12|
|RNF-13|As ajudas do usuário devem ser apagadas depois de um tempo limite|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_4-quais-funcionalidades-seriam-essenciais-para-um-aplicativo-de-a%c3%a7%c3%a3o-social)|ENF13|
|RNF-14|Um usuários só pode ajudar outros usuários que estiverem dentro do seu raio de distância|[Brainstorm](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/brainstorming?id=_4-quais-funcionalidades-seriam-essenciais-para-um-aplicativo-de-a%c3%a7%c3%a3o-social)|ENF14|
|RNF-15|Se deve avisar ao usuário caso o sistema esteja offline e ter uma estimativa de volta.|[Especificação Suplementar](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/specification?id=confiabilidade)|ENF15|

<br> 

## Elos Funcionais

### **EF01**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF02**
**Categoria Meta-Modelo:** Ambiental,Organizacional
<br>
**Elo:** 

### **EF03**
**Categoria Meta-Modelo:** Ambiental,Organizacional
<br>
**Elo:** 

### **EF04**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF05**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF06**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF07**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF08**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF09**
**Categoria Meta-Modelo:** Ambiental,Organizacional
<br>
**Elo:** 

### **EF10**
**Categoria Meta-Modelo:** Ambiental,Organizacional
<br>
**Elo:** 

### **EF11**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF12**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF13**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF14**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF15**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF16**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF17**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **EF18**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 
<br>

## Elos Não Funcionais

### **ENF01**
**Categoria Meta-Modelo:** Desenvolvimento,Organizacional
<br>
**Elo:** 

### **ENF02**
**Categoria Meta-Modelo:** Desenvolvimento,Organizacional
<br>
**Elo:** 

### **ENF03** 
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF04**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF05**
**Categoria Meta-Modelo:** Desenvolvimento,Organizacional
<br>
**Elo:** 

### **ENF06**
**Categoria Meta-Modelo:** Desenvolvimento,Organizacional
<br>
**Elo:** 

### **ENF07**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF08**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF09**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF10**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF11** 
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF12**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF13**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF14**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br>
**Elo:** 

### **ENF15**
**Categoria Meta-Modelo:** Ambiental,Desenvolvimento
<br> 
**Elo:** 
<br>

## Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|19/11/2020|0.1|Criação do documento|Pedro Vítor de Salles Cella|
|23/11/2020|0.2|Adicionando origens da matriz de requisitos funcionais|Paulo Gonçalves Lima|
|23/11/2020|0.3|Adicionando origens da matriz de requisitos não funcionais|Paulo Gonçalves Lima|
|24/11/2020|0.3|Adicionando categorias e elos|Pedro Vítor de Salles Cella e Paulo Gonçalves Lima|

## Referências
[DBD PUC Rio Pagina 12](http://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf)<br>
[Matriz de rastreabilidade dos requisitos PMO](https://escritoriodeprojetos.com.br/matriz-de-rastreabilidade-dos-requisitos)<br>
[Matriz Backward-Form Audible](https://requisitos-de-software.github.io/2019.2-Audible/matrizBackward-from/)<br>
[TORANZO CESPEDES, Marco Antonio; Uma Proposta para Melhorar o Rastreamento de Requisitos de Software](https://repositorio.ufpe.br/bitstream/123456789/1947/1/arquivo5128_1.pdf)