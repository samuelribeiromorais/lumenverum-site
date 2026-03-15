# Scripts de Postagem para Grupos Tecnicos
## Estrategia de Divulgacao - SPDA Risk Analyzer

> Regra de ouro: NUNCA poste o link de venda direto. Sempre entregue valor tecnico primeiro.
> Use o sistema de dois CTAs: CTA 1 (engajamento) + CTA 2 (recomendacao leve).

---

## POST 1 — Gancho Normativo (Atualizacao 2026)

**Objetivo:** Gerar autoridade mostrando conhecimento da norma atualizada.

**Texto:**

Voce ja atualizou sua analise de risco para a 2a edicao da NBR 5419-2:2026?

Muita gente ainda esta usando a versao anterior e nao sabe que agora existe uma nova exigencia: o calculo da Frequencia de Danos (F) para sistemas internos.

Antes, a norma exigia apenas R1, R3 e R4. Agora, alem desses riscos, voce precisa calcular F = FB + FC + FM + FV + FW + FZ e comparar com a tolerancia FT.

Sistemas criticos (hospitais, datacenters): FT = 0,1
Sistemas nao criticos (escritorios, comercio): FT = 1,0

Se voce nao incluir esse calculo, seu laudo pode ser questionado em uma pericia ou auditoria.

Alguem aqui ja esta aplicando essa nova exigencia nos projetos?

CTA 1: "Se tiver duvidas sobre como calcular F, me chama no direct que explico."
CTA 2: "Eu uso uma ferramenta online que ja faz esse calculo automaticamente. Se alguem quiser conhecer, e so me chamar."

---

## POST 2 — Dica Pratica (Erro Comum)

**Objetivo:** Mostrar conhecimento tecnico e gerar identificacao com a dor.

**Texto:**

Um erro que vejo com frequencia em laudos de SPDA: usar o valor de NG (densidade de descargas) generico para o estado inteiro.

A NBR 5419-2 exige que voce use o NG especifico do municipio onde a estrutura esta localizada (Anexo F). A diferenca pode ser enorme.

Exemplo real:
- Sao Paulo capital: NG = 12,6 descargas/km2/ano
- Campos do Jordao (SP): NG = 5,8 descargas/km2/ano

Se voce usar o NG errado, todos os calculos de ND (eventos perigosos) ficam comprometidos, e o resultado de R1 pode mudar de "adequado" para "inadequado" — ou pior, o contrario.

Dica: O Anexo F da norma tem dados para todos os 5.565 municipios brasileiros. Sempre consulte.

CTA 1: "Ja pegaram algum laudo com NG errado? Comenta aqui a experiencia."
CTA 2: "Tem uma ferramenta que eu uso que ja puxa o NG automatico por municipio. Quem quiser saber mais, me manda mensagem."

---

## POST 3 — Resultado / Caso de Uso

**Objetivo:** Mostrar o resultado que o sistema entrega sem vender diretamente.

**Texto:**

Hoje terminei uma analise de risco de SPDA para uma industria quimica em Paulinia/SP. Compartilho o processo:

1. Estrutura: 80m x 40m x 12m, isolada, piso de concreto
2. Linha de energia aerea de 2km + linha de sinal enterrada de 500m
3. Tipo de estrutura: risco de explosao (rf alto)
4. SPDA existente: Nivel III

Resultado: R1 = 3,2 x 10^-5 (acima do toleravel de 10^-5)

Ou seja: o SPDA Nivel III nao e suficiente. Precisaria de Nivel I + DPS coordenado para trazer R1 para 8,7 x 10^-6.

Isso e o tipo de coisa que uma planilha mal configurada pode nao pegar. O componente RU (sobretensoes na linha de energia) estava dominando o risco.

CTA 1: "Se quiserem, posso fazer um post detalhando como identificar qual componente de risco esta dominando no R1."
CTA 2: "Usei um software online que mostra um grafico de barras com cada componente (RA, RB, RC, RM, RU, RV, RW, RZ). Facilita muito a analise. Quem quiser conhecer, chama no privado."

---

## POST 4 — Educacional (Memorial Descritivo)

**Objetivo:** Ensinar algo util e posicionar o sistema como ferramenta.

**Texto:**

Voce sabe quantas descidas o SPDA da sua estrutura precisa ter?

A resposta depende do Nivel de Protecao e do perimetro da estrutura:

NP I: a cada 10m de perimetro
NP II: a cada 10m
NP III: a cada 15m
NP IV: a cada 20m

Para uma estrutura de 60m x 30m (perimetro = 180m):
- NP I: 18 descidas
- NP II: 18 descidas
- NP III: 12 descidas
- NP IV: 9 descidas

