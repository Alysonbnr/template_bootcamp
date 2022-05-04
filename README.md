# Raíz do projeto
### Orientações :

Os arquivos .py devem realizar a chamada de uma única função que executa todo o pipiline proposto de cada projeto.
A pasta src deve conter as funções e implementações dos pipilines. 
Todas as funções devem ser documentadas explicando
qual a finalidade desta, o que significam os argumentos de entrada, se houver, e o retorno.

#### nlp

A pasta nlp contem as funções e pipilines exclusivos para nlp e nenhuma outra categoria


#### vc

A pasta nlp contem as funções e pipilines exclusivos para processamento digital de imagens(pdi) e machine learning e nenhuma outra categoria.
Funções que manipulam imagens (pré-processamento, segmentção..) são definidas e implementadas nesse .py.
Funções que utilizam classificadores, treinamento, normalização de dados e outras técnicas relacioanadas com machine learning
devem ser implementadas em machine_learning.py.


#### utils

Funções que são genéricas de entrada de arquivos, para mostrar gráficos, leitura de arquivos, escrita devem ser implementadas dentro  da pasta utils.
Neste caso é possivel subcategorizar se necessário, criando mais arquivos .py para alguma categoria específica dentro da pasta utils, por exemplo, arquivo .py destiado exclusivo para implementações de funções de leitura e escrita de arquivos.


