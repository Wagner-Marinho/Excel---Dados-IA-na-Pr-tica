# Excel---Dados-IA-na-Pr-tica
Utilizando excel para criar uma tabela de investimento.
# 📈 WM - Invest | Planejador de Investimentos & Simulador de FIIs

Este repositório contém o resumo explicativo do arquivo de planilha **`WM - Invest.xlsx`**, desenvolvido para planejamento financeiro, simulação de juros compostos a longo prazo e distribuição percentual de aportes em Fundos de Investimento Imobiliário (FIIs) com base no perfil de investidor.

---

## 📑 Estrutura da Planilha

A planilha é composta por **duas abas principais**:

1. **`Invest`**: Aba interativa onde ocorrem as simulações financeiras e a divisão dos aportes mensais em FIIs.
2. **`Inf.`**: Aba de referência/matriz contendo as regras de alocação de carteira de acordo com cada perfil de risco.

---

## 🔍 Detalhamento dos Conteúdos

### 1. Aba `Invest` (Simulador & Alocação)

A aba é dividida em três seções principais de análise:

#### 💵 A. Informações Financeiras Base
* **Salário Base**: R$ 1.700,00
* **Rendimento da Carteira (Mês)**: ~1,03%
* **Sugestão de Aporte Recomendada (30% do Salário)**: R$ 510,00

---

#### ⏱️ B. Simulador de Projeção de Patrimônio (Juros Compostos)
Parâmetros simulados para projeção de acúmulo de capital:
* **Aporte Mensal**: R$ 200,00
* **Horizonte de Tempo (Padrão)**: 5 Anos
* **Taxa de Rendimento Mensal**: 1,04%

**Projeções Calculadas por Período:**

| Tempo (Anos) | Patrimônio Acumulado | Dividendos Mensais Estimados |
| :---: | :---: | :---: |
| **2 anos** | R$ 5.420,36 | R$ 55,83 |
| **5 anos** | R$ 16.545,65 | R$ 170,42 |
| **10 anos** | R$ 47.326,76 | R$ 487,47 |
| **20 anos** | R$ 211.124,24 | R$ 2.174,58 |
| **30 anos** | R$ 778.025,92 | R$ 8.013,67 |

---

#### 📊 C. Distribuição de Aporte em FIIs (Perfil Atual: **Agressivo**)
Com um aporte planejado de **R$ 200,00/mês**, a planilha divide os recursos entre diferentes segmentos de Fundos Imobiliários:

| Tipo de FII | Percentual Sugerido | Valor Aportado (R$) |
| :--- | :---: | :---: |
| **Papel** | 50% | R$ 100,00 |
| **Tijolo** | 10% | R$ 20,00 |
| **Híbrido** | 5% | R$ 10,00 |
| **FOFs (Fundos de Fundos)** | 5% | R$ 10,00 |
| **Desenvolvimento** | 20% | R$ 40,00 |
| **Hotelarias** | 10% | R$ 20,00 |
| **TOTAL** | **100%** | **R$ 200,00** |

---

### 2. Aba `Inf.` (Matriz de Perfis de Investidor)

Esta aba define a matriz de alocação estratégica (%) para os perfis **Conservador**, **Moderado** e **Agressivo**:

| Perfil | Papel | Tijolo | Híbrido | FOFs | Desenvolvimento | Hotelarias | Total |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Conservador** | 30% | 50% | 10% | 10% | 0% | 0% | 100% |
| **Moderado** | 32% | 35% | 8% | 5% | 10% | 10% | 100% |
| **Agressivo** | 50% | 10% | 5% | 5% | 20% | 10% | 100% |

---

## 🛠️ Tecnologias e Formatos
* **Formato**: Microsoft Excel (`.xlsx`)
* **Uso**: Planejamento de Finanças Pessoais & Renda Passiva com FIIs
