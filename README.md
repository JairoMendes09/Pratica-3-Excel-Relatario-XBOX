# Prática 3 Excel - Relatário XBOX
# 🎮 Xbox Game Pass — Relatório de Assinaturas e Vendas

Dashboard interativo e modelo relacional em Excel desenvolvido para análise de dados de assinaturas da plataforma Xbox, controle de planos (Core, Standard e Ultimate), renovações automáticas, passes de temporada (EA Play e Minecraft) e métricas de faturamento.

---

## 🚀 Sobre o Projeto

Este projeto faz parte de um estudo prático de análise de dados aplicada a negócios no ecossistema de games. A ferramenta foi estruturada para centralizar o banco de dados de assinantes, aplicar regras de negócio através de fórmulas avançadas e tabelas dinâmicas, e apresentar os principais indicadores de desempenho (KPIs) comerciais e de retenção.

---

## 📂 Estrutura da Planilha

A workbook está organizada em abas modulares que separam a identidade visual, o banco de dados transacional, as análises de negócio e o painel visual:

1. **`Assets`**: Guia de identidade visual contendo a paleta de cores oficial inspirada na marca Xbox (verde vibrante, tons complementares e zonas de destaque) e ativos gráficos.
2. **`Bases`**: A base de dados transacional contendo o histórico completo dos assinantes, tipos de planos e valores agregados.
3. **`Cálculos`**: Área de suporte analítico onde foram estruturadas as respostas para perguntas de negócio específicas por meio de tabelas dinâmicas e consolidações.
4. **`Dashboard`**: Painel visual executivo (KPIs e gráficos) com os principais indicadores consolidados para tomada de decisão.

---

## 📊 Dicionário de Dados (`Bases`)

A tabela principal de assinaturas armazena os seguintes atributos por cliente:

| Coluna | Descrição |
| :--- | :--- |
| `Subscriber ID` | Identificador único do assinante. |
| `Name` | Nome completo do cliente. |
| `Plan` | Categoria do plano de assinatura (**Core**, **Standard** ou **Ultimate**). |
| `Start Date` | Data de início da vigência da assinatura. |
| `Auto Renewal` | Status de renovação automática (`Yes` / `No`). |
| `Subscription Price` | Preço base do plano principal. |
| `Subscription Type` | Periodicidade de cobrança (**Monthly**, **Quarterly** ou **Annual**). |
| `EA Play Season Pass` | Adesão ao passe de temporada do EA Play (`Yes` / `No`). |
| `EA Play Season Pass Price` | Valor agregado do passe EA Play. |
| `Minecraft Season Pass` | Adesão ao passe de temporada do Minecraft. |
| `Minecraft Season Pass Price` | Valor agregado do passe Minecraft. |
| `Coupon Value` | Desconto aplicado via cupons promocionais. |
| `Total Value` | Valor líquido total faturado por transação. |

---

## 💡 Perguntas de Negócio Respondidas

A aba de **Cálculos** resolve questionamentos estratégicos essenciais para o negócio:

* **Pergunta 1:** Qual o faturamento total de vendas de planos anuais considerando todas as assinaturas agregadas?
* **Pergunta 2:** Qual o faturamento total de planos anuais segmentado pelo status de **Auto Renovação** (`Yes` vs `No`)?
* **Pergunta 3:** Qual o volume total de vendas de assinaturas e passes do **EA Play** agrupados por categoria de plano?
* **Pergunta 4:** Qual o faturamento gerado pelos passes de temporada do **Minecraft** por tipo de plano?

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Microsoft Excel:** Modelagem de dados, funções condicionais e financeiras, formatação condicional e Tabelas Dinâmicas.
* **Design de Dashboards:** Aplicação de conceitos de UI/UX para planilhas corporativas, paleta de cores temática e hierarquia visual.
* **Git & GitHub:** Versionamento de código e documentação técnica.

---

## 📥 Como Utilizar

1. Faça o download do arquivo `Relatorio XBOX.xlsx` diretamente deste repositório.
2. Abra a planilha no Microsoft Excel para interagir com o modelo.
3. Navegue até a aba **Dashboard** para visualizar os gráficos de faturamento e comportamento dos usuários.
4. Consulte a aba **Bases** caso queira auditar os registros transacionais individuais.

---

## 📌 Licença
Este projeto é de uso livre para fins educacionais, portfólios de análise de dados e estudos de inteligência de mercado. Sinta-se à vontade para clonar e sugerir melhorias!
