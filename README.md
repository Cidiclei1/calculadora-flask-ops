# Calculadora Web (Python Flask HTML e JavaScript)

**Autor:** Cidiclei Junior

Este projeto é uma aplicação web simples desenvolvida com **Python + Flask + HTML + JavaScript**, baseada no projeto de exemplo e expandida com as operações de **Soma**, **Subtração**, **Multiplicação** e **Divisão**, cada uma com sua própria página e navegação pelo menu superior.

---

## Requisitos

- Python 3 instalado
- VS Code (com extensão de Python)
- Ambiente virtual (`venv`)
- Flask instalado

---

## Estrutura do Projeto

```text
meu_projeto_calculadora/
│
├── app.py              # Rotas Flask
├── operacoes.py        # Funções matemáticas
├── requirements.txt    # Dependências
├── README.md           # Documentação do projeto
├── templates/          # Páginas HTML
│   ├── index.html
│   ├── soma.html
│   ├── subtracao.html
│   ├── multiplicacao.html
│   └── divisao.html
└── static/             # Arquivos estáticos
    └── script.js