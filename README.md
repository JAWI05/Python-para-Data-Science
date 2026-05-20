# 🐍 Python para Data Science

Bem-vindo ao repositório central da disciplina **Python para Data Science**. Este espaço foi projetado para consolidar códigos, análises estatísticas, automações e projetos práticos voltados à extração de insights, lógica algorítmica, manipulação de dados e integração com ferramentas em nuvem.

---

## 📚 Conteúdo Programático & Estrutura do Curso

### 🛠️ Módulo 1: Fundamentos, Lógica Computacional & Jogos
* **Estruturas de Dados:** Listas, dicionários, tuplas e matrizes flat (mapeamento de vetores).
* **Controle de Fluxo e Funções:** Estruturas condicionais (`if/else`), laços de repetição (`for/while`), funções personalizadas e a biblioteca nativa `random`.
* **Lógica Algorítmica Aplicada:** Desenvolvimento de IA básica para jogos de tabuleiro (validação de estados de vitória, controle de turnos e prevenção de jogadas inválidas).

### 📊 Módulo 2: Manipulação de Dados & Integração Cloud (Google Ecosystem)
* **Google Drive API & PyDrive2:** Autenticação via Google Colab, upload, download e gerenciamento de arquivos automatizados em nuvem usando a API REST (v3).
* **Google Sheets com Python:** Integração com a biblioteca `gspread`, leitura de tabelas, atualização em lote de células e manipulação de planilhas diretamente pelo Python.

### 📈 Módulo 3: Data Science Aplicada, Análise Estrutural e Gráficos
* **Computação Numérica:** Manipulação de matrizes e arrays multidimensionais com `numpy`.
* **Análise e Engenharia:** Desenvolvimento de scripts para tomadas de decisão complexas (Cálculos de engenharia, tensões, massas e custos).
* **Visualização de Dados:** Geração de matrizes de confusão coloridas, heatmaps e gráficos analíticos avançados usando `matplotlib`.

---

## 🚀 Projetos em Destaque

### 🎮 1. Jogo da Velha Inteligente (Man vs. Machine)
Um script interativo rodando via terminal que coloca o usuário para enfrentar uma inteligência artificial em um tabuleiro clássico de 3x3.
* **Mecanismo de IA:** O computador avalia em tempo real os espaços disponíveis usando *List Comprehension* e escolhe de forma semi-aleatória (`random.choice`) sua jogada estratégica.
* **Engine de Validação:** Varredura iterativa em matrizes de condições de vitória para determinar instantaneamente o campeão ou cenário de empate ("Velha").

### 🧮 2. Sistema de Orçamento Automático de Materiais Compósitos
Script analítico desenvolvido em ambiente Jupyter Notebook/Google Colab voltado à engenharia e análise de custo-benefício de materiais.
* **Dimensionamento Estrutural:** Cálculo automático de diâmetros e massas com base na densidade de diferentes materiais (Aço, Epóxi, Fibra de Vidro, Carbono e Aramida).
* **Matriz de Custo vs. Segurança:** Geração de um mapa de calor visual (Heatmap) cruzando o preço estimado das barras em função do material e do fator de segurança escolhido com `matplotlib`.

### ☁️ 3. Pipeline de Automação de Arquivos e Planilhas (Cloud Data)
Scripts focados em engenharia de dados e automação de rotinas de escritório em nuvem.
* **CRUD de Arquivos:** Upload automatizado de relatórios textuais diretamente para o Google Drive utilizando a API Rest e `MediaFileUpload`.
* **Data Ingestion via Sheets:** Geração automatizada de planilhas no ecossistema Workspace preenchidas dinamicamente via Python através do `gspread`.

---

## 🛠️ Tecnologias, Ferramentas e Bibliotecas

* **Linguagem Principal:** Python 3
* **Ambiente de Desenvolvimento:** Google Colab, Jupyter Notebook, VS Code
* **Bibliotecas de Data Science e Gráficos:** `numpy`, `matplotlib`
* **Integração Cloud:** `gspread`, `pydrive2`, `googleapiclient`
* **Módulos Nativos:** `random`, `math`
│   ├── orcamento_compositos.py  # Script interativo de cálculo de diâmetro e massa
│   └── Orcamento_Graficos.ipynb # Notebook com análise de custo e matriz de calor (Matplotlib)
└── README.md                    # Documentação do repositório
