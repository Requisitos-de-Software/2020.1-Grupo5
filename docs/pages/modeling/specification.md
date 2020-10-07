# Especificação Suplementar
 
## Finalidade
 
- Este documento tem como finalidade reconhecer requisitos não funcionais relacionados do aplicativo que não foram identificados previamente pelas outras técnicas de modelagem.
 
## Escopo
 
- Uma aplicação *mobile* com o objetivo de facilitar a junção entre as pessoas que precisam de ajuda e as que querem ajudá-las de alguma forma.
 
## Requisitos não funcionais
 
|Número|Requisito|
|:-:|:-:|
|9|O usuário deve ser capaz de criar diversos pedidos de ajuda|
|13|O usuário deve ser capaz de ver as informações básicas de quem lhe ofereceu ajuda|
|14|O usuário deve ser capaz de visualizar seu histórico de ajudas|
|15|O usuário deve ser capaz de trocar sua senha quando solicitado|
|16|O usuário deve ser capaz de informar se faz parte do grupo de risco da COVID-19|
|17|O usuário deve ser capaz de informar que é um profissional da saúde mental|
|20|O usuário deve ser capaz de selecionar a categoria de sua ajuda para que a mesma possa ser filtrada por outros usuários|
|21|O E-mail do usuário não pode se repetir|
|22|O CPF do usuário não pode se repetir|
|26|O usuário deve receber notificações quando tiver uma oferta de ajuda aceita|
|27|O usuário deve ter um limite de pedidos de ajuda abertos simultaneamente|
|29|O E-mail do usuário deve ser validado ao criar uma nova conta|
|30|As ajudas do usuário devem ser apagadas depois de um tempo limite|
|31|Um usuários só pode ajudar outros usuários que estiverem dentro do seu raio de distância|
|32|Se deve avisar ao usuário caso o sistema esteja *offline* e ter uma estimativa de volta.||
## Usabilidade
 
### Facilidade de uso
 
O *app* deve ser intuitivo. A criação de novas ajudas deve está apresentada de forma clara para o usuário, qualquer pessoa, não importando sua familiaridade com o aplicativo ou idade, deve ser capaz de conseguir realizar o fluxo da criação de um pedido de ajuda. Assim como a criação do pedido de ajuda deve ser bem simples, a oferta de uma ajuda deve ser do mesmo jeito. As páginas de pedidos de ajuda e de ofertas, devem ser apresentadas de maneira simples e a partir da sua data de criação.
 
### Mensagens de Erro
 
O *app* deve apresentar mensagens quando alguma coisa não ocorre como o esperado. Um exemplo é na página de login, se o usuário informar uma senha ou e-mail inconsistentes avisá-lo através de um *pop-up*.
 
### Consistência e Padronização
 
O *app* deve seguir um padrão visual de cores e símbolos para que o usuário não se perca e sinta-se confortável.

### Idioma
O idioma da aplicação se deve ser a língua falada no país ou com o idioma pré-configurado no dispositivo móvel, caso não seja possivel identificar alguma lingua por esses dois meios se deve usar ingles como idioma da aplicação.
 
## Confiabilidade
 
### Disponibilidade
 
O sistema deve ficar disponível pelo maior tempo possível, o ideal seria que a aplicação ficasse disponível a todo o momento, mas na ocorrência da manutenção do sistema ou a tipo de falha é possível, deixando o sistema disponível, é necessário deixar o usuário ciente do que está ocorrendo.
 
### Segurança dos Dados Informados
 
Garantir a total segurança e privacidade no armazenamento de dados do usuário, mantendo o usuário íntegro e protegido com criptografia de seus dados.
 
### Transparência
 
O sistema deve deixar da forma mais clara possível, sobre o que ocorre dentro do sistema, para o usuário. Na ocorrência de uma falha do sistema se deve dar um feedback, sobre possíveis soluções e a causa do problema, ao usuário para que o próprio usuário consiga executar.
 
## Desempenho
 
### Tempo de Resposta
 
O sistema deve ter o mínimo tempo de resposta para requisições feitas pelo usuário durante o uso do aplicativo. Não podendo passar de 45 segundos para uma melhor experiência enquanto se utiliza a aplicação.
 
### Escalabilidade
 
O sistema deve ser capaz de responder simultaneamente cada usuário do Mia ajuda, simultaneamente, sem que cause algum tipo de problema para a experiência dos usuários
 
## Suportabilidade
 
O sistema deve estar disponível para celulares móveis. Independente de seu sistema operacional.
 
## Interface
 
### Interfaces do Usuário
 
 O sistema deve ter disponivel ao usuario uma interface grafica, com os componentes do sistema, de forma que o usuario tenha uma maior facilidade de utilizar a aplicação da melhor forma possivel.
 
### Interfaces de Hardware
 
O hardware deve ser capaz de fazer a comunicação com o servidor, acessara a internet para que o sistema possa funcionar de modo correto.

### Interfaces de Comunicação
 
O sistema deve possuir uma comunicção entre as diversas requisições de dados do sistema, mantendo a integridade de todas as requisições.

## Requisitos de Licenciamento 

### Termos de Uso

O sistema deve ter uma politica de uso sobre os daddos dos usuarios, seus direitos e explicando a razão de coletar dados do usuario.


---
|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|06/10/2020|0.1|Criação do arquivo de Especificação Suplementar|Danillo Souza|
|06/10/2020|0.2|Adicionado a Confiabilidade, Desempenho, Interface, idioma e requisitos de licenciamento|Paulo Gonçalves Lima|
