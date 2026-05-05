# Tratamento de Erros e Exceções

## Explicação Teórica
Use `try/except` para capturar erros. `finally` executa sempre. Tipos comuns: ValueError, TypeError.

## Exemplos de Código
```python
# Tratando erro de conversão
try:
    numero = int(input("Digite um número: "))
    print(f"Número: {numero}")
except ValueError:
    print("Entrada inválida!")
```

```python
# Múltiplas exceções
try:
    resultado = 10 / int(input("Divisor: "))
except ZeroDivisionError:
    print("Divisão por zero!")
except ValueError:
    print("Entrada inválida!")
finally:
    print("Fim da operação")
```

## Resumo de Sintaxe
- `try:`: Bloco a testar.
- `except TipoErro:`: Trata erro específico.
- `finally:`: Executa sempre.