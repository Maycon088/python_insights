# Análise de cancelamento de clientes

Projeto desenvolvido durante a segunda aula da **Imersão Python**, da **Hashtag Programação**. O objetivo é explorar uma base de clientes, identificar padrões associados ao cancelamento e levantar ações que possam ajudar a reduzir a saída de clientes.

## Conteúdo

- [`analise.ipynb`](./analise.ipynb): notebook com a análise exploratória.
- [`cancelamentos.csv`](./cancelamentos.csv): base de dados utilizada pelo notebook.

## Tecnologias

- Python
- Pandas
- Plotly
- Jupyter Notebook

## Como executar

1. Tenha o Python instalado.
2. Instale as dependências:

   ```bash
   pip install pandas plotly jupyter
   ```

3. Abra o projeto no Jupyter:

   ```bash
   jupyter notebook
   ```

4. Abra `analise.ipynb` e execute as células na ordem, mantendo `cancelamentos.csv` na mesma pasta do notebook.

## Etapas da análise

1. Carregamento da base `cancelamentos.csv`.
2. Remoção da coluna `CustomerID`, que não é usada na análise.
3. Inspeção e remoção de registros com valores ausentes.
4. Contagem e cálculo da proporção de clientes que cancelaram.
5. Geração de histogramas para comparar as variáveis com o status de cancelamento.
6. Avaliação de filtros e possíveis ações relacionados à duração do contrato, às ligações para o call center e aos dias de atraso.

## Dados analisados

A base contém informações como idade, sexo, tempo como cliente, frequência de uso, ligações para o call center, dias de atraso, assinatura, duração do contrato, gasto total, meses desde a última interação e status de cancelamento.

## Observação

Esta é uma análise exploratória para fins de aprendizado. Os padrões observados podem apoiar hipóteses e investigações futuras, mas não demonstram, por si só, que uma característica causa o cancelamento.
