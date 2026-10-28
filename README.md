Análise de Viagens de Táxi em Chicago

Descrição do projeto

Este projeto analisa dados de corridas de táxi em Chicago, com o objetivo de identificar padrões de demanda, comparar o desempenho das empresas de táxi e investigar a influência das condições climáticas na duração das viagens.

A análise contempla o número de corridas por empresa, os bairros de destino mais frequentes e um teste de hipótese sobre a duração das viagens entre o Loop e o Aeroporto Internacional O’Hare em sábados chuvosos e não chuvosos.

Objetivos

* Identificar as empresas de táxi com maior número de corridas.
* Analisar os bairros de destino com maior média de viagens.
* Explorar a distribuição da demanda de transporte na cidade.
* Investigar se as condições climáticas influenciam a duração das viagens.
* Aplicar testes estatísticos para avaliar diferenças entre grupos.

Ferramentas e tecnologias

* Python
* Pandas
* Matplotlib
* SciPy
* Jupyter Notebook

Etapas da análise

1. Carregamento e exploração inicial dos dados.
2. Análise do número de corridas por empresa de táxi.
3. Identificação dos dez principais bairros de destino por média de viagens.
4. Criação de visualizações para comparar empresas e destinos.
5. Preparação dos dados de viagens, incluindo a conversão de datas e a identificação dos sábados.
6. Separação das viagens de acordo com as condições climáticas.
7. Aplicação do teste de Levene para avaliar a igualdade das variâncias.
8. Aplicação de um teste t para amostras independentes para investigar diferenças na duração média das viagens.

Principais questões investigadas

* Quais empresas de táxi apresentam o maior número de corridas?
* Quais bairros de Chicago são os destinos mais frequentes?
* A duração média das viagens entre o Loop e o Aeroporto Internacional O’Hare difere entre sábados chuvosos e não chuvosos?

Teste de hipótese

O projeto investiga a seguinte hipótese:

* Hipótese nula (H₀): a duração média das viagens entre o Loop e o Aeroporto Internacional O’Hare é igual em sábados chuvosos e não chuvosos.
* Hipótese alternativa (H₁): a duração média das viagens é diferente entre esses dois grupos.

Foi adotado um nível de significância de 5% (α = 0,05). O teste t para amostras independentes foi utilizado para comparar as médias dos grupos, considerando a independência das observações e a avaliação das variâncias.

Resultados e conclusão

A análise exploratória evidencia diferenças na distribuição das corridas entre as empresas de táxi e na frequência de destinos em Chicago.

Na análise das condições climáticas, o resultado registrado no notebook apresenta um valor-p inferior a 0,05. Esse resultado fornece evidências estatísticas de uma diferença na duração média das viagens entre sábados chuvosos e não chuvosos, levando à rejeição da hipótese nula.

Arquivo do projeto

* Sprint 7(1).ipynb — notebook com a exploração dos dados, visualizações e testes estatísticos.

Autora

Déborah Villar

Projeto desenvolvido durante a formação em Análise de Dados da TripleTen.
