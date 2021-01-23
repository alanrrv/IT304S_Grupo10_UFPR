# IT304S_Grupo10_UFPR
# Projeto de Migração para o Mercado Livre de Energia da Universidade Federal do Paraná - UFPR
Disciplina de Mestrado: IT304S - Contratação de Energia para Grandes Consumidores

Prof. Dr Luiz Carlos Pereira da Silva

# Estrutura de Arquivos e Pastas

Foi adotada a estrutura proposta pelo [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/). A estrutura geral é a seguinte e será detalhada a seguir:

~~~
├── README.md          <- apresentação do projeto
│
├── data
│   ├── external       <- dados de terceiros
│   ├── interim        <- dados intermediários, e.g., resultado de transformação
│   ├── processed      <- dados finais usados para a modelagem
│   └── raw            <- dados originais sem modificações
│
├── notebooks          <- Jupyter notebooks ou equivalentes
│
├── src                <- fonte em linguagem de programação ou sistema (e.g., Orange)
│   └── README.md      <- instruções básicas de instalação/execução
│
└── assets             <- mídias usadas no projeto
~~~

O arquivo `README.md` contém a apresentação do projeto.

## `data`

Dados utilizados no projeto respeitadas as implicações éticas.

Foram mantidos os dados originais para garantir a reprodutibilidade do processo. Os originais foram colocados na subpasta `raw`. Na subpasta `external` estão os dados de terceiros. Dados intermediários (por exemplo, dados tratados, resumidos etc.) estão na pasta `interim`. Os dados finais que serviram de entrada para as análises estão na subpasta `processed`.

## `notebooks`

Código do projeto que pode ser executado online sem instalação de software, tal como um notebook em Jupyter.

## `src`

Código em alguma linguagem ou projeto em Orange, Weka e similares.

Se for código em linguagem de programação, tente organizá-lo de forma que seja simples a sua execução por terceiros, por exemplo, acrescente as bibliotecas necessárias etc. Acrescente na raiz um arquivo `README.md` com as instruções básicas de instalação e execução.

## `assets`

Qualquer mídia usada no projeto: vídeo, ilustrações, arquivos PDF, etc.


# Projeto Migração para o Mercado Livre de Energia da Universidade Federal do Paraná - UFPR
Project Migration to the Free Energy Market of Federal University of Paraná - UFPR

# Descrição Resumida do Projeto

As 5 unidades consumidoras que mais consomem energia da UFPR foram selecionadas com intuito de realizar análise de viabilidade econômica para migração destas unidades para o Mercado Livre de Energia, haja vista estas unidades serem elegíveis para a migração de acordo com a legislação em vigor.
As contratações de energia no mercado livre tem demonstrado vantagem financeira perante as contratações no mercado regulado. O projeto alcançou projeções de economia na ordem de 10 a 30% com a migração quando comparado a contratação atual no mercado regulado.

# Abstract

The 5 consumer units that most consume energy from UFPR were selected in order to carry out an economic feasibility analysis for the migration of these units to the Free Energy Market, since these units are eligible for migration according to the legislation in force.
Energy contracting in the free market has demonstrated a financial advantage over contracting in the regulated market. The project achieved projections of savings in the order of 10 to 30% with migration when compared to the current contract in the regulated market.


# Equipe
* `Alan Ramos Rodrigues do Vale - RA 233136`
* `Diogo Schuarz - RA 159671`
* `Henrique Carvalho - 233203`
* `Rafael Augusto de Godoy Rosolen - RA 261565`

# Vídeo do Projeto
`<coloque um link para o vídeo apresentado o projeto.>`

# Introdução e Motivação

O Mercado Livre de Energia tem se tornado atrativo para consumidores de energia de médio e grande porte como é o caso da maioria das universidades públicas do país. A adesão ao Mercado Livre (ML) possibilita alcançar reduções de até 30% nas faturas de energia.

