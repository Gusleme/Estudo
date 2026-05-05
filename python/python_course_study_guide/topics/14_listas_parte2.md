# Listas (Parte 2) e Matrizes

## Explicação Teórica
Listas compostas criam matrizes (listas de listas). Use loops aninhados para percorrer. Copie com `[:]` para evitar referência.

## Exemplos de Código
```python
# Matriz 3x3
matriz = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
print(matriz[0][1])  # 2
```

```python
# Percorrendo matriz
for linha in matriz:
    for elemento in linha:
        print(elemento, end=" ")
    print()
```

## Resumo de Sintaxe
- Matriz: `matriz = [[linha1], [linha2]]`.
- Acesso: `matriz[linha][coluna]`.
- Cópia: `nova_lista = lista[:]`.