# Checando propriedades com Lógica Temporal

## Model Checking
 
- Diferentes níveis de verificação de software 
    - Fuzzing e simulação (inputs aleatórios e mais focados)
    - Model checking
    - Provas (com assistente de provas)
- Uso:
    - Input
        - maquina de estados finita -> modelo
        - formula de logica temporal -> propriedade
    - Output:
        - Sucesso
        - Contra exemplo (sequencia de estados qeu viola a propriedade)
        - falta de memoria
- Principais operadores:
    - Unários:
        - Sempre
        - Eventualmente
        - Proximo
    - Binários:
        - Até
        - Libera
- Invariante é uma propriedade valida para todos os estados do sistema
- LTL - Linear Temporal Logic (Lógica Temporal Linear)
    - Não ramifica
- CTL - Computational Tree Logic (Lógica de Árvore Computacional)
    - Ramifica