A Universidade Federal do Paraná - UFPR com somatório de Demanda Contratada acima de 3.000kW é elegível para acessar o mercado livre há anos. Até 2019, clientes com demanda contratada maior ou igual a 3.000kW eram elegíveis para a migração e a partir de Jan/2021, de acordo com a Portaria 465/2019 do Ministério de Minas e Energia, consumidores com demanda mínima contratada de 1.500kW passam a ser elegíveis a migrar para o Mercado Livre.

Até 1995 o mercado de energia no Brasil era basicamente estatal. A expansão do sistema necessitava de investimento público, ocorriam paralisações em obras, tarifas defasadas e os investimentos eram insuficientes. Entre 1995 e 2001 o governo federal realizou privatizações no setor elétrico, criou instituições como ANEEL, ONS, CCEE entre outras que viabilizaram a partir de 2001 a adoção de ambientes de contratação de energia que podem ser regulado (ACR) com agentes de geração e de distribuição de energia ou livre (ACL) com geradores, distribuidores, comercializadores, importadores e exportadores, além dos consumidores livres e especiais. Há ainda o mercado de curto prazo, também conhecido como mercado de diferenças, no qual se promove o ajuste entre os volumes contratados e os volumes medidos de energia.

A UFPR apresenta um gasto com energia elétrica na ordem de dezenas de milhões de reais e este projeto pretente demonstrar a viabilidade em migrar para o Mercado Livre de Energia e os valores que poderão ser economizados no futuro.


## Perguntas de Pesquisa

1. Qual é a universidade pesquisada? Onde fica? Quantos alunos? Qual grupo de consumidores esta universidade está inserida?

2. Qualidade dos dados: há dados faltantes? Há consumo atípico em algum mês?

3. Análise de Demanda: a Demanda Contratada está adequada? Qual deveria ser a demanda?

4. Análise de Reativos: Há excesso de reativos? É necessário fazer correção do fator de potência da instalação?

5. Existe tendência de crescimento no consumo de energia? E na Demanda Registrada?

6. Gráficos com Demanda Contratada, Demanda Registrada, Consumo de Energia, etc.;

7. Outras análises que os alunos considerem pertinentes.

8. Vale a pena migrar para o Mercado Livre? Como consumidor livre ou especial?

9. Qual é a economia estimada?

10. Qual é o preço da energia a partir de quando compensa a migração?

11. Qual a recomendação para uma contratação? (Características de contrato como volume, flexibilidade, modulação, sazonalização)

12. Outras análises

## Objetivos do projeto

O projeto pretende apresentar os valores da economia estimada ao migrar as unidades consumidoras escolhidas para o mercado livre de energia realizando previsões de consumo, demanda e valor da tarifa, simulando os custos de faturas de energia elétrica para os próximos 2 anos.

# Recursos e Métodos

## Bases de Dados

Base de Dados | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Base 1 | https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/external/PLD_CCEE_HISTORICO.xlsx | Dados históricos do PLD na CCEE
Base 2 | https://github.com/alanrrv/IT304S_Grupo10_UFPR/tree/main/data/interim | Dados alterados para transformação
Base 3 | https://github.com/alanrrv/IT304S_Grupo10_UFPR/tree/main/data/processed/CONSUMO_2021.xlsx | Dados de consumo processados
Base 4 | https://github.com/alanrrv/IT304S_Grupo10_UFPR/tree/main/data/processed/DEMANDA_PONTA_2021.xlsx | Dados de Demanda processados
Base 5 | https://github.com/alanrrv/IT304S_Grupo10_UFPR/tree/main/data/processed/PLD_2021.xlsx | Dados de PLD processados


## Ferramentas

Ferramenta | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Ferramenta 1 | https://www.statsmodels.org/stable/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html | Previsão de séries temporais com uso de SARIMAX

# Metodologia

