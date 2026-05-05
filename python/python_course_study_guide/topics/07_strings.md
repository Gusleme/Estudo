# Manipulando Texto (Strings)

## Explicação Teórica
Strings são sequências de caracteres. Acesse com índices (0-based), fatiamento `[inicio:fim]`, métodos como `.upper()`, `.lower()`, `.strip()`. Concatene com `+`.

## Exemplos de Código
```python
# Manipulação básica
frase = "Olá, Python!"
print(frase[0])      # 'O'
print(frase.upper()) # 'OLÁ, PYTHON!'
print(frase[4:10])   # ' Python'
```

```python
# Contando vogais
texto = input("Digite um texto: ")
vogais = texto.count('a') + texto.count('e') + texto.count('i') + texto.count('o') + texto.count('u')
print(f"Vogais: {vogais}")
```

## Resumo de Sintaxe
- Índice: `string[posicao]`.
- Fatiamento: `string[inicio:fim]`.
- Métodos: `.len()`, `.upper()`, `.lower()`, `.strip()`.