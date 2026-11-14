# 🏠 Kitnet Manaus

Sistema desktop para gerenciamento de kitnets, desenvolvido como projeto acadêmico utilizando Python, Tkinter e SQLite.

## 📌 Sobre o projeto

O **Kitnet Manaus** tem como objetivo facilitar o gerenciamento de imóveis e suas respectivas operações, centralizando informações em um sistema com interface gráfica.

O projeto foi desenvolvido com foco na aplicação prática de conceitos de programação orientada a objetos, organização de código e banco de dados.

## 🚀 Tecnologias utilizadas

- **Python** — linguagem principal.
- **Tkinter** — desenvolvimento da interface gráfica.
- **SQLite** — armazenamento e gerenciamento dos dados.

## ⚙️ Funcionalidades e módulos

O sistema possui módulos organizados para:

- Cadastro e gerenciamento de kitnets.
- Cadastro e gerenciamento de estudantes.
- Controle de locações.
- Gerenciamento de pagamentos.
- Controle de manutenções.
- Gerenciamento de despesas.
- Relatórios gerenciais.
- Exportação de informações.

## 📁 Estrutura do projeto

```text
KITNET_MANAUS/
│
├── database/
│   ├── conexao.py
│   └── criar_tabelas.py
│
├── interfaces/
│   ├── estudante_interface.py
│   ├── kitnet_interface.py
│   ├── locacao_interface.py
│   ├── manutencao_interface.py
│   ├── pagamento_interface.py
│   └── menu.py
│
├── models/
│   ├── estudante.py
│   ├── kitnet.py
│   ├── locacao.py
│   ├── manutencao.py
│   ├── pagamento.py
│   └── despesa.py
│
├── services/
│   ├── estudante_service.py
│   ├── kitnet_service.py
│   ├── locacao_service.py
│   ├── pagamento_service.py
│   └── relatorio_service.py
│
├── kitnet_manaus.db
├── main.py
└── corrigir_encoding.py
```

## ▶️ Como executar o projeto

1. Instale o Python 3.
2. Clone este repositório:

```bash
git clone https://github.com/naironalmeida/KITNET_MANAUS.git
```

3. Entre na pasta do projeto:

```bash
cd KITNET_MANAUS
```

4. Execute o sistema:

```bash
python main.py
```

## 🗄️ Banco de dados

O projeto utiliza SQLite para armazenar as informações do sistema, por meio do arquivo `kitnet_manaus.db`.

## 🎓 Objetivo acadêmico

Este projeto foi desenvolvido com o objetivo de colocar em prática conhecimentos adquiridos durante a graduação em Engenharia de Software, envolvendo programação Python, interfaces gráficas, banco de dados e organização de sistemas.

---

**Projeto: Kitnet Manaus**  
**Tecnologias: Python | Tkinter | SQLite**
