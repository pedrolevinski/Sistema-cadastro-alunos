# 📘 Sistema de Cadastro de Alunos

Este é um projeto simples em Python desenvolvido como parte do portfólio de **Análise de Dados**, com foco em leitura e escrita de arquivos `.csv`, estruturação de código em funções e manipulação de dados de entrada do usuário.

## 💡 Funcionalidades

- Cadastro de novos alunos
- Validação de notas (entre 0 e 10)
- Cálculo automático da média
- Salvamento dos dados em um arquivo `alunos.csv`
- Visualização de todos os alunos cadastrados via terminal
- Criação automática do cabeçalho no CSV

## 🖥 Tecnologias utilizadas

- Python 3.x
- Módulos padrão:
  - `csv`
  - `os`

## 📂 Estrutura do Arquivo CSV

O programa cria (ou atualiza) um arquivo chamado `alunos.csv` com o seguinte formato:

Nome, Nota 1, Nota 2, Nota 3, Média

Maria, 8.0, 7.5, 9.0, 8.17  

João, 6.5, 5.0, 7.0, 6.17


✅ Próximas melhorias (ideias para evolução)
Exibir alunos aprovados e reprovados (ex: média >= 7)

Buscar aluno por nome

Exportar o CSV formatado para Excel

Interface gráfica (com Tkinter ou Web com Streamlit)

✍️ Autor
Desenvolvido por [Pedro Henrique Levinski].


Projeto do portfólio do curso de Análise de Dados — EBAC.



## ▶️ Como executar

1. Certifique-se de ter o **Python 3** instalado.
2. Baixe o arquivo `.py` com o código-fonte.
3. Execute no terminal ou na sua IDE preferida:

```bash
python sistema_cadastro.py


