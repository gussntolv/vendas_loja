# 📊 Análise de Vendas - Loja de Informática

## 🎯 Sobre o Projeto

Este projeto é uma análise de dados realística de uma loja de informática. Foram analisadas 10 vendas para extrair insights de negócio como faturamento total, ticket médio e produtos mais vendidos.

**Motivação:** Praticar análise de dados com pandas e criar um portfólio para a área de Dados.

---

## 📂 Dados Utilizados

Os dados estão no arquivo `vendas_loja.csv` e contêm:

| Coluna | Descrição | Exemplo |
|--------|-----------|---------|
| data | Data da venda | 2024-01-01 |
| produto | Nome do produto | Notebook, Mouse, Teclado, Monitor |
| quantidade | Quantidade vendida | 2 |
| preco_unitario | Preço por unidade (R$) | 2500 |

---

## 🔧 Tecnologias Utilizadas

- **Python** - Linguagem de programação
- **Pandas** - Manipulação e análise de dados
- **Jupyter Notebook** - Ambiente de desenvolvimento

---

## 📊 O que o Projeto Faz

| Tarefa | Descrição |
|--------|-----------|
| ✅ Leitura de CSV | Carrega os dados do arquivo |
| ✅ Feature Engineering | Cria coluna de faturamento (qtd × preço) |
| ✅ Estatísticas | Calcula total, média, máximo |
| ✅ GroupBy | Agrupa faturamento por produto |
| ✅ Filtros | Responde perguntas específicas |
| ✅ Exportação | Salva resultados em CSV |

---

## 📈 Principais Insights

| Métrica | Valor |
|---------|-------|
| Faturamento total | R$ 15.000,00 |
| Ticket médio | R$ 1.500,00 |
| Produto mais vendido (unidade) | Mouse (5 unidades) |
| Produto que mais faturou | Notebook (R$ 10.000,00 - 66,67% do total) |

---

## 🚀 Como Executar

### 1. Clone o repositório
```bash
git clone [https://github.com/gussntolv/vendas_loja.git]
