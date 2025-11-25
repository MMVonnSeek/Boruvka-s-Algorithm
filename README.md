# Boruvka’s Algorithm – Minimum Spanning Tree (MST)

[![Autor: Max Muller](https://img.shields.io/badge/Autor-Max%20Muller-0A66C2?style=for-the-badge&logo=github)]()
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()

## Sobre o Projeto
Este repositório apresenta uma implementação completa do **Algoritmo de Borůvka**, utilizado para encontrar a **Árvore Geradora Mínima (MST)** de um grafo ponderado.  

Borůvka é um dos algoritmos fundamentais em teoria dos grafos e estrutura de dados, sendo uma excelente demonstração de:
- Componentes conectados (Union-Find simplificado)  
- Escolha gulosa de arestas mínimas  
- Iterações paralelas de otimização  
- Construção progressiva de MST  

---

## Tecnologias Utilizadas
- **Python 3.x**

---

## Entendendo o Algoritmo de Borůvka
O algoritmo trabalha repetidamente encontrando, para cada componente do grafo, a aresta de menor peso que leva a outro componente.

Processo:
1. Cada vértice começa como seu próprio componente.  
2. Para cada componente, identifica-se sua menor aresta de saída.  
3. As arestas mínimas são adicionadas à MST.  
4. Componentes são unificados.  
5. Repete-se até restar apenas um componente.

Complexidade:  
**O(E log V)** — desempenho excelente para grafos esparsos.

---

## Como Executar

1. Clone o repositório:

git clone https://github.com/seuusuario/boruvkas-algorithm

2. Execute o script:

python boruvka.py


### Autor

Max Muller
Desenvolvedor e professor especializado em algoritmos, grafos e Python avançado.

Se este projeto ajudou você a evoluir, deixe uma ⭐ e compartilhe o conhecimento. Obrigado por usar este repositório!

![octocat-1688653141486](https://github.com/MMVonnSeek/Boruvka-s-Algorithm/assets/89359847/dd3d5462-c46b-4668-88bd-1f577fc6866e)
