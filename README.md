# Projeto de Dados: Python, SQL e Docker

Bem-vindo ao repositório **dados-sql-docker**!

Este projeto foi desenvolvido com o propósito prático de consolidação de conhecimentos. Ele reflete minha jornada de aprendizado e transição de carreira para a área de tecnologia e análise de dados, sendo o espaço onde os conceitos acadêmicos de Análise e Desenvolvimento de Sistemas da USF encontram as ferramentas práticas do mercado.

## 🎯 Sobre o Projeto

O objetivo central deste repositório é criar, gerenciar e documentar um ambiente de processamento de dados robusto e reprodutível. A arquitetura foi pensada para integrar três pilares fundamentais:

- **Python**: Linguagem principal utilizada para extração, manipulação de dados e lógica de programação dos fluxos de trabalho.
- **SQL**: Foco na modelagem, construção de queries estruturadas e prática avançada de manipulação de dados em bancos relacionais.
- **Docker**: Ferramenta de conteinerização responsável por garantir o isolamento da aplicação e facilitar a execução da infraestrutura em qualquer máquina sem conflitos.

A presença de diretórios como `dags` indica também o estudo de ferramentas de orquestração (como o Apache Airflow) para automatizar os pipelines desenvolvidos.

## 📂 Estrutura do Repositório

- `config/`: Arquivos e parâmetros de configuração do ambiente.
- `dags/`: Definição dos pipelines de dados e fluxos de orquestração.
- `data/`: Armazenamento local de datasets brutos e processados para consumo.
- `notebook/`: Jupyter Notebooks utilizados para análises exploratórias de dados (EDA) e prototipagem inicial de scripts.
- `src/`: Código-fonte principal com os módulos em Python.
- `docker-compose.yaml`: Orquestração local dos containers necessários para a infraestrutura do projeto.
- `pyproject.toml` / `uv.lock`: Arquivos de gerenciamento moderno de dependências em Python.

## 🚀 Como Executar

1. Certifique-se de ter o **Docker** e o **Docker Compose** instalados na sua máquina.
2. Faça o clone deste repositório:
   ```bash
   git clone [https://github.com/Guilhermetrindade01/dados-sql-docker.git](https://github.com/Guilhermetrindade01/dados-sql-docker.git)
   ```