A metodologia aplicada neste projeto foi o modelo de aprendizado de máquina chamado ARIMA (Autoregressive Integrated Moving Average Model). Após identificar a existência de sazonalidade nos dados, indenficou-se a oportunidade de aplicar uma variante do ARIMA, o SARIMAX (Seasonal Autoregressive Integrated Moving Average with external variables). Nessa variante do ARIMA, o modelo de aprendizagem de máquina foca em identificar sazonalidades anteriores e projetar no futuro.

O intuito foi validar aplicação de um Modelo ARIMA na projeção da Demanda Ponta e Fora Ponta, Consumo e para o PLD Médio histórico. Para isso, o primeiro passo é decomposição dos dados em três parcelas, sendo elas a Tendência, Sazonalidade e Resíduos. 

~~~
from pylab import rcParams
rcParams['figure.figsize'] = 18, 8
decomposition = sm.tsa.seasonal_decompose(df_input, model='additive')
fig = decomposition.plot()
plt.show()
~~~

![alt text](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/Decomposicao_curva_consumo.png)

Após notar com clareza a existência da sazonalidade, validou-se a oportunidade de uso do modelo SARIMAX utilizando a variável em questão. É importante buscar os parâmetros para o modelo, para entender de forma mais profunda o que são esses parâmetros, recomenda-se a leitura do artigo a seguir:

https://www.statsmodels.org/stable/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html

Para encontrar esses ajustes dos parâmetros, ou pelo menos aqueles parâmetros que seriam os melhores para calcular, é necessário testar hipóteses. Para isso, utilizou-se uma rotina de cálculo com base no AIC (Akaike Information Critera), esse critério passa basicamente uma ideia geral de ajuste das projeções com base no histórico de dados. Para entender mais afundo o Akaike Information Critera na avaliação e as possibilides que podem ser exploradas com suas variantes próximas, recomenda-se a leitura a seguir:

https://www.researchgate.net/figure/Goodness-of-fit-criteria-AIC-AICC-BIC-for-ARIMA-models_tbl1_330721947

Compreendido a necessidade pela busca de um parâmetro ótimo que aponte para um bom ajuste das projeções ao histórico de dados, implementou-se a rotina a seguir e buscou os dados que apresentavam o menor critério AIC, para determinada parametrização do SARIMAX.

~~~
df = pd.DataFrame(columns=['PARAMETER(Y0,Y1,Y2)','PARAM_SEASON(Y0,Y1,Y2,12)','AIC'])

for param in pdq:
    for param_seasonal in seasonal_pdq:
        try:
            mod = sm.tsa.statespace.SARIMAX(df_input,
                                            order=param,
                                            seasonal_order=param_seasonal,
                                            enforce_stationarity=False,
                                            enforce_invertibility=False)
            results = mod.fit()

            df = df.append({'PARAMETER(Y0,Y1,Y2)': param,
                            'PARAM_SEASON(Y0,Y1,Y2,12)': param_seasonal,
                            'AIC': results.aic},
                            ignore_index=True)
            
        except:
            continue
 

df.sort_values('AIC')
~~~

![alt text](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/parametros_SARIMAX.jpeg)

A partir dessa rotina, escolheu-se os parametrox 	(1, 1, 0)x(1, 1, 0, 12) pois eram aqueles que possuiam o menor AIC calculado. Com isso realizado um diagnóstico do modelo obtido.

~~~
results.plot_diagnostics(figsize=(16, 8), lags=8)
plt.show()
~~~

![alt text](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/diagnosticos.jpeg)

Com base neste diagnóstico foi possível constatar que os possuem resíduos que variam de aproximadamente -1.5 até 1, possuem uma distribuição que pode ser aproximado normal e por fim seu correlograma indica que Março e Julho seriam os meses com maior tendencia de sazonalidade. Com essa constatação, validou-se os dados projetados a partir dos dados históricos.

