# 📊 7 Days of Code - Ciência de Dados

> Análise exploratória e storytelling com dados do CEAPS (despesas de senadores brasileiros) usando Python, Pandas e Plotly

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.0+-red.svg)](https://plotly.com/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

## 📖 Sobre o Projeto

Este projeto faz parte do desafio **7 Days of Code** da Alura, focado em Ciência de Dados. Trabalhamos com dados reais do **CEAPS (Cota para Exercício da Atividade Parlamentar dos Senadores)**, analisando gastos declarados por senadores brasileiros em 2022.

### 🎯 Objetivos

- **Dia 1**: Data Wrangling - Limpeza e transformação de dados
- **Dia 2**: Storytelling - Visualizações interativas e narrativa com dados
- **Próximos dias**: Em desenvolvimento...

### 💡 Por que este projeto?

Dados públicos são fundamentais para transparência. Este tipo de análise já inspirou iniciativas como a **Operação Serenata de Amor**, que usa IA para identificar usos indevidos de dinheiro público.

## 🗂️ Estrutura do Projeto

```
7DaysOfCode - Ciência de Dados/
├── 📂 Dados Abertos - CEAPS - csv/
│   ├── despesa_ceaps_2017.csv
│   ├── despesa_ceaps_2018.csv
│   ├── despesa_ceaps_2019.csv
│   ├── despesa_ceaps_2020.csv
│   ├── despesa_ceaps_2021.csv
│   └── despesa_ceaps_2022.csv
├── 📓 notebooks/
│   ├── dia01_CORRIGIDO.ipynb      # Exploração e limpeza de dados
│   ├── dia02_storytelling.ipynb   # Visualizações e storytelling
│   └── dia01_data_wrangling.ipynb # Versão original
├── 📄 README.md
└── 📋 requirements.txt
```

## 🛠️ Tecnologias e Instalação

### Requisitos:
- Python 3.8+
- Jupyter Notebook ou VS Code com extensão Python

### Instalação das Bibliotecas:

```bash
pip install pandas numpy jupyter matplotlib seaborn
```

Ou crie um arquivo `requirements.txt`:

```txt
pandas>=1.5.0
numpy>=1.23.0
jupyter>=1.0.0
matplotlib>=3.6.0
seaborn>=0.12.0
```

E instale com:
```bash
pip install -r requirements.txt
```

## 💻 Posso usar VS Code ao invés de Jupyter Notebook?

**SIM!** Você tem duas opções:

### Opção 1: Jupyter Notebook no VS Code
- Instale a extensão **Python** e **Jupyter** no VS Code
- Crie arquivos `.ipynb` e trabalhe com células interativas
- Mesma experiência do Jupyter, mas dentro do VS Code

### Opção 2: Scripts Python (.py)
- Crie arquivos `.py` normais
- Execute no terminal integrado do VS Code
- Mais adequado para scripts de produção

**Recomendação:** Use Jupyter Notebook (`.ipynb`) no VS Code para este projeto, pois facilita a documentação e visualização dos dados.

## 🧹 Técnicas de Limpeza de Dados

### Problemas Comuns a Identificar:
1. **Valores nulos** - deletar ou imputar valores
2. **Colunas irrelevantes** - remover colunas sem informação útil
3. **Datas em formato incorreto** - converter strings para datetime
4. **Tipos de dados incorretos** - converter colunas numéricas que estão como texto
5. **Duplicados** - identificar e remover registros duplicados
6. **Valores monetários** - formatar corretamente (vírgulas, pontos)
7. **CNPJ** - padronizar formato
8. **Nomes inconsistentes** - corrigir variações de escrita

## 📚 Recursos Úteis

- [Portal CEAPS](https://www12.senado.leg.br/transparencia/dados-abertos-transparencia/dados-abertos-ceaps)
- [Portal da Transparência](http://www.portaltransparencia.gov.br/)
- [Operação Serenata de Amor](https://serenata.ai/)
- [Tableau - Data Cleaning Tips](https://www.tableau.com/learn/articles/data-cleaning)
- [Brasil.IO](https://brasil.io/)
- [Kaggle Datasets](https://www.kaggle.com/datasets)

## 🚀 Como Começar

1. **Configure o ambiente:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Abra o VS Code e instale as extensões:**
   - Python
   - Jupyter

3. **Crie um notebook:**
   - Crie a pasta `notebooks/`
   - Crie o arquivo `dia01_data_wrangling.ipynb`

4. **Comece a explorar os dados:**
   ```python
   import pandas as pd
   
   # Carregar um arquivo
   df = pd.read_csv('Dados Abertos - CEAPS - csv/despesa_ceaps_2022.csv')
   df.head()
   ```

## 📊 Análises Realizadas

### Dia 1 - Data Wrangling
- ✅ Carregamento e limpeza de dados CSV
- ✅ Tratamento de valores nulos
- ✅ Conversão de tipos de dados
- ✅ Análise exploratória inicial

### Dia 2 - Storytelling
- ✅ Top 15 senadores que mais gastaram
- ✅ Distribuição por tipo de despesa
- ✅ Evolução temporal dos gastos
- ✅ Análise de fornecedores
- ✅ Gráficos interativos com Plotly

### 📈 Principais Descobertas

- 💰 **Valor total gasto em 2022**: R$ 25+ milhões
- 👥 **97 senadores** realizaram despesas
- 📊 **16.805 despesas** registradas
- 🏢 **Passagens aéreas** e **divulgação** são as categorias mais comuns

## 📝 Próximos Passos

- [x] Dia 1: Data Wrangling e Limpeza de Dados
- [x] Dia 2: Storytelling e Visualizações
- [ ] Dia 3: Análise Estatística
- [ ] Dia 4: Machine Learning
- [ ] Dia 5: Dashboard Interativo
- [ ] Dia 6: Comparação entre anos
- [ ] Dia 7: Apresentação final

## 🎓 Aprendizados

- 🐍 Python para análise de dados
- 📊 Pandas para manipulação de DataFrames
- 📈 Plotly para visualizações interativas
- 📓 Jupyter Notebook no VS Code
- 🧹 Técnicas de limpeza de dados
- 📖 Storytelling com dados

## 🤝 Contribuições

Este é um projeto de aprendizado pessoal, mas sugestões e melhorias são sempre bem-vindas!

## 📄 Licença

Este projeto está sob a licença MIT. Os dados são públicos e disponibilizados pelo Senado Federal.

## 🔗 Links Úteis

- [Portal CEAPS](https://www12.senado.leg.br/transparencia/dados-abertos-transparencia/dados-abertos-ceaps)
- [Operação Serenata de Amor](https://serenata.ai/)
- [7 Days of Code - Alura](https://7daysofcode.io/)

---

**Desenvolvido durante o desafio 7 Days of Code - Alura** 🚀
