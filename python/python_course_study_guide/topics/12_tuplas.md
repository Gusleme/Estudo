# Tuplas

## Explicação Teórica
Tuplas são sequências imutáveis. Criadas com `()` ou sem parênteses. Acesse por índice, desempacote com múltiplas variáveis.

## Exemplos de Código
```python
# Criando tupla
frutas = ("maçã", "banana", "laranja")
print(frutas[0])  # 'maçã'
```

```python
# Desempacotamento
a, b, c = frutas
print(a, b, c)
```

## Resumo de Sintaxe
- Criação: `tupla = (item1, item2)`.
- Acesso: `tupla[indice]`.
- Imutável: Não pode alterar itens.