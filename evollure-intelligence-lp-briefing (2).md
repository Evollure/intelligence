# BRIEFING — Landing Page Evollure Intelligence

> **Este documento contém a COPY FINAL e a estrutura de cada seção da LP.**
> Deve ser usado JUNTO com o `evollure-design-system-prompt.md` (DNA visual).
> A IA implementadora lê o design system pra identidade e este briefing pra conteúdo + estrutura.

---

## CONTEXTO DO PROJETO

| Campo | Valor |
|---|---|
| **Nome do projeto** | Evollure Intelligence |
| **O que vende** | Plataforma premium de análise de calls de vendas com IA. Totalmente personalizada às diretrizes comerciais de cada empresa. Cada operação recebe seu próprio "Cérebro Comercial" — um framework de avaliação sob medida com os critérios, pesos e regras que refletem exatamente o processo de vendas daquela empresa. Não é um template genérico. É uma solução construída em torno da sua operação. |
| **Para quem** | Diretores comerciais e gestores de vendas de empresas com times de 5-50 vendedores. Segmentos: franquias, seguros, energia solar, SaaS, clínicas, educação. Brasil e Portugal/Europa. Dor principal: não conseguem ouvir todas as calls, não sabem onde estão perdendo dinheiro, dependem de "feeling" ao invés de dados. |
| **Ação desejada** | Agendar uma demonstração (call de 30min) |
| **Sensação desejada** | "Isso é premium. Isso é sob medida. Isso resolve exatamente o meu problema." |
| **O que NÃO parecer** | Template de SaaS genérico. Página de vendas clickbait. Produto "one size fits all". Ferramenta que revela a tecnologia por trás em vez de mostrar o resultado. |
| **Modo** | DARK |
| **Referência de energia** | Gong.io (resultado > tech) + Linear (dark, limpo, tipografia como arma) + Academia Lendária (bold, itálico, cinematográfico) |

---

## NARRATIVA DE SCROLL (Blueprint)

| # | Seção | Energia | Fundo | Layout | Papel narrativo |
|---|---|---|---|---|---|
| 1 | Nav | Sutil, presente | Transparente → solid on scroll | Fixo, 64px | Orientação |
| 2 | Hero | ALTA — impacto | Void + glow ember | Split: texto esquerda, visual direita | A promessa |
| 3 | Ticker de dor | BAIXA — tensão | Carbon-950 | Marquee horizontal | Tensão antes da solução |
| 4 | O Problema | ALTA — espelho | Void | Texto centralizado, número grande | Tempo + dinheiro perdido |
| 5 | O Cérebro Comercial | ALTA — diferencial | Carbon-950 | Split: texto esquerda, visual direita | O core do produto |
| 6 | O Ecossistema | ALTA — clareza | Void | Path SVG + 4 steps visuais | Visão do todo |
| 7 | O que o Dashboard revela | ALTA — prova | Carbon-950 | Alternado texto/visual, exemplos reais | Demonstração concreta |
| 8 | Para Quem | MÉDIA — conexão | Void | Grid 2x3 | Identificação |
| 9 | Depoimento | BAIXA — respiro | Carbon-950 | Quote grande centralizado | Prova emocional |
| 10 | FAQ | BAIXA — resolução | Void | Accordion | Remoção de dúvidas |
| 11 | CTA Final | ALTA — clímax | Void + glow forte | Centralizado, headline enorme | Conversão |
| 12 | Footer | BAIXA — encerramento | Void | Minimal | Credibilidade |

---

## SEÇÃO 1 — NAV

**Esquerda:** Orbital Knot SVG (28px) + "Evollure" em Neue Montreal Regular 18px + badge "Intelligence" em IBM Plex Mono 9px, uppercase, ember.

**Direita:** Links: "O ecossistema" · "Para quem" · "FAQ" — em 13px, weight 400, color c200. Botão CTA: "Agendar Demo" — ember, cantos retos, 13px, weight 700.

**Comportamento:** Transparente no topo. Ganha fundo surface-elevated (carbon-950 com 85% opacity + backdrop-blur 12px) ao scrollar 80px.

---

## SEÇÃO 2 — HERO

**Label acima do headline:**
IBM Plex Mono, 9px, uppercase, ember: `EVOLLURE INTELLIGENCE`

**Headline:**
```
Seu time fez 40 calls hoje.
Você não ouviu nenhuma.
E tá tudo bem — agora tem quem ouça.
```
> "agora tem quem ouça." em bold italic ember.