~~~
pred = results.get_prediction(start=pd.to_datetime('2019-01-01'), dynamic=False)
pred_ci = pred.conf_int()
ax = df_input['2015':].plot(label='Observado')
pred.predicted_mean.plot(ax=ax, label='Projeção com um passo a frente', alpha=.7, figsize=(14, 7))
ax.fill_between(pred_ci.index,
                pred_ci.iloc[:, 0],
                pred_ci.iloc[:, 1], color='k', alpha=.2)
ax.set_xlabel('Data')
ax.set_ylabel('Consumo [kWh]')
plt.legend()
plt.show()
~~~

![alt text](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/validacao.jpeg)

A partir dessa validação foi possível observar uma tendência inicial dos dados em não convergir e causar erros elevados, porém o final da validação já indicava tendência de excesso de ajuste, o que poderia viciar a projeção. Ainda assim, com um cenário aberto buscamos verificar o comportamento final das projeções.

~~~

pred_uc = results.get_forecast(steps=24)
pred_ci = pred_uc.conf_int()
ax = df_input_orig.plot(label='Observado', figsize=(14, 7))
pred_uc.predicted_mean.plot(ax=ax, label='Projeção')
ax.fill_between(pred_ci.index,
                pred_ci.iloc[:, 0],
                pred_ci.iloc[:, 1], color='k', alpha=.25)
                #39, color='k', alpha=.25)
ax.set_title('Projeção com método ARIMA para Consumo 2021', fontsize = 30)
ax.set_xlabel('Data')
ax.set_ylabel('Consumo Total [kWh]')
plt.legend()
plt.show()
~~~

![alt text](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/projecao_2021.jpeg)

Visto a quantidade de dados utilizada para projeção foi pequena, validou-se por meio do teste final ds projeções que o modelo SARIMAX seria uma boa tentativa para explorar outras váriáveis.

## Detalhamento do Projeto

Foram analisados dados de Consumo, Demanda e PLD. A projeção desses valores é fundamental para calcular a previsão de gastos com as faturas de energia. Segue parte do código usado para prever o preço do PLD até 2022:

Projeção do PLD até 2022
---
~~~python
pred_uc = results.get_forecast(steps=36)
pred_ci = pred_uc.conf_int()
ax = df_input_orig['2017':].plot(label='Observado', figsize=(14, 7))
pred_uc.predicted_mean.plot(ax=ax, label='Projeção')
ax.fill_between(pred_ci.index,
                pred_ci.iloc[:, 1],
                39, color='k', alpha=.25)

ax.set_title('Projeção com método ARIMA para a média do PLD até 2022', fontsize = 30)
ax.set_xlabel('Data')
ax.set_ylabel('Preço médio PLD [R$]')
plt.legend()
plt.show()
~~~

![alt text](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/Previsao_PLD.png)

Código Completo
----

https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/notebooks/IT304S_GRUPO_10.ipynb


## Evolução do Projeto

Iniciamos considerando a análise de dados de 2 anos, porém, o modelo ARIMA utilizado para realizar as previsões de Demanda(kW), Consumo(kWh) e Tarifa de Energia (R$) não se comportou como esperado. Consideramos que a baixa quantidade de dados impactou significativamente as previsões, já que quando separamos em torno de 70% dos dados para treino e 30% para teste, não houve uma definição clara da sazonalidade e tendência, parâmetros estes relevantes para o ARIMA.
Após isso, decidimos inserir mais 12 meses de dados para todas as unidades consumidoras, ficando 24 para dados de treino e 12 meses para teste.

# Resultados e Discussão
~~~
<Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de detalhamento do projeto (o que for mais pertinente).

A discussão dos resultados também pode ser feita aqui na medida em que os resultados são apresentados ou em seção independente. Aspectos importantes a serem discutidos: É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?>
~~~

1. Qual é a universidade pesquisada? Onde fica? Quantos alunos? Qual grupo de consumidores esta universidade está inserida?

