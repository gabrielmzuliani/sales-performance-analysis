# Sobre o projeto
O projeto de análise de vendas é minha solução referente ao desafio prático proposto pela plataforma Xperiun. Embora o desafio fornecesse um contexto inicial, toda a modelagem, desenvolvimento do dashboard, documentação, interpretação dos resultados e recomendações neste repositório foram desenvolvidas por mim.

# Contexto
Este projeto utiliza uma base de dados fictícia, desenvolvida para simular o contexto de uma empresa do setor esportivo. O objetivo foi construir um dashboard estratégico capaz de consolidar indicadores de desempenho, responder perguntas de negócio e apoiar decisões comerciais baseadas em dados. 

As principais perguntas desenvolvidas no projeto estão listadas abaixo:
* O crescimento observado é sustentável?
* Quais fatores sustentam esse crescimento?
* Quais regiões apresentam maior potencial de expansão?
* Como otimizar o portfólio de produtos para aumentar a rentabilidade?

Você pode realizar o download do dashboard interativo [aqui.]()

# Modelagem dos dados
Depois das etapas de limpeza e organização dos dados, o modelo foi estruturado em três tabelas principais: fVendas (24.543 registros), dRegiões e dCategorias, além da tabela auxiliar dCalendário.

<img width="767" height="395" alt="image" src="https://github.com/user-attachments/assets/fc56da6f-2e13-4bb0-bf82-c0f07a856338" />

Toda a extração, limpeza e modelagem foram realizadas dentro do Power BI, que você encontra [aqui].()

# Sumário Executivo
### Overview
Ao longo dos últimos 12 meses, a empresa apresentou um crescimento consistente, expandindo seu volume de vendas sem comprometer sua rentabilidade. Os resultados indicam não apenas uma expansão das operações, mas também a capacidade de transformar esse crescimento em maior geração de lucro.

Em relação ao período anterior, foram observados os seguintes indicadores:
* **Receita:** +25,47%
* **Quantidade Vendida:** +24,83%
* **Custo dos produtos:** +24,83%
* **Lucro:** +26,28%
* **Margem de lucro:** 44,9%

O aumento da receita ocorreu praticamente na mesma proporção que o aumento do volume vendido, o que indica uma expansão consistente das operações. Ao mesmo tempo, o lucro apresentou um crescimento superior à receita, sugerindo que a empresa conseguiu preservar sua eficiência operacional ao mesmo diante do aumento dos custos.

Esse comportamento indica que o crescimento observado não foi sustentado apenas pelo aumento das vendas, mas também pela capacidade de manter níveis saudáveis de rentabilidade.

No entanto, antes de direcionar novos investimentos, é importante compreender quais fatores sustentam esse crescimento. Identificar regiões e categorias responsáveis pelos melhores resultados permite definir estratégias comerciais mais eficientes e direcionar recursos para mercados com maior potencial de retorno.

### Regiões
Embora as regiões Sudeste e Sul concentrem cerca de 82% do faturamento da empresa, a análise regional mostra que as maiores oportunidades de crescimento não estão necessariamente nos mercados com maior participação. Regiões como Norte e Centro-Oeste apresentam uma combinação mais favorável entre crescimento da receita e margem de lucro, indicando potencial para expansão.

| Região        | Participação da Receita | Crescimento (vs. 2023) | Margem de Lucro |
|---------------|------------------------:|------------------------:|----------------:|
| Sudeste       | 64%                     | +27,49%                    | 44,0%           |
| Sul           | 18%                     | +4,64%                    | 45,0%           |
| Nordeste      | 9%                     | +18,18%                 | 46,7%           |
| Centro-Oeste  | 6%                     | +69,27%                 | 47,8%           |
| Norte         | 4%                      | +122,39%                | 49,4%           |

#### Sudeste
O Sudeste representa 64% da receita total, sendo o principal mercado da empresa. Seu comportamento ao longo de 2024 foi mais estável quando comparado às demais regiões, indicando uma demanda relativamente previsível.

Além disso, aproximadamente metade do faturamento da região está concentrada nas categorias Raquetes e Bolas, evidenciando uma forte dependência das categorias principais do portfólio.

Como consequência, o Sudeste deve ser tratado como um mercado consolidado, no qual estratégias voltadas à eficiência operacional, fidelização e aumento do ticket médio tendem a gerar melhores resultados do que iniciativas focadas apenas na expansão do volume de vendas.

#### Sul






