# 🐍 Manipulação de Tuplas

> Exercício básico de Python sobre criação, acesso e características das tuplas.

## 🎯 Objetivo
Compreender como criar tuplas, acessar seus elementos e realizar o desempacotamento de valores.

## 📚 Conceitos utilizados
- Tuplas (`()`)
- Indexação (`[0]`)
- Imutabilidade
- Desempacotamento de tuplas
- Constantes por convenção (`LIMITES`)

## ⚙️ Código

```python
ponto = (-22.9, -43.2)

ponto[0]

ponto[0] = 0

lat, lon = ponto

LIMITES = (70, 90)
```

## 📊 Funcionamento
- `ponto`: cria uma tupla com dois valores.
- `ponto[0]`: acessa o primeiro elemento.
- `ponto[0] = 0`: tenta modificar um elemento, mas gera um erro porque tuplas são imutáveis.
- `lat, lon = ponto`: desempacota os valores em duas variáveis.
- `LIMITES`: armazena dois valores em uma tupla, seguindo a convenção de nomes em maiúsculas.

## 🧠 Aprendizado
Compreensão das características das tuplas, principalmente sua imutabilidade, indexação e capacidade de desempacotar valores em variáveis independentes.