**Subtítulo:**
```
O Evollure Intelligence analisa cada call do seu time contra
as diretrizes comerciais da sua empresa. Em 5 minutos no dashboard
você descobre o que levaria 6 horas ouvindo calls pra encontrar.
Erros, acertos, padrões e dinheiro deixado na mesa — tudo visível.
```
> Color c200, 18px, weight 400, max-width 540px.

**CTAs:**
- Primário: `Agendar Demo` — ember, cantos retos
- Secundário: `Ver o ecossistema ↓` — outline, cantos retos

**Visual (lado direito):**
Composição SVG conceitual: ondas sonoras estilizadas (representando a voz na call) que fluem pra um núcleo central (representando a análise), de onde saem linhas conectando nós com labels simplificados (rapport, diagnóstico, fechamento, score). Representa: conversa → inteligência → resultado. Tudo em ember + carbon. Sem mencionar tecnologia.

---

## SEÇÃO 3 — TICKER DE DOR

**Formato:** Marquee horizontal contínuo, lento, em IBM Plex Mono 11px, color c400, separado por " · ".

**Conteúdo (loop infinito):**
```
Um time de 10 vendedores faz +800 calls por mês — você não consegue ouvir nem 5% · Cada call não analisada é um erro repetido amanhã · O vendedor que pula o diagnóstico perde o deal — e ninguém vê · Follow-up atrasado é dinheiro que evapora em silêncio · Quanto custa um vendedor que improvisa 100% das calls? · O gestor que não tem dados toma decisão por feeling — e paga caro por isso · 5 minutos no dashboard substituem 6 horas ouvindo calls
```

---

## SEÇÃO 4 — O PROBLEMA (Espelho Incômodo)

**Número grande:** `800+`
> 72px, weight 800, ember, centralizado.

**Headline:**
```
calls por mês. Zero analisadas.
Quanto dinheiro tá escapando?
```
> 28px, weight 800, centralizado. "escapando?" em bold italic ember.

**Corpo:**
```
Faz as contas. Um time de 10 vendedores faz 40 calls por dia.
São mais de 800 por mês. Você não tem 6 horas por dia pra
ouvir gravação. Ninguém tem.

Então o que acontece? O vendedor que pula o diagnóstico repete
o erro amanhã. O que não faz follow-up perde o deal em silêncio.
O que improvisa o script inteiro continua improvisando. E você
só descobre quando o número não bate no fim do mês — tarde demais.

O Evollure Intelligence ouve cada uma dessas 800 calls.
Analisa contra as regras do SEU processo comercial.
E te entrega num dashboard o que levaria semanas pra descobrir:
quem tá performando, quem tá custando dinheiro e onde
exatamente o time precisa melhorar.

5 minutos olhando a tela. Insights que mudam o mês inteiro.
```
> 15px, color c300, centralizado, max-width 600px, line-height 1.9. "5 minutos olhando a tela. Insights que mudam o mês inteiro." em 16px, weight 700, color white, margin-top 16px — funciona como punchline visual separada do corpo.

---

## SEÇÃO 5 — O CÉREBRO COMERCIAL (O Core do Produto)

**Label:** `O DIFERENCIAL` — mono, 9px, ember, uppercase.

**Headline:**
```
Não é uma ferramenta genérica.
É o seu processo de vendas
transformado em inteligência.
```
> 28px, weight 800. "seu processo de vendas" em italic ember.

**Corpo:**
```
O Cérebro Comercial é o coração do Evollure Intelligence.
Antes de analisar uma única call, nós mapeamos junto com
você as diretrizes comerciais da sua empresa — os critérios
que definem uma boa venda no SEU negócio.

Não são métricas genéricas. São os seus critérios, com os
seus pesos, refletindo o seu processo.
```
> 15px, color c300, max-width 520px, line-height 1.9.

**Bloco de exemplo — "Como um Cérebro Comercial é montado":**

Layout: card com fundo carbon-900, borda carbon-700, padding generoso. Dentro, uma lista visual de 8 critérios com barra de peso ao lado de cada um. Estilizado como uma configuração de sistema, não como tabela genérica.

```
Exemplo: Cérebro Comercial — Rede de Franquias de Energia Solar

① Rapport e conexão inicial .............. peso 10%
② Diagnóstico da necessidade do cliente ... peso 20%
③ Apresentação técnica da solução ........ peso 15%
④ Cálculo de economia e payback .......... peso 15%
⑤ Quebra de objeções .................... peso 15%
⑥ Fechamento e próximos passos .......... peso 10%
⑦ Tom de voz e profissionalismo ......... peso 5%
⑧ Aderência ao script da franqueadora .... peso 10%
```

