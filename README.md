# Busca A* para o Problema de Arad a Bucareste

## Descrição

Este projeto implementa a solução do problema de busca de caminho mais curto entre duas cidades, Arad e Bucareste, usando o Algoritmo de Busca A*. 
O algoritmo busca encontrar o caminho mais eficiente entre as duas cidades com base em uma heurística que estima a distância restante até o objetivo.

## Objetivos

O objetivo do algoritmo de busca A* no problema de Arad a Bucareste é encontrar o caminho mais curto e eficiente entre as cidades de Arad e Bucareste no mapa da Romênia. O algoritmo deve calcular a sequência de cidades a serem percorridas, minimizando o custo total da viagem, que pode ser medido em termos de distância, tempo ou outro critério relevante.

Para alcançar esse objetivo, o A* utiliza uma função de avaliação f(n) = g(n) + h(n), onde:

g(n) representa o custo acumulado do caminho desde o ponto de partida (Arad) até o nó atual n.
h(n) é uma estimativa heurística do custo para chegar do nó n até o destino final (Bucareste).
O A* garante que o caminho encontrado será o mais curto, desde que a heurística utilizada seja admissível, ou seja, nunca superestime o custo real para alcançar o destino. No contexto deste problema, a heurística mais comum é a distância em linha reta entre as cidades.

## Algoritmo

Componentes de um problema 
► 1. Estado inicial; 
► 2. Estado final (objetivo); 
► 3. Espaço de estados; 
► 4. Ações para passar de um estado para outro; 
► 5. Solução (caminho que leva do estado inicial ao estado final).

## Estrutura do Projeto

- **`src/`**: Código-fonte do projeto.
	- **`Principal.java`**: Implementação principal do algoritmo de busca gulosa.
	- **`Busca Gulosa.java`**: Implementação principal do algoritmo de busca gulosa.
	- **`Grafos.java`**: Implementação principal do algoritmo de busca gulosa.
	- **`Vertice.java`**: Implementação principal do algoritmo de busca gulosa.
	- **`VetorOrdenado.java`**: Implementação principal do algoritmo de busca gulosa.
	- **`Adjacente.java`**: Implementação principal do algoritmo de busca gulosa.

## Como Executar

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/samerzito/Algoritmo-Busca-AEstrela.git
