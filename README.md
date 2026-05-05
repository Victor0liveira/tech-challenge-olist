# 📊 Tech Challenge — Análise E-commerce Olist

Análise estratégica do Brazilian E-Commerce Public Dataset by Olist,
desenvolvida como projeto final da Fase 1 do curso DTAT — POSTECH.

## 🎯 Objetivo

Transformar dados transacionais em recomendações acionáveis para
investidores e acionistas do setor de e-commerce brasileiro.

## 📁 Estrutura do Repositório

├── notebooks/
│   └── analise_olist.ipynb   # Notebook principal com toda a análise
├── assets/
│   ├── receita_mensal.png    # Evolução de receita e ticket médio
│   ├── satisfacao.png        # Avaliações e tempo de entrega
│   └── categorias.png        # Top 10 categorias por receita
└── README.md

## 📈 Principais Achados

| Indicador | Resultado |
|---|---|
| Receita total (2016–2018) | R$ 12,4 milhões |
| Total de pedidos | 90.126 |
| Ticket médio | R$ 132,99 |
| Nota média dos clientes | 4,16 / 5,0 |
| Clientes satisfeitos (nota 4–5) | 78,9% |
| Tempo médio de entrega (nota 5) | 10,2 dias |
| Tempo médio de entrega (nota 1) | 20,8 dias |

## 🔍 Trilhas Analisadas

- **Crescimento e Receita:** evolução mensal, sazonalidade e ticket médio
- **Satisfação do Cliente:** distribuição de notas e impacto do prazo de entrega
- **Top Categorias:** ranking de receita por segmento de produto

## 🎯 Recomendações

1. **Logística em primeiro lugar** — reduzir lead time de 12 para 7 dias
2. **Investir nas top 3 categorias** — Beleza, Relógios e Cama/Mesa/Banho
3. **Sazonalidade planejada** — campanhas estruturadas para outubro/novembro

## 🛠️ Tecnologias

- Python 3 · Pandas · Matplotlib · Seaborn
- Google Colab
- Dataset: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