> Mono, 12px, c200. Os pesos em ember. Cada linha é um row visual com a barra proporcional ao peso.

**Nota abaixo do card:**
```
Cada empresa tem o seu. Franquias avaliam aderência ao script.
SaaS avalia diagnóstico técnico. Seguros avaliam compliance.
O Cérebro Comercial se adapta — porque a sua venda é única.
```
> 13px, c400, italic, centralizado.

---

## SEÇÃO 6 — O ECOSSISTEMA

**Label:** `O ECOSSISTEMA COMPLETO` — mono, 9px, ember, uppercase.

**Headline:**
```
Da gravação ao relatório.
Tudo conectado.
```
> 28px, weight 800. "Tudo conectado." em italic ember.

**Intro:**
```
O Evollure Intelligence não é só um dashboard. É um ecossistema
que cobre toda a cadeia — da captura da call até a decisão de coaching.
```
> 15px, c300, max-width 520px.

**Composição visual:** Path SVG horizontal (ou vertical em mobile) serpenteando por 4 estágios. Cada estágio é um nó com ícone + título + descrição. Path em ember com draw-on animation no scroll.

**Estágio 1 — Captura**
- Ícone: ondas sonoras
- Título: `O vendedor faz a call normalmente` (18px, bold)
- Descrição: `O app da Evollure roda em segundo plano no computador do vendedor. Sem mudar a rotina, sem complicação. A call é gravada e enviada automaticamente.` (14px, c300)

**Estágio 2 — Transcrição**
- Ícone: linhas de texto
- Título: `Cada palavra é transcrita com precisão` (18px, bold)
- Descrição: `A inteligência artificial transcreve a call inteira — com separação de quem falou o quê, timestamps e identificação de trechos-chave. Você pode ler a conversa como se fosse um roteiro.` (14px, c300)

**Estágio 3 — Análise**
- Ícone: gauge/medidor
- Título: `Avaliação automática contra o seu Cérebro Comercial` (18px, bold)
- Descrição: `Cada call é avaliada critério por critério — com score individual e score geral. A IA não dá opinião. Ela mede contra as diretrizes que você definiu. Se o vendedor pulou a etapa de diagnóstico, o score reflete. Se o fechamento foi fraco, aparece.` (14px, c300)

**Estágio 4 — Decisão**
- Ícone: dashboard simplificado
- Título: `Dashboard com a verdade da sua operação` (18px, bold)
- Descrição: `Você abre o painel e vê: quem está performando, quem precisa de coaching, qual critério está mais fraco no time, como a performance evolui semana a semana. Decisões de gestão baseadas em dados — não em achismo.` (14px, c300)

---

## SEÇÃO 7 — O QUE O DASHBOARD REVELA

**Label:** `NA PRÁTICA` — mono, 9px, ember, uppercase.

**Headline:**
```
Exemplos reais do que
você vai enxergar.
```
> 28px, weight 800. "enxergar." em italic ember.

**Intro:**
```
O dashboard do Evollure Intelligence não mostra só números.
Ele conta a história da sua operação.
```
> 15px, c300, max-width 520px.

**Exemplo 1 — Visão do Diretor**
- Layout: texto esquerda, visual direita
- Título: `"Meu time tem 12 vendedores. 3 carregam 70% do resultado."` (20px, bold, com aspas em ember)
- Corpo: `O painel do Diretor mostra o ranking de vendedores por score geral, volume de calls, taxa de conversão e evolução ao longo do tempo. Num relance, você sabe quem está performando e quem está custando dinheiro. Sem ouvir uma call sequer.` (14px, c300)
- Visual: SVG estilizado de ranking — 12 barras horizontais de alturas diferentes, as 3 primeiras em ember (top performers), as demais em tons de carbon. Label "SCORE MÉDIO: 7.8" no topo.

**Exemplo 2 — Visão do Gestor**
- Layout: visual esquerda, texto direita
- Título: `"O João tem score 4.2 em fechamento. Toda semana."` (20px, bold, com aspas em ember)
- Corpo: `O Gestor mergulha no time. Vê o score de cada vendedor por critério do Cérebro Comercial. Identifica padrões — o João é bom em rapport mas fraco em fechamento. A Maria qualifica bem mas pula o follow-up. Coaching cirúrgico, não genérico.` (14px, c300)
- Visual: SVG de radar chart estilizado (ou barras por critério) de um vendedor individual — mostrando scores por critério: rapport 8.5, diagnóstico 7.2, fechamento 4.2, follow-up 3.8. Os scores baixos em ember-dim, os altos em ember.

