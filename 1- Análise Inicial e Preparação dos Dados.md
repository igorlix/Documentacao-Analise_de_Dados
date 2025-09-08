# Análise de Dados
Enquanto um processo obrigatório para se trabalhar com dados, seja ao inferir, classificar ou modelar. A Análise de Dados nos permite observar, através de nuances, relações que passam despercebidas, mas muitas vezes podem ser explicadas matematicamente. Descrevendo a jornada da observação de dados brutos, até tomadas de decisões que são decorrentes dessa análise.

Inicialmente, ao trabalhar com dados brutos, deve-se antes de tudo entender algumas questões que direcionarão a análise, permitindo que esses dados oferecem certos "insights" e evidências que corroboram com o propósito da análise. Nessa etapa algumas perguntas devem ser respondidas, tais como: 

## Natureza dos Dados: 

- **Qual a natureza desses dados?** Esse é o cerne da análise, identificar a natureza nos permite não somente interpretá-los corretamente, como também nos dá indícios de outro fator extremamante importante, o contexto. 

1. Dados Categóricos: Qualitativos, representam categorias.

* Nominais: Categorias sem ordem (ex: Gênero, Cidade, etc.).

* Ordinais: Categorias com uma ordem intrínseca (ex: Escolaridade, Nível de satisfação).

2. Dados Numéricos: Quantitativos, representam uma medida.

* Discretos: Contagens, números inteiros (ex: Nº de filhos, Quantidade de produtos vendidos).

* Contínuos: Podem assumir qualquer valor em um intervalo (ex: Altura, Salário, Temperatura).

Representação visual da natureza dos dados:

![Natureza dos Dados](https://github.com/igorlix/Documentacao-Analise_de_Dados/blob/49ef6aba5c8c889c2e50bb71a6d25a210163dd2d/Imagens/O-ge%CC%82nesis-das-ana%CC%81lises-de-dados-%E2%80%93-Entenda-a-Natureza-dos-Seus-Dados_0.png)

## Conhecimentos e Aplicações:

- **Que conhecimentos posso adquirir com esses dados?** Nesse contexto, é necessário entender o que se refere como "conhecimento". Dados brutos são apenas elementos com potencial de gerar informações, mas que ainda não foram processados, eles podem ser numéros, letras, símbolos, etc. Sua compreensão se deve ao processo de organização e interpretação, gerando sentido claro e valor funcional, esses dados agora são informações. O conhecimento portanto, é a aplicação dessas informaçãoes garatindo significado ao contexto, sendo assim, entender que conhecimentos esses dados podem prover nos permite compreender que aplicações eles podem gerar. 


## Processo de Análise de Dados:
Partindo dessa premissa, devemos definir a pipeline da análise, que consiste em uma série de etapas que vão desde a definição do objeto de análise, até a interpretação dos resultados.  

1. Definição do Problema e dos Objetivos
* O que queremos descobrir ou resolver? 
* Que perguntas de negócio precisam ser respondidas?
* Qual é a hipótese inicial? (Ex: "A nova campanha de marketing aumentou as vendas").

2. Coleta e Entendimento dos Dados
* De onde vêm os dados? 
* Qual é o dicionário de dados? O que cada coluna significa?
* Aqui entra a Análise da Natureza dos Dados que detalhamos acima (Categórico, Numérico, etc.).

3. Limpeza e Pré-processamento dos Dados
* Tratamento de valores ausentes (nulos).
* Correção de erros de digitação e inconsistências.
* Remoção de dados duplicados.
* Normalização ou Padronização.

4. Análise Exploratória de Dados (EDA - Exploratory Data Analysis)
* Estatísticas Descritivas: Calcular médias, medianas, desvios-padrão, frequências.
* Visualização de Dados: Gerar histogramas, boxplots, gráficos de dispersão para "sentir" os dados.
* Diagnóstico: Testes de Normalidade como Shapiro-Wilk para decidir o caminho da análise.

5. Teste de Hipóteses e Modelagem 
* Com base nos objetivos (Etapa 1) e no diagnóstico (Etapa 4), selecionamos os testes estatísticos apropriados:
* Preciso comparar grupos? T-Test, ANOVA ou Mann-Whitney.
* Preciso ver a relação entre variáveis? Qui-Quadrado ou Correlação de Pearson/Spearman.
* Aplicação prática dos testes para validar ou refutar as hipóteses.

6. Interpretação e Comunicação dos Resultados
* O que os resultados dos testes significam em termos práticos e de negócio? 
* Tradução do "p-valor < 0.05" para "Sim, a campanha nova teve um efeito real e significativo nas vendas".
* Criação de um relatório, dashboard ou apresentação para comunicar as descobertas de forma clara para o público-alvo