Alem disso, o memorial descritivo do SPDA deve incluir:
- Captacao (esfera rolante, malha, angulo de protecao)
- Aterramento (comprimento minimo l1)
- Equipotencializacao (aneis a cada 20m de altura)
- Distancia de seguranca (s)
- Secoes minimas de condutores (NBR 5419-3)

Montar isso manualmente leva um bom tempo. Vale ter um modelo padrao ou uma ferramenta que gere automaticamente.

CTA 1: "Duvidas sobre memorial descritivo? Pergunta aqui que respondo."
CTA 2: "Eu uso um sistema que gera o memorial completo automaticamente com base no NP escolhido. Se alguem quiser testar, me chama."

---

## POST 5 — Dor + Urgencia (Responsabilidade Tecnica)

**Objetivo:** Criar senso de urgencia com responsabilidade profissional.

**Texto:**

Pergunta honesta: voce confia 100% na sua planilha de analise de risco?

Ja vi casos em pericias judiciais onde o laudo de SPDA foi questionado porque:

- O NG usado era do estado, nao do municipio
- Nao considerou a estrutura adjacente
- Faltava o calculo de F (exigido desde 2026)
- O relatorio nao tinha memorial descritivo
- Os fatores de perda estavam com valores das tabelas erradas

O engenheiro que assina o laudo responde tecnicamente por ele. Com a ART emitida, qualquer inconsistencia pode virar um problema serio — especialmente se houver um acidente.

Revisar sua metodologia de calculo e garantir conformidade com a norma atualizada nao e opcional. E protecao profissional.

CTA 1: "Se quiserem, posso compartilhar um checklist com os pontos que a norma exige na analise de risco. Comenta 'EU QUERO' que mando no direct."
CTA 2: (nao usar neste post — manter 100% tecnico para gerar confianca)

---

## POST 6 — Prova Social / Depoimento

**Objetivo:** Usar prova social para gerar interesse.

**Texto:**

Feedback que recebi de um colega engenheiro que comecou a usar uma ferramenta online para analise de risco de SPDA:

"Antes eu levava quase um dia inteiro entre calculos, consultas a norma e montagem do relatorio. Agora faco em menos de uma hora. O que mais gostei foi o memorial descritivo automatico — ele ja calcula descidas, aterramento e tudo conforme o NP."

Perguntei o que ele faria com o tempo que economiza. Resposta: "Mais projetos. No mesmo mes que assinei, ja paguei a ferramenta com o primeiro laudo adicional que consegui entregar."

Para quem trabalha com SPDA, a relacao custo-beneficio de automatizar a analise de risco e absurda. O valor de uma assinatura mensal e menor que o valor de uma hora tecnica.

CTA 1: "Quem aqui trabalha com projetos de SPDA? Como voces fazem a analise de risco hoje?"
CTA 2: "Se quiserem conhecer a ferramenta que ele usa, me chama no direct que passo o link."

---

## POST 7 — Conteudo para X (Twitter)

**Objetivo:** Monitorar e responder a quem menciona SPDA/NBR 5419.

**Modelo de resposta para quem posta duvidas:**

"Boa pergunta! Sobre [tema que a pessoa mencionou], a NBR 5419-2:2026 diz que [explicacao tecnica breve]. Se quiser se aprofundar, tem um artigo completo comparando a edicao 2015 com a 2026 no site da Lumen Verum: lumenverum.com.br/nbr-5419-2015-vs-2026.html. Me chama no DM se tiver duvidas!"

**Termos para monitorar no X:**
- "SPDA"
- "NBR 5419"
- "analise de risco" + "raio" ou "descarga atmosferica"
- "para-raios" + "projeto"
- "laudo SPDA"
- "protecao contra descargas atmosfericas"

---

## REGRAS GERAIS DE POSTAGEM

1. **Frequencia:** 2-3 posts por semana em cada grupo
2. **Horarios:** Terca a quinta, entre 8h-10h ou 19h-21h
3. **Nunca** poste o link de venda diretamente no grupo
4. **Sempre** responda todos os comentarios com mais valor tecnico
5. **Converta no 1 a 1:** A venda acontece no Direct/WhatsApp, nao no post
6. **Varie os tipos:** Normativo > Dica > Caso > Educacional > Prova Social
7. **Grupos recomendados:** Engenharia Eletrica, SPDA, Seguranca do Trabalho, Projetos Eletricos, CREA
8. **Adapte o tom:** Formal tecnico nos grupos de engenharia, mais acessivel nos grupos de seguranca do trabalho
