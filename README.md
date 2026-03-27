# Verificador de Ordem de Letras

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white) ![Topic](https://img.shields.io/badge/Topic-python-regex-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

## Descrição

Utilitário Python com regex para verificar se as letras de uma palavra aparecem na mesma ordem dentro de uma frase, sem necessidade de serem contíguas.

## Funcionalidades

- Verificação de subsequência de letras em frases
- Uso avançado de expressões regulares com o módulo `re`
- Função reutilizável `verificar_ordem_letras(palavra, frase)`
- Lógica compacta e de fácil integração

## Stack Tecnológico

| Tecnologia | Descrição |
|---|---|
| Python | Linguagem principal |
| re | Módulo de expressões regulares (stdlib) |

## Como Usar

```python
from solucao import verificar_ordem_letras

resultado = verificar_ordem_letras("amor", "a melhor forma de viver")
print(resultado)  # True ou False
```

## Estrutura de Pastas

```
├── solucao.py
└── README.md
```

---

> Feito com ❤️ por Rone Bragaglia · ML Engineer & Fundador CobrançaAuto
