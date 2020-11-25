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
|01|O usuário deve ser capaz de escolher sua localização no mapa| - | Mapa | - | US02 | 
|02|O usuário deve ser capaz de pedir ajuda para outros usuários| C1, C10, C11. | Ajudas abertas;<br>Ajudas finalizadas;<br>Ajudas em Andamento. | [Criar Pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=criar-pedido-de-ajuda)<br>| US11 ||
|03|O usuário deve ser capaz de oferecer ajuda a outros usuários| C3, C4, C5, C7, C8, C9, C11, C12.| Ajudante;<br>Possíveis ajudantes;<br>Oferta. | [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US19 |
|04|O usuário deve ser capaz de finalizar uma ajuda quando quiser| C11. | Finalizar ajuda. | - ||
|05|O usuário deve ser capaz de escolher o usuário que vai lhe ajudar| C4, C5, C7, C8, C9.| Possíveis ajudantes. | - | US14 |
|06|O usuário deve ser capaz de entrar em contato com o usuário que lhe ofereceu ajuda| C4, C5, C7, C9.| Abrir serviços externos. | - | US06, US15, US24 |
|07|O usuário deve ser capaz de finalizar um pedido de ajuda depois de ter sido ajudado| C4, C7.| Finalizar ajuda;<br> Ajudas finalizadas.| - | US16 |
|08|O usuário deve ser capaz de finalizar uma oferta de ajuda após ajudar um usuário| C4, C7.| Finalizar ajuda. | [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US20 |
|10|O usuário deve ser capaz de visualizar seus pedidos de ajuda| C1, C10, C11.| Ajudas abertas;<br> Pedido de ajuda.| - | US18 |
|11|O usuário deve ser capaz de visualizar suas ofertas de ajuda|C3, C4, C5, C7, C8, C9.| *Oferta.| [Aceitar pedido de Ajuda](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=aceitar-pedido-de-ajuda) | US21 |
|12|O usuário deve ser capaz de visualizar os pedidos de ajuda de outros usuários no mapa|C3, C4, C5, C7, C8, C9.| Ajudas abertas;<br> Mapa.| - | US12 |
|13|O usuário deve ser capaz de dar um título ao pedido de ajuda| C1.| - | - |
|14|O usuário deve ser capaz de adicionar uma breve descrição ao pedido de ajuda| C1, C4, C5, C7, C8, C9, C10.| *Categorias.| - | US06 |
|15|O usuário pode editar seu telefone|C2.| Editar perfil.| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US08 |
|16|O usuário pode editar seu endereço|C2.| Editar perfil.| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US09 |
|17|O usuário pode editar sua foto de perfil|C2.| Editar perfil.| [Editar Perfil](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/useCase/useCase?id=editar-perfil) | US07 |
|18|O usuário deve ser capaz de logar e deslogar de sua conta quando quiser|C6, C13.| Login;<br> Sair.| - |

<br>

### Matriz de Requisitos não Funcionais

|RNF|Requisito|Cenários|Léxicos|Casos de Uso|Histórias de Usuários|Categoria|Elo
|:-:|:-:|:-|:-|:-|:-|:-|:-|
|01|O usuário deve ser capaz de criar diversos pedidos de ajuda|C1.|| - |
|02|O usuário deve ser capaz de ver as informações básicas de quem lhe ofereceu ajuda| C3, C4, C5, C7, C8, C9.|| - |
|03|O usuário deve ser capaz de visualizar seu histórico de ajudas| - |Histórico| - |US17, US26|
|04|O usuário deve ser capaz de trocar sua senha quando solicitado| - || - |US10|
|05|O usuário deve ser capaz de informar se faz parte do grupo de risco da COVID-19| C4 || - |US05|
|06|O usuário deve ser capaz de informar que é um profissional da saúde mental|C7|| - |US03|
|07|O usuário deve ser capaz de selecionar a categoria de sua ajuda para que a mesma possa ser filtrada por outros usuários|C5| Filtrar pedidos de ajuda;<br> *Mapa;<br> Categorias.| - |US27|
|08|O E-mail do usuário não pode se repetir| C2 | E-mail | - |
|09|O CPF do usuário não pode se repetir| C2 || - |
|10|O usuário deve receber notificações quando tiver uma oferta de ajuda aceita|C11|| - |US22|
|11|O usuário deve ter um limite de pedidos de ajuda abertos simultaneamente| - || - |
|12|O E-mail do usuário deve ser validado ao criar uma nova conta| C2|| - |
|13|As ajudas do usuário devem ser apagadas depois de um tempo limite| - || - |
|14|Um usuários só pode ajudar outros usuários que estiverem dentro do seu raio de distância| C2, C12 || - |
|15|Se deve avisar ao usuário caso o sistema esteja offline e ter uma estimativa de volta.| - || - |

## Detalhamento

## Login

***Figura 1 - Login***|
|:-:|
|![Login](./images/login.jpg ':size=200')|

<br>

## Cadastro

|***Figura 2 - Cadastrar localização inicial***|***Figura 3 - Cadastrar informações do usuário***|
|:-:|:-:
![LocalizaçãoCadastro](./images/cadastroLoc.jpg ':size=200') |![Cadastro](./images/cadastro.jpg ':size=200')|

<br>

## Página Inicial

***Figura 5 - Visualizando pedidos próximos***|
|:-:|
|![AdicionarLocalização](./images/loc.jpg ':size=200')|

<br>

## Pedir ajuda

***Figura 4 - Criando um pedido de ajuda***|
|:-:|
|![PrimeiroPedido](./images/pedirAjuda.jpg ':size=200')|

<br>

## Pedidos em andamento

***Figura 6 - Pedidos em andamento***|
|:-:|
|![PedidoemAndamento](./images/pedidosAndamento.jpg ':size=200') |

<br>

## Ajuda com Itens de Proteção

***Figura 7 - Filtro de itens de proteção***|
|:-:|
|![GrupodeRisco](./images/itensProtecao.jpg ':size=200')|

<br>

## Ajuda com Pequenos Serviços

***Figura 8 - Filtro de Pequenos Serviços***|
|:-:|
|![PequenosServiços](./images/pequenosServicos.jpg ':size=200')|

<br>

## Ajuda Psicológica

***Figura 9 - Filtro de Ajuda Psicológica***|
|:-:|
| ![AjudaPsicológica](./images/apoioPsicologico.jpg ':size=200')|

<br>

## Ajuda com Transporte de Emergência

***Figura 10 - Filtro de Transporte de Emergência***|
|:-:|
| ![TransportedeEmergência](./images/transporte.jpg ':size=200')|

<br>

## Ajuda com Apoio Social

***Figura 11 - Filtro de Apoio Social***|
|:-:|
| ![ApoioSocial](./images/apoioSocial.jpg ':size=200') |

<br>

## Pedidos Finalizados

***Figura 12 - Página com pedidos finalizados***|
|:-:|
| ![MeusPedidos](./images/meusPedidos.jpg ':size=200')|

<br>

## Logout

***Figura 13 - Sair do aplicativo***|
|:-:|
| ![LogOut](./images/logout.jpg ':size=200')|

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
