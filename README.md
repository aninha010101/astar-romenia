 Busca A* em Python — Arad até Bucareste

Implementação do algoritmo de busca **A* (A-Estrela)** utilizando Python, com o objetivo de encontrar o caminho de menor custo entre as cidades de Arad e Bucareste, na Romênia.

O projeto foi desenvolvido como atividade prática da disciplina **Inteligência Artificial I**, explorando conceitos de busca heurística, grafos e estruturas de dados.

## O projeto

O algoritmo A* é um algoritmo de busca informada que utiliza o custo já percorrido e uma estimativa do custo restante para determinar o caminho mais econômico até um destino.

Neste projeto, utilizamos o mapa rodoviário da Romênia, no qual:

- As cidades representam os vértices do grafo.
- As estradas representam as arestas.
- As distâncias entre as cidades representam os custos.
- A distância em linha reta até Bucareste é utilizada como heurística.

A busca utiliza a seguinte função:

**f(n) = g(n) + h(n)**

Onde:

- **g(n):** custo real do caminho percorrido desde Arad até a cidade atual.
- **h(n):** estimativa da distância restante até Bucareste.
- **f(n):** custo total estimado, utilizado para selecionar o próximo nó a ser explorado.

## Objetivo

Implementar o algoritmo A* passo a passo, compreendendo seu funcionamento e aplicando conceitos fundamentais de Inteligência Artificial e programação em Python.

## Tecnologias utilizadas

- Python 3
- Git
- GitHub
- Visual Studio Code

## Estrutura do projeto

```text
astar-romenia/
│
├── mapa.py
├── fase1_explorar.py
├── fase2_caminhos.py
├── fase3_fronteira.py
├── fase4_expandir.py
├── fase5_busca.py
├── a_estrela.py
│
├── README.md
└── .gitignore
```

## Etapas de desenvolvimento

O projeto foi dividido em seis fases para facilitar a compreensão e implementação do algoritmo.

| Fase | Descrição |
|---|---|
| 0 | Preparação do ambiente, Git e GitHub |
| 1 | Exploração dos dados do mapa da Romênia |
| 2 | Cálculo do custo dos caminhos e função f(n) |
| 3 | Implementação dos nós e da fronteira |
| 4 | Expansão dos nós e controle dos explorados |
| 5 | Implementação do laço principal da busca A* |
| 6 | Integração e execução do algoritmo completo |

## Resultado esperado

A partir da execução do algoritmo, o menor caminho encontrado entre Arad e Bucareste é:

**Arad → Sibiu → Rimnicu Vilcea → Pitesti → Bucharest**

<pre>
Distância total: 418 km
</pre>

O resultado demonstra como a busca A* combina o custo real do percurso com a estimativa heurística para encontrar uma solução de menor custo.


## Referências

RUSSELL, Stuart; NORVIG, Peter. **Inteligência Artificial**. 3. ed. Rio de Janeiro: Elsevier, 2013. Capítulo 3.

## Autoria

Projeto acadêmico desenvolvido como parte das atividades da disciplina Inteligência Artificial I — FATEC

**Desenvolvido por:** Ana Beatriz

