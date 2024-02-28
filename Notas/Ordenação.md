**Método da Bolha:** O método da bolha é um algoritmo de ordenação simples que percorre repetidamente a lista, compara elementos adjacentes e os troca se estiverem na ordem errada. O processo é repetido até que a lista esteja ordenada.
![[Pasted image 20240228132101.png]]
<iframe width="853" height="480" src="https://www.youtube.com/embed/8RkZoBZNNgI" title="O que é e COMO FUNCIONA o BubbleSort (passo-a-passo)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<iframe width="853" height="480" src="https://www.youtube.com/embed/xli_FI7CuzA" title="Ordenação de bolhas em 2 minutos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Ordenação por Seleção:** Na ordenação por seleção, o array é dividido em duas partes: uma ordenada e outra não ordenada. O algoritmo encontra o menor elemento na parte não ordenada e o troca com o primeiro elemento não ordenado. Esse processo se repete até que toda a lista esteja ordenada.
![[Pasted image 20240228132124.png]]
<iframe width="853" height="480" src="https://www.youtube.com/embed/g-PGLbMth_g" title="Seleção de ordenação em 3 minutos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Ordenação por Inserção:** Na ordenação por inserção, o array é percorrido, e em cada passo, um elemento é removido da lista e inserido na posição correta na parte ordenada do array.
![[Pasted image 20240228132204.png]]
<iframe width="853" height="480" src="https://www.youtube.com/embed/JU767SDMDvA" title="Ordenação por inserção em 2 minutos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Diferenças:**

- **Bubble Sort:** Troca elementos adjacentes repetidamente até que a lista esteja ordenada. É ineficiente para listas grandes.
- **Selection Sort:** Encontra o menor elemento e o troca com o primeiro elemento não ordenado. Funciona melhor que o bubble sort, mas ainda assim é ineficiente para listas grandes.
- **Insertion Sort:** Constrói uma lista ordenada, inserindo elementos na posição correta. Mais eficiente que os anteriores para listas pequenas ou parcialmente ordenadas.

**Complexidade:**

- **Bubble Sort e Selection Sort:** O(n^2) no pior caso, pois envolvem dois loops aninhados.
- **Insertion Sort:** O(n^2) no pior caso, mas eficiente para listas pequenas e quase ordenadas.

**Nota:** Algoritmos de ordenação mais eficientes, como o Merge Sort e Quick Sort, são preferidos para grandes conjuntos de dados. Esses algoritmos possuem complexidade O(n log n) no pior caso.