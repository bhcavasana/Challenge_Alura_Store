# Análise de Desempenho das Lojas AluraStore

## Propósito da Análise

O propósito desta análise é avaliar o desempenho de quatro lojas da AluraStore para fornecer insights que possam auxiliar na tomada de decisão estratégica. Especificamente, o objetivo é determinar qual loja apresenta o menor desempenho geral, considerando várias métricas como faturamento, avaliação dos clientes, custo de frete, etc., para que o Sr. João possa decidir qual loja vender para investir em um novo negócio.

## Estrutura do Projeto e Organização dos Arquivos

O projeto está organizado da seguinte forma:

-   `AluraStoreBr_Finalizado.ipynb`: Este Jupyter Notebook contém todo o código da análise, desde a importação dos dados até a geração dos gráficos e a conclusão final.
-   `loja_1.csv`, `loja_2.csv`, `loja_3.csv`, `loja_4.csv`: Estes arquivos CSV contêm os dados de cada uma das quatro lojas. Os dados incluem informações sobre produtos, categorias, preços, frete, datas de compra, vendedores, locais de compra, avaliações, tipos de pagamento, parcelas, localização (latitude e longitude) e a qual loja a venda pertence.
    -   Os arquivos CSV são carregados diretamente dos URLs:
        -   `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv`
        -   `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv`
        -   `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv`
        -   `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv`

## Exemplos de Gráficos e Insights Obtidos

1.  **Faturamento Total por Loja**:
    
    * Este gráfico de barras compara o faturamento total de cada loja.
    * **Insight**: A Loja 1 tem o maior faturamento (R$ 1.534.509,12), enquanto a Loja 4 tem o menor (R$ 1.384.497,58). Isso indica que a Loja 4 é a menos lucrativa em termos de vendas.
    
    ```
    Loja  Faturamento Total
    0  Loja 1         1534509.12
    1  Loja 2         1488459.06
    2  Loja 3         1464025.03
    3  Loja 4         1384497.58
    ```
    
2.  Outros gráficos e insights podem ser encontrados no notebook para análise de avaliação da compra por loja, custo de frete, etc.

## Instruções para Executar o Notebook

Para executar o notebook e reproduzir a análise, siga as instruções abaixo:

1.  **Pré-requisitos**:
    
    * Certifique-se de ter o Python instalado (versão 3.6 ou superior).
    * Instale as seguintes bibliotecas Python, caso ainda não as tenha:
        
        ```bash
        pip install pandas matplotlib seaborn numpy IPython
        ```
        
2.  **Execução do Notebook**:
    
    * Abra o arquivo `AluraStoreBr_Finalizado.ipynb` usando o Jupyter Notebook, JupyterLab, VS Code com extensão Python ou outra ferramenta que suporte notebooks Jupyter.
    * Execute as células do notebook sequencialmente. Cada célula contém código Python ou texto explicativo.
    * Os resultados da análise, incluindo tabelas e gráficos, serão exibidos diretamente no notebook.
    
3.  **Visualização dos Resultados**:
    
    * Após executar todas as células, revise os resultados e a conclusão final para entender o desempenho de cada loja e a recomendação de venda.

## Conclusão

Com base na análise abrangente, a **Loja 4** apresenta o menor desempenho geral e é a loja recomendada para venda. Esta decisão é fundamentada principalmente no menor faturamento total da Loja 4, que é um indicador chave da saúde financeira da loja. Embora outras métricas tenham sido consideradas, o faturamento foi priorizado na análise final.

A análise completa está detalhada no notebook `AluraStoreBr_Finalizado.ipynb`, incluindo a metodologia de pontuação ponderada e outras considerações relevantes para a decisão.
