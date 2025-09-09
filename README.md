# Projeto Certificado – Parte 2: Avaliação de Atletas 🏆

Este projeto é a **segunda parte do meu projeto de JavaScript**, agora adicionando **mais dados sobre os atletas**, como idade, peso, altura, cálculo de IMC e categoria, além das notas da competição.

O objetivo é **organizar os dados de cada atleta em uma classe**, permitindo cálculos automáticos de:

- Categoria por faixa etária
- IMC (Índice de Massa Corporal)
- Média válida das notas (eliminando a maior e menor nota)

---

## Como funciona

1. Cada atleta possui:
   - Nome
   - Idade
   - Peso
   - Altura
   - 5 notas de jurados

2. O sistema calcula:
   - **Categoria**: Infantil, Juvenil, Intermediário ou Adulto
   - **IMC**: usando fórmula clássica `peso / (altura * altura)`
   - **Média válida**: considera apenas as 3 notas do meio

3. Todos os cálculos são feitos através de métodos da **classe `Atleta`**.

---

## Tecnologias usadas

- JavaScript (ES6)
- Classes e métodos
- Array methods (`sort`, `slice`, `reduce`)
- Spread operator (`[...]`) para não alterar o array original

---

## Como usar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/notas-atletas.git
