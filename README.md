# Maze Solver usando Algoritmo A*

![hardmaze](https://github.com/Miguell-J/IA-Labirinto/assets/138534658/30c24826-11c5-429d-9dd6-c02365edec92)

> Este é um projeto Python que utiliza o algoritmo A* para encontrar o caminho mais curto através de um labirinto gerado aleatoriamente. O labirinto é criado usando a biblioteca pyamaze, que fornece funcionalidades para gerar e exibir labirintos.

---

## Instalação
Certifique-se de ter o Python instalado em seu sistema. Além disso, instale a biblioteca pyamaze usando o seguinte comando:

```python
pip install pyamaze
```

## Uso
- Execute o script Python maze_solver.py.
- Um labirinto será gerado aleatoriamente.
- O agente, representado por um ponto no labirinto, começará a encontrar o caminho mais curto para o destino (posição (1, 1)).
- As células sendo analisadas pelo algoritmo A* serão destacadas no labirinto.

## Detalhes do Algoritmo A*
- O algoritmo A* é um algoritmo de busca informada que utiliza duas funções de custo, g(n) e h(n), para determinar a ordem de exploração. Neste projeto:

```
g_score: Representa o custo real para alcançar uma célula a partir da célula inicial.
h_score: Representa uma estimativa do custo para alcançar o destino a partir de uma determinada célula.
f_score: Soma de g_score e h_score, usada para classificar as células na fila de prioridade.
```

O algoritmo continua explorando as células até atingir o destino, e o caminho encontrado é destacado no labirinto.

## Resultados
- O número total de células no labirinto é exibido no final da execução. O caminho mais curto é traçado no labirinto, destacando as células exploradas durante o processo.

- Esse projeto é uma demonstração prática de como o algoritmo A* pode ser aplicado para resolver problemas de caminho em um ambiente de labirinto.

- Observação: Este readme assume que você tem conhecimentos básicos sobre labirintos e algoritmos de busca, como A*.

- Divirta-se explorando os labirintos e os caminhos encontrados pelo algoritmo!
