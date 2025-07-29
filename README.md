# 📊 Dashboard de Vendas

Este projeto tem como objetivo apresentar uma análise visual e interativa das vendas, utilizando como base um conjunto de dados de vendas, setores e margens de lucro.

## 🧾 Sobre os Dados

Os dados utilizados estão no arquivo `Base de dados Vendas.xlsx`, e incluem informações como:

- Data da venda
- Setor e produto
- Vendedor e cliente
- Estado e região
- Faturamento, margem de lucro e lucro

Exemplo de registros:
| Data da Venda | Setor      | Produto | Vendedor | Faturamento | Lucro   |
|---------------|------------|---------|----------|-------------|---------|
| 2035-01-01    | Carnes     | Suína   | Amaral   | R$ 633,45   | R$ 82,35|
| 2035-01-01    | Congelados | Sorvete | Leo      | R$ 721,52   | R$ 57,72|

## 📈 Análises no Power BI

Utilizei o Power BI para desenvolver um dashboard com os seguintes elementos:

- Evolução do faturamento por mês
- Comparativo de faturamento entre setores
- Lucro por produto e região
- Performance de vendedores

### 🖼️ Dashboard:

<div align="center">
  <img src="imagens/grafico1.png" width="700px" alt="Faturamento mensal">
  <p><i>Gráfico de faturamento mensal</i></p>

  <img src="imagens/grafico2.png" width="700px" alt="Lucro por setor">
  <p><i>Lucro por setor</i></p>
</div>

## 📂 Estrutura do Projeto

- `base/`: contém a base de dados utilizada
- `dashboard/`: arquivo `.pbix` do Power BI com as análises
- `imagens/`: prints do dashboard exportados do Power BI

## 🛠️ Ferramentas Utilizadas

- Microsoft Power BI
- Excel (organização da base)
