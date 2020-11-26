# NFR Framework

## Introdução

Esse documento visa a verificação do artefato [NFR Framework](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/modeling/framework/framework), ou seja, uma avaliação da situação atual do documento corrigindo falhas e adicionando especificações que estiverem em falta. Para isso devemos considerar como sendo uma análise de modelos, desempenhada com as regras bem definidas e de fácil entendimento.

## Metodologia

Para esse caso devemos analisar se existe algo de errado com nosso modelo já desenvolvido em termos de notação, processo e procedimentos executados. Assim avaliamos se o documento está de acordo com o que é esperado dele utilizando as estratégias apresentadas abaixo. O grupo optou para isso a utilização de checklist pela eficácia em conjunto com as questões elaboradas. Ao final serão revisados e corrigidos os itens defeituosos no documento em questão.

## Checklist

### Legenda
|Símbolo|Descrição|
|:-|:-|
|OK|Contém|
|X|Não contém|

|Itens|NFR Geral|NFR Confiabilidade|NFR Desempenho|NFR Usabilidade|
|:-|:-:|:-:|:-:|:-:|
|1. Respeita as regras de metodologia?|OK|OK|OK|OK|
|2. Softgoals autoexplicativos?|OK|OK|OK|OK|
|3. Operadores com finalidades definidas?|OK|OK|OK|OK|
|4. Existe impactos colaterais?|X|X|X|OK|
|5. Existe impactos em ancestrais?|OK|OK|OK|OK|
|6. Operadores geram impactos nos softgoals?|OK|OK|OK|OK|
|7. Operadores geram impactos em outros operadores?|X|OK|OK|OK|
|8. SoftGoals geram impactos em outros softgoals?|OK|OK|OK|OK|
|9. Existe ao menos um operador que tenha dependências(AND/OR) para atender o softgoal?|X|OK|OK|OK|
|10. Softgoals escritos como nome?|OK|OK|OK|OK|
|11. Operadores escritos como verbos?|X|OK|OK|OK|
|12. Existência de prioridade no NFR, seja operador ou softgoal?|OK|OK|OK|OK|
|13. Os critérios são completamente satisfatórios?|X|X|X|X|
|14. Os critérios são parcialmente satisfatórios?|OK|OK|OK|OK|
|15. Existência de softgoals ou operadores que não são satisfatórios?|OK|OK|OK|OK|
|16. Possui rastreabilidade?|OK|OK|OK|OK|
|17. Possui versionamento?|OK|OK|OK|OK|
|18. NFR condiz com requisitos já apresentados?|OK|OK|OK|OK|
|19. NFR possuem linkagens?|OK|X|OK|OK|
|**Porcentagem de sucesso**|**73%**|**85%**|**89%**|**95%**|

<br>

## Observações

|NFR Framework|Observações|
|:-|:-|
|NFR Geral|- Sem existência de impactos colaterais;<br>- Sem operadores que geram impactos em outros operadores;<br>- Sem existência de operadores (AND/OR);<br>- Sem operadores escritos com verbos;<br>- Não há critérios completamente satisfatórios.|
|NFR Confiabilidade|- Sem existência de impactos colaterais;<br>- Não possui linkagens<br>- Não há critérios completamente satisfatórios.|
|NFR Desempenho|- Sem existência de impactos colaterais;<br>- Não há critérios completamente satisfatórios;|
|NFR Usabilidade|- Não há critérios completamente satisfatórios.|

<br>

## Conclusão

 Pela análise e observações do checklist, nota-se que os frameworks não abrangiram o suficiente para obter impacto colaterais, e a grande parte dos softgoals atingem apenas critérios parcialmente satisfatórios.  
 É possível fazer uma nova versão do Framework Geral que atinja mais itens, mas apesar das deficiência dos outros três isso não quer dizer que seja um problema no framework, pois a satisfação não alcançada é devido as funcionalidades do aplicativo.

---

## Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|02/11/2020|0.1|Criação do documento|Pedro Vítor de Salles Cella|
|05/11/2020|0.2|Descrição da Introdução e Metodoliga |Ailamar Alves Guimarães|
|05/11/2020|0.3|Realização do checklist |Ailamar Alves Guimarães e Pedro vìtor de Salles Cella|

<br/>

## Referências

- [Página de verificação dos RichPictures do grupo Audible - 2019.2](https://requisitos-de-software.github.io/2019.2-Audible/verificacao_nfr/)
