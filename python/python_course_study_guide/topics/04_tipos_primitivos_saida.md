# Tipos Primitivos e Saída de Dados

## Explicação Teórica
Python tem tipos primitivos: int (inteiros), float (decimais), str (strings), bool (verdadeiro/falso). Use `type()` para verificar o tipo. A saída formatada usa f-strings ou `.format()`.

## Exemplos de Código
```python
# Verificando tipos
numero = 42
texto = "Python"
print(type(numero))  # <class 'int'>
print(type(texto))   # <class 'str'>
```

```python
# Saída formatada
preco = 29.99
print(f"O preço é R${preco:.2f}")
```

## Resumo de Sintaxe
- Tipos: `int`, `float`, `str`, `bool`.
- F-string: `f"Texto {variavel}"`.
- `type(variavel)`: Retorna o tipo.