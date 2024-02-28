**Busca Sequencial:** Na busca sequencial, percorremos os elementos do array um por um até encontrar o elemento desejado ou concluir que não está presente. Aqui está um exemplo simples em Python:
![[Pasted image 20240228123845.png]]
Exemplo de uso:
![[Pasted image 20240228123910.png]]
![[Pasted image 20240228124006.png]]
**Busca Binária:** Na busca binária, o array deve estar ordenado. A ideia é dividir o array ao meio repetidamente, eliminando metade dos elementos a cada passo, até encontrar o elemento desejado. Aqui está um exemplo em Python:
![[Pasted image 20240228123924.png]]
Exemplo de uso:
![[Pasted image 20240228124454.png]]
![[Pasted image 20240228124017.png]]
<iframe width="853" height="480" src="https://www.youtube.com/embed/fDKIpRe8GW4" title="Pesquisa binária em 4 minutos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Complexidade:**
- A complexidade de busca sequencial é O(n) no pior caso, pois pode ser necessário percorrer todo o array.
- A complexidade de busca binária é O(log n) no pior caso, pois a cada passo, reduzimos pela metade a porção do array a ser pesquisada.

**Explicação da Complexidade:**
- "O(n)" significa que o tempo de execução aumenta linearmente com o tamanho do array.
- "O(log n)" significa que o tempo de execução aumenta de maneira logarítmica com o tamanho do array. Em busca binária, o array é dividido pela metade a cada passo, o que leva a essa complexidade eficiente.