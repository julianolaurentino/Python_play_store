# ETL - Google Play Store Data

Este projeto realiza o processo de **ETL (Extração, Transformação e Carga)** nos dados da Google Play Store e suas avaliações, preparando-os para análise e visualização no Tableau.

## 📂 Estrutura do Projeto
```
📁 ETL_GooglePlay
│── 📄 etl_googleplay.py       # Script de ETL para Google Play Store
│── 📄 etl_googleplay_reviews.py # Script de ETL para reviews dos usuários
│── 📁 data                    # Diretório de arquivos CSV originais
│── 📁 output                  # Diretório para armazenar os dados tratados
│── 📄 README.md               # Documentação do projeto
```

## 🔧 Tecnologias Utilizadas
- **Python** (Pandas, NumPy)
- **Tableau** (para visualização de dados)

## 🚀 Como Executar o Projeto

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seuusuario/ETL_GooglePlay.git
   cd ETL_GooglePlay
   ```
2. **Instale as dependências** (caso ainda não tenha Pandas instalado)
   ```bash
   pip install pandas numpy
   ```
3. **Execute os scripts de ETL**
   ```bash
   python etl_googleplay.py
   python etl_googleplay_reviews.py
   ```
4. **Os arquivos tratados serão gerados no diretório `output/`**

## 📊 Próximos Passos
- Criar dashboards no **Tableau** para análise de KPIs.
- Explorar insights sobre categorias, avaliações e sentimentos dos usuários.

## Autor

- [@JulianoLaurentino](https://www.linkedin.com/in/julianolaurentinodasilva/)