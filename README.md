# DadosSobreBancos

Objetivos:
-Avaliar a concentração das operações entre conglomerados financeiros.

-Identificar quais estados concentraram maior volume renegociado.

-Calcular tickets médios por banco e por estado.

-Detectar outliers na distribuição dos volumes.

-Analisar a evolução temporal das renegociações.

-Produzir visualizações para apoiar a interpretação dos resultados.

-Base de Dados

Os dados utilizados contêm informações sobre:

-Conglomerado financeiro responsável pela renegociação;

-Unidade da federação;

-Volume financeiro renegociado;

-Número de operações;

-Data-base das operações.

Tecnologias Utilizadas:

-Python

-Pandas

-NumPy

-Matplotlib

-Jupyter Notebook

Etapas da Análise:
1. Limpeza e Preparação dos Dados

Foram realizadas verificações de:

-Valores nulos;

-Registros duplicados;

-Conversão de variáveis numéricas.


Resultado:

-Nenhum valor nulo identificado;

-Nenhum registro duplicado encontrado.

2. Concentração por Instituição Financeira

-Foi calculado o volume total renegociado por conglomerado financeiro.

Principal resultado:
-Os cinco maiores conglomerados financeiros concentraram aproximadamente 69% do volume total renegociado, indicando forte concentração das operações em poucas instituições.

3. Distribuição Regional

-Foi analisado o volume renegociado por estado.

-Destaques:

Os estados do Sudeste apresentaram maior participação:

São Paulo
Rio de Janeiro
Minas Gerais

São Paulo lidera amplamente o volume renegociado.

4. Ticket Médio

O ticket médio foi calculado pela fórmula:

Ticket Medio = Volume Total/Número de Operações
	​


A análise foi realizada tanto para:

Bancos;
Estados.

Estados como Tocantins, Santa Catarina e São Paulo apresentaram alguns dos maiores tickets médios observados.

5. Análise Estatística

Foram calculadas medidas descritivas da distribuição dos volumes:

-Média;

-Mediana;

-Quartis;

-Assimetria;

-Curtose.

Conclusões:
-A distribuição apresenta forte assimetria positiva.

-Poucos bancos concentram volumes extremamente elevados.

-Existem outliers superiores relevantes.

6. Detecção de Outliers

Foi utilizado o método IQR (Intervalo Interquartil) para identificar instituições com comportamento excepcional.

Resultado:

-Não foram encontrados outliers inferiores.

-Foram identificados diversos outliers superiores, indicando elevada concentração do mercado.

7. Evolução Temporal

Foi construída uma série temporal do volume renegociado.

-Principais observações

-Pico inicial em setembro de 2023.

-Redução significativa nos meses seguintes.

-Recuperações pontuais ao longo de 2024, especialmente em agosto e dezembro.

-Visualizações Produzidas

O projeto inclui:

-Top 10 bancos por volume renegociado;

-Evolução temporal das renegociações;

-Participação percentual dos estados;

-Ranking dos estados por ticket médio;

-Histograma da distribuição dos volumes estaduais.

-Principais Conclusões

-O mercado de renegociação do Desenrola Brasil apresentou forte concentração bancária.

-Os cinco maiores conglomerados responderam por cerca de 69% do volume total.

-Estados do Sudeste concentraram grande parte das operações.

-A distribuição dos volumes apresenta assimetria elevada e presença de outliers.

-O programa teve maior intensidade nos primeiros meses de implementação, seguida por desaceleração e recuperações pontuais.
