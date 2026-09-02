# 📊 Análise Estatística Descritiva com Python e SQL

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange.svg)
![SQL](https://img.shields.io/badge/SQL-SQLite-blue.svg)

## 📋 Sobre o Projeto

Este projeto apresenta uma análise estatística descritiva desenvolvida em **Python**, utilizando uma base de dados de exemplo com informações como idade, salário, experiência profissional, avaliação, departamento e cidade.

O objetivo é explorar os dados e aplicar conceitos de **estatística descritiva, análise de correlação, identificação de possíveis outliers e visualização de dados**.

O projeto também utiliza **SQLite e SQL** para armazenar os dados e realizar consultas, integrando diferentes etapas do processo de análise.

Foi desenvolvido como projeto de estudo e portfólio durante minha preparação para oportunidades de **Estágio em Tecnologia e Dados**.

---

## 🎯 Objetivos

- Gerar e estruturar uma base de dados para análise;
- Explorar características das variáveis numéricas;
- Aplicar estatística descritiva;
- Identificar possíveis outliers utilizando o método IQR;
- Analisar correlações entre variáveis;
- Criar visualizações para facilitar a interpretação dos dados;
- Armazenar dados em banco SQLite;
- Realizar consultas utilizando SQL;
- Praticar organização e desenvolvimento de análises utilizando Python.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Utilização |
|------------|------------|
| **Python** | Desenvolvimento da análise |
| **Pandas** | Manipulação e análise dos dados |
| **NumPy** | Geração e operações numéricas |
| **Matplotlib** | Criação de gráficos |
| **Seaborn** | Visualização estatística |
| **SQLite3** | Banco de dados |
| **SQL** | Consultas e agregação de dados |

---

## 📊 Estrutura dos Dados

A base utilizada no projeto contém **200 registros** e as seguintes variáveis:

| Variável | Descrição |
|----------|-----------|
| `idade` | Idade do registro |
| `salario` | Salário |
| `experiencia` | Anos de experiência |
| `avaliacao` | Avaliação entre 1 e 5 |
| `departamento` | Departamento |
| `cidade` | Cidade |

Os dados são gerados para fins de estudo utilizando NumPy, permitindo a criação de uma base controlada para aplicar as técnicas estatísticas.

---

## 📈 Análise Estatística

As variáveis numéricas são identificadas automaticamente utilizando Pandas.

Em seguida, são calculadas estatísticas descritivas como:

- Contagem de registros;
- Média;
- Desvio padrão;
- Valor mínimo;
- Primeiro quartil (25%);
- Mediana (50%);
- Terceiro quartil (75%);
- Valor máximo.

A utilização do método `describe()` permite obter uma visão geral da distribuição das variáveis numéricas.

---

## 🔍 Detecção de Outliers

O projeto utiliza o método **IQR (Intervalo Interquartil)** para identificar possíveis valores discrepantes.

O cálculo considera:

- Primeiro quartil (Q1);
- Terceiro quartil (Q3);
- Intervalo interquartil (IQR);
- Limite inferior;
- Limite superior.

A análise é aplicada à primeira variável numérica identificada na base.

---

## 🔗 Análise de Correlação

Foi criada uma **matriz de correlação** utilizando as variáveis numéricas da base.

Essa análise permite observar a intensidade e a direção da relação linear entre as variáveis.

A matriz também é apresentada visualmente por meio de um **heatmap**, facilitando a interpretação dos resultados.

---

## 📉 Visualizações

O projeto utiliza diferentes visualizações para apoiar a análise exploratória:

### Histograma + KDE

Permite observar a distribuição da variável analisada.

### Boxplot

Utilizado para visualizar a distribuição dos dados e possíveis valores discrepantes.

### Heatmap

Representa visualmente a matriz de correlação entre as variáveis numéricas.

---

## 💾 Banco de Dados e SQL

Os dados analisados são armazenados em um banco **SQLite** utilizando Python.

O projeto cria uma tabela chamada `dados` e realiza uma consulta SQL para calcular a média de idade e a quantidade de registros por departamento.

A consulta utiliza conceitos como:

- `SELECT`;
- `AVG()`;
- `COUNT()`;
- `GROUP BY`;
- `ORDER BY`.

Essa etapa demonstra a integração entre **Python, Pandas e SQL** durante o processo de análise.

---

## 🧩 Fluxo do Projeto

```text
Geração dos dados
       ↓
Criação do DataFrame
       ↓
Identificação das variáveis numéricas
       ↓
Estatística descritiva
       ↓
Detecção de possíveis outliers
       ↓
Análise de correlação
       ↓
Visualização dos dados
       ↓
Armazenamento em SQLite
       ↓
Consulta SQL
       ↓
Resultados da análise
```

---

## 📁 Estrutura do Projeto

```text
📁 AnalisePython/
│
├── 📄 .gitignore
├── 📄 README.md
├── 📄 tradd.txt
└── 📓 Untitled4.ipynb
```

### Arquivos

- **`Untitled4.ipynb`** → Notebook contendo o desenvolvimento completo da análise.
- **`requirements.txt`** → Dependências utilizadas no ambiente Python.
- **`.gitignore`** → Arquivos e pastas que não devem ser enviados ao Git.
- **`README.md`** → Documentação do projeto.

---

## 🚀 Como Executar

### Google Colab

O projeto foi desenvolvido em formato de **Jupyter Notebook** e pode ser executado no Google Colab.

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)]https://colab.research.google.com/drive/1D9PrfJ9FOe_X3mkK_yVb5-FCF59QEgjs#scrollTo=rvnQIyMtzLu7

