# Nota do CFO: Licenças (despachante digital de AET)

> **Como ler as tabelas:** $ = R$. "A day" significa **licenças emitidas naquele mês** (o modelo usa 1 "dia" por mês).
> **Premissas:** R$ 60 de honorário por licença. As taxas dos órgãos (DNIT/DER) são **repassadas** ao cliente e ficam fora da receita. Cada transportadora tira **5 AETs por mês** (informado pelo fundador). O ritmo é **ilustrativo**: 3 transportadoras no mês 1, mais 2 por mês, chegando a 25 no mês 12 (125 licenças/mês). Troque pelo número real.

- **A margem:** cada licença deixa **R$ 58,20** depois da taxa de cobrança (estimativa de 3%). Com 125 licenças por mês, a margem é de **93%**. É um negócio de software: o custo quase não cresce com o volume.
- **O ponto de equilíbrio:** **6 licenças por mês**, ou seja, **2 transportadoras**, pagam o servidor (estimativa de R$ 300/mês).
- **Ano 1 (exemplo):** **R$ 45.288** de lucro operacional sobre R$ 50.400 de receita, antes de impostos.
- **O número a vigiar: quantas transportadoras você conquista.**

| Cenário (ano 1) | Lucro |
|---|---:|
| Metade das transportadoras | R$ 20.844 |
| **Base do exemplo** (25 no mês 12) | **R$ 45.288** |
| O dobro (50 no mês 12) | R$ 94.176 |
| 4 vezes (100 no mês 12) | R$ 191.952 |
| Honorário de R$ 80 (base) | R$ 62.088 |
| Honorário −10% (R$ 54) | R$ 40.248 |

- **Caixa:** praticamente zero, porque a sua empresa banca o desenvolvimento. **Atenção:** o custo do software (horas de desenvolvimento e manutenção de cada integração com DER) não entrou na conta porque não foi informado. Ele existe, mesmo que não saia do seu bolso.
- **O que não está incluído:** seu tempo; manutenção quando um órgão muda o sistema; impostos (Simples Nacional, a confirmar com contador); custo para conquistar cada transportadora; e quem resolve os pedidos indeferidos.

**Três formas de melhorar a margem:**
1. **Mais transportadoras:** cada uma rende cerca de R$ 291/mês (5 × R$ 58,20) e quase não aumenta o custo.
2. **Honorário de R$ 80** em vez de R$ 60: +R$ 16.800 no ano 1 do exemplo, se o mercado aceitar (`/founder-competitors` mostra o que os despachantes cobram).
3. **Mensalidade por caminhão** (sugestão do conselho): torna a receita previsível e paga as renovações automáticas. Precisa ser testada.

**Condições do conselho (`founder/board.md`):**
- [x] Regra de preço: taxas repassadas, R$ 60 de honorário.
- [x] Volume por cliente: 5 AETs/mês (informado; validar com mais transportadoras).
- [ ] Custo do software e da manutenção: **não informado**.
- [ ] Custo de conquistar cada transportadora: **desconhecido**.
- [ ] Automação aceita pelos órgãos: **não provada** (ver `founder/regulacao.md`).

*Isto não é aconselhamento financeiro, fiscal ou jurídico. Um contador deve conferir impostos e estrutura.*

---

# Unit economics: Licenças (despachante digital de AET)

Every number below comes from the input file. Nothing is looked up or guessed.

## One licença (AET) emitida

| line | per licença (AET) emitida |
| --- | ---: |
| Price | $60.00 |
| Taxa de cobrança Pix/boleto/cartão (ESTIMATIVA ~3%) | -$1.80 |
| **Contribution** (what each licença (AET) emitida leaves to pay the fixed costs) | **$58.20** (97%) |

## The margin that matters

Fixed costs: $300 a month (Servidor/hospedagem do robô (ESTIMATIVA, não informado) $300).

- **Break-even: 6 licença (AET) emitidas a day.** Below that you lose money every month.
- **Profit margin at your plan** (125 a day): **93%** of every sale, after every cost.

## Year 1, month by month

| month | licença (AET) emitidas a day | revenue | profit | cumulative (after $0 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 15 | $900 | $573 | $573 |
| 2 | 25 | $1,500 | $1,155 | $1,728 |
| 3 | 35 | $2,100 | $1,737 | $3,465 |
| 4 | 45 | $2,700 | $2,319 | $5,784 |
| 5 | 55 | $3,300 | $2,901 | $8,685 |
| 6 | 65 | $3,900 | $3,483 | $12,168 |
| 7 | 75 | $4,500 | $4,065 | $16,233 |
| 8 | 85 | $5,100 | $4,647 | $20,880 |
| 9 | 95 | $5,700 | $5,229 | $26,109 |
| 10 | 105 | $6,300 | $5,811 | $31,920 |
| 11 | 115 | $6,900 | $6,393 | $38,313 |
| 12 | 125 | $7,500 | $6,975 | $45,288 |

- **Year 1 operating profit: $45,288** on $50,400 of revenue.
- After the $0 startup spend: $45,288.
- Startup money earned back: month 1.
- Cash you need before it pays for itself: **$0**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 93% | 6 | $45,288 |
| Price -10% | 92% | 6 | $40,248 |
| Volume -20% | 92% | 6 | $35,510 |
| Unit costs +15% | 93% | 6 | $45,061 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
