# 🌍 Análise da Pegada de Carbono: Brasil e Comparações Globais

Este projeto analisa a pegada de carbono do Brasil em comparação com outras nações e grupos, incluindo dados globais, o continente americano, países membros da OCDE e os Estados Unidos. Utilizamos fontes confiáveis e aplicamos técnicas de limpeza, visualização e modelagem de dados com algoritmos de aprendizado supervisionado para fornecer insights sobre a sustentabilidade das emissões brasileiras.

## 👥 Integrantes

- **Gabriel Pacheco** - RM550191
- **Gustavo Veríssimo** - RM551244
- **Murilo Obinata** - RM99855

## 🗂️ Estrutura do Projeto

```
AnaliseCarbono_Brasil-Mundo/
├── data/                   # Conjunto de dados utilizados na análise
│   ├── raw/                # Dados brutos
│   └── processed/          # Dados processados
├── notebooks/              # Jupyter Notebooks com análises
│   ├── 01_data_cleaning.ipynb    # Limpeza de dados
│   ├── 02_data_visualization.ipynb # Visualização de dados
│   └── 03_modeling.ipynb         # Modelagem e aprendizado de máquina
├── reports/                # Relatórios gerados
│   └── figures/            # Imagens e gráficos
├── requirements.txt        # Lista de dependências do projeto
└── README.md               # Documentação do projeto
```

## 🛠️ Tecnologias Utilizadas

- **Python** 3.x
- **Jupyter Notebook**
- Bibliotecas:
  - **Pandas**: Manipulação e análise de dados
  - **NumPy**: Computação numérica
  - **Matplotlib** e **Seaborn**: Visualização de dados
  - **Scikit-learn**: Algoritmos de aprendizado de máquina

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/pacheco365/AnaliseCarbono_Brasil-Mundo.git
   cd AnaliseCarbono_Brasil-Mundo
   ```

2. **Crie um ambiente virtual (opcional, mas recomendado):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Inicie o Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Em seguida, navegue até a pasta `notebooks/` e abra os notebooks para explorar as análises.

## 📊 Conjuntos de Dados

Os dados utilizados neste projeto foram obtidos de fontes públicas e confiáveis. Eles estão armazenados na pasta `data/` e são divididos em:

- `raw/`: Contém os dados brutos originais.
- `processed/`: Contém os dados após processos de limpeza e transformação.

## 📈 Metodologia

1. **Limpeza de Dados:** Tratamento de valores ausentes, remoção de duplicatas e padronização de formatos.
2. **Visualização de Dados:** Criação de gráficos e tabelas para entender padrões e tendências nas emissões de carbono.
3. **Modelagem:** Aplicação de algoritmos de aprendizado supervisionado para prever tendências futuras e identificar fatores determinantes nas emissões de carbono.

## 📄 Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes.

---

*Projeto desenvolvido por Gabriel Pacheco, Gustavo Veríssimo e Murilo Obinata como parte de uma iniciativa acadêmica para analisar a pegada de carbono do Brasil em um contexto global.*
