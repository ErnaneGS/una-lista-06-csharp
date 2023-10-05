# una-lista-06-csharp
Repositório destina a resolução da Lista de Exercício VI. UC: Estrutura de Dados e Análise de Algoritmos

## Vetor

Um vetor é uma estrutura de dados unidimensional de elementos do mesmo tipo. Cada elemento é acessado por um índice que representa sua posição no vetor. Em C#, os vetores são representados usando o tipo de dados "array".

### Exemplo de um vetor em C#
```csharp
//Criando um vetor e atribuindo valores
int[] vetor = new int[5] { 1, 2, 3, 4, 5 };

// Acessando elementos do vetor
int valor = vetor[1];
```

## Matriz

Uma matriz é uma estrutura de dados bidimensional que armazena elementos organizados em linhas e colunas, sendo acessados por dois índices, um para a linha e outro para a coluna.

### Exemplo de uma matriz em C#
```csharp
//Declarando uma matriz
int[,] matriz = new int[2, 3];

//Atribuindo um valor
matriz[1, 2] = 20;

//Acessando um valor
int valor = matriz[1, 2];
```

## Cubo

Um cubo é uma coleção tridimensional de elementos organizados em três dimensões. Assim como nas matrizes, os elementos de um cubo são acessados por três índices.

### Exemplo de um cubo em C#
```csharp
//Declarando um cubo
int[,,] cubo = new int[3, 3, 3];

//Atribuindo um valor
cubo[0, 0, 0] = 1;

//Acessando um valor
int valor = cubo[0, 0, 0];
```
