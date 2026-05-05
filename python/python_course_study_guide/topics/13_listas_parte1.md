# Listas (Parte 1)

## Explicação Teórica
Listas são mutáveis. Criadas com `[]`. Adicione com `.append()`, remova com `.remove()`, acesse por índice.

## Exemplos de Código
```python
# Manipulação de lista
numeros = [1, 2, 3]
numeros.append(4)
print(numeros)  # [1, 2, 3, 4]
numeros.remove(2)
print(numeros)  # [1, 3, 4]
```

```python
# Ordenação
lista = [3, 1, 4, 1, 5]
lista.sort()
print(lista)  # [1, 1, 3, 4, 5]
```

## Resumo de Sintaxe
- Criação: `lista = [item1, item2]`.
- Adicionar: `.append(item)`.
- Remover: `.remove(item)`.
- Ordenar: `.sort()`.