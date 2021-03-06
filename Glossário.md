# Glossário

# Supervicionado

## Classificação

* *K-Nearest Neighbors* (kNN) (ou K-Vizinhos mais próximos) 

___

# Métricas

* **Matriz de confusão** é uma tabela que confrontra os valores reais com os preditos. <a href="https://pt.wikipedia.org/wiki/Matriz_de_confus%C3%A3o#:~:text=No%20campo%20do%20Aprendizado%20de,de%20um%20algoritmo%20de%20classifica%C3%A7%C3%A3o%20.">[ref.]</a>

* *Precision* é intuitivamente a capacidade do classificador de não rotular como **positiva** uma amostra **negativa**
  
  Precision = tp / (tp + fp)
    * tp é o verdadeiro positivo
    * fp é o falso positivo

* *Recall* é intuitivamente a capacidade do classificador de encontrar **todas** as amostras **positivas**.

  Recall = tp / (tp + fn)
    * tp é o verdadeiro positivo 
    * fn é o falso negativo

* *F1-Score* pode ser interpretada como uma média pondera da *precision* e *recall*, onde 1 é o melhor valor e 0 o pior valor.

  f1 = 2 * (precision * recall) / (precision + recall)

* *Support* é o número de cada classe no conjunto de teste, ou seja **y_test**.

* *Accuracy* é a quantidade de acerto frente o total de amostras.
