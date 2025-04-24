# Análise de Desempenho das Lojas AluraStore

## Propósito da Análise

O propósito desta análise é avaliar o desempenho de quatro lojas da AluraStore para fornecer insights que possam auxiliar na tomada de decisão estratégica. Especificamente, o objetivo é determinar qual loja apresenta o menor desempenho geral, considerando várias métricas como faturamento, avaliação dos clientes, custo de frete, etc., para que o Sr. João possa decidir qual loja vender para investir em um novo negócio.

## Estrutura do Projeto e Organização dos Arquivos

O projeto está organizado da seguinte forma:

-   `AluraStoreBr_Finalizado.ipynb`: Este Jupyter Notebook contém todo o código da análise, desde a importação dos dados até a geração dos gráficos e a conclusão final.
-   `loja_1.csv`, `loja_2.csv`, `loja_3.csv`, `loja_4.csv`: Estes arquivos CSV contêm os dados de cada uma das quatro lojas. Os dados incluem informações sobre produtos, categorias, preços, frete, datas de compra, vendedores, locais de compra, avaliações, tipos de pagamento, parcelas, localização (latitude e longitude) e a qual loja a venda pertence.

## Exemplos de Gráficos e Insights Obtidos

1.  **Faturamento Total por Loja**:
    
    * Este gráfico de barras compara o faturamento total de cada loja.
    * **Insight**: A Loja 1 tem o maior faturamento, enquanto a Loja 4 tem o menor. Isso indica que a Loja 4 pode ser a menos lucrativa em termos de vendas.
    
    <div align="center">
    <img src="seu_diretorio_para_a_imagem/faturamento_total_por_loja.png" alt="Faturamento Total por Loja" width="400"/>
    </div>
    
2.  **Média de Avaliação da Compra por Loja**:
    
    * Este gráfico de barras mostra a média das avaliações dos clientes para cada loja.
    * **Insight**: A Loja 1 tem a menor média de avaliação, sugerindo que os clientes estão menos satisfeitos com essa loja em comparação com as outras.
    
    <div align="center">
    <img src="seu_diretorio_para_a_imagem/media_avaliacao_por_loja.png" alt="Média de Avaliação da Compra por Loja" width="400"/>
    </div>
    
3.  **Custo Médio de Frete por Loja**:
    
    * Este gráfico de barras compara o custo médio de frete de cada loja.
    * **Insight**: A Loja 1 tem o custo de frete mais alto, o que pode impactar a lucratividade das vendas dessa loja.
    
    <div align="center">
    <img src="seu_diretorio_para_a_imagem/custo_frete_por_loja.png" alt="Custo Médio de Frete por Loja" width="400"/>
    </div>

## Instruções para Executar o Notebook

Para executar o notebook e reproduzir a análise, siga as instruções abaixo:

1.  **Pré-requisitos**:
    
    * Certifique-se de ter o Python instalado (versão 3.6 ou superior).
    * Instale as seguintes bibliotecas Python, caso ainda não as tenha:
        
        ```bash
        pip install pandas matplotlib seaborn numpy
        ```
        
        Se você estiver usando o Jupyter Notebook, você também precisará do IPython:
        
        ```bash
        pip install ipython
        ```
        
2.  **Execução do Notebook**:
    
    * Abra o arquivo `AluraStoreBr_Finalizado.ipynb` usando o Jupyter Notebook, JupyterLab, VS Code com extensão Python ou outra ferramenta que suporte notebooks Jupyter.
    * Execute as células do notebook sequencialmente. Cada célula contém código Python ou texto explicativo.
    * Os resultados da análise, incluindo tabelas e gráficos, serão exibidos diretamente no notebook.
    
3.  **Visualização dos Resultados**:
    
    * Após executar todas as células, revise os resultados e a conclusão final para entender o desempenho de cada loja e a recomendação de venda.

## Conclusão

Com base na análise abrangente, a **Loja 4** apresenta o menor desempenho geral e é a loja recomendada para venda. Esta decisão é fundamentada principalmente no menor faturamento total da Loja 4, que é um indicador chave da saúde financeira da loja. Embora outras métricas tenham sido consideradas, o faturamento foi priorizado na análise final.

---

Este README fornece um resumo completo do projeto, permitindo que outros entendam facilmente o propósito, a estrutura e os resultados da análise, além de fornecer instruções claras para reproduzir a análise.
