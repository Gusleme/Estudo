# Estrutura de Repetição while

## Explicação Teórica
`while` repete enquanto condição for verdadeira. Use para loops indeterminados. Combine com `break` e `continue`.

## Exemplos de Código
```python
# Contagem regressiva
contador = 10
while contador > 0:
    print(contador)
    contador -= 1
print("Fim!")
```

```python
# Validação de entrada
senha = ""
while senha != "python":
    senha = input("Digite a senha: ")
print("Acesso liberado")
```

## Resumo de Sintaxe
- `while condicao:`: Repete enquanto verdadeiro.
- `break`: Sai do laço.
- `continue`: Pula iteração.