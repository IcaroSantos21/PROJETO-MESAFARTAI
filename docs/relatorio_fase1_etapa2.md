# Relatório de execução
1.	Informe quantos número de árvores foram utilizados no motor NLU.
R: 80

2.	Informa qual o valor de threshold foi utilizado no processo de limiar de confiança
R: 0.60

3.	Coloque o resultado da primeira execução
R: Entrada: 'Tenho 30 kg de banana para doar'
   Intenção: cadastrar_doacao | Confiança: 0.93
   Retorno: Intenção 'cadastrar_doacao' identificada com 92.5% de confiança.

4.	Descreva como você poderia fazer para os resultados de testes serem melhores, aumento o grau de confiança dos resultados
R: Aumentar nossa base de treino

5.	Descreva por que o Random Forest foi o melhor método de Machine Learning para essa fase.
R: Ele usa 80 arvores para classificar a melhor intenção, e ve qual a maior média entre as 80
