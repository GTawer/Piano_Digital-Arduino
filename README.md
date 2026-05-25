# 🎹 Piano Digital Cromático: Automação Sonora com Arduino UNO 𝄞 

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge&logo=github)
![Platform](https://img.shields.io/badge/Plataforma-Tinkercad%20%2F%20Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

Este projeto foi desenvolvido com o objetivo de integrar conceitos de **eletrônica digital, lógica de programação embarcada em C++ e acústica**. A proposta inicial da atividade era expandir um protótipo de 4 notas para um piano básico de 7 notas (uma oitava natural de Dó a Si). 

No entanto, o projeto foi levado além: foi desenvolvida uma **escala cromática completa de 12 notas (oitava com semitons)**, incluindo todas as teclas "brancas e pretas", garantindo maior fidelidade musical e complexidade lógica.

---

## 📂 Detalhes do Projeto

| Item | Descrição | Status |
| :--- | :--- | :--- |
| `Hardware` | Montagem de 12 botões (teclas) e 1 Buzzer piezoelétrico na Protoboard. | ✅ |
| `Frequências (Hz)`| Mapeamento exato das frequências em Hertz para cada nota musical. | ✅ |
| `Código-Fonte` | Estrutura em C++ otimizada para leitura de múltiplos inputs digitais. | ✅ |
| `Diferencial` | **Expansão:** Inclusão dos 5 semitons (notas sustenidas♯/bemóis♭). | 🚀 Superado |

---

## ⚙️ Funcionamento e Engenharia do Código

O funcionamento do piano eletrônico se baseia na varredura de sinais digitais e na conversão de comandos lógicos em ondas sonoras físicas:

* **Leitura Digital:** O Arduino monitora constantemente as portas de entrada conectadas aos botões (teclas).
* **Processamento de Frequência:** Ao detectar o acionamento de um botão, o microcontrolador processa a nota correspondente e envia uma modulação de onda específica para o buzzer através da função `tone()`.
* **Escala Cromática Implementada:**  **Notas Naturais:** Dó♮, Ré♮, Mi♮, Fá♮, Sol♮, Lá♮, Si♮ (7 notas)
  * **Semitons (Teclas Pretas):** Dó#, Ré#, Fá#, Sol#, Lá# (5 notas adicionadas como diferencial)

> 🎼 **Raciocínio Lógico:** A expansão para 12 notas exigiu uma organização rigorosa da protoboard e dos resistores de pull-down/pull-up para evitar mau contato ou conflito de frequências, simulando fielmente o comportamento de um sintetizador real.

---

## 🔗 Link do Projeto
* [Acesse aqui o projeto no Tinkercad](https://www.tinkercad.com/things/fmJcnjJpE4I-piano-digital-12-notas?sharecode=QfTPPEnqFVSUGyktGpL8LWI_NVJL0sp5CLJp_qFlneQ)

---

## 🛠️ Ferramentas Utilizadas

* **Tinkercad:** Ambiente de simulação de circuitos digitais.
* **Arduino UNO:** Microcontrolador responsável pelo processamento dos inputs e geração de tons.
* **Buzzer Piezoelétrico:** Transdutor que converte os sinais elétricos em frequências sonoras audíveis.
* **Linguagem C/C++** 

---

* **Disciplina:** Lógica de Programação (LOPAL) / Internet das Coisas (IoT)
* **Professores:** Raul Porto Lopes e Paulo Cesar Camargo
* **Aluno:** Gabriel de Araujo Torres (Nº 08)
* **Data:** 25/05/2026

#### Projeto desenvolvido no SENAI A. Jacob Lafer.


<p align="left">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3N5bXBoZXoxNTRidmxtOHF0ZW8yYXphcjB4Mzg2bXExMGZ5aG05diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/9372Cfs94wKllXvThY/giphy.gif" width="220" height="auto" alt="Cat playing piano animation" />
</p>