A UNIVERSIDADE FEDERAL DO PARANÁ - UFPR, localizada no estado do Paraná, possui 164 cursos de graduação, 45 cursos de especialização, 89 mestrados e 61 doutorados. São quase 28 mil estudantes da graduação, e outros 6,2 mil da pós-graduação.
Fonte: <https://g1.globo.com/pr/parana/educacao/noticia/2019/09/26/mais-de-34-mil-alunos-da-ufpr-podem-ficar-sem-aulas-ainda-neste-ano-diz-instituicao.ghtml>.

Possui um gasto mensal médio de energia na ordem de R$1 milhão considerando todas as suas Unidades Consumidoras atendidas pela distribuidora COPEL. Suas unidades estão inseridas no Grupo A4 (13,8kV) e B. Das  Unidades Consumidoras da UFPR, consideramos trabalhar com as 5 listadas abaixo:


UC | Nome do Campus | Distribuidora | Subgrupo | Endereço
------ | -------------------- | ----- | --- | ------------------------------
19450729 | CENTRO POLITÉCNICO - UFPR | COPEL |  A4 | RODOVIA BR 116 - JARDIM DAS AMÉRICAS - CURITIBA - PR
44895780 | SUBSEDE DA SAÚDE - UFPR | COPEL | A4 | AV. PREF LOTHARIO MEISSNER, 632 - J. BOTANICO - CURITIBA - PR - CEP 80210-170
1936905 | SETOR DE CIENCIAS AGRARIAS - UFPR | COPEL | A4 |R JAIME BALAO, 675 - HUGO LANGE - CURITIBA - PR - CEP: 80040-340
79888534 | PALOTINA - UFPR | COPEL | A4 | R PIONEIRO, 2153 - DALLAS - PALOTINA - PR - CEP: 85950-000
44860480 | SETOR DE CIENCIAS DA SAUDE - UFPR | COPEL | A4 | R PE CAMARGO, 280 - ALTO DA GLORIA - CURITIBA - PR - CEP: 80060-240


2. Qualidade dos dados: há dados faltantes? Há consumo atípico em algum mês?

Não há dados faltantes. O consumo atípico ocorre a partir de Abril/2020 devido a pandemia do COVID-19.
Devido este padrão verificado neste relatório será avaliado o uso de dados anteriores, ainda focando no uso de dados referentes a um período de 36 meses, visto que é possível identificar a sazonalidade.


3. Análise de Demanda: a Demanda Contratada está adequada? Qual deveria ser a demanda?

Tabela 1 - Análise da demanda contratada comparada com a demanda registrada

UC | Demanda Média Contratada (kW)* | Demanda Faturada (kW) | Adequada? | Demanda Ajustada (kW)
-- | ---- | ---- | ---- | -----
1 | 1882 | 2100 | Não | 2000
2 | 442 | 220 | Não | 480
3 | 338 | 380 | Sim | N/A
4 | 373 | 500 | Não | 425
5 | 117 | 130 | Sim | N/A

*Excluiram-se os meses de pandemia.

Portanto, verfica-se que das 5 unidades consumidoras avaliadas, 3 necessitam de ajustes na demanda.

4. Análise de Reativos: Há excesso de reativos? É necessário fazer correção do fator de potência da instalação?


UC |  DEMANDA MÉDIA REATIVA PONTA [KVAR] | DEMANDA MÉDIA REATIVA FORA PONTA [KVAR]
-- | --------------- | -----------
1 |  37,21 | 333,50
2 | 515,08 | 6703,83
3 | 418,00 | 2654,71
4 | 338,21 | 3107,79
5 | 0,04 | 0,00

Com exceção da UC 5, todas as outras necessitam fazer correção do fator de potência por excesso de reativos.


5. Existe tendência de crescimento no consumo de energia? E na Demanda Registrada?

