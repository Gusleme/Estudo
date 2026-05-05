# Estruturas Condicionais (Parte 2)

## Explicação Teórica
Adicione `elif` para múltiplas condições. Aninhe ifs para lógica complexa. Use operadores lógicos: `and`, `or`, `not`.

## Exemplos de Código
```python
# Classificação por idade
idade = int(input("Idade: "))
if idade < 12:
    print("Criança")
elif idade < 18:
    print("Adolescente")
else:
    print("Adulto")
```

```python
# Aprovado ou reprovado
nota = float(input("Nota: "))
if nota >= 7.0:
    print("Aprovado")
elif nota >= 5.0:
    print("Recuperação")
else:
    print("Reprovado")
```

## Resumo de Sintaxe
- `elif condicao:`: Condição alternativa.
- `and`, `or`, `not`: Operadores lógicos.