**Exemplo 3 — Visão do Vendedor**
- Layout: texto esquerda, visual direita
- Título: `"Eu sei exatamente onde preciso melhorar."` (20px, bold, com aspas em ember)
- Corpo: `O vendedor acessa seus próprios scores. Vê a evolução call a call. Entende quais critérios estão puxando o score pra baixo. Não precisa esperar feedback do gestor — o dado está ali, transparente, em tempo real. O vendedor que quer crescer, cresce.` (14px, c300)
- Visual: SVG de timeline/gráfico de evolução — uma linha subindo ao longo de "semanas", com pontos marcados. A tendência é ascendente. Label "SCORE GERAL: 6.1 → 7.8 EM 6 SEMANAS".

---

## SEÇÃO 8 — PARA QUEM

**Label:** `PARA QUEM É O EVOLLURE INTELLIGENCE` — mono, 9px, ember, uppercase.

**Headline:**
```
Se o seu time vende por telefone,
isso foi feito pra você.
```
> 28px, weight 800. "pra você." em italic ember.

**Layout:** Grid 2x3 com 6 cards de segmento. Cada card: ícone simplificado (SVG geométrico) + nome do segmento + 1 linha de contexto.

**Card 1 — Franquias**
- Ícone: grid de 4 quadrados (representando unidades)
- Texto: `Padronize o atendimento em todas as unidades.`

**Card 2 — Seguros**
- Ícone: escudo simplificado
- Texto: `Garanta compliance e qualidade em cada proposta.`

**Card 3 — Energia Solar**
- Ícone: círculo com raios (sol estilizado)
- Texto: `Acompanhe a qualificação técnica do vendedor.`

**Card 4 — SaaS / Tecnologia**
- Ícone: terminal/código
- Texto: `Meça a aderência ao playbook de vendas.`

**Card 5 — Clínicas e Saúde**
- Ícone: cruz simplificada
- Texto: `Avalie o acolhimento e a conversão de agendamentos.`

**Card 6 — Educação**
- Ícone: livro aberto
- Texto: `Otimize a matrícula e o follow-up de leads.`

> Cards: bg carbon-950, border 1px carbon-800, padding 24px. Ícones em ember, 24px. Título do segmento em 16px bold. Descrição em 13px c300. Hover: border ember + translateY(-3px).

---

## SEÇÃO 9 — DEPOIMENTO

**Layout:** Quote centralizado, grande, com muito espaço negativo (padding 120px+).

**Quote:**
```
"Antes eu achava que sabia como meu time vendia.
O Evollure me mostrou que eu não fazia ideia."
```
> 28px, weight 700, centralizado, line-height 1.5. Aspas em ember.

**Autor:**
```
Diretor Comercial — Rede de Franquias
```
> Mono, 11px, c400, centralizado.

> [NOTA: Placeholder. Substituir por depoimento real quando disponível.]

---

## SEÇÃO 10 — FAQ

**Label:** `PERGUNTAS FREQUENTES` — mono, 9px, ember, uppercase.

**Layout:** Accordion. Título em 16px bold, corpo em 14px c300. Ícone + que rotaciona pra × ao abrir. Border-bottom c700 entre itens.

**Q1:** `Como funciona a gravação das calls?`
**A1:** `O vendedor usa nosso app desktop (Windows/Mac) que roda em segundo plano durante a ligação. Não precisa mudar nada na rotina. A call é gravada e enviada automaticamente pra plataforma assim que termina.`

**Q2:** `O que é o Cérebro Comercial?`
**A2:** `É o framework de avaliação totalmente personalizado da sua empresa. Nós mapeamos junto com você os critérios que definem uma boa venda no seu negócio — e atribuímos pesos a cada um. Cada call é avaliada contra esse framework, gerando um score de 0 a 10 por critério e um score geral.`

**Q3:** `É personalizado mesmo? Ou é um template?`
**A3:** `É sob medida. Cada empresa tem seu próprio Cérebro Comercial, configurado durante o onboarding. Uma franquia de energia solar tem critérios completamente diferentes de uma corretora de seguros. O sistema se adapta ao SEU processo, não o contrário.`

