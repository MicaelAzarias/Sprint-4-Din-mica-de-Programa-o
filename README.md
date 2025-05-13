# Projeto de Otimização com Grafos e Algoritmo de Dijkstra

## 1 - Aplicação de Grafo

**Arquivo:** `1-Aplicacao_de_Grafo.ipynb`

Este script implementa um grafo representando a distância entre um cliente e diversas lojas. Ele utiliza o algoritmo de Dijkstra para:

- Calcular a menor distância do cliente até cada loja.
- Identificar qual loja está mais próxima do cliente.
- Ordenar todas as lojas em ordem crescente de proximidade com o cliente.

O grafo é definido com 7 vértices:
- Cliente
- Loja_Berrini
- Loja_Paulista
- Loja_Morumbi
- Loja_Pinarello
- Loja_Lapa
- Loja_Vila_Madalena

A saída do programa exibe os resultados de forma clara para auxiliar decisões logísticas.

---

## 2 - Algoritmo de Dijkstra com Rotas Otimizadas

**Arquivo:** `2-Algoritmo_de_Dijkstra.ipynb`

Este script resolve uma versão simplificada do **Problema do Caixeiro Viajante**, usando o algoritmo de Dijkstra para calcular o custo entre pares de locais. Ele:

- Gera todas as possíveis sequências de visitas às lojas.
- Calcula o custo total de cada rota, partindo do cliente.
- Escolhe a rota de menor custo total como a melhor rota para entrega.

É ideal para aplicações em que é necessário encontrar o caminho mais eficiente para visitar todos os pontos (lojas) partindo de um único ponto (cliente), com base em distâncias predefinidas.

---

✅ Ambos os arquivos utilizam estruturas de grafos e priorizam eficiência no trajeto, com base no algoritmo de Dijkstra e suas aplicações.

