# NFR Framework

## Introdução

O NFR (Non-Functional Requirements) Framework trata-se de um framework conceitual para condução da Engenharia de Requisitos  com uma extensão que apoia suposições para avaliação de
satisfação das metas-flexíveis.  
Esse modelo foi criado por CHUNG (1995), e adota uma abordagem específica para o tratamento de Requisitos Não-Funcionais e fornece uma rica representação para expressar esses requisitos.

## Metodologia 

Como explicado acima, neste documento estamos focados nos Requisitos Não-Funcionais.
Para isso criamos uma abstração buscando atingir funcionalidades específicas, fazendo análise das possíveis situações, considerando as aplicações e tecnologias já pré-existentes no aplicativo Mia Ajuda.

## NFR's

Esses são os Requisitos não Funcionais levantados a partir da [Introspecção](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/elicitations/introspection) que foram usados para criação do Framework:

|Número|Requisito|
|:-:|:-:|
|1|O usuário deve ser capaz de criar diversos pedidos de ajuda|
|2|O usuário deve ser capaz de ver as informações básicas de quem lhe ofereceu ajuda|
|3|O usuário deve ser capaz de visualizar seu histórico de ajudas|
|4|O usuário deve ser capaz de trocar sua senha quando solicitado|
|5|O usuário deve ser capaz de informar se faz parte do grupo de risco da COVID-19|
|6|O usuário deve ser capaz de informar que é um profissional da saúde mental|
|7|O usuário deve ser capaz de selecionar a categoria de sua ajuda para que a mesma possa ser filtrada por outros usuários|
|8|O E-mail do usuário não pode se repetir|
|9|O CPF do usuário não pode se repetir|
|10|O usuário deve receber notificações quando tiver uma oferta de ajuda aceita|
|11|O usuário deve ter um limite de pedidos de ajuda abertos simultaneamente|
|12|O E-mail do usuário deve ser validado ao criar uma nova conta|
|13|As ajudas do usuário devem ser apagadas depois de um tempo limite|
|14|Um usuário só pode ajudar outros usuários que estiverem dentro do seu raio de distância|
|15|Se deve avisar ao usuário caso o sistema esteja *offline* e ter uma estimativa de volta.||

## Modelagens NFR's

### Legendas

<p align="center">
  <img src="./images/legenda4.PNG" alt="Figuras 1 e 2" width="40%"/>
  <br/><br/>
  <img src="./images/legenda3.PNG" alt="Figura 3" width="50%"/>

</p>

### NFR01 Geral

### NFR01 Propagação

### NFR02 Desempenho

### NFR02 Propagação

### NFR03 Usabilidade

### NFR03 Propagação

### NFR04 Confiabilidade

### NFR04 Propagação

### NFR05 Suportabilidade

### NFR05 Propagação

---

Versionamento 

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|16/10/2020|0.1|Criação do escopo do documento|Ailamar Alves
|21/10/2020|0.2|Adição da lista de NFR e legendas|Ailamar Alves

<br/>
Referências

- Requisitos - Modelagem. SERRANO, Milene; SERRANO, Maurício. Disponível em: <https://aprender3.unb.br/pluginfile.php/426768/mod_resource/content/1/Requisitos%20-%20Aula%20019a.pdf>. Acesso em: out 2020.
- Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. DA SILVA, Reinaldo Antônio. Diponível em: <https://aprender3.unb.br/pluginfile.php/573096/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf>. Acesso em: out 2020.
