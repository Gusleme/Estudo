# Dicionários

## Explicação Teórica
Dicionários armazenam pares chave-valor. Criados com `{}`. Acesse com `dict[chave]`, adicione com `dict[chave] = valor`.

## Exemplos de Código
```python
# Criando dicionário
pessoa = {"nome": "João", "idade": 25}
print(pessoa["nome"])  # 'João'
pessoa["cidade"] = "São Paulo"
print(pessoa)
```

```python
# Iterando
for chave, valor in pessoa.items():
    print(f"{chave}: {valor}")
```

## Resumo de Sintaxe
- Criação: `dicionario = {"chave": "valor"}`.
- Acesso: `dicionario["chave"]`.
- Adicionar: `dicionario["nova_chave"] = valor`.
- Itens: `.items()`.