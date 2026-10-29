# Análise e visualização de Dados das IFES (1996–2026)

## 📋 Sobre o Projeto
 O objetivo principal é aplicar conceitos de agrupamento, transformação e agregação de dados através da biblioteca pandas para fundamentar decisões de visualização. O foco é avaliar e justificar as melhores escolhas gráficas, utilizando as bibliotecas seaborn e matplotlib, para comunicar de forma clara a evolução histórica do investimento público e da força de trabalho nas Instituições Federais de Ensino Superior (IFES) ao longo de um período de três décadas.

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em **Python** utilizando as seguintes bibliotecas[cite: 2, 8]:
* **Pandas**: Manipulação dados.
* **Matplotlib** e **Seaborn**: Geração de visualizações gráficas e gráficos estatísticos.
* **Jupyter Notebook**: Ambiente interativo de desenvolvimento.

## 🚀 Como Executar o Projeto
1. Clone este repositório para a sua máquina:
   ```bash
   git clone [https://github.com/MarinaWang11/Visualizacao_de_Dados_das_IFES.git](https://github.com/MarinaWang11/Visualizacao_de_Dados_das_IFES.git)

   ```

2. Certifique-se de ter o Python instalado, e crie um ambiente virtual com o Conda:


```bash
conda create -n propagacao python=3.12 -y
conda activate propagacao

```


3. Instale as dependências necessárias:
```bash
conda install -c conda-forge pandas seaborn matplotlib jupyter notebook -y

```


4. Abra o VS Code, selecione o kernel correspondente ao seu ambiente e execute o arquivo `.ipynb` célula por célula.



## 📊 Principais Etapas Desenvolvidas

* **Etapa 1:** Exploração e Preparação de Dados: Carregamento da série histórica (1996-2026) e identificação das diferentes ordens de grandeza das variáveis.   

* **Etapa 2:** Evolução Temporal e Ajuste de Escalas: Utilização de agrupamentos (groupby) para analisar o crescimento absoluto dos investimentos e das vagas de estudantes ao longo dos anos. 

* **Etapa 3:** Análise de Proporção da Força de Trabalho: Criação de métricas agregadas para demonstrar a proporção de estudantes por docente e de estudantes por Técnico-Administrativo em Educação (TAE).   

* **Etapa 4:** Correlação entre Fatores e Orçamento: Uso do método agg por períodos históricos para extrair estatísticas descritivas sobre o investimento em assistência estudantil e o total de vagas.   

* **Etapa 5:** Filtragem Condicional de Anos Críticos: Aplicação do método filter para identificar anos em que houve estagnação ou cortes na assistência estudantil, apesar do aumento de vagas.   

* **Etapa 6:** Métricas Customizadas e Escolha de Cores: Criação de uma função personalizada via apply para classificar os anos em diferentes graus de consolidação institucional (ex: "Alta Expansão", "Retração Orçamentária") e seleção de uma paleta de cores adequada no seaborn que traduza intuitivamente esses fenómenos político-económicos.   

## **Autora:** [Marina Rihs Matos Wang](https://github.com/MarinaWang11)
