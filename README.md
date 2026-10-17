# 📊 Dashboard de Vendas — Xbox Game Pass

Dashboard desenvolvido em Excel para analisar as vendas de assinaturas do Xbox Game Pass, incluindo planos, periodicidade, renovação automática, benefícios adicionais e evolução mensal da receita.

## 🎯 Objetivo

Transformar os dados de assinaturas em informações gerenciais, facilitando a identificação dos planos e serviços que mais contribuem para o faturamento.

## ❓ Perguntas de negócio

O dashboard responde às seguintes perguntas:

1. Qual é o faturamento total das assinaturas?
2. Quantos assinantes existem na base?
3. Qual é o ticket médio por assinante?
4. Qual é a taxa de renovação automática?
5. Qual plano gera mais receita: Core, Standard ou Ultimate?
6. Qual é a quantidade de assinantes por plano?
7. Qual periodicidade gera mais receita: mensal, trimestral ou anual?
8. Qual é o faturamento dos planos anuais?
9. Quanto foi faturado com o EA Play Season Pass?
10. Quanto foi faturado com o Minecraft Season Pass?
11. Qual é o valor total de cupons concedidos?
12. Como a receita evoluiu ao longo dos meses?
13. Qual é a diferença de receita entre clientes com e sem renovação automática?

## 📌 Principais indicadores

| Indicador | Resultado |
|---|---:|
| Receita total | R$ 7.633,00 |
| Assinantes | 295 |
| Ticket médio | R$ 25,87 |
| Renovação automática | 50,2% |
| Receita EA Play | R$ 2.940,00 |
| Receita Minecraft | R$ 3.880,00 |
| Receita de planos anuais | R$ 1.754,00 |
| Cupons concedidos | R$ 2.122,00 |

**Período analisado:** 01/01/2024 a 16/12/2024.

## 📈 Análises disponíveis

### Receita por plano

| Plano | Receita | Assinantes |
|---|---:|---:|
| Core | R$ 444,00 | 101 |
| Standard | R$ 1.801,00 | 96 |
| Ultimate | R$ 5.388,00 | 98 |

### Receita por periodicidade

| Periodicidade | Receita | Assinantes |
|---|---:|---:|
| Mensal | R$ 3.571,00 | 139 |
| Trimestral | R$ 2.308,00 | 85 |
| Anual | R$ 1.754,00 | 71 |

### Renovação automática

| Renovação | Receita | Assinantes |
|---|---:|---:|
| Sim | R$ 3.786,00 | 148 |
| Não | R$ 3.847,00 | 147 |

## 💡 Principais insights

- O plano **Ultimate** representa aproximadamente **70,6% da receita total**.
- A modalidade **mensal** possui a maior quantidade de assinantes e o maior faturamento.
- A base está praticamente equilibrada entre clientes com e sem renovação automática.
- O Minecraft Season Pass gerou mais receita adicional que o EA Play.
- Dezembro apresenta receita parcial, pois a base termina em **16/12/2024**.

## 📊 Visualizações

O dashboard possui três gráficos principais:

- Receita por plano;
- Receita por periodicidade;
- Evolução mensal da receita.

Também apresenta cards executivos para acompanhamento rápido dos principais indicadores.

## 🗂️ Estrutura do arquivo

| Planilha | Descrição |
|---|---|
| Dashboard | Painel executivo com KPIs e gráficos |
| Dados | Base com 295 registros de assinantes |
| Análises | Cálculos e tabelas auxiliares dos gráficos |

## 🛠️ Recursos utilizados

- Microsoft Excel;
- Tabelas estruturadas;
- Fórmulas `SUM`, `SUMIFS`, `COUNTIF`, `COUNTA`, `MIN` e `MAX`;
- Formatação condicional;
- Gráficos de colunas, rosca e linhas;
- Indicadores dinâmicos;
- Formatação corporativa inspirada na identidade visual do Xbox.

## ▶️ Como utilizar

1. Faça o download do arquivo Excel;
2. Abra-o no Microsoft Excel;
3. Acesse a planilha **Dashboard**;
4. Consulte os indicadores e gráficos;
5. Utilize a planilha **Dados** para analisar os registros individuais.

Os indicadores estão vinculados à base por fórmulas e são recalculados quando os dados existentes são atualizados.

## 📷 Prévia do dashboard

Adicione uma imagem do dashboard ao repositório e utilize:

![Dashboard Xbox Game Pass](images/dashboard-xbox.png)

## 📚 Contexto

Projeto desenvolvido como parte de um desafio de curso, com foco na organização de dados, criação de indicadores e construção de dashboards corporativos no Excel.

## 👤 Autor

**Rodrigo Tulio**

---

⭐ Caso este projeto seja útil, deixe uma estrela no repositório.
