# Modularização em Python

## Explicação Teórica
Divida código em módulos (.py) e pacotes (pastas com __init__.py). Importe com `import` ou `from`.

## Exemplos de Código
# Arquivo meu_modulo.py
def dobro(x):
    return x * 2

# Arquivo principal
import meu_modulo
print(meu_modulo.dobro(5))  # 10

## Resumo de Sintaxe
- Módulo: Arquivo .py com funções.
- Pacote: Pasta com __init__.py.
- Import: `import modulo` ou `from modulo import funcao`.