# Pipeline ETL Python - Extração de API Bitcoin com Agno Agente AI, SQL e Streamlit

<a href="https://www.linkedin.com/in/oceanalves/">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/56139923?v=4" width="100px;" alt=""/>
<h1>Ocean Alves</h1>

[![Linkedin Badge](https://img.shields.io/badge/-OceanAlves-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/oceanalves/)](https://www.linkedin.com/in/oceanalves/)
[![Github Badge](https://img.shields.io/badge/-OceanAlves-c14438?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/oceanalves/)](https://github.com/oceanalves)

[![Ocean Alves](https://img.shields.io/badge/oceanalves-GitHub-black.svg)](https://github.com//)

<hr>

<p align="center">
    <a alt="GitHub">
        <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
    </a>
    <a alt="PostGresql">
        <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
    </a>
    <a alt="Vscode">
        <img src="https://img.shields.io/badge/Vscode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
    </a>
    <a alt="Streamlit">
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" />
    </a>
    <a alt="Git">
        <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" />
    </a>
</p>

Este projeto demonstra um pipeline ETL completo utilizando Python para extrair dados da API do Bitcoin, processá-los com o Agno Agente AI, armazená-los em um banco de dados SQL e visualizá-los com Streamlit.

## Funcionalidades

- **Extração:** Coleta de dados em tempo real da API do Bitcoin.
- **Transformação:** Processamento e enriquecimento dos dados utilizando Agno Agente AI.
- **Carga:** Armazenamento dos dados processados em um banco de dados SQL.
- **Visualização:** Dashboard interativo criado com Streamlit.

## Tecnologias Utilizadas

- Python 3.x
- Requests
- Agno Agente AI
- SQL (SQLite, PostgreSQL, etc.)
- SQLAlchemy
- Streamlit

## Como Executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/oceanalves/Pipeline-API-e-Agno
   cd Pipeline-API-e-Agno
   ```

2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Execute o pipeline ETL:

   ```bash
   python etl.py
   ```

4. Inicie o dashboard Streamlit:
   ```bash
   streamlit run dashboard.py
   ```

## Estrutura do Projeto

```
├── etl.py
├── dashboard.py
├── requirements.txt
└── README.md
```

## Licença

Este projeto está licenciado sob a licença MIT.
