# Utilizando Módulos

## Explicação Teórica
Módulos são bibliotecas de funções. Importe com `import modulo` ou `from modulo import funcao`. Exemplos: `math` para matemática, `random` para aleatórios.

## Exemplos de Código
```python
import math
print(math.sqrt(16))  # 4.0
```

```python
import random
numero = random.randint(1, 10)
print(f"Número aleatório: {numero}")
```

## Resumo de Sintaxe
- `import modulo`: Importa o módulo inteiro.
- `from modulo import funcao`: Importa função específica.
- `modulo.funcao()`: Chama a função.