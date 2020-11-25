# Léxico
 
## Introdução
 
Trata-se de uma técnica que descreve os símbolos de uma linguagem. Esses símbolos são descritos com noções e impactos, além disso são divididos entre estados, objetos e verbos.
 
## Estados
 
### Ajudante
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Estado|Usuário que foi escolhido para ajudar|Usuário entra contato com o criador do pedido de ajuda|Doador
 
### Ajudas abertas
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Estado|Ajudas recém criadas que ainda não possuem um ajudante definido|Ajuda aparece no mapa publicamente para todos os usuários, pode ser finalizada a qualquer momento|Ajudas em potencial
 
### Ajudas em andamento
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Estado|Ajudas que possuem um ajudante já definido|Ajudas em andamento param de aparecer no mapa e os usuários podem entrar em contato entre si|Ajudas em progresso
 
### Ajudas finalizadas
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Estado|Quando uma ajuda é concluída, o usuário termina o seu pedido de ajuda|O pedido de ajuda some do mapa, o mesmo passa para o histórico| Ajudadas terminadas
 
## Objetos
 
### Categorias
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|Tipo da ajuda que foi cadastrada|Categoriza ajudas tornando possível a filtragem|Tipo do pedido
 
### E-mail
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|Correio eletrônico|O cadastro do usuário só se torna possível a partir de um E-mail|Gmail, Outlook, Yahoo
 
### Histórico
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|Lista de ajudas finalizadas|O usuário pode visualizar todas as suas ajudas e ofertas realizadas anteriormente|História, Lista de atividades finalizadas|
 
### Mapa
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|Página que fornece localização do usuário e pedidos de ajuda|Fornecer localizações importantes no app|Localizações|
 
### Pedido de ajuda
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|O objeto que representa a ajuda em si, possui um título, descrição e categoria|Os pedidos aparecem, publicamente, no mapa para todos os usuários|Pedido|
 
### Possíveis ajudantes
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|Lista de usuários que ofertaram ajuda|O usuário que fez o pedido de ajuda poderá escolher, em uma lista, de quem ele deseja ajudar| Interessados em ajudar
 
## Verbos
 
### Abrir serviços externos
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Redirecionamento do usuário para o Google Maps ou para o Whatsapp|Usuário possui acesso a rota até a ajuda e também tem a possibilidade de entrar em contato com quem pediu a ajuda| Redirecionamento
 
### Ajuda
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Solicitação de auxílio|O usuário que está passando por alguma dificuldade pode pedir ajuda através do app|Auxílio, Doação, Pedido
 
### Cadastrar
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Criar uma conta no Mia Ajuda|Assim que o usuário se cadastrar ele terá acesso ao aplicativo|Registrar, *Sign Up*|
 
### Editar perfil
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Editar informações e fotos cadastradas|Os dados de contato e informações básicas do usuário, com exceção do CPF e E-mail|Alterar dados
 
### Filtrar pedidos de ajuda
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Filtrar pedidos de ajuda no mapa a partir da categoria de cada uma delas|Separa as ajudas, que serão mostradas no mapa, por categorias|Separar, Selecionar, Especificar
 
### Finalizar ajuda
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Encerrar o pedido de ajuda assim que for concluído com sucesso|Usuário finaliza a ajuda assim que o seu objetivo for concluído| Encerrar, Concluir, Terminar
 
### Login
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Usuário fornece suas credenciais de acesso para poder utilizar o aplicativo|Se o usuário já tiver sido cadastrado, basta fornecer sua senha e email para que possa utilizar o aplicativo normalmente| *Sign In*, Entrar, Logar
 
### Oferta
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|São ofertas de algum tipo de auxílio para outros usuários|Usuário se propõem a ajudar um terceiro|Doação, Oferecer ajuda, Filantropia
 
### Sair
 
|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Desconectar da conta|O usuário desconecta da conta em seu aparelho|*Logout*, Desconectar
 
---
 
## Versionamento
 
|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|02/10/2020|0.1|Criação do documento de léxico|Danillo Souza|
|06/10/2020|0.2|Organizando léxico, adicionando novos tópicos e separando-os por categorias|Danillo Souza|
|21/10/2020|0.3|Tópicos E-mail e Mapa adicionado|Danillo Souza|
|04/11/2020|0.4|Documento verificado e corrigido|Danillo Souza|