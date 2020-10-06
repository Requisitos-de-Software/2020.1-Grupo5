# Léxico

## Introdução

Trata-se de uma técnica que descreve os símbolos de uma linguagem. Esses símbolos são descritos com noções e impactos, além disso são divididos entre estados, objetos e verbos.

## Estados

### Ajudante

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Estado|Usuário que ofertou ajuda é selecionado entre os possíveis ajudantes|Usuário tem a possibilidade de entrar em contato direto com o criador do pedido de ajuda|Doador

### Ajudas abertas

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Estado|Ajudas que ainda não foram concluídas ou que ainda não tiveram um ajudador definido|Ajuda aparece no mapa publicamente para todos os usuários, pode ser finalizada a qualquer momento|Ajudas em potencial

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
|Objeto|Tipo de ajuda que foi cadastrada|Categoriza ajudas tornando possível a filtragem|Tipo do pedido

### Histórico

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|Lista de ajudas finalizadas|Assim que um pedido de ajuda for finalizado, o mesmo irá para um histórico onde o usuário pode ver todas suas ajudas já realizadas|Ajudas finalizadas|

### Pedido de ajuda

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|São ajudas que estão mapeadas e são mostradas para todos os usuários|Todas as ajudas criadas por usuários são mostradas, publicamente, no mapa|Ajudas mapeadas, Local da ajuda|

### Possíveis ajudantes

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Objeto|São uma lista de usuários que ofertaram ajuda|O usuário que fez o pedido de ajuda poderá escolher, em uma lista, de quem ele deseja ajudar| Lista de pessoas interessadas em ajudar

## Verbos

### Abrir serviços externos

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Ao se tornar um ajudante, o usuário pode ter ser redirecionado ao Google Maps ou para o Whatsapp|Usuário possui acesso a rota até a ajuda e também tem a possibilidade de entrar em contato com quem pediu a ajuda| Redirecionamento

### Ajuda

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Ajudas são pedidos de algum tipo de auxílio. Podem ser doação, ajuda física, mental e etc. Qualquer tipo de caridade.|O usuário cria um pedido de ajuda descrevendo o que é necessário, o título e a categoria.|Auxílio, Doação, Pedido

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
|Verbo|Filtrar pedidos de ajuda no mapa a partir da categoria de cada uma delas|O usuário terá a oportunidade de visualizar somente uma categoria de ajudas|Separar, Selecionar, Especificar

### Finalizar ajuda

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Encerrar o pedido de ajuda assim que for concluído com sucesso|Assim que a ajuda for realizada, ela poderá ser finalizada e irá para um histórico| Encerrar, Concluir, Terminar

### Login

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Usuário fornece suas credenciais de acesso para poder utilizar o aplicativo|Se o usuário já tiver sido cadastrado, basta fornecer sua senha e email para que possa utilizar o aplicativo normalmente| *Sign In*, Entrar, Logar

### Oferta

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|São ofertas de algum tipo de auxílio para outros usuários|O usuário que fez uma oferta se tornará um possível ajudante|Doação, Oferecer ajuda, Filantropia

### Sair

|Tipo|Noção|Impacto|Sinônimos|
|:-:|:-:|:-:|:-:|
|Verbo|Desconectar da conta|O usuário desconecta da conta em seu aparelho|*Logout*, Desconectar

---
|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|02/10/2020|0.1|Criação do documento de léxico|Danillo Souza|
|06/10/2020|0.2|Organizando léxico, adicionando novos tópicos e separando por categorias|Danillo Souza|
