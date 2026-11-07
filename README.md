# 🚲 Power BI Portfolio | Casos Práticos - Artefact

Repositório dedicado aos casos práticos de Business Intelligence e Análise de Dados desenvolvidos com base nos desafios de negócio da **Artefact**. O objetivo principal é transformar bases de dados brutas em relatórios executivos dinâmicos, intuitivos e de alto impacto para tomada de decisão (*C-Level*).

---

## 📊 Projetos Desenvolvidos

### 1. Sales & Profit Dashboard (Caso de Vendas)
Painel executivo focado na avaliação de performance comercial global, margens de lucro e segmentação de mercado para uma empresa de comércio de bicicletas.

* **Dimensão do Painel:** 1280x720 (resolução otimizada para apresentações executivas).
* **Identidade Visual (Paleta Oposta / Dark Mode):**
  * **Fundo Geral:** Preto carvão profundo (`#121212`).
  * **Containers/Visuais:** Antracite refinado (`#1E1E1E`).
  * **Tipografia e Eixos:** Branco puro (`#FFFFFF`) para máxima legibilidade.
  * **Cor de Destaque:** Laranja/Coral vibrante (`#FF7A00`) nas linhas e barras principais.
* **Estrutura do Layout:**
  * **Cabeçalho Superior:** Título centralizado com fundo em bloco sólido.
  * **Gráfico Temporal (Topo):** Linha de evolução temporal de vendas/lucro.
  * **Gráficos Inferiores (Lado a Lado):** Análise comparativa por **País** (*Country*) e por **Segmento** (*Segment: Government, Small Business, Enterprise, etc.*).
  * **Rótulos de Dados:** Ativados em todos os visuais para leitura rápida sem necessidade de interação excessiva.

---

### 2. Manufacturing & Costs Dashboard (Caso de Produção)
Painel operacional voltado para o controlo de custos industriais, eficiência de processos e despesas de fabrico.
* *Desenvolvido com foco na ótica de custos e otimização de recursos logísticos e industriais.*

---

## 🛠️ Engenharia de Dados & Tratamento (ETL no Power Query)
Antes da modelagem visual, as bases de dados brutas passaram por um rigoroso processo de limpeza e tratamento no **Power Query**:
* **Padronização de Categoria:** Uniformização de termos inconsistentes (ex: correção de *Smal Business* para *Small Business*, *Enter&rise* para *Enterprise* e *FrancE* para *France*).
* **Limpeza Estrutural:** Remoção de colunas redundantes ou vazias (como a coluna *Product_Name*) para otimizar a performance do modelo relacional.
* **Tipagem de Dados:** Garantia de que colunas numéricas, datas e chaves categóricas estavam configuradas com os tipos corretos para cálculos DAX precisos.

---

## 📁 Estrutura do Repositório
```text
├── datasets/            # Ficheiros de dados limpos e preparados (.xlsx / .csv)
├── reports/             # Ficheiros finais do Power BI (.pbix)
├── screenshots/         # Capturas de ecrã em alta resolução dos dashboards
└── README.md            # Documentação detalhada do projeto
