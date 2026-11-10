# Olá, eu sou o Gabriel 👋

**Analista Financeiro** em uma cooperativa de crédito, formado em Administração e cursando **pós-graduação em Engenharia de Dados & IA**. No dia a dia de contas a pagar, conciliação e classificação contábil, eu transformo rotinas manuais em **automações, painéis e controles com dados**.

Os projetos abaixo nasceram de problemas reais do meu trabalho e foram **reescritos com dados 100% fictícios** para poderem ser públicos.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black) ![Excel](https://img.shields.io/badge/Excel%20%2F%20VBA-217346?logo=microsoftexcel&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)

## Projetos

### Dados e SQL
| Projeto | O que resolve | Stack |
|---|---|---|
| [**sql-analise-contas-a-pagar**](https://github.com/Gabriel9719/sql-analise-contas-a-pagar) | Modelo estrela + 11 consultas analíticas (aging, curva ABC, LAG, ranking, conciliação com FULL OUTER JOIN, qualidade de dados). Mesmo SQL validado em SQLite e PostgreSQL | SQL · SQLite · PostgreSQL · CI |
| [**radar-contas-a-pagar**](https://github.com/Gabriel9719/radar-contas-a-pagar) | Painel gerencial de contas a pagar: regra D+3, pontualidade, YoY em período equivalente, ABC dinâmica | Power BI · DAX · Power Query |
| [**painel-reembolsos-cartoes-prepagos**](https://github.com/Gabriel9719/painel-reembolsos-cartoes-prepagos) | Reembolsos, limite de manutenção dos cartões, prazo de prestação de contas e conciliação do fundo fixo | Python ETL · Power BI |

### Automação com Python
| Projeto | O que resolve | Stack |
|---|---|---|
| [**conferencia-fatura-cartao-corporativo**](https://github.com/Gabriel9719/conferencia-fatura-cartao-corporativo) | Lê a fatura em PDF e concilia cada compra com a contabilidade (estornos, compras internacionais, virada de ano) | pdfplumber · pandas · openpyxl |
| [**analise-resgates-capital**](https://github.com/Gabriel9719/analise-resgates-capital) | Integra 5 bases, detecta concentração de exceções com critério estatístico e gera Excel + PowerPoint automaticamente | pandas · python-pptx · matplotlib |

### Excel e VBA
| Projeto | O que resolve | Stack |
|---|---|---|
| [**controle-despesas-recorrentes**](https://github.com/Gabriel9719/controle-despesas-recorrentes) | Quais fornecedores recorrentes não enviaram a fatura do mês, com alertas por e-mail roteados por PA/departamento | Excel · VBA (Outlook) |
| [**conciliacao-livro-razao**](https://github.com/Gabriel9719/conciliacao-livro-razao) | Conciliação razão × pré-registros só com fórmulas (sem macros), validada contra Python | Excel · LibreOffice · pytest |
| [**exportador-arquivo-bancario**](https://github.com/Gabriel9719/exportador-arquivo-bancario) | Remessa bancária de largura fixa (200 posições) com layout declarativo, validação de CPF/CNPJ e leitura de volta | Python · VBA |

### Apps web
| Projeto | O que resolve | Stack |
|---|---|---|
| [**auditoria-retencoes-nfse**](https://github.com/Gabriel9719/auditoria-retencoes-nfse) | Lê a DANFSe em PDF no navegador e confere ISS, IRRF, PIS/COFINS/CSLL e INSS **antes** do pagamento | JavaScript · pdf.js |
| [**manual-contabilizacao**](https://github.com/Gabriel9719/manual-contabilizacao) | Manual de classificação contábil gerado a partir do histórico do Livro Razão, com gerador de histórico padronizado | HTML/JS · Python |

## Como eu trabalho
- **Problema real primeiro**: cada projeto começa numa dor do contas a pagar.
- **Regras testadas**: todo repositório tem testes automatizados rodando no GitHub Actions.
- **Dados fictícios com problemas plantados**: os geradores criam duplicidades, divergências e exceções de propósito, e os testes provam que as análises as encontram.

## Contato
[LinkedIn](https://www.linkedin.com/in/gabriel-ant%C3%B4nio-ribeiro-017808210)
