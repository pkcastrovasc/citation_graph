# Análise de Rede de Citações

Este projeto realiza a análise estrutural de um grafo direcionado que representa uma rede de citações. O código lê os dados do grafo, calcula as métricas estruturais principais, visualiza as distribuições de graus (In-degree e Out-degree) e realiza o ajuste matemático da Lei da Potência (Power Law).

## 📊 Funcionalidades
- **Leitura do Grafo:** Processamento do arquivo `grafo.txt` utilizando a biblioteca `algs4`.
- **Métricas Básicas:** Cálculo do número de vértices (|V|), número de arestas (|E|), densidade e grau médio.
- **Visualização Gráfica:** Geração de histogramas e gráficos de dispersão (escala linear e Log-Log) para as distribuições de *In-degree* e *Out-degree* usando a biblioteca `matplotlib`.
- **Ajuste da Lei da Potência:** Ajuste da distribuição de graus e extração dos parâmetros Gama (Alpha) e xmin utilizando a biblioteca `powerlaw`.

## 📂 Estrutura do Repositório
- `grafo.txt`: Arquivo de texto contendo as ligações do grafo (valores separados por tabulação).
- `requirements.txt`: Lista de dependências e bibliotecas necessárias para a execução local do código.
- `citation_graph.ipynb`: O código principal do projeto com toda a lógica e visualizações.

## 🚀 Como executar o projeto localmente

**Pré-requisitos:** É necessário ter o **Python 3** instalado no computador.

1. **Clonar o repositório:**
   Abre o terminal e executa os seguintes comandos:
   ```bash
   git clone [https://github.com/pkcastrovasc/citation_graph.git](https://github.com/pkcastrovasc/citation_graph.git)
   cd citation_graph
   ```
   
2. **Instalar as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Executar o código:**
Se preferir usar o Jupyter Notebook:

   ```bash
   jupyter notebook citation_graph.ipynb
   ```
(Ou executa o ficheiro .py correspondente, se tiver convertido: python citation_graph.py)
