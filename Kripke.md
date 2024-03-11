# Estruturas de Kripke

## Sistema de transições

- Abstrações que descrevem o comportamento de sistemas com precisão matemática e sem ambiguidade
- Representado por grafo
    - nó -> estado (info do sistema em um momento)
    - aresta ->  transição (como mudar de um estado para outro)
- Definido por tripla:
    - conjunto de estados
    - transições
    - estados iniciais
- Kripke é um sistema de transição com um adicional
    - relação → deve ser total ou ∀s ∈ S, ∃s′ ∈ S : s → s′
    - não tem estado final(normal) devido a isso
    - estado terminal é estado que possui transição apenas para si mesmo


