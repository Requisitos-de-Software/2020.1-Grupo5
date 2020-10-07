# Cenários

## Introdução

Um cenário é um ambiente criado pela equipe de projeto para representar situações que ajude a compreender as interações entre os sistemas e também elicitar a parte comportamental do software. Essa técnica tem se provado muito eficiente para levantamento de requisitos apesar de informal.

## Metodologia 

A técnica funciona com a criação de narrativas que descrevem um episódio específico que necessitam do uso da tecnologia do nosso projeto. Assim criamos uma breve história de uma cena bem detalhada com atores para simular a situação.<br/><br/>
Na criação dos nossos cenários utilizamos o seguinte modelo base:  
<br/>

Tópico | Descrição 
:----: | :--------
**Título**   | Nome breve para o cenário
**Objetivo** | Finalidade da história 
**Contexto** | Local, tempo e pré-condição da história
**Atores**   | Personagens que participarão da história
**Recurso**  | Recursos envolvidos
**Restrição** | Critérios favoráveis, caso tenha
**Exceção**  | Critérios desfavoráveis, caso tenha
**Episódio** | Descrição da narrativa 
<br/>

## Nossos cenários

### C1 - Primeiro pedido de ajuda

|      | Descrição 
:----- | :--------
**Objetivo** | Adicionar seu primeiro pedido de ajuda no aplicativo 
**Contexto** | Local: em casa<br/>Tempo: pela manhã<br/> Pré-condição: precisar de algo urgente
**Ator(es)** | Nova usuária
**Recurso**  | Telefone com o aplicativo<br/> Telefone com internet
**Restrição** | Pedido possível de ser feito pelo aplicativo
**Exceção**  | Falta de sinal de internet
**Episódio** | Usuária conhece o Mia Ajuda e se cadastra.<br/> Usuária necessitou de remédios para seu filho.<br/> Usuária anuncia sobre sua necessidade.<br/>Usuária aguarda que seu pedido seja atendido.
<br/>

### C2 - Primeira ajuda realizada

|      | Descrição 
:----- | :--------
**Objetivo** | Executar um pedido de ajuda no aplicativo 
**Contexto** | Local: em casa<br/>Tempo: pela manhã<br/> Pré-condição: ter a agenda livre
**Ator(es)** | Nova usuária
**Recurso**  | Telefone com o aplicativo<br/> Telefone com internet<br/> 
**Restrição** | Encontrar pedido em uma localidade próxima<br/>Condição de contribuir com a ajuda
**Episódio** | Usuária conhece o Mia Ajuda e se cadastra.<br/> Usuária pretende contribuir com sua primeira ação solidária.<br/> Usuária encontra no mapa uma solicitação próxima a sua residência.<br/>Usuária aceita pedido.
<br/>

### C3 - Ajudando pessoas do grupo de risco

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer ajuda para alguém no isolamento social
**Contexto** | Local: trabalho<br/>Tempo: horário de almoço<br/>Pré-condição: poder sair do escritório
**Ator(es)** | Ajudante e idoso
**Recurso**  | Telefone com o aplicativo<br/> Acesso à internet<br/> Automóvel
**Restrição** | Não possuir outro compromisso na hora do almoço
**Exceção**  | Pouco tempo disponível<br/>Possuir algum simtoma de COVID-19
**Episódio** | Ajudante entra no aplicativo.<br/> Ajudante busca por pedidos de ajuda em localidades próximas.<br/> Ajudante encontra um idoso que precisa de fazer compra suprimentos básicos para casa.<br/> Ajudante contacta o idoso para mais informações.<br/> Ajudante vai ao mercado às compras.<br/>Ajudante e idoso se encontram com todo cuidado necessário e finalizam o pedido.
<br/>

### C4 - Mão de obra amiga

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer pequenos serviços
**Contexto** | Local: bairro próximo<br/>Tempo: sábado de manhã<br/>Pré-condição: não possuir outro compromisso
**Ator(es)** | Usuário ajudante, usuário ajudado
**Recurso**  | Carro<br/>Telefone com aplicativo<br/>Telefone com acesso à internet<br/>Ferramentas de construção
**Restrição** | Ter o dia livre<br/>Familiaridade com as ferramentas<br/>
**Exceção**  | Problemas com carregamento de peso ou esforço físico<br/>Usuário ajudante com alguma deficiência
**Episódio** | Ajudante pode contribuir no aplicativo com pedidos apoio físico.<br/>Ajudado solicita voluntário para demolição das paredes de um cômodo em sua casa.<br/>Ajudante aceita o pedido e marca um horário.<br/>Ao final do dia as paredes estavam derrubadas.<br/>
<br/>

### C5 - Colaboração psicológica

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer ajuda psicológica 
**Contexto** | Local: clínica de terapia<br/>Tempo: sexta a tarde<br/>Pré-condição: agenda de atendimentos vazia
**Ator(es)** | Psicóloga, usuário ajudado
**Recurso**  | Telefone com aplicativo<br/>Telefone com acesso à internet<br/>
**Exceção**  | Não ser profissional da área de psicologia.
**Episódio** | Psicóloga entra no aplicativo.<br/>Psicóloga encontra pedido de apoio psicológico.<br/>Usuário e psicóloga combinam um horário para a sessão.<br/>Em uma chamada pelo telefone ocorre o diálogo.<br/>Primeira seção de conversa finalizada.
<br/>

