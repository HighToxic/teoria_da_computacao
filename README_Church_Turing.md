# A Tese de Church-Turing: O Fundamento da Computação

Este repositório contém um resumo detalhado sobre a **Tese de Church-Turing**, um dos pilares fundamentais da Ciência da Computação teórica.

## 📌 Introdução

A Tese de Church-Turing afirma que qualquer função que possa ser calculada por um algoritmo (de forma eficaz e mecânica) pode ser calculada por uma **Máquina de Turing**. Em termos simples, ela define os limites do que pode e do que não pode ser computado por qualquer computador físico ou teórico.

## 🧪 Origens e Contexto

Na década de 1930, dois matemáticos tentaram formalizar a definição de "computabilidade" de formas independentes:

1.  **Alonzo Church:** Criou o **Cálculo Lambda ($\lambda$-calculus)**, um sistema baseado em funções matemáticas.
2.  **Alan Turing:** Criou a **Máquina de Turing**, um modelo teórico que simula a manipulação de símbolos em uma fita infinita.

Surpreendentemente, ambos provaram que seus modelos eram equivalentes: qualquer problema que o Cálculo Lambda resolve, a Máquina de Turing também resolve, e vice-versa.

## ⚙️ O que a Tese estabelece?

A tese não é um "teorema" matemático passível de prova formal (pois "algoritmo" é um conceito intuitivo), mas sim uma hipótese amplamente aceita que sustenta que:

* **Universalidade:** Se um problema não pode ser resolvido por uma Máquina de Turing, ele não pode ser resolvido por nenhum computador algorítmico existente ou futuro.
* **Turing-Completude:** Uma linguagem de programação ou sistema é dito "Turing-completo" se ele possui o mesmo poder computacional de uma Máquina de Turing (ou seja, pode resolver qualquer problema computável).

## 🚀 Implicações na Computação

* **Limites do Conhecimento:** Através dela, Turing provou a existência de problemas "indecidíveis", como o **Problema da Parada** (*Halting Problem*), mostrando que existem perguntas que nenhum algoritmo pode responder corretamente em tempo finito.
* **Design de Hardware e Software:** Todos os computadores modernos (arquitetura de Von Neumann) são implementações físicas de uma Máquina de Turing Universal.
* **Inteligência Artificial:** A tese levanta questões filosóficas sobre se o cérebro humano também opera sob os limites da computabilidade de Turing.

## 📚 Conclusão

A Tese de Church-Turing transformou a computação de um conceito vago em uma ciência rigorosa. Ela nos diz que, embora o hardware possa evoluir infinitamente em velocidade, a natureza fundamental do que é "calculável" permanece a mesma desde 1936.

---
**Dica de estudo:** Se você está interessado em Teoria da Computação, pesquise sobre *Máquinas de Turing Universais* e *Hierarquia de Chomsky*.
