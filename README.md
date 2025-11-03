# Simulador de Gerenciamento de Heap

## Descrição

Este programa simula o gerenciamento de memória dinâmica (heap) com diferentes estratégias de alocação. Permite visualizar como cada estratégia se comporta ao alocar e desalocar blocos de memória.

## Funcionalidades

**Estratégias de Alocação:**
- **First Fit**: Aloca no primeiro bloco livre suficiente
- **Best Fit**: Aloca no menor bloco livre suficiente
- **Worst Fit**: Aloca no maior bloco livre disponível
- **Next Fit**: Continua busca de onde parou

**Operações:**
- Alocar memória
- Desalocar memória
- Atribuir variável
- Visualizar estado do heap
- Reiniciar heap

## Como Compilar e Executar

```bash
gcc main.c heap.c heap.h -o heap
./heap
```

Siga o menu interativo para escolher estratégias e manipular a memória.

## Estrutura do Projeto

- `heap.h` - Definições de structs e protótipos
- `heap.c` - Implementação das funções
- `main.c` - Menu interativo e programa principal
