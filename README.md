# ⚡ Calculadora de Consumo de Energia

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![GitHub](https://img.shields.io/badge/GitHub-Reposit%C3%B3rio-black?logo=github)
![Energia](https://img.shields.io/badge/Energia-El%C3%A9trica-yellow)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)

## 📌 Sobre o projeto

A **Calculadora de Consumo de Energia** é um programa desenvolvido em Python que permite calcular o consumo mensal de energia elétrica de um aparelho específico.

Para funcionar, o usuário deve informar qual aparelho ele que saber, colocar a quantidade exata do aparelho ou do tipo e colocar a quantidade de horas que ele quer saber e, com isso o programa irá calcular rápidamente os resultados.

## 🛠️ Tecnologias utilizadas

* 🐍 Python
* 💻 Visual Studio Code
* 🐙 Git e GitHub

## 💻 Fórmula utilizada

O consumo mensal é calculado através da seguinte fórmula:

```text
Consumo mensal = (Potência × Horas por dia × 30) ÷ 1000
```

O custo estimado é calculado considerando o valor fixo de **R$ 0,75 por kWh**:

```text
Custo = Consumo mensal × 0,75
```

## ▶️ Como executar

### 1. Instale o Python

Tenha o Python instalado no computador.

### 2. Abra o projeto

Abra a pasta `consumo-energia` no Visual Studio Code.

### 3. Execute o programa

Abra o terminal do VS Code e digite:

```bash
git clone https://github.com/vhpagliarini-hub/consumo-energia.git
```
```bash
cd consumo-energia
```
```bash
python app.py
```
