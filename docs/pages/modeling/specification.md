# Especificação Suplementar

## Introdução

A especificação suplementar é um documento com intuito de explicitar os requisitos não funcionais e informações, que não foram coletados não imediatamente pelos casos de uso.

## Escopo

O Mia Ajuda foi criado com o intuito de aproximar pessoas que precisam de ajuda daqueles que desejam contribuir de alguma forma.
  
## Requisitos não funcionais

|Número|Requisito|
|:-:|:-:|
|RNF01|O usuário deve ser capaz de criar diversos pedidos de ajuda|
|RNF02|O usuário deve ser capaz de ver as informações básicas de quem lhe ofereceu ajuda|
|RNF03|O usuário deve ser capaz de visualizar seu histórico de ajudas|
|RNF04|O usuário deve ser capaz de trocar sua senha quando solicitado|
|RNF05|O usuário deve ser capaz de informar se faz parte do grupo de risco da COVID-19|
|RNF06|O usuário deve ser capaz de informar que é um profissional da saúde mental|
|RNF07|O usuário deve ser capaz de selecionar a categoria de sua ajuda para que a mesma possa ser filtrada por outros usuários|
|RNF08|O E-mail do usuário não pode se repetir|
|RNF09|O CPF do usuário não pode se repetir|
|RNF10|O usuário deve receber notificações quando tiver uma oferta de ajuda aceita|
|RNF11|O usuário deve ter um limite de pedidos de ajuda abertos simultaneamente|
|RNF12|O E-mail do usuário deve ser validado ao criar uma nova conta|
|RNF13|As ajudas do usuário devem ser apagadas depois de um tempo limite|
|RNF14|Um usuários só pode ajudar outros usuários que estiverem dentro do seu raio de distância|
|RNF15|Se deve avisar ao usuário caso o sistema esteja *offline* e ter uma estimativa de volta.|

## Usabilidade

### Facilidade de uso

O *app* deve ser intuitivo. A criação de novas ajudas deve está apresentada de forma clara para o usuário, qualquer pessoa, não importando sua familiaridade com o aplicativo ou idade, deve ser capaz de conseguir realizar o fluxo da criação de um pedido de ajuda. Assim como a criação do pedido de ajuda deve ser bem simples, a oferta de uma ajuda deve ser do mesmo jeito. As páginas de pedidos de ajuda e de ofertas, devem ser apresentadas de maneira simples e a partir da sua data de criação.

### Mensagens de Erro

O *app* deve apresentar mensagens quando alguma coisa não ocorre como o esperado. Um exemplo é na página de login, se o usuário informar uma senha ou e-mail inconsistentes avisá-lo através de um *pop-up*.

### Consistência e Padronização

O *app* deve seguir um padrão visual de cores e símbolos para que o usuário não se perca e sinta-se confortável.

## Confiabilidade

### Disponibilidade

O *app*, se houver conexão com a internet, deve estar sempre disponível para o usuário, não importando o horário ou dia da semana. A não ser que esteja ocorrendo alguma manutenção no sistema.

### Segurança dos Dados Informados

O sistema deve assegurar que os dados dos usuários estarão seguros e informações importantes, como o CPF e senhas, serão totalmente sigilosas e estarão seguras.

### Transparência

O sistema deve ter transparência com os usuários, e deve explicitar quais dados estão sendo coletados e o porquê estão sendo coletados.

## Desempenho

### Tempo de Resposta

O *app* deve possuir um tempo de resposta instantâneo e mostrar todos os pedidos de ajuda disponíveis assim que eles forem criados.

### Escalabilidade

O *app* deve ser capaz de suportar inúmeros pedidos de ajuda criados por usuários simultâneamente. O sistema tabém deve ser capaz de retornar todas as ajudas próximas do usuário sem que o servidor ou o aparelho do mesmo seja sobrecarregado.

## Suportabilidade

O *app* deve ter suporte para aparelhos Android. Em breve, também, para iOS.

## Interface

### Interfaces do Usuário

O sistema deve ter disponível para o usuário uma interface gráfica, simples e intuitiva, de forma que o mesmo tenha uma maior familiaridade ao utilizar a aplicação.

### Interfaces de Hardware

O hardware deve ser capaz de fazer a comunicação com o servidor, acessar a internet para que o sistema possa funcionar de modo correto.

### Interfaces de Comunicação

As requisições do sistema devem ser, todas, a partir do acesso com a internet.

## Requisitos de Licenciamento

### Termos de Uso

O sistema deve possuir uma política de uso. O documento deve explicar como os dados do usuário estão sendo coletados, o porquê estão sendo coletados, o que está sendo feito com essas informações e quais os direitos e deveres que os individuos cadastrados possuem dentro da plataforma.

---
## Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|06/10/2020|0.1|Criação do arquivo de Especificação Suplementar|Danillo Souza|
|06/10/2020|0.2|Adicionado a Confiabilidade, Desempenho, Interface, idioma e requisitos de licenciamento|Paulo Gonçalves Lima|
|07/10/2020|0.3|Revisando, corrigindo e atualizando tópicos do documento|Danillo Souza|
