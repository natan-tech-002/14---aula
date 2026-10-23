# Aula 14 — Operador ternário em Python

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

Repositório de exercícios da graduação em Inteligência Artificial — UniFAJ. O foco deste material é praticar o **operador ternário** do Python, uma forma compacta de escolher um valor com base em uma condição.

## 📘 Material principal

[**Abrir o notebook: Exercicio_operador_ternario.ipynb**](https://github.com/natan-tech-002/14---aula/blob/main/py/Exercicio_operador_ternario.ipynb)

O notebook apresenta a sintaxe e exemplos práticos de condições, incluindo:

- Número par ou ímpar.
- Maioridade.
- Comparação entre dois números.
- Aprovação por nota e média.
- Verificação de senha e nome de usuário.
- Classificação de temperatura.
- Número positivo ou negativo.
- Aplicação de desconto em uma compra.

## 💡 Como funciona o operador ternário

```python
resultado = valor_se_verdadeiro if condição else valor_se_falso
```

Exemplo:

```python
idade = 20
mensagem = "Maior de idade" if idade >= 18 else "Menor de idade"
print(mensagem)
```

## ▶️ Como executar

**Opção 1 — Google Colab:** abra o [notebook no Colab](https://colab.research.google.com/github/natan-tech-002/14---aula/blob/main/py/Exercicio_operador_ternario.ipynb) e execute as células em sequência.

**Opção 2 — Jupyter Notebook:** instale Python e Jupyter, baixe o repositório e abra o arquivo `py/Exercicio_operador_ternario.ipynb`.

Os exemplos que usam `input()` pedem que você informe valores durante a execução. Experimente alterar as entradas e executar novamente para comparar os resultados.

## 🎯 Objetivo de aprendizagem

Praticar expressões condicionais, operadores de comparação, entrada de dados e a leitura de expressões curtas em Python.

---

Material acadêmico em evolução. Sugestões e melhorias podem ser incorporadas conforme os estudos avançam.
