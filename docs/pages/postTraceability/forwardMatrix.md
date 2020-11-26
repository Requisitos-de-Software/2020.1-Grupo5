# Matriz Forward-Form

## Introdução

A rastreabilidade de requisitos pode ser vista como a habilidade de acompanhar e descrever a vida de um requisito, em ambas as direções.  
A técnica de Pós-Rastreabilidade Forward-Form visa ligar documentos obtidos no processo de elicitação no plano de negócio a requisitos relevantes, ou seja, ao usarmos o método de Forward-Form, vinculamos os requisitos a artefatos de desenho do sistema e sua implementação.  

## Metodologia

A metodologia escolhida para o desenvolvimento da matriz é a proposta de Toranzo para a rastreabilidade. As informações a serem rastreadas serão classificadas em quatro níveis: ambiental, organizacional, gerencial e desenvolvimento. Essa classificação é definida como:

- Ambiental: informações de contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido;
- Organizacional: informações pertencentes à organização (missão, objetivos e estratégias);
- Gerencial: informações que auxiliam a gerência do projeto;
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

<br>

### Forward-Form

### Matriz de Requisitos Funcionais

|RF|Requisito|Cenários|Léxicos|Casos de Uso|Histórias de Usuários|Tela|Categoria|Elo
|:-:|:-:|:-|:-|:-|:-|:-|:-|:-
|01|O usuário deve ser capaz de escolher sua localização no mapa| [C2 - Cadastro no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo) | [Mapa](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=mapa) | - | US02 | [Fig. 2](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=cadastro) | Desenvolvimento | Agregação<br> Responsabilidade
|02|O usuário deve ser capaz de pedir ajuda para outros usuários| [C1 - Primeiro pedido de ajuda,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c1-primeiro-pedido-de-ajuda) <br> [C10 - Emergência com itens de proteção,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c10-emerg%c3%aancia-com-itens-de-prote%c3%a7%c3%a3o) <br> [C11 - Pedido de ajuda confirmado](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c11-pedido-de-ajuda-confirmado) | [Ajudas abertas,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-abertas)<br>[Ajudas finalizadas,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-finalizadas)<br>[Ajudas em andamento](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-em-andamento) | [Criar Pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=criar-pedido-de-ajuda)<br>| US11 | [Fig. 5](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedir-ajuda) | Desenvolvimento | Agregação<br> Responsabilidade
|03|O usuário deve ser capaz de oferecer ajuda a outros usuários| [C3 - Primeira ajuda realizada](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c3-primeira-ajuda-realizada) <br> [C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco) <br> [C5 - Mão de obra amiga,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c5-m%C3%A3o-de-obra-amiga) <br> [C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica) <br> [C8 - Auxílio com transporte de emergência](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c8-aux%c3%adlio-com-transporte-de-emerg%c3%aancia) <br> [C9 - Apoio Social](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c9-apoio-social) <br> [C11 - Pedido de ajuda confirmado](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c11-pedido-de-ajuda-confirmado) <br> [C12 - Procurar pedido de ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c12-procurar-pedido-de-ajuda) | [Ajudante,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudante)<br>[Possíveis ajudantes,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=possíveis-ajudantes)<br>[Oferta](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=oferta)| [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US19 | [Fig. 4](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=p%c3%a1gina-inicial) | Desenvolvimento | Satisfação<br> Responsabilidade
|04|O usuário deve ser capaz de finalizar uma ajuda quando quiser| [C11 - Pedido de ajuda confirmado](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c11-pedido-de-ajuda-confirmado) | [Finalizar ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=finalizar-ajuda) | - | - | - | Ambiental | Responsabilidade<br> Satisfação
|05|O usuário deve ser capaz de escolher o usuário que vai lhe ajudar| [C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br> [C5 - Mão de obra amiga,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c5-m%C3%A3o-de-obra-amiga)<br>[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)<br> [C8 - Auxílio com transporte de emergência](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c8-aux%c3%adlio-com-transporte-de-emerg%c3%aancia)<br> [C9 - Apoio Social](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c9-apoio-social)| [Possíveis ajudantes](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=possíveis-ajudantes) | - | US14 | - | Ambiental | Responsabilidade<br> Recurso
|06|O usuário deve ser capaz de entrar em contato com o usuário que lhe ofereceu ajuda| [C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br> [C5 - Mão de obra amiga,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c5-m%C3%A3o-de-obra-amiga)<br>[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)<br> [C9 - Apoio Social](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c9-apoio-social)| [Abrir serviços externos](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=abrir-serviços-externos) | - | US06, US15, US24 | - | Ambiental | Responsabilidade<br> Satisfação
|07|O usuário deve ser capaz de finalizar um pedido de ajuda depois de ter sido ajudado| [C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br>[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)| [Finalizar ajuda,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=finalizar-ajuda)<br> [Ajudas finalizadas](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-finalizadas)| - | US16 | - | Desenvolvimento | Satisfação<br> Agregação
|08|O usuário deve ser capaz de finalizar uma oferta de ajuda após ajudar um usuário|[C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br>[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)| [Finalizar ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=finalizar-ajuda) | [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US20 | - | Desenvolvimento | Satisfação<br> Agregação
|10|O usuário deve ser capaz de visualizar seus pedidos de ajuda| [C1 - Primeiro pedido de ajuda,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c1-primeiro-pedido-de-ajuda) <br> [C10 - Emergência com itens de proteção,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c10-emerg%c3%aancia-com-itens-de-prote%c3%a7%c3%a3o)<br>[C11 - Pedido de ajuda confirmado](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c11-pedido-de-ajuda-confirmado)| [Ajudas abertas,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-abertas)<br> [Pedido de ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=pedido-de-ajuda)| - | US18 | [Fig. 6](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedidos-em-andamento) | Desenvolvimento | Satisfação<br> Recurso
|11|O usuário deve ser capaz de visualizar suas ofertas de ajuda|[C3 - Primeira ajuda realizada](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c3-primeira-ajuda-realizada)<br>[C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br> [C5 - Mão de obra amiga,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c5-m%C3%A3o-de-obra-amiga)<br>[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)<br> [C8 - Auxílio com transporte de emergência](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c8-aux%c3%adlio-com-transporte-de-emerg%c3%aancia)<br> [C9 - Apoio Social](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c9-apoio-social)| [Oferta](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=oferta)| [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US21 | [Fig. 12](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedidos-finalizados) | Desenvolvimento | Recurso<br> Agregação<br> Responsabilidade
|12|O usuário deve ser capaz de visualizar os pedidos de ajuda de outros usuários no mapa|[C3 - Primeira ajuda realizada](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c3-primeira-ajuda-realizada)<br>[C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br> [C5 - Mão de obra amiga,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c5-m%C3%A3o-de-obra-amiga)<br>[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)<br> [C8 - Auxílio com transporte de emergência](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c8-aux%c3%adlio-com-transporte-de-emerg%c3%aancia)<br> [C9 - Apoio Social](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c9-apoio-social)|  [Ajudas abertas,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-abertas)<br> [Mapa](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=mapa)| - | US12 | [Fig. 4](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=p%c3%a1gina-inicial) | Desenvolvimento | Recurso<br> Agregação
|13|O usuário deve ser capaz de dar um título ao pedido de ajuda| [C1 - Primeiro pedido de ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c1-primeiro-pedido-de-ajuda)| - | - | - | [Fig. 5](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedir-ajuda) | Desenvolvimento | Alocado<br> Recurso
|14|O usuário deve ser capaz de adicionar uma breve descrição ao pedido de ajuda| [C1 - Primeiro pedido de ajuda,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c1-primeiro-pedido-de-ajuda)<br>[C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br> [C5 - Mão de obra amiga,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c5-m%C3%A3o-de-obra-amiga)<br>[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)<br> [C8 - Auxílio com transporte de emergência](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c8-aux%c3%adlio-com-transporte-de-emerg%c3%aancia)<br> [C9 - Apoio Social](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c9-apoio-social) <br> [C10 - Emergência com itens de proteção,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c10-emerg%c3%aancia-com-itens-de-prote%c3%a7%c3%a3o)| [Categorias](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=categorias)| - | US06 | [Fig. 5](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedir-ajuda) | Desenvolvimento | Alocado<br> Recurso
|15|O usuário pode editar seu telefone|[C2 - Cadastro no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo)| [Editar perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=editar-perfil)| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US08 | [Fig. 13](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=perfil) | Ambiental | Recurso<br> Satisfação
|16|O usuário pode editar seu endereço|[C2 - Cadastro no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo)| [Editar perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=editar-perfil)| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US09 | [Fig. 13](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=perfil) | Ambiental | Recurso<br> Satisfação
|17|O usuário pode editar sua foto de perfil|[C2 - Cadastro no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo)| [Editar perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=editar-perfil)| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US07 | - | Ambiental | Recurso<br> Satisfação
|18|O usuário deve ser capaz de logar e deslogar de sua conta quando quiser|[C6 - Logar no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c6-logar-no-aplicativo)<br>[C13 - Sair do aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c13-sair-do-aplicativo)| [Login,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=login)<br>[Sair](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=sair)| - | - | [Fig. 1,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=login) [Fig. 13](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=perfil) | Ambiental | Recurso<br> Satisfação<br> Responsabilidade

<br>

### Matriz de Requisitos não Funcionais

|RNF|Requisito|Cenários|Léxicos|Histórias de Usuários|Tela|Categoria|Elo
|:-:|:-:|:-|:-|:-|:-|:-|:-|
|01|O usuário deve ser capaz de criar diversos pedidos de ajuda|[C1 - Primeiro pedido de ajuda,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c1-primeiro-pedido-de-ajuda)| [Ajudas abertas,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-abertas)<br> [Ajudas em andamento](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-em-andamento)| - | [Fig. 5](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedir-ajuda) | Ambiental | Satisfação<br> Recurso<br> Alocado
|02|O usuário deve ser capaz de ver as informações básicas de quem lhe ofereceu ajuda| [C3 - Primeira ajuda realizada](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c3-primeira-ajuda-realizada)<br>[C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco)<br>[C5 - Mão de obra amiga,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c5-m%C3%A3o-de-obra-amiga)<br>[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)<br>[C8 - Auxílio com transporte de emergência](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c8-aux%c3%adlio-com-transporte-de-emerg%c3%aancia)<br>[C9 - Apoio Social](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c9-apoio-social)| [Possíveis ajudantes](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=possíveis-ajudantes)| - | - | Ambiental | Satisfação
|03|O usuário deve ser capaz de visualizar seu histórico de ajudas| - |[Histórico,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=histórico)<br> [Ajudas finalizadas](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-finalizadas)|US17, US26| [Fig. 6,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedidos-em-andamento) [Fig. 12](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedidos-finalizados) | Desenvolvimento | Satisfação<br> Recurso
|04|O usuário deve ser capaz de trocar sua senha quando solicitado| - | - |US10| - | Ambiental | Satisfação<br> Agregado
|05|O usuário deve ser capaz de informar se faz parte do grupo de risco da COVID-19| [C4 - Ajudando pessoas do grupo de risco,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c4-ajudando-pessoas-do-grupo-de-risco) | - |US05| - | Ambiental | Satisfação<br> Alocado
|06|O usuário deve ser capaz de informar que é um profissional da saúde mental|[C7- Colaboração Psicológica](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c7-colabora%C3%A7%C3%A3o-psicol%C3%B3gica)| - |US03| - | Ambiental | Satisfação<br> Alocado
|07|O usuário deve ser capaz de selecionar a categoria de sua ajuda para que a mesma possa ser filtrada por outros usuários|[C5 - Mão de obra amiga,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c5-m%C3%A3o-de-obra-amiga)| [Filtrar pedidos de ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=filtrar-pedidos-de-ajuda)<br> [Mapa,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=mapa)<br> [Categorias](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=categorias)| US27| [Fig. 7](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=ajuda-com-itens-de-prote%c3%a7%c3%a3o) | Ambiental | Recuso<br> Agregação
|08|O E-mail do usuário não pode se repetir| [C2 - Cadastro no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo) | [E-mail](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=e-mail) | - | - |Organizacional, Desenvolvimento | Alocado
|09|O CPF do usuário não pode se repetir| [C2 - Cadastro no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo) | - | - | - | Organizacional, Desenvolvimento | Alocado
|10|O usuário deve receber notificações quando tiver uma oferta de ajuda aceita|[C11 - Pedido de ajuda confirmado](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c11-pedido-de-ajuda-confirmado)| [Ajudas em andamento](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-em-andamento)|US22| [Fig. 6](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedidos-em-andamento) | Ambiental |
|11|O usuário deve ter um limite de pedidos de ajuda abertos simultaneamente| - | - | - | - | Organizacional | Satisfação
|12|O E-mail do usuário deve ser validado ao criar uma nova conta| [C2 - Cadastro no aplicativo](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo)| [E-mail](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=e-mail) | - |  [Fig. 3](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=cadastro) | Organizacional | Alocado<br> Recurso
|13|As ajudas do usuário devem ser apagadas depois de um tempo limite| - | [Ajudas abertas](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=ajudas-abertas)| - | [Fig. 6](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=pedidos-em-andamento) | Organizacional, Desenvolvimento | Alocado<br> Recurso
|14|Um usuários só pode ajudar outros usuários que estiverem dentro do seu raio de distância| [C2 - Cadastro no aplicativo,](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c2-cadastro-no-aplicativo)<br>[C12 - Procurar pedido de ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/scenario?id=c12-procurar-pedido-de-ajuda)  | [Pedido de ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/lexicon?id=pedido-de-ajuda)| - | [Fig. 4](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/postTraceability/forwardMatrix?id=p%c3%a1gina-inicial) | Ambiental, Desenvolvimento | Agregação
|15|Se deve avisar ao usuário caso o sistema esteja offline e ter uma estimativa de volta.| - | - | - | - | Organizacional, Ambiental | Satisfação<br> Recurso

## Detalhamento

## Login

***Figura 1 - Login***  
![Login](./images/login.jpg ':size=200')

<br>

## Cadastro

|***Figura 2 - Cadastrar localização inicial***|***Figura 3 - Cadastrar informações do usuário***|
|:-:|:-:
![LocalizaçãoCadastro](./images/cadastroLoc.jpg ':size=200') |![Cadastro](./images/cadastro.jpg ':size=200')|

<br>

## Página Inicial

***Figura 4 - Visualizando pedidos próximos***  
![AdicionarLocalização](./images/loc.jpg ':size=200')

<br>

## Pedir ajuda

***Figura 5 - Criando um pedido de ajuda***  
![PrimeiroPedido](./images/pedirAjuda.jpg ':size=200')

<br>

## Pedidos em andamento

***Figura 6 - Pedidos em andamento***  
![PedidoemAndamento](./images/pedidosAndamento.jpg ':size=200') 

<br>

## Ajuda com Itens de Proteção

***Figura 7 - Filtro de itens de proteção***  
![GrupodeRisco](./images/itensProtecao.jpg ':size=200')

<br>

## Ajuda com Pequenos Serviços

***Figura 8 - Filtro de Pequenos Serviços***  
![PequenosServiços](./images/pequenosServicos.jpg ':size=200')

<br>

## Ajuda Psicológica

***Figura 9 - Filtro de Ajuda Psicológica***  
![AjudaPsicológica](./images/apoioPsicologico.jpg ':size=200')

<br>

## Ajuda com Transporte de Emergência

***Figura 10 - Filtro de Transporte de Emergência***  
![TransportedeEmergência](./images/transporte.jpg ':size=200')

<br>

## Ajuda com Apoio Social

***Figura 11 - Filtro de Apoio Social***  
![ApoioSocial](./images/apoioSocial.jpg ':size=200') 

<br>

## Pedidos Finalizados

***Figura 12 - Página com pedidos finalizados***  
![MeusPedidos](./images/meusPedidos.jpg ':size=200')

<br>

## Perfil

***Figura 13 - Editar perfil ou sair do aplicativo***  
![LogOut](./images/logout.jpg ':size=200')

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