### C6 - Auxílio com transporte de emergência

|      | Descrição 
:----- | :--------
**Objetivo** | Levar o usuário em uma consulta médica 
**Contexto** | Local: hospital regional<br/>Tempo: à tarde<br/>Pré-condição: possuir um automóvel.
**Ator(es)** | Usuário voluntário, usuário ajudado
**Recurso**  | Telefone com aplicativo<br/>Telefone com acesso à internet<br/>Carro<br/>
**Restrição** | Veículo com gasolina<br/>Tempo para esperar<br/>Não ser do grupo de risco
**Exceção**  | Hospital muito distante.<br/>
**Episódio** | Usuário voluntário entra no aplicativo em busca de solicitações de ajuda.<br/>Usuário voluntário encontra próximo à sua casa um pedido.<br/>Usuário voluntário vê descrição breve sobre o pedido.<br/>Usuário ajudado precisa de alguém que o leve em uma consulta no dia seguinte.<br/>Usuário voluntário está disponível no horário descrito.<br/>Pedido de ajuda aceito.
<br/>

### C7 - Apoio social

|      | Descrição 
:----- | :--------
**Objetivo** | Promover uma ajuda de apoio social
**Contexto** | Local: centro de ajudas sociais<br/>Tempo: a tarde<br/>Pré-condição: um grupo de pessoas dispostas a ajudar
**Ator(es)** | Usuários ajudantes, usuário cadastrado, criança carente
**Recurso**  | Acesso ao aplicativo<br/>
**Restrição** | Disponibilidade de tempo<br/>Conhecimento sobre ajudas sociais
**Episódio** | Usuários ajudantes entram no aplicativo em busca de pedidos.<br/> Usuário cadastrado conhece uma criança desamparada.<br/>Usuário cadastrado no Mia Ajuda cria um pedido de apoio social para a criança carente.<br/>Usuarios ajudantes aceitam o pedido e assumem a responsabilidade do caso.
<br/>

### C8 - Emergência com itens de proteção

|      | Descrição 
:----- | :--------
**Objetivo** | Doação de itens de proteção contra COVID-19
**Contexto** | Local: em casa<br/>Tempo: horário do almoço<br/>Pré-condição: 
**Ator(es)** | Usuário
**Recurso**  | Acesso ao aplicativo<br/>Máscaras<br/>Embalagem de álcool<br/>Luvas<br/>Avental
**Restrição** | Equipamentos esterilizados
**Exceção**  | Ajudantes com mais de 60 anos<br/>Ajudantes com algum sintoma de COVID-19
**Episódio** | Usuário participa de um trabalho voluntário durante a pandemia.<br/> Usuário não possui recursos para comprar seus materiais de proteção frequentemente.<br/>Usuário solicita no Mia Ajuda um pedido dos seguintes itens de proteção (máscaras, álcool, luvas e avental).
<br/>

### C9 - 

|      | Descrição 
:----- | :--------
**Objetivo** | Doação de itens de proteção contra COVID-19
**Contexto** | Local: em casa<br/>Tempo: horário do almoço<br/>Pré-condição: 
**Ator(es)** | Usuário
**Recurso**  | Acesso ao aplicativo<br/>Máscaras<br/>Embalagem de álcool<br/>Luvas<br/>Avental
**Restrição** | Equipamentos esterilizados
**Exceção**  | Ajudantes com mais de 60 anos<br/>Ajudantes com algum sintoma de COVID-19
**Episódio** | Usuário participa de um trabalho voluntário durante a pandemia.<br/> Usuário não possui recursos para comprar seus materiais de proteção frequentemente.<br/>Usuário solicita no Mia Ajuda um pedido dos seguintes itens de proteção (máscaras, álcool, luvas e avental).
<br/>

### C10 - 

|      | Descrição 
:----- | :--------
**Objetivo** | Doação de itens de proteção contra COVID-19
**Contexto** | Local: em casa<br/>Tempo: horário do almoço<br/>Pré-condição: 
**Ator(es)** | Usuário
**Recurso**  | Acesso ao aplicativo<br/>Máscaras<br/>Embalagem de álcool<br/>Luvas<br/>Avental
**Restrição** | Equipamentos esterilizados
**Exceção**  | Ajudantes com mais de 60 anos<br/>Ajudantes com algum sintoma de COVID-19
**Episódio** | Usuário participa de um trabalho voluntário durante a pandemia.<br/> Usuário não possui recursos para comprar seus materiais de proteção frequentemente.<br/>Usuário solicita no Mia Ajuda um pedido dos seguintes itens de proteção (máscaras, álcool, luvas e avental).
<br/>

---

### Versionamento

|Data|Versão|Descrição|Autor|
|:--:|:----:|:-------:|:---:|
|3/10/2020| 0.1| Criação do escopo do documento| Ailamar Alves Guimarães|
|5/10/2020| 0.2| Adição dos cenários C1 a C10 | Ailamar Alves Guimarães|

### Referências 

- Requisitos - Aula 10. Milene Serrano e Maurício Serrano. Disponívem em: <https://aprender3.unb.br/pluginfile.php/426741/mod_resource/content/1/Aula%2010.pdf>. Acesso em out. 2020.

- Modelagem - Cenários. ?????? . Disponível em: <https://requisitos-de-software.github.io/2019.2-Audible/cenarios/>. Acesso em out. 2020.
