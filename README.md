<div align="center">

# 🐍 fcc-python

### Códigos do curso de Python do freeCodeCamp

Exercícios e projetos da certificação, tudo em um só lugar.

<br>

![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![freeCodeCamp](https://img.shields.io/badge/freeCodeCamp-0A0A23?style=for-the-badge&logo=freecodecamp&logoColor=white)
![License](https://img.shields.io/badge/Licença-MIT-22C55E?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Em%20andamento-F59E0B?style=for-the-badge)

<br>

[📂 Estrutura](#-estrutura-do-repositório) •
[🏆 Projetos](#-projetos-da-certificação) •
[🚀 Como começar](#-como-começar) •
[📄 Licença](#-licença)

</div>

---

## 📌 Sobre

Este repositório reúne os **códigos** desenvolvidos durante o
**curso de Python do [freeCodeCamp](https://www.freecodecamp.org/)**,
incluindo exercícios e os projetos da certificação.

> [NOTE]
> Este repositório contém apenas código. Não há material teórico nem anotações.

---

## 🧭 Visão geral

```mermaid
flowchart LR
    A[🐍 fcc-python] --> B[📘 Exercícios]
    A --> C[🏆 Projetos da certificação]
    B --> B1[01-fundamentals]
    B --> B2[02-data-structures]
    B --> B3[03-functions-and-oop]
    C --> C1[user-config-manager]
    C --> C2[budget-app]
    C --> C3[polygon-area-calculator]
    C --> C4[hash-table]
    C --> C5[tower-of-hanoi]
```

---

## 📂 Estrutura do repositório

```text
📦 fcc-python
├── 📁 01-fundamentals
├── 📁 02-data-structures
├── 📁 03-functions-and-oop
├── 📁 certification-projects
│   ├── 📁 user-config-manager
│   ├── 📁 budget-app
│   ├── 📁 polygon-area-calculator
│   ├── 📁 hash-table
│   └── 📁 tower-of-hanoi
├── 📄 .gitignore
├── 📄 LICENSE
├── 📄 README.md
└── 📄 requirements.txt
```

| 📁 Pasta                 | 📝 Conteúdo                                       |
| ------------------------ | ------------------------------------------------- |
| `01-fundamentals`        | Variáveis, tipos, condicionais e laços de repetição |
| `02-data-structures`     | Listas, dicionários, tuplas e conjuntos           |
| `03-functions-and-oop`   | Funções e programação orientada a objetos         |
| `certification-projects` | Projetos exigidos para a certificação             |

---

## 🏆 Projetos da certificação

| Status | Projeto                         | Pasta                                                                        |
| :----: | ------------------------------- | ---------------------------------------------------------------------------- |
|   ⬜   | Gerenciador de configuração de usuário | [`user-config-manager`](certification-projects/user-config-manager)   |
|   ⬜   | App de orçamento                | [`budget-app`](certification-projects/budget-app)                            |
|   ⬜   | Calculadora de área de polígono | [`polygon-area-calculator`](certification-projects/polygon-area-calculator)  |
|   ⬜   | Tabela hash                     | [`hash-table`](certification-projects/hash-table)                            |
|   ⬜   | Torre de Hanói                  | [`tower-of-hanoi`](certification-projects/tower-of-hanoi)                    |

> **Legenda:** ⬜ pendente · 🟨 em andamento · ✅ concluído

**Progresso:** `░░░░░░░░░░` 0 / 5

- [ ] Gerenciador de configuração de usuário
- [ ] App de orçamento
- [ ] Calculadora de área de polígono
- [ ] Tabela hash
- [ ] Torre de Hanói

---

## 🚀 Como começar

### 📋 Requisitos

- 🐍 **Python** 3.12 ou superior
- 📦 **pip** atualizado
- 🔧 **Git**

### ⚙️ Instalação

**1. Clone o repositório**

```bash
git clone https://github.com/dexthw/fcc-python.git
cd fcc-python
```

**2. Crie e ative um ambiente virtual**

```bash
python -m venv .venv
```

| 💻 Sistema       | ⌨️ Comando de ativação          |
| ---------------- | ------------------------------- |
| Linux / macOS    | `source .venv/bin/activate`     |
| Windows (CMD)    | `.venv\Scripts\activate.bat`    |
| Windows (PS)     | `.venv\Scripts\Activate.ps1`    |

**3. Instale as dependências**

```bash
pip install -r requirements.txt
```

### ▶️ Executando um projeto

```bash
python certification-projects/tower-of-hanoi/main.py
```

<details>
<summary><b>🧪 Executar os testes</b></summary>

<br>

```bash
python -m unittest discover -s certification-projects/tower-of-hanoi
```

</details>

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo [`LICENSE`](LICENSE)
para mais detalhes.

---

<div align="center">

### 👤 Autor

**Matheus Brasil**

[![GitHub](https://img.shields.io/badge/GitHub-dexthw-181717?style=for-the-badge&logo=github)](https://github.com/dexthw)

<br>

⭐ Se este repositório foi útil, deixe uma estrela!

</div>