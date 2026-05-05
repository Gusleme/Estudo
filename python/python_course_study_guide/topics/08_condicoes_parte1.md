# Estruturas Condicionais (Parte 1)

## Explicação Teórica
Condicionais executam código baseado em condições. Use `if` para verdadeiro, `else` para falso. Comparadores: ==, !=, >, <, >=, <=.

## Exemplos de Código
```python
# Verificando maioridade
idade = int(input("Idade: "))
if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```

```python
# Par ou ímpar
numero = int(input("Número: "))
if numero % 2 == 0:
    print("Par")
else:
    print("Ímpar")
```

## Resumo de Sintaxe
- `if condicao:`: Executa se verdadeiro.
- `else:`: Executa se falso.
- Comparadores: `==`, `!=`, `>`, `<`, `>=`, `<=`.