Não há uma tendência clara para as Unidades Consumidoras estudadas. No entanto, temos uma expectativa pelo aumento tanto no Consumo quanto na Demanda Registrada para os próximos meses, haja vista a redução abrupta ocorrida desde abril/2020 devido à pandemia nas UCs 2, 3, 4 e 5, e novas tecnologias e equipamentos que podem vir a ser instalados no campus. 
Notícias divulgadas recentemente apresentaram o projeto da usina fotovoltaica construída na UC1, portanto neste caso específico a expectativa é de redução do consumo.
Fonte: https://www.ufpr.br/portalufpr/noticias/ufpr-inaugura-nesta-sexta-feira-a-maior-usina-fotovoltaica-em-universidade-publica-do-brasil/


6. Gráficos com Demanda, Consumo de Energia.

Demanda Registrada
---
![alt text](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/Demanda_Registrada.png)

Consumo Registrado
---
![alt_texte](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/Consumo_registrado.png)

PLD Histórico
---
![alt_texte](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/PLD_historico.png)


7. Outras análises que os alunos considerem pertinentes.

As Unidades Consumidoras escolhidas representam juntas mais de 50% de todo consumo da UFPR consolidado.


8. Vale a pena migrar para o Mercado Livre? Como consumidor livre ou especial?

Considerando uma economia estimada em torno de 10% somente considerando a média 


9. Qual é a economia estimada?

A economia estimada, calculada como sendo a diferença entre a fatura das UCs no Mercado Livre e no Mercado Regulado, é em torno de 11% com base na média do histórico, podendo ser otimizada capturando sazonalidade na contração de energia.


10. Qual é o preço da energia a partir de quando compensa a migração?

Inicialmente definiremos o conceito de Taxa Interna de Retorno (TIR). É a taxa de desconto que torna o Valor Atual Líquido do investimento igual a zero ao final do horizonte de planejamento do investimento a ser analisado. A TIR é uma técnica sofisticada de análise de investimentos sendo possivelmente a mais utilizada na avaliação de projetos econômicos. Essa Taxa Interna de Retorno deve ser comparada com a outra caixa denominada Taxa Mínima de Atratividade (TMA) (REBELATTO, Daisy Aparecida Do Nascimento. Projeto de investimento: Com estudo de caso completo na área de serviços. 1 ed. Barueri/SP: Editora Manole Ltda, 2004).

O critério para aceitação ou não de um projeto no que se refere a Taxa Interna de Retorno é a comparação com a Taxa Mínima de Atratividade. Se a mesma for maior do que a TMA se aceita o projeto, ao passo que se esta for menor que a TMA se rejeita o projeto. Este critério de análise de investimento determina ser inviável um projeto cujo Taxa Interna de Retorno não seja superior a Taxa Mínima de Atratividade.

Contudo é não há como estipularmos uma TMA para a UFPR pois desconhecemos o Custo de Oportunidade dos projetos que esta instituição possui como alternativas concorrentes à presente proposta de investimento. Por isso, apresentaremos a TIR deste projeto para três prazos distintos (1 ano, 3 anos e 15 anos) de modo que seja fácil para a instituição, que conhece bem sua própria TMA, avaliar a atratividade financeira da migração para o ACL.

Considerando as projeções apresentadas anteriormente no desenvolvimento do item Metodologia acima, estimou-se para o ano de 2020 (com base no histórico dos dados de 2017 a 2019) as faturas das 5 Unidades Consumidoras mais representativas da UFPR nos cenários de manuntenção de seus contratos no ACR e migrando para o ACL nas categorias de contratação Convencional, Incentivada 50% e Incentivada 100%. 

Para cada categoria calculou-se a TIR no horizonte de investimentos de 1 ano, 3 anos e 15 anos tendo como receita (saving) a diferença entre a fatura das UCs no Mercado Livre e no Mercado Regulado. Em contrapartida, os custos modelados foram os referentes à Migração, Emolumento Adesão CCEE, Contribuição Associativa CCEE e Custo de Gestão. No longo prazo também se projetou um crescimento do preço da energia acima da Inflação (crescimento real) pois esta foi a realidade do setor brasileiro historicamente.  

![alt_texte](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/retorno_investimento.jpeg)

Do fluxo de caixa fica evitente que os retornos projetados superam em muito o investimento despendido para a migração das 5 UCs. Este cenário, não usual nos investimentos tradicionais, gera uma TIR notadamente grande para todos os horizontes de investimento.

 TIR | 15 anos	| 3 anos | 1 ano
--- | ----- | ---- | ----
TIR ACL - Conv	| 645,93%	| 644,27%	| 543,84%
TIR ACL - I5	| 586,76%	| 584,81%	| 484,42%
TIR ACL - I1	| 834,81%	| 833,72%	| 732,57%

Desta maneira, foi feita uma análise de sensibilidade no modelo para identificar a partir de qual valor de energia o fluxo de caixa anual se aproximaria de zero (savings e custos se anulariam). Este valor foi encontrado como sendo R$ 311,50 / MWh, qualquer valor mais barato do que este é entendido como sendo positivo para a migração das UCs. 

11. Qual a recomendação para uma contratação? (Características de contrato como volume, flexibilidade, modulação, sazonalização)

Quando consdierado contratação no mercado de longo prazo, a economia utilizando a média histórica fica em torno de 10% e há redução de custo com gestão de contrato. Deverá ser sazonal (20%), de acordo com o apetite ao risco do mercado curto prazo. Uso de licitação (30%), compra de energia mais em conta.


Projeção da contratação de Demanda
---
![alt_texte](https://github.com/alanrrv/IT304S_Grupo10_UFPR/blob/main/data/images/orientacao_demanda_fora_ponta.jpeg)

Adicionalmente, conforme detalhado na resposta à décima pergunta, recomenda-se uma contratação no ACL a valores menores do que R$ 311,50 / MWh.

Quanto a demanda contratada Fora Ponta, com uso das projeções realizadas pelo modelo SARIMAX fica clara a tendência de redução do consumo para os próximos ciclos, de forma que manter a contratação como está até o presente momento, seria a orientação mais indicada para o futuro.

# Conclusões

O modelo de AutoRegressive Integrated Moving Average (ARIMA) apresentou um comportamento adequado quando utilizado na projeção do PLD. Embora apresente valores mínimos inferiores 0 e que assim seriam inferiores ao piso do PLD para o período, o algoritmo foi capaz de compreender a existência de uma faixa onde a grandeza permanece variando. A capacidade de identificar esse comportamento é algo positivo e importante para previsão dos preços em um horizonte de curto a médio prazo.

Para as grandezas avaliadas Consumo Total, Demanda Ponta e Demanda Fora Ponta, o modelo ARIMA conseguiu apresentar uma previsão pelo menos razoável, podendo fornecer insumos para contratação de energia como janelas de sazonalidade de consumo elevado e consumo baixo, o mesmo se aplica para demanda.

Ainda assim, o modelo ARIMA não conseguiu apresentar uma convergência para os valores máximos e mínimos das grandezas Consumo Total, Demanda Ponta e Demanda Fora Ponta. Este ponto pode ser melhorado utilizando outros métodos de projeção, um ínicio seria utilizando o modelo Prophet do Facebook, pois é um modelo capaz de capturar com facilidade sazonalidades. No entanto, sua aplicação neste caso precisa ser melhor avaliada, pois o Prophet é um modelo preparado para receber Big Data, algo que pode não compreender muito bem se tiver poucos dados.

# Trabalhos Futuros

Desenvolver métodos para contratar energia no Mercado Livre em órgãos públicos sob a ótica da Lei das Licitações - Lei 8.666/1993, considerando alguns aspectos como tempestividade de processos licitatórios, prestação de garantias, entre outros.
