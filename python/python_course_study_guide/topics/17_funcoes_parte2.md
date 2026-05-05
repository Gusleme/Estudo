# Funções (Parte 2)

## Explicação Teórica
Funções podem ter parâmetros opcionais (default), *args (múltiplos posicionais), **kwargs (múltiplos nomeados). Use docstrings para documentar.

## Exemplos de Código
```python
# Parâmetros opcionais
def potencia(base, expoente=2):
    return base ** expoente

print(potencia(3))    # 9
print(potencia(3, 3)) # 27
```

```python
# *args
def soma(*numeros):
    return sum(numeros)

print(soma(1, 2, 3, 4))  # 10
```

## Resumo de Sintaxe
- Default: `def funcao(param=default):`.
- *args: `def funcao(*args):`.
- **kwargs: `def funcao(**kwargs):`.