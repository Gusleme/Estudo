# Estrutura de Repetição for

## Explicação Teórica
`for` itera sobre sequências (listas, strings, range). Use `range(inicio, fim, passo)` para números. Interrompa com `break`, pule com `continue`.

## Exemplos de Código
```python
# Contagem de 1 a 5
for i in range(1, 6):
    print(i)
```

```python
# Soma de lista
numeros = [1, 2, 3, 4, 5]
soma = 0
for num in numeros:
    soma += num
print(f"Soma: {soma}")
```

## Resumo de Sintaxe
- `for variavel in sequencia:`: Itera sobre a sequência.
- `range(inicio, fim)`: Gera sequência numérica.
- `break`: Sai do laço.
- `continue`: Pula iteração.