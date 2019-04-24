# Panorama dos acidentes de trabalho no Brasil

## Introdução

Em 2018 diversos portais como o próprio ministério público do trabalho e a associação nacional de medicina do trabalho reproduziram a notícia de que o Brasil seria o 4° pais em um ranking feito com base em dados da OIT, que diz respeito aos países com a maior quantidade de acidentes de trabalho. Segundo, a própria OIT (truconosestados) tal ranking nunca existiu. Essa informação foi replicada, inclusive no programa de governo de um deputado no rio grande do sul. Na época, a OIT só possuía informações a respeito do assunto até o ano de 2011.

A desinformação a respeito dos acidentes de trabalho no país é em si alarmante. A situação se agrava, em vista que em 2017 foram registrados 895770 acidentes no país, segundo dados do MPT. Anualmente a previdência social busca publicar um relatório informando os dados que serão discutidos neste artigo. No anuário de 2017 consta que a previdência social mantinha 34,3 milhões de benefícios ativos, dos quais 2,3% são benefícios relacionados a acidentes de trabalho, totalizando o montante de R$ 970.777 Milhões.

Outro aspecto pouco abordado, é  o impacto na produtividade. Sousa Santana (2006) estimou para o estado da bahia no ano de 2007, um total de aproximadamente meio milhão de dias perdidos, de trabalho no ano; levando-se a população de 2857 acidentados.

Entender onde, com quem, quando e como ocorrem os acidentes de trabalho são os primeiros passos para o norteamento de políticas públicas de prevenção de acidentes.  Com isso em mente esse trabalho se propõem a realizar uma analise, a partir das bases de dados disponibilizadas, através do portal da transparência, pela previdência social a respeito dos acidentes do trabalho ocorridos no pais no período x.  

## CAT - Comunicação de Acidente de Trabalho
A comunicação de acidente de trabalho (CAT) é um documento emitido para reconhecer tanto um  acidente de trabalho ou  de trajeto, bem como uma  doença ocupacional(INSS). Aqui vale a definição desses termos:

-   Acidente de trabalho ou de trajeto:é o acidente ocorrido no exercício da atividade profissional a serviço da empresa ou no deslocamento
```mermaid
	graph LR
    id1[Residência] --> Trabalho
    Trabalho --> Residência
```

    
-   Doença ocupacional: é aquela produzida ou desencadeada pelo exercício do trabalho peculiar a determinada atividade e constante da respectiva relação elaborada pelo Ministério do Trabalho e da Previdência Social.
    

O INSS informa que a CAT é um documento obrigatório e possui um prazo de emissão curto. Mesmo que não haja afastamento, a CAT deve ser emitida até o primeiro dia útil seguinte ao da ocorrência; sob o risco de multa. Por conta desta característica a base de dados do INSS é útil e pouco defasada da realidade brasileira, portanto um bom instrumento para análise.



## Metodologia  
A princípio foram adquiridas 6 bases de dados, com diferentes recortes a respeito do tema. Elas são:  
1. Acidentes de Trabalho por UF  
2. Acidentes de Trabalho por mês  
3. Acidentes de Trabalho por faixa-etaria e sexo  
4. Acidentes de Trabalho por parte do corpo atingida  
5. Acidentes de Trabalho por CID  
6. Acidentes de Trabalho por CBO  
  
Todas as bases de dados são segmentadas por ano. Todas contêm algum indicativo se houve ou não uma comunicação de acidente de trabalho registrada. Igualmente, todas possuem um campo com a tipificação do acidente, seja ele típico, de trajeto ou uma doença de trabalho. Cada base será analisada individualmente, em seu contexto específico, com base em estudos a respeito do tema. Uma vez explorada todas essas seis dimensões do problema, será possível chegar em um compreendimento maior a respeito de como se apresenta a situação dos acidentes de trabalho no Brasil.

## Acidentes de Trabalho por UF

O primeiro conjunto de dados a ser estudado diz respeito aos acidentes de trabalho por unidade federal. Com essa base de dados pretende-se responder a pergunta: "Onde ocorrem os acidentes de trabalho?". Também sera mostrado a evolução ao longo do tempo para as grandes regiões do pais. Das 2893 linhas contidas na base de dados, apenas uma continha valores nulos, portanto foi descartada.


## Referencias Bibliográficas

%Mundo
https://onlinelibrary.wiley.com/doi/abs/10.1002/(SICI)1097-0274(199911)36:5%3C487::AID-AJIM1%3E3.0.CO;2-2
http://ilo.org/wcmsp5/groups/public/---ed_protect/---protrav/---safework/documents/publication/wcms_110382.pdf
https://www.ilo.org/safework/info/publications/WCMS_142840/lang--en/index.htm
%Brasil
https://www.scielosp.org/scielo.php?pid=S0034-89102006000700007&script=sci_arttext&tlng=en
http://www.scielo.br/scielo.php?pid=S1413-81232005000400009&script=sci_abstract&tlng=pt
http://www.scielo.br/scielo.php?script=sci_arttext&pid=S0034-89102006000700007&lng=en
http://www.scielo.br/scielo.php?script=sci_arttext&pid=S0102-311X2014000901957&lang=en
Empresa de Tecnologia e Informações da Previdência Social. Anuário estatístico da previdência social: 2017. [http://www.previdencia.gov.br/dados-abertos/dados-abertos-previdencia-social/](http://www.previdencia.gov.br/dados-abertos/dados-abertos-previdencia-social/) (acessado em 24/Fev/2019).
> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI4NjQ3MDkwMiwtOTA1NTEyODE5LC0xMj
U4NjA1NjYyLDEzMzMxMjQ3ODUsMTMyOTUzNjkxOSwtMjM5Nzk5
MzY3LC01Njc1NTMzNzMsLTE0MzUxMDgzMzAsLTEzNzI5NzgwND
QsLTgzNjEwMDkyMSwtNTM3MjE3NjY0LC0xNDgwNTAxMDgsNzQ5
NjYyNDk4LDg5NjMwOTU1MywxMTU4NjUwNjE2LDIyNDgyNTM4Ml
19
-->