## Checking for acyclicity
Определить, является ли граф ацикличным.
Метод решения: поиск в глубину

# Файл входных данных
Граф, заданный матрицей смежности. <br>
N - количество вершин в графе. <br>
Далее построчно расположена матрица смежности размерности N x N. <br>

#Пример. Для графа

    1 -- 2    4
    |    |    |
    + -- 3 -- +

файл данных должен быть следующим:

    4
    0 1 1 0
    1 0 1 0
    1 1 0 1
    0 0 1 0
  
# Файл результатов
Если граф ацикличен, то в файл результатов необходимо записать "A"(латинское). <br>
Иначе "N" и далее вершины входящие в первый найденный цикл. Вершины в цикле должны юыть упорядочены по возрастанию <br>
номеров. <br>

Для примера, приведенного в описании файла исходных данных, файл результатов должен быть следующим :

    N
    [1, 2, 3]