---
title: "BDI: o cálculo que faz você perder dinheiro sem perceber"
description: "BDI é o que separa orçamento que dá lucro de orçamento que sangra a empresa. A maioria das empreiteiras pequenas erra. Aqui como calcular certo, com exemplos numéricos."
pubDate: 2026-05-07
tags: ["BDI", "Orçamento", "Margem"]
author: "Reginaldo Rodrigues"
readingTime: "8 min de leitura"
---

Você fechou uma obra de R$ 200 mil. No fim do mês, olha o extrato e percebe: não sobrou nada. Pior, faltou pra pagar o último carregamento de cimento.

Como assim? O cliente pagou tudo. Os funcionários receberam. Os materiais foram comprados. Mas o lucro evaporou.

Resposta provável: BDI calculado errado.

O BDI (Benefícios e Despesas Indiretas) é o número que separa orçamento profissional de orçamento amador. E a maioria das empreiteiras pequenas no Brasil erra esse cálculo. Não por preguiça — por desconhecer a fórmula correta. Ou por copiar planilha de WhatsApp que está errada há anos.

Esse artigo mostra:

- O que é BDI de verdade (não a versão simplificada que a maioria aprende)
- A fórmula completa, com exemplo numérico de uma obra de R$ 200 mil
- Os 4 erros mais comuns que custam dinheiro mês após mês
- Como o RR Engine calcula o BDI automaticamente baseado no perfil da sua empresa

## O que é BDI, na prática

BDI é o percentual que você adiciona em cima do **custo direto** (mão de obra + material + equipamento de uma obra específica) pra cobrir os **custos indiretos** que existem mesmo quando você não está executando: aluguel do escritório, contador, software, conta de luz da sede, salário do administrativo, marketing.

E mais o **lucro** — porque empresa não existe pra empatar.

Se você pega um custo direto de R$ 100 mil e aplica BDI de 25%, sua proposta vai por R$ 125 mil. Os R$ 25 mil cobrem indiretos + lucro + tributos.

Parece simples. **Não é.**

## A fórmula completa do BDI

A fórmula reconhecida pela ABNT (NBR 12721) e usada em licitações públicas é:

```
BDI = ((1 + AC + S + R + G) × (1 + DF) × (1 + L)) / (1 - I) - 1
```

Onde:

- **AC** = Administração Central (escritório, equipe administrativa, software, contador)
- **S** = Seguros (RC, vida, responsabilidade civil profissional)
- **R** = Riscos (imprevistos, retrabalho, perda)
- **G** = Garantias (caução, seguro garantia exigido em contrato)
- **DF** = Despesas Financeiras (capital de giro, juros)
- **L** = Lucro líquido pretendido
- **I** = Tributos sobre faturamento (PIS + COFINS + ISS + CSLL + IRPJ, conforme regime)

A diferença entre essa fórmula e a "simplificada" que circula em planilhas de WhatsApp é que **os tributos NÃO somam, eles dividem**.

Por que isso importa? Porque imposto incide sobre o preço final, não sobre o custo. Quando você divide por `(1 - I)`, está dizendo: "o preço final precisa ser tal que, depois de pagar imposto, ainda sobre o que eu calculei".

## Exemplo numérico — obra de R$ 200 mil de custo direto

Vamos calcular o BDI pra uma empreiteira pequena no Simples Nacional, faixa V (alíquota efetiva ~14%):

| Componente | Percentual |
|------------|-----------|
| Administração Central (AC) | 4% |
| Seguros (S) | 0,8% |
| Riscos (R) | 1,5% |
| Garantias (G) | 0,3% |
| Despesas Financeiras (DF) | 1% |
| Lucro pretendido (L) | 8% |
| Tributos (I) | 14% |

Aplicando a fórmula:

```
BDI = ((1 + 0,04 + 0,008 + 0,015 + 0,003) × (1 + 0,01) × (1 + 0,08)) / (1 - 0,14) - 1
BDI = (1,066 × 1,01 × 1,08) / 0,86 - 1
BDI = 1,1631 / 0,86 - 1
BDI = 1,3525 - 1
BDI = 0,3525  →  35,25%
```

**Preço final** = R$ 200.000 × (1 + 0,3525) = **R$ 270.500**

Decomposição do BDI:

- Custo direto: R$ 200.000 (74%)
- Indiretos administrativos: ~R$ 12.000 (4,4%)
- Despesas financeiras: ~R$ 2.700 (1%)
- Lucro líquido pretendido: R$ 16.000 (5,9%)
- Tributos: R$ 37.870 (14%)
- Margens de risco/seguros/garantias: ~R$ 4.930

A maioria das empreiteiras chuta "uns 25%" em cima do custo. Aplicando 25% nessa mesma obra: R$ 250.000. Diferença: **R$ 20.500 a menos no bolso, todo mês, em cada obra**. Em 5 obras por ano, R$ 102 mil de prejuízo invisível.

## Os 4 erros mais comuns

### 1. Esquecer que os tributos dividem, não somam

O erro mais comum em planilha de WhatsApp:

```
BDI errado = AC + S + R + G + DF + L + I
```

Esse cálculo subestima o BDI em 3-5 pontos percentuais. Em obra de R$ 200 mil, são R$ 6 a 10 mil que você deixa na mesa.

Por que está errado? Porque imposto não é "mais um custo somado". Imposto incide sobre o preço de venda. Você precisa do preço final tal que, depois do imposto, sobre o lucro que você quer.

### 2. Ignorar despesas financeiras

A maioria assume DF = 0. Errado. Sua obra dura 90 dias. O cliente paga 30/60/90. Você precisa pagar fornecedor à vista, salário toda semana. Esse capital de giro tem custo, mesmo que você use dinheiro próprio (custo de oportunidade).

DF realista pra empreiteira pequena: 1% a 2,5%, dependendo do prazo de pagamento que o cliente pediu.

### 3. Subestimar Riscos

Riscos são **certeza estatística**. Não é "se" — é "quando". Vai chover, vai ter retrabalho, vai sumir material, fornecedor vai atrasar.

Empreiteira pequena que coloca R = 0% paga isso quando der ruim. E sempre dá ruim em pelo menos uma obra do ano.

R realista: 1,5% a 3%, dependendo do tipo de obra. Reforma residencial em prédio antigo é mais arriscada que construção nova em terreno limpo.

### 4. Esquecer Lucro Líquido

O erro fatal: confundir margem com lucro.

Algumas empreiteiras colocam "lucro = 10%" e ficam felizes. Mas esse 10% é antes do imposto. Depois de pagar Simples (ou Lucro Presumido), sobra ~6%. Tira despesa financeira não prevista, sobra 4%. Tira pró-labore que você não considerou, sobra 2%.

**Lucro líquido pretendido** é o que SOBRA depois de tudo. Pra empreiteira pequena profissionalizada, alvo é 5% a 12%. Abaixo disso, o negócio não cresce. Acima, você fica caro e perde obra.

## Como calcular BDI sem errar

Tem 3 caminhos:

**1. Planilha Excel feita do zero por você ou contador**, baseada na fórmula ABNT. Funciona, mas exige manutenção. Toda vez que muda alíquota, você atualiza. Cada faixa do Simples tem alíquota diferente. Dá trabalho.

**2. Software de orçamentação tradicional** (Volare, Sienge). Calcula certo, mas custa R$ 500 a R$ 2.000/mês. E você precisa saber preencher 50 campos pra cada obra.

**3. RR Engine.** Você cadastra o regime tributário e os percentuais base da empresa uma vez. O sistema aplica a fórmula automaticamente em cada orçamento, com a alíquota correta da sua faixa. O BDI vem calculado certo, em 10 minutos, sem você precisar lembrar da fórmula.

E mais — o RR Engine mostra a **decomposição do BDI** na proposta final. Cliente exigente vê AC, S, R, G, DF, L, I separados. Vira sinal de profissionalismo.

## Quanto isso muda nas suas finanças

Imagine sua operação atual: 12 obras/ano, ticket médio de custo direto R$ 150 mil. Volume: R$ 1,8 milhão de custo direto.

Cenário A — BDI errado a 25%: receita R$ 2,25 milhões, lucro líquido real ~3% = **R$ 67 mil/ano**

Cenário B — BDI certo a 35%: receita R$ 2,43 milhões, lucro líquido real ~7% = **R$ 170 mil/ano**

Diferença: **R$ 103 mil/ano**, sem trabalhar mais. Só calculando certo.

## Próximo passo

Se você quer aplicar o BDI correto sem ter que decorar fórmula, o RR Engine faz isso pra você. Cadastra o regime tributário da empresa, os percentuais base, e cada orçamento sai com BDI calculado conforme a NBR 12721.

[Testa grátis](https://engine.rres.com.br/sign-up). Em 10 minutos você vê seu primeiro orçamento com BDI decomposto, memória de cálculo SINAPI e proposta comercial pronta.

Sem decorar fórmula. Sem planilha de WhatsApp. Sem perder R$ 100 mil por ano sem perceber.
