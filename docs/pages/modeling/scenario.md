# Cenários

## Introdução

Um cenário é um ambiente criado pela equipe de projeto para representar situações que ajude a compreender as interações entre os sistemas e também elicitar a parte comportamental do software. Essa técnica tem se provado muito eficiente para levantamento de requisitos apesar de informal.

## Metodologia 

A técnica funciona com a criação de narrativas que descrevem umaeposódio específico da necessidade do uso da técnologia do nosso projeto. Assim criamos uma narrativa de uma cena bem detalhada com atores para simular a situação.  
Na criação dos nossos cenários utilizamos o seguinte modelo base apresentado abaixo:  
<br/>
Tópico | Descrição 
:----: | :--------
**Título**   | Nome breve para o cenário
**Objetivo** | Finalidade da história 
**Contexto** | Local, tempo e pré-condição da história
**Atores**   | Personagens que participarão da história
**Recurso**  | Recursos envolvidos
**Restrição** | Alguma observação, caso tenha
**Exceção**  | Exeção do cenário, caso tenha
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
**Exceção**  | Faltar de sinal da internet
**Episódio** | Usuária conhece o Mia Ajuda e se cadastra.<br/> Usuária necessitou de remédios para seu filho.<br/> Usuária anuncia sobre sua necessidade.<br/>Usuária aguarda que seu pedido seja atendido.
<br/>

### C2 - Ajudando pessoas do grupo de risco

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer ajuda para alguém no isolamento social
**Contexto** | Local: trabalho<br/>Tempo: horário de almoço<br/>Pré-condição: poder sair do escritório
**Ator(es)** | Ajudante e idoso
**Recurso**  | Telefone com o aplicativo<br/> Acesso à internet<br/> Automóvel
**Restrição** | Algum outro compromisso na hora do almoço
**Exceção**  | Pouco tempo disponível
**Episódio** | Ajudante entra no aplicativo.<br/> Ajudante busca por pedidos de ajuda em localidades próximas.<br/> Ajudante encontra um idoso que precisa de fazer compra de algumas coisas para casa.<br/> Ajudante contacta o idoso para mais informações.<br/> Ajudante vai ao mercado às compras.<br/>Ajudante e idoso se encontram com todo cuidado necessário e finalizam o pedido.
<br/>

### C3 - Mão de obra amiga

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer pequenos serviços
**Contexto** | Local: bairro próximo<br/>Tempo: sábado de manhã<br/>Pré-condição: não posuir outro compromisso
**Ator(es)** | Usuário ajudante, usuário ajudado
**Recurso**  | Carro<br/>Telefone com aplicativo<br/>Telefone com acesso à internet<br/>Ferramentas de construção
**Restrição** | Problemas com carregamento de peso ou esforço físico
**Exceção**  | Usuário ajudante com alguma deficiência
**Episódio** | Ajudante pode contribuir no aplicativo com pedidos apoio físico.<br/>Ajudado solicita voluntário para demolição das paredes de um cômodo em sua casa.<br/>Ajudante aceita o pedido e combinam um horário.<br/>Ao final do dia as paredes estavam derrubadas.<br/>
<br/>

### C4 - Colaboração piscológica

|      | Descrição 
:----- | :--------
**Objetivo** | Oferecer ajuda piscológica 
**Contexto** | Local: clínica de terapia<br/>Tempo: sexta a tarde<br/>Pré-condição: agenda de atendimentos vazia
**Ator(es)** | Psicóloga, usuário ajudado
**Recurso**  | Telefone com aplicativo<br/>Telefone com acesso à internet<br/>
**Exceção**  | Não ser profissional da área de psicologia.
**Episódio** | Psicologa entra no aplicativo.<br/>Psicóloga encontra pedido de apoio psicológico.<br/>Usuário e psicóloga combinam um horário para a seção.<br/>Em uma chamada pelo telefone ocorre o diálogo.<br/>Primeira seção de conversa finalizada.
<br/>

### C5 - Auxílio com transporte de emergência

|      | Descrição 
:----- | :--------
**Objetivo** | Levar o usuário em uma consulta médica 
**Contexto** | Local: hospital regional<br/>Tempo: à tarde<br/>Pré-condição: possuir um altomóvel.
**Ator(es)** | Usuário voluntário, usuário ajudado
**Recurso**  | Telefone com aplicativo<br/>Telefone com acesso à internet<br/>Carro<br/>
**Exceção**  | Hospital muito distante.<br/>
**Episódio** | Usuário voluntário entra no aplicativo em busca de solicitações de ajuda.<br/>Usuário voluntário encontra próximo à sua casa um pedido.<br/>Usuário voluntário vê descrição breve sobre o pedido.<br/>Usuário ajudado precisa de alguém que o leve em uma consulta no dia seguinte.<br/>Usuário voluntário está disponível no horário descrito.<br/>Pedido de ajuda aceito.
<br/>

### C6 - Emergência com itens de proteção

|      | Descrição 
:----- | :--------
**Objetivo** | Doação de itens de proteção contra COVID-19
**Contexto** | Local: em casa<br/>Tempo: horário do almoço<br/>Pré-condição: 
**Ator(es)** | Usuário
**Recurso**  | Acesso ao aplicativo<br/>Máscaras<br/>Embalagem de alcóol<br/>Luvas<br/>Avental
**Restrição** | Equipamentos esterelizados
**Exceção**  | Ajudantes com mais de 60 anos<br/>Ajudantes com algum sintoma de COVID-19
**Episódio** | Usuário participa de um trabalho voluntário durante a pandemia.<br/> Usuário não possui recursos para comprar seus materias de proteção frequentemente.<br/>Usuário solicita no Mia Ajuda um pedido dos seguintes intens de proteção (máscaras, alcóol, luvas e avental).
<br/>

---

### Versionamento

|Data|Versão|Descrição|Autor|
|:--:|:----:|:-------:|:---:|
|3/10/2020| 0.1| Criação do escopo do documento| Ailamar Alves Guimarães|
|5/10/2020| 0.2| Adição de cenários| Ailamar Alves Guimarães|

### Referências 

- Requisitos - Aula 10. Milene Serrano e Maurício Serrano. Disponívem em: <https://aprender3.unb.br/pluginfile.php/426741/mod_resource/content/1/Aula%2010.pdf>. Acesso em out. 2020.

- Modelagem - Cenários. ?????? . Disponível em: <https://requisitos-de-software.github.io/2019.2-Audible/cenarios/>. Acesso em out. 2020.
