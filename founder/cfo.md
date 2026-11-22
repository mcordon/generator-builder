# Nota do CFO: ScSuporte WL

> **Como ler as tabelas abaixo:** a ferramenta escreve "$" e "a day" (por dia). Aqui, **$ = R$**, e "a day" significa **computadores ativos pagando naquele mês** (o modelo usa 1 "dia" por mês, porque a cobrança é mensal).
>
> **Atenção:** o ritmo de crescimento (10 computadores novos por mês, chegando a 120 no mês 12) **é um exemplo ilustrativo, não uma previsão**. Ele equivale a fechar 1 empresa nova de 10 computadores por mês. Troque pelo seu número real quando souber.

- **A margem:** cada computador paga R$ 40 e deixa **R$ 38,80** depois da taxa de cobrança (estimativa de 3%). Com 120 computadores, a margem de lucro é de **84%**.
- **O ponto de equilíbrio:** **16 computadores ativos** pagam o servidor de R$ 600. Com imposto estimado em 6% (Simples Nacional, a confirmar com contador), são **17**. Acima disso, quase toda a receita vira lucro.
- **A taxa inicial de R$ 1.500** não entra nas tabelas. No exemplo (1 empresa nova por mês), ela soma **R$ 18.000 no ano 1**, além dos **R$ 23.064** de lucro operacional das mensalidades: cerca de **R$ 41.000 no ano 1**, antes de impostos e sem contar o seu tempo.
- **O número a vigiar: o volume de clientes**, não o custo. Com metade do volume (`--volume 0.5`), o lucro do ano 1 cai para R$ 7.932. Com preço de R$ 30, cai para R$ 15.264. Com custos 15% maiores, quase não muda (R$ 22.924).
- **Caixa:** com investimento inicial zero, faltariam só **R$ 212** no mês 1. Mas esse número ignora custos não informados: seu tempo ou salário, suporte aos clientes, certificado de assinatura de código, CNPJ/contador, marketing e o custo para conquistar cada empresa.

**Três formas de melhorar a margem:**
1. **Mais computadores por cliente:** o custo fixo é baixo, então cada computador a mais é quase lucro puro (+R$ 38,80/mês cada).
2. **Não baixar o preço:** de R$ 40 para R$ 30, o lucro do ano cai R$ 7.800 (de R$ 23.064 para R$ 15.264).
3. **Manter a taxa de R$ 1.500:** ela paga o custo de conquistar e implantar cada cliente.

**Condições do conselho (`founder/board.md`):**
- [x] Cobrança recorrente definida: R$ 40/mês por computador atendido.
- [x] Margem positiva após o servidor: sim, acima de 16 computadores.
- [ ] Custo de conquistar cada cliente: **desconhecido**. É a maior pergunta em aberto.
- [ ] Volume real de clientes: **não validado** (`/founder-consumer`).

*Isto não é aconselhamento financeiro, fiscal ou jurídico. Um contador deve conferir impostos, a estrutura da empresa e os custos antes de você investir.*

---

# Unit economics: ScSuporte WL (software de suporte remoto white label)

Every number below comes from the input file. Nothing is looked up or guessed.

## One computador atendido por mês

| line | per computador atendido por mês |
| --- | ---: |
| Price | $40.00 |
| Taxa de cobrança Pix/boleto/cartão (ESTIMATIVA ~3%) | -$1.20 |
| **Contribution** (what each computador atendido por mês leaves to pay the fixed costs) | **$38.80** (97%) |

## The margin that matters

Fixed costs: $600 a month (Servidor (informado pelo fundador) $600).

- **Break-even: 16 computador atendido por mêss a day.** Below that you lose money every month.
- **Profit margin at your plan** (120 a day): **84%** of every sale, after every cost.

## Year 1, month by month

| month | computador atendido por mêss a day | revenue | profit | cumulative (after $0 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 10 | $400 | -$212 | -$212 |
| 2 | 20 | $800 | $176 | -$36 |
| 3 | 30 | $1,200 | $564 | $528 |
| 4 | 40 | $1,600 | $952 | $1,480 |
| 5 | 50 | $2,000 | $1,340 | $2,820 |
| 6 | 60 | $2,400 | $1,728 | $4,548 |
| 7 | 70 | $2,800 | $2,116 | $6,664 |
| 8 | 80 | $3,200 | $2,504 | $9,168 |
| 9 | 90 | $3,600 | $2,892 | $12,060 |
| 10 | 100 | $4,000 | $3,280 | $15,340 |
| 11 | 110 | $4,400 | $3,668 | $19,008 |
| 12 | 120 | $4,800 | $4,056 | $23,064 |

- **Year 1 operating profit: $23,064** on $31,200 of revenue.
- After the $0 startup spend: $23,064.
- Startup money earned back: month 3.
- Cash you need before it pays for itself: **$212**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 84% | 16 | $23,064 |
| Price -10% | 83% | 18 | $19,944 |
| Volume -20% | 81% | 16 | $17,011 |
| Unit costs +15% | 84% | 16 | $22,924 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
