# CALCULADORA DE MÉDIA BÁSICA
 ---

 ### **Resumo:** 
 Código elaborado em laboratório universitario com o objetivo de realizar cálculos de média entre as notas do aluno utilizando dois algarismos de forma simples em Python.

---

 # TECNOLOGIAS UTILIZADAS:
- **Editor de Texto:** Visual Studio Code 
- **Extensões:** Python 3
- **Copilador:** Terminal Linux 

---

# COMO INSTALAR E EXECUTAR: 
 Utilizar software compativel com o versionamento do código IDE

---

# Como funciona
O programa solicita ao usuário duas notas:
1. Primeira nota
2. Segunda nota 
Em seguida, calcula a média utilizando a fórmula:
média = (nota1 + nota2) / 2
Depois, verifica o resultado:
Média ≥ 7,0: APROVADO
Média < 7,0: REPROVADO

---

# Exemplo de execução:
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 8
Digite a segunda nota: 6
A média final é: 7.00
status: APROVADO
📂 Estrutura do projeto
aula 01/
│
├── app.py
└── README.md

---

# O que foi praticado:

Neste projeto foram praticados conceitos fundamentais de Python, principalmente a criação e utilização de funções e estruturas condicionais.
A função calcular_media() recebe duas notas e retorna a média:
def calcular_media(nota1, nota2):
   return (nota1 + nota2) / 2
A estrutura if/else é utilizada para determinar o status do aluno:
if media >= 7.0:
   print("status: APROVADO")
else:
   print("status: REPROVADO")

---

# Autora
Ana Clara Rosa
Estudante de Análise e Desenvolvimento de Sistemas (ADS).


