# Calculadora de Média do Aluno

Projeto simples feito em **Python** para calcular a média de duas notas e mostrar se o aluno foi aprovado ou reprovado.

> Projeto desenvolvido durante meus estudos de Design Profissional.

---

## Tecnologias utilizadas

* 🐍 **Python 3**

---

## Como instalar e utilizar

Primeiro, é necessário ter o **Python 3** instalado no seu computador, depois:

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto no **VS Code** ou outro editor de código.
3. Execute o arquivo `app.py`.
4. Digite as duas notas quando forem solicitadas.

---

## Exemplo de uso

O programa solicita duas notas e calcula a média entre elas.

A partir do resultado, verifica se o aluno foi aprovado ou reprovado:

*  **Média igual ou maior que 7:** aprovado
*  **Média menor que 7:** reprovado

### Exemplo:

```text
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 8
Digite a segunda nota: 6

A média final é: 7.00
Status: APROVADO!
```

### Como o código funciona

A função `calcular_media()` recebe as duas notas e faz o cálculo da média:

```python
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2
```

Depois, o `if` verifica se a média chegou a 7:

```python
if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO.")
```
---

## Autor e contato

**Jonathan Estevão Lopes da Silva**

**GitHub:** [GitHub](https://github.com/jonathanestevao) \
**LinkedIn:** [LinkedIn](http://www.linkedin.com/in/jonathanestevao)\
**Dev.to:** [Dev.to](http://www.dev.to/jonathanestevao)
