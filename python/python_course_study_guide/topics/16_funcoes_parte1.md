# Funções (Parte 1)

## Explicação Teórica
Funções encapsulam código reutilizável. Defina com `def nome(parametros):`, chame com `nome(argumentos)`. Retorne valores com `return`.

## Exemplos de Código
```python
# Função simples
def saudacao(nome):
    return f"Olá, {nome}!"

print(saudacao("Maria"))
```

```python
# Função com cálculo
def area_retangulo(largura, altura):
    return largura * altura

print(area_retangulo(5, 10))  # 50
```

## Resumo de Sintaxe
- Definição: `def funcao(parametros):`.
- Chamada: `funcao(argumentos)`.
- Retorno: `return valor`.