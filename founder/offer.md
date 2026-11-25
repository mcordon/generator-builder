# Oferta: Com Que Roupa (v2)

Método: a lente Oferta (`founder-board/lenses.md`), um resumo de um framework publicado. Não são palavras do autor.

## 1. Problemas (na voz da usuária, do painel v1)
**Antes:** 1. "Ninguém repara se eu repetir" (necessidade, 6). 2. "Já vejo no Instagram e no rolo da câmera" (hábito, 9). 3. "Não pago assinatura de app." 4. "Já larguei app de closet." 5. "Não quero dar acesso aos contatos." 6. "Marcar amiga sem ela saber parece vigilância" (valores, 3). 7. "Para onde vão os dados?" (confiança, 2). 8. "Só funciona se as amigas usarem."
**Durante:** 9. "Vou esquecer de tirar foto e marcar no meio da festa." 10. "Cadastrar o guarda-roupa dá trabalho." 11. "Se faltar evento, o histórico fica furado." 12. "Vou ter que corrigir tudo à mão."
**Depois:** 13. "O grátis já basta." 14. "R$ 14,90 é caro" (faixa v1: R$ 3 a R$ 15). 15. "Não me ajuda a gastar menos." 16. "Não me ajuda no conteúdo." 17. "Para casamento eu compro roupa nova de qualquer jeito."

## 2. Soluções (valor x custo, 1 a 5)
| Solução | Resolve | Valor | Custo | Fica? |
|---|---|---:|---:|---|
| Ler o rolo da câmera e reconhecer as roupas (fundador confirmou que consegue) | 2, 9, 10, 11 | 5 | 3 (desenvolvimento; processar no celular evita custo de servidor) | ✅ |
| Grupos com apelido, sem contatos, sem reconhecer rostos, ninguém marcado | 5, 6, 8 | 4 | 1 | ✅ |
| Dados só no celular | 7 | 4 | 1 (reduz custo de servidor) | ✅ |
| Premium a R$ 7,90 | 3, 14 | 4 | — | ✅ |
| Grátis limitado aos últimos 3 meses | 13 | 3 | 1 | ✅ |
| 30 dias de Premium grátis, sem cartão | 4, 12 | 4 | 1 | ✅ |
| Painel de gasto com roupa por evento | 15 | 3 | 2 | ✅ |
| Planejamento de looks para viagens e casamentos | 17 | 4 | 2 | ✅ |
| Escolher só algumas fotos (em vez do rolo inteiro) | 7 | 4 | 1 | ➕ próxima versão (pedido no reteste) |
| Lembrete automático pela agenda antes do evento | 9 | 4 | 2 | ➕ próxima versão (pedido no reteste) |
| Sugerir vender no brechó as peças muito vistas | 15 | 4 | 2 | ➕ próxima versão (pedido no reteste) |
| Importar do Instagram | 2 | 4 | ? | ❌ depende das regras da Meta; não prometer |
| Reconhecer rostos | 9 | — | — | ❌ dado biométrico (LGPD) |

## 3. O pacote: "Com Que Roupa: o guarda-roupa que se monta sozinho"
- **Núcleo:** sem cadastro. O app lê o rolo da câmera, reconhece as roupas e mostra o que cada grupo já viu.
- **Bônus 1:** grupos com apelido, sem contatos e sem marcar ninguém. (Resolve: privacidade.)
- **Bônus 2:** planejamento de looks para casamentos e viagens. (Resolve: "compro roupa nova para casamento".)
- **Bônus 3:** painel de quanto você gasta com roupa por evento. (Resolve: "não me ajuda a economizar".)
- **Garantia:** 30 dias de Premium grátis, sem cartão. Cancela quando quiser.
- **Urgência:** nenhuma. Não há motivo real para criar.

## 4. Equação de valor (1 a 10)
| Elemento | v1 | v2 | O que mudou |
|---|---:|---:|---|
| Resultado dos sonhos | 5 | 6 | Economizar e acertar o look de casamento |
| Probabilidade percebida | 3 | 5 | Privacidade resolvida; ainda há dúvida se o reconhecimento acerta em foto escura |
| Tempo até o resultado | 3 | 7 | Guarda-roupa pronto na primeira leitura do rolo |
| Esforço e sacrifício | 2 | 7 | Sem cadastro e sem marcar ninguém |

## 5. Reteste (mesmas 20 usuárias, semente 323592)
| | v1 (R$ 14,90, foto e marcação manual) | v2 (R$ 7,90, leitura automática, sem contatos) |
|---|---:|---:|
| Assinariam | **0 de 20** | **2 de 20 (10%)** |
| Não por hábito | 9 | 10 |
| Não por necessidade | 6 | 8 |
| Não por valores/privacidade | 3 | **0** |
| Não por confiança | 2 | **0** |
| Faixa de preço aceitável | R$ 3 a R$ 15 | R$ 2 a R$ 13 |

- **O que caiu:** as objeções de **privacidade e confiança sumiram** (de 5 para 0).
- **Quem assina:** as que **se preocupam em não repetir look** (2 de 4) e a **fase de casamentos e chás** (25%). Universitárias, criadoras de conteúdo, compradoras por impulso e as que não ligam para repetir: 0.
- **O que não mudou:** **hábito e necessidade** (18 de 20). Quem repete sem culpa ou compra roupa nova para cada evento não tem o problema. Isso é **mercado**, não oferta.
- **Objeções novas:** "vai errar em foto escura, com filtro ou em grupo"; "não quero que leia o rolo inteiro"; "as fotos do evento ficam no celular das amigas"; "vou esquecer de abrir antes de sair".
- **O que fariam mudar:** lembrete automático pela agenda, escolher só algumas fotos, ajudar a vender no brechó (Enjoei) as peças muito vistas, funções para conteúdo.

**Leitura honesta:** a assinatura sozinha atrai pouca gente (10% de usuárias simuladas, que tendem a ser otimistas). O público que mais responde é **quem está na fase de casamentos e quem já se preocupa em não repetir**. O caminho de receita mais promissor pode ser o **brechó** (vender o que já foi muito visto) e as **lojas parceiras**, não só a assinatura.
