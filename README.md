# Desafio-Manipulae

No algoritmo escrito foi feito primeiro a aquisição dos dados para visualizar o formato da tabela e de suas colunas, onde foi verificado o tamanho do datasheet e o tipo de vairável de cada coluna.

Em seguida foi feito a adição de duas colunas na tabela para ajudar na previsão do valor correto, são essa a coluna CAP e a coluna diferença, a primeira é o unidade de volume e a segunda a diferença entre os preços calculados e correto.
A próxima parte foi checada a correlação entre as ultimas 4 colunas que são, qtdInsumos, calculado, correto, diferença e CAP. Nessa etapa foi observado o comportamento de variação das variáveis em relação a variação do preço correto, para seber se tinham uma correlação mínima para serem usadas.

As próximas etapas são a organização dos dados para treinar e validar os modelos de regressão para serem usados no final. A tabela foi separada em duas partes, onde foram usados 4000 dados para treino e validação e 3121 dados para prever o valor correto.

Foram testados três modelos de regressão, Regressão linear, Arvore de Decisão e Máquina de Vetor de Suporte Linear. O desempenho dos modelos foram apresentados em seguida, juntamente com uma tabela comparativa entre  valor correto os valores calculados pelos modelos e o valor calculado fornecido pelo datasheet.

Na parte final onde foi realizado a previsão das ultimas 3121 linhas foi feita a média da diferença dos dados de trerino, pois a coluna diferença foi escolhida para ser usada na previsão, também foi escolhido o modelo com mais precisão dentre os três citados. Após a previão foi exibido uma tabela comparativa com o valor correto, o valor calculado do modelo escolhido e o valor calculado do datasheet, para que a difernça possa ser vista, também foi mostrado um gráfico para melhor visualização dos resultados.
