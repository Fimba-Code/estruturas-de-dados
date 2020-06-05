<h1 align="center">Desafio de Estruturas de Dados e Algoritmos: #1</h1>
  
## Introdução 📜

Este desafio foi desenhado para programadores iniciantes, e também os mais experientes que desejam acrescentar os seus conhecimentos sobre a implementação de algumas estruturas de dados e algoritmos.  As soluções não estarão restritas à nenhuma linguagem de programação específica, os nossos **moderadores** encorajam todos os participantes a usar as linguagens de programação de sua preferência. 

## Submissão 🚀

As soluções desenvolvidas devem ser partilhadas no canal [**#code-drop** no discord](https://discord.gg/XDPbSUN), posteriormente, as melhores soluções serão colocadas neste repo e os devs receberão kudos no twitter ou outra rede social de sua preferência. 

**Dicas importantes**

1. Não te esqueças de formatar o teu código antes de o enviar à communidade, para mais informações visite => [discord](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline).
2. Use funções no teu programa sempre que necessário para a reutilização de códigos e simplificação dos programas. 
3. Resolva os teus exercícios streaming live (ajuda-te a ganhar mais pontos)
4. Desenvolva e partilhe o seu pseudocódigo(algoritimo) junto da tua submissão.


## Challenge 🥋

Os challenges (desafios) começarão do mais simples ao mais arduo, mas poderás resolver-los de forma aleatória. Esse challenge será composto por 4 problemas sendo que os mesmos ajudarão o participante à desenvolver algum skill específico.

### Challenge #1 - Fila(Queue) 🧊

<div align="center">
  <img src="https://user-images.githubusercontent.com/23306911/83900117-d70b6e80-a759-11ea-91da-1b793e2ed385.png" width="200"/>
</div>

Fila é uma estrutura de dados linear que nos permite processar elementos dependendo da ordem na qual foram adicionados, regra esta é: Os primeiros a serem adicionados à fila, serão os primeiros a serem atendidos ou executados, ou seja **Primeiro dentro, Primeiro Fora(FIFO)**. Filas são muito usadas quando precisamos processar informações em serie(uma atrás da outra, do primeiro ao último). 

Implememente uma Fila com os seguintes metodos:

- **isEmpty**: Método verificar se a fila está vazia.
- **enqueue**: Método para adicionar novos elementos à fila.
- **dequeue**: Método para remover o ultimo elemento da fila.
- **print**: Método imprimir todos os elementos da fila.

Exemplo:

```javascript

// Inicializando a Fila
const queue = new Queue();

// Adicionando novos elementos
queue.enqueue(2);
queue.enqueue(1);
queue.enqueue(5);

// Removendo elementos
queue.dequeue();
queue.dequeue();

// Imprimindo 
queue.print(); // imprime: 5

// Verificando se a fila está vázia
queue.isEmpty(); // imprime: false
```

### Challenge #2 - Pilha(Stack) 🧊

<div align="center">
  <img src="https://user-images.githubusercontent.com/23306911/83900124-d96dc880-a759-11ea-9a93-db4b20f9bd60.png" width="200"/>
</div>

Pilha é uma estrutura de dados linear que nos permite processar elementos dependendo da ordem na qual foram adicionados, regra esta é: Os últimos a serem adicionados à fila, serão os primeiros a serem atendidos ou executados. Pilhas são muito usadas quando precisamos processar informações em serie(uma atrás da outra, do último ao primeiro). 

Implememente uma Pilha com os seguintes metodos:

- **isEmpty**: Método verificar se a pilha está vazia.
- **push**: Método para adicionar novos elementos à pilha.
- **pop**: Método para remover o ultimo elemento da pilha.
- **print**: Método imprimir todos os elementos da pilha.

Exemplo:

```javascript
// Inicializando a Fila
const stack = new Stack();

// Adicionando novos elementos
stack.push(2);
stack.push(1);
stack.push(5);

// Removendo elementos
stack.pop();
stack.pop();

// Imprimindo 
stack.print(); // imprime: 2

// Verificando se a fila está vázia
stack.isEmpty(); // imprime: false
```

### Challenge #3 - Lista Ligada(Linked-List) 🧊

<div align="center">
  <img src="https://user-images.githubusercontent.com/23306911/83902866-7847f400-a75d-11ea-82fd-a54ad5e9be69.png" width="300"/>
</div>

Lista Ligada é uma estrutura de dados linear e dinâmica. Ela é composta por células que apontam para o próximo elemento da lista. Para "ter" uma lista ligada/encadeada, basta guardar seu primeiro elemento, e seu último elemento aponta para uma célula nula. O esquema a seguir representa uma lista ligada/encadeada com 5 elementos. [Fonte: Wikipedia](https://pt.wikipedia.org/wiki/Lista_ligada)

Implememente uma Lista Ligada com os seguintes métodos:

- **insert**: Método para inserir novos elementos à lista.
- **remove**: Método para remover o ultimo elemento da lista.
- **print**: Método imprimir todos os elementos da lista.

Exemplo:

```javascript
// Inicializando a Fila
const lista = new ListaLigada();

// Adicionando novos elementos
lista.insert(2);
lista.insert(1);
lista.insert(5);

// Removendo elementos
lista.remove(2);
lista.remove(5);

// Imprimindo 
lista.print(); // imprime: 1

// Verificando se a fila está vázia
lista.isEmpty(); // imprime: false
```

### Challenge #3 - Árvore de pesquisa binária(BST - Binary Search Tree) 🧊

<div align="center">
  <img src="https://user-images.githubusercontent.com/23306911/83900140-e1c60380-a759-11ea-9d81-3d6fcad9e48c.png" width="300"/>
</div>

BST é uma estrutura de dados de árvore binária baseada em nós, onde todos os nós da subárvore esquerda possuem um valor numérico inferior ao nó raiz e todos os nós da subárvore direita possuem um valor superior ao nó raiz (esta é a forma padrão, podendo as subárvores serem invertidas, dependendo da aplicação) [Fonte: Wikipédia](https://pt.wikipedia.org/wiki/%C3%81rvore_bin%C3%A1ria_de_busca)



Implememente uma **BST** com os seguintes metodos:

- **isEmpty**: Método verificar se a árvore está vazia.
- **insert**: Método para adicionar novos elementos à árvore.
- **find**: Método para pesquisar determinado valor na árvore.
- **remove**: Método remover determinado valor da árvore.

Exemplo:

```javascript
// Inicializando a Fila
const bst = new BinarySearchTree();

// Adicionando novos elementos
bst.insert(2);
bst.insert(1);
bst.insert(5);

// Removendo elementos
bst.remove(2);
// Imprimindo 
bst.find(2); // imprime: true

// Verificando se a fila está vázia
bst.isEmpty(); // imprime: false
```