### Execução local

Caso utilize Jupyter Notebook, primeiro instale as dependências:

```bash
pip install -r tradd.txt
```

Depois, abra o arquivo:

```text
Untitled4.ipynb
```

e execute as células do notebook.

---

## 📦 Dependências

As principais bibliotecas utilizadas no projeto são:

```text
pandas
numpy
matplotlib
seaborn
```

O arquivo `requirements.txt` contém as versões mínimas das bibliotecas utilizadas no ambiente do projeto.

---

## 🎓 O que Aprendi

Este projeto permitiu praticar conceitos importantes de **Tecnologia e Dados**, incluindo:

- 🐍 Desenvolvimento em Python;
- 🐼 Manipulação de dados com Pandas;
- 🔢 Operações numéricas com NumPy;
- 📊 Estatística descritiva;
- 🔍 Detecção de possíveis outliers;
- 🔗 Análise de correlação;
- 📈 Visualização de dados;
- 🗃️ Utilização de SQL;
- 💾 Integração com banco SQLite;
- 📝 Organização e documentação de projetos;
- 🐙 Utilização do Git e GitHub.

---

## 💡 Relação com Tecnologia e Dados

O projeto reúne conhecimentos que considero importantes para meu desenvolvimento na área de Tecnologia e Dados, principalmente **Python, SQL, análise estatística e exploração de dados**.

Além da parte técnica, o desenvolvimento permitiu praticar a organização de um fluxo de análise, desde a geração e estruturação dos dados até a obtenção e interpretação dos resultados.

Como próximos passos, pretendo aprofundar meus conhecimentos em **Machine Learning, Inteligência Artificial e desenvolvimento de soluções orientadas por dados**.

---

## 🚀 Próximos Passos

Como evolução deste projeto, pretendo explorar:

- Análise exploratória de dados mais aprofundada;
- Novos testes estatísticos;
- Machine Learning;
- Modelos preditivos;
- Automação de análises;
- Integração com ferramentas de Business Intelligence;
- Aplicações de Inteligência Artificial em projetos de dados.

---

## 👨‍💻 Autor

**Saedi Huiza**

Estudante de **Análise e Desenvolvimento de Sistemas**, com interesse em **Tecnologia, Dados, Analytics e Inteligência Artificial**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saedi-huiza-631a43386/)

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/saedihuiza22-ctrl)


## 📝 Licença

Este projeto foi desenvolvido para fins educacionais, de aprendizado e demonstração de conhecimentos em programação, estatística e análise de dados.

⭐ Se este projeto foi útil ou interessante, fique à vontade para deixar uma estrela no repositório.
