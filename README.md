# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é um dashboard interativo construído com **Streamlit** para explorar e analisar dados de salários na área de dados em diferentes anos, senioridades, tipos de contrato e tamanhos de empresa.

---

### 🚀 Funcionalidades

* **Filtros Interativos**: Utilize a barra lateral para filtrar os dados por ano, senioridade, tipo de contrato e tamanho da empresa.
* **Métricas Chave (KPIs)**: Visualize as principais métricas, como salário médio, salário máximo e o total de registros, atualizadas em tempo real com base nos filtros.
* **Análises Visuais**: Explore gráficos de barra, histogramas e gráficos de pizza para entender a distribuição de salários, a proporção de tipos de trabalho e os cargos mais bem pagos.
* **Mapa Interativo**: Visualize o salário médio de Cientistas de Dados por país em um mapa.
* **Tabela Detalhada**: Veja a tabela completa de dados filtrados para uma análise detalhada.

---

### 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido em **Python** e utiliza as seguintes bibliotecas:

* **Streamlit**: Para a criação da interface do usuário (UI) do dashboard.
* **Pandas**: Para a manipulação e análise dos dados.
* **Plotly Express**: Para a criação dos gráficos e visualizações de dados interativas.

---

### ⚙️ Como Executar o Projeto

Siga os passos abaixo para rodar o dashboard em sua máquina local:

1.  **Clone o Repositório:**
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    cd [pasta_do_projeto]
    ```

2.  **Crie e Ative um Ambiente Virtual (Recomendado):**
    ```bash
    # Cria o ambiente virtual
    python -m venv .venv

    # Ativa o ambiente virtual (Windows)
    .venv\Scripts\activate
    
    # Ativa o ambiente virtual (macOS/Linux)
    source .venv/bin/activate
    ```

3.  **Instale as Dependências:**
    ```bash
    pip install pandas streamlit plotly
    ```

4.  **Execute o Dashboard:**
    ```bash
    streamlit run [nome_do_seu_arquivo].py
    ```
    Substitua `[nome_do_seu_arquivo].py` pelo nome do arquivo Python que contém o código do dashboard.

---

### 📝 Estrutura do Código

O código é organizado da seguinte forma:

* **Configuração da Página**: Define o título, ícone e layout do dashboard.
* **Carregamento dos Dados**: O dataset é carregado diretamente de uma URL do GitHub para garantir que o projeto seja autocontido.
* **Barra Lateral (Filtros)**: Seção dedicada à criação dos filtros interativos.
* **Conteúdo Principal**: Contém o título do dashboard, as métricas chave (KPIs) e os gráficos.
* **Visualizações com Plotly**: Cada seção de gráfico é organizada em colunas para um layout responsivo.

---

### 🌐 Fonte de Dados

Os dados utilizados neste projeto foram retirados do seguinte arquivo CSV hospedado no GitHub:

`https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv`

---

### ✒️ Autor

* **Daniel Vieira Novais** - [https://www.linkedin.com/in/daniel-vieira-novais-3a644a148/]
