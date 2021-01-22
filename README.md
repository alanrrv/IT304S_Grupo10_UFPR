# IT304S_Grupo10_UFPR
Projeto de Migração para o Mercado Livre de Energia da Universidade Federal do Paraná - UFPR

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

# Modelo para Apresentação do Projeto

Este é um guia de como produzir documentação em Markdown. Para entender como criar documentos em Markdown no Github, veja o material/vídeo:
[Guia de Uso do Markdown](https://github.com/mc-unicamp/oficinas/tree/master/docs).

Vide detalhes sobre o Markdown em: [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).

E mais especificamente sobre tabelas em: [Organizing information with tables](https://help.github.com/en/articles/organizing-information-with-tables)

O projeto pode ser apresentado em uma das possíveis formas:
1. texto completo no arquivo `README.md`;
2. texto no arquivo `README.md` e seção de Resultados e Discussão dentro de um notebook Jupyter ou equivalente -- nesse caso, deve haver um link para se abrir o notebook na respectiva seção;
3. texto completo dentro de um notebook Jupyter ou equivalente -- nesse caso, o arquivo README.md deve conter pelo menos: o título, os componentes da equipe e um link para o notebook.

Só será aceito o uso de notebook Jupyter (ou equivalente) para apresentação do projeto ou parte dele (formas 2 e 3), se for possível executá-lo online a partir de um link sem instalação local de software.

Para todos os casos, a estrutura Markdown proposta abaixo poderá ser usada, dado que os notebooks aceitam Markdown.

Segue abaixo o modelo de como deve ser apresentado e documentado o projeto. Tudo o que for indicado entre `<...>` indica algo que deve ser substituído pelo indicado. No modelo são colocados exemplos ilustrativos, que serão substituídos pelos do seu projeto.

# Modelo para Apresentação do Projeto

# Projeto `Migração para o Mercado Livre de Energia da Universidade Federal do Paraná - UFPR`
# Project `<Title in English>`

# Descrição Resumida do Projeto
~~~
<Descreva resumidamente o que fará o projeto. O resumo idealmente deve: apresentar o contexto; indicar o problema; apresentar a sua solução para o problema; indicar porque a sua solução é melhor do que os esforços atuais (não obrigatório); concluir com os resultados alcançados.>
~~~

Foram selecionadas as 5 unidades consumidoras que mais consomem energia da UFPR com intuito de realizar análise de viabilidade econômica para migração destas unidades para o Mercado Livre de Energia, haja vista estas unidades serem elegíveis para a migração.
As contratações de energia no mercado livre tem demonstrado vantagem financeira perante as contratações no mercado regulado.


# Abstract in English
~~~
<English version of the abstract.>
~~~

# Equipe
* `Alan Ramos Rodrigues do Vale` - `233136`
* `Diogo Schuarz` - `<RA>`
* `Henrique` - `<RA>`
* `Rafael Rosolen` - `<RA>`

# Vídeo do Projeto
`<coloque um link para o vídeo apresentado o projeto.>`

# Introdução e Motivação
~~~
<Descrição do tema do projeto, incluindo motivação, contexto gerador e caracterização do problema. A introdução também pode apresentar iniciativas correlatas para lidar com o problema (não obrigatório) e deve introduzir de forma mais detalhada que o resumo a solução proposta e resultados alcançados. Aqui também são apresentadas as seções do projeto.>
~~~

## Perguntas de Pesquisa
~~~
<Perguntas de pesquisa que o projeto pretende responder ou hipóteses a serem avaliadas, enunciadas de maneira objetiva e verificável.>

1. Qual é a sua universidade? Onde fica? Quantos alunos? Qual grupo de consumidores esta universidade está inserida?

2. Qualidade dos dados: há dados faltantes? Há consumo atípico em algum mês?

3. Análise de Demanda: a Demanda Contratada está adequada? Qual deveria ser a demanda?

4. Análise de Reativos: Há excesso de reativos? É necessário fazer correção do fator de potência da instalação?

5. Existe tendência de crescimento no consumo de energia? E na Demanda Registrada?

6. Gráficos com Demanda Contratada, Demanda Registrada, Consumo de Energia, etc.;

7. Outras análises que os alunos considerem pertinentes.

8. Vale a pena migrar para o Mercado Livre? Como consumidor livre ou especial?

9. Qual é a economia estimada?

10. Qual é o preço da energia a partir de quando compensa a migração?

11. Qual a recomendação para uma contratação? (Características de contrato
como volume, flexibilidade, modulação, sazonalização)

12. Outras análises

~~~

## Objetivos do projeto
~~~
<Como seu projeto propôs abordar o problema apresentado.>
O projeto pretende apresentar os valores da economia estimada ao migrar as unidades consumidoras escolhidas para o mercado livre de energia realizando previsões de consumo, demanda e valor da tarifa, simulando os custos de faturas de energia para os próximos 2 anos.

~~~

# Recursos e Métodos

## Bases de Dados
`<Elencar bases de dados utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Base de Dados | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Base 1 | http://base1.org/ | `<Descrição da Base 1 e para que ela foi usada no projeto.>`
Base 2 | http://base2.org/ | `<Descrição da Base 2 e para que ela foi usada no projeto.>`

## Ferramentas

`<Elencar ferramentas utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Ferramenta | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Ferramenta 1 | http://ferramenta1.org/ | `<Descrição da Ferramenta 1 e para que ela foi usada no projeto.>`
Ferramenta 2 | http://ferramenta2.org/ | `<Descrição da Ferramenta 2 e para que ela foi usada no projeto.>`

# Metodologia
~~~
<Abordagem/metodologia adotada, incluindo especificação de quais técnicas foram exploradas, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas.>
~~~



## Detalhamento do Projeto
~~~
<Apresente aqui detalhes da análise. Nesta seção ou na seção de Resultados podem aparecer destaques de código como indicado a seguir. Note que foi usada uma técnica de highlight de código, que envolve colocar o nome da linguagem na abertura de um trecho com `~~~`, tal como `~~~python`.

Os destaques de código devem ser trechos pequenos de poucas linhas, que estejam diretamente ligados a alguma explicação. Não utilize trechos extensos de código. Se algum código funcionar online (tal como um Jupyter Notebook), aqui pode haver links. No caso do Jupyter, preferencialmente para o Binder abrindo diretamente o notebook em questão.>
~~~

~~~python
df = pd.read_excel("/content/drive/My Drive/Colab Notebooks/dataset.xlsx");
sns.set(color_codes=True);
sns.distplot(df.Hemoglobin);
plt.show();
~~~

## Evolução do Projeto
~~~
<Relate a evolução do projeto: possíveis problemas enfrentados e possíveis mudanças de trajetória. Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.>
~~~

# Resultados e Discussão
~~~
<Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de detalhamento do projeto (o que for mais pertinente).

A discussão dos resultados também pode ser feita aqui na medida em que os resultados são apresentados ou em seção independente. Aspectos importantes a serem discutidos: É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?>
~~~



# Conclusões
~~~
<Apresente aqui as conclusões finais do trabalho e as lições aprendidas.>
~~~

# Trabalhos Futuros
~~~
<Indique trabalhos futuros a partir do ponto alcançado.>
~~~