**Q4:** `Funciona pra qualquer tipo de venda?`
**A4:** `Funciona pra qualquer venda que aconteça por telefone ou videochamada. Franquias, seguros, energia solar, SaaS, clínicas, educação — qualquer operação com vendedores que fazem calls.`

**Q5:** `Quanto tempo leva pra implementar?`
**A5:** `Menos de uma semana. Dia 1: onboarding e configuração do Cérebro Comercial junto com a nossa equipe. Dia 2-3: instalação do app nos vendedores. Dia 4+: primeiras calls analisadas. Em poucos dias você já tem dados suficientes pra tomar decisões.`

**Q6:** `Quem tem acesso ao quê?`
**A6:** `O sistema tem três níveis de acesso: Diretor vê toda a operação. Gestor vê o time dele. Vendedor vê os próprios scores e evolução. Cada papel vê o que precisa pra tomar decisão — nada mais, nada menos.`

**Q7:** `É seguro? E o RGPD/LGPD?`
**A7:** `Sim. As calls são criptografadas em trânsito e em repouso. Os dados ficam em servidores seguros. Para clientes europeus, somos compliance com RGPD. Para Brasil, LGPD. Você controla quem tem acesso a quê.`

**Q8:** `Funciona pra times pequenos?`
**A8:** `Sim. O Evollure Intelligence funciona pra times a partir de 5 vendedores. Times menores costumam ver resultado mais rápido porque o gestor consegue agir nos dados imediatamente.`

---

## SEÇÃO 11 — CTA FINAL

**Orbital Knot SVG** no fundo em opacity 12%, tamanho grande (240px). Glow ember mais forte da página (opacity 10%).

**Headline:**
```
Cada dia sem dados é um dia
que o dinheiro escapa.
```
> 42px, weight 800, centralizado. "o dinheiro escapa." em italic ember.

**Subtítulo:**
```
Agende 30 minutos com a nossa equipe. Vamos analisar uma call
real do seu time e te mostrar o que o dashboard revela.
```
> 16px, c200, centralizado.

**CTA:** `Agendar Demo` — ember, cantos retos, tamanho grande (padding 16px 48px, 16px font).

**Micro-copy abaixo do botão:**
```
30 minutos · Uma call real do seu time · Resultado na hora
```
> Mono, 10px, c400, centralizado.

---

## SEÇÃO 12 — FOOTER

**Layout:** Minimal, 3 colunas.

**Esquerda:** Orbital Knot (20px) + "Evollure" (Neue Montreal Regular, 16px) + "IA aplicada a negócios" (mono, 9px, c400)

**Centro:** Links em 12px, c300: `Intelligence · Reach · Prospect · Sobre · Contato`

**Direita:** `© 2026 Evollure` (mono, 9px, c500) + ícones sociais: Instagram, LinkedIn, WhatsApp (em c400, 16px, hover ember)

**Divider no topo:** Linha 1px gradient (transparent → c700 → transparent)

---

## INSTRUÇÕES PARA A IA IMPLEMENTADORA

1. **Leia o `evollure-design-system-prompt.md` ANTES de começar.** Ele contém todos os tokens, regras visuais, composições narrativas e proibições.
2. **Este documento é a copy FINAL.** Implemente o texto exatamente como está. Não reescreva headlines, não mude a estrutura das seções, não invente copy nova.
3. **Cada seção deve respeitar a energia definida no blueprint.** Seções de ALTA energia têm composições visuais densas. Seções de BAIXA energia têm espaço negativo generoso.
4. **NUNCA mencione tecnologias específicas (Whisper, GPT, OpenAI, modelos de IA).** O produto é descrito pela funcionalidade e resultado — não pela stack técnica.
5. **O Cérebro Comercial é o protagonista da LP.** A personalização total é o maior diferencial. Cada menção ao produto deve reforçar: é sob medida, não genérico.
6. **Os exemplos de dashboard (Seção 7) devem ter composições visuais únicas.** Ranking de vendedores, radar de critérios por vendedor, e gráfico de evolução temporal. Tudo em SVG/CSS, estilizado com a paleta Carbon + Ember.
7. **Tudo em um único arquivo HTML** (ou React component). Inline styles via Tailwind ou CSS custom properties. NUNCA arquivos CSS separados.
8. **O resultado deve ser indistinguível de uma LP feita por um estúdio de design premium.** Não é um wireframe. É uma LP pronta pra ir ao ar.
