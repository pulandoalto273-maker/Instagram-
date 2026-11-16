# Levantamento técnico — Instagram (novembro/2026)

> Ponto de partida baseado em estudos de mercado. Os horários definitivos serão
> ajustados com os dados reais da própria conta (Insights), coletados pela automação.

## 1. Melhores horários de publicação

### O que os estudos dizem
| Fonte | Achado principal |
|---|---|
| Buffer (9,6 mi de posts) | Melhores dias: quarta, quinta, terça. Picos: qui 9h, qua 12h, qua 18h |
| Sprout Social (~2 bi interações) | Terça 13h–19h e quarta 12h–21h. Sábado é o pior dia |
| Hootsuite | Janelas no fim da tarde (15h–19h) na maioria dos dias; Reels seg–qui 9h–12h |
| Later (6 mi de posts) | 5h da manhã (fuso do público) — destoa dos demais |
| Opinion Box (dado brasileiro) | Maior uso do app das 18h às 20h e das 20h à meia-noite |

### Grade inicial recomendada (horário de Brasília)
| Dia | Feed / Carrossel | Reels | Stories |
|---|---|---|---|
| Seg | 18h30 | 11h | 8h, 12h, 19h |
| Ter | 12h | 19h | 8h, 12h, 19h |
| Qua | 12h e 18h30 | 9h | 8h, 12h, 19h |
| Qui | 9h | 19h | 8h, 12h, 19h |
| Sex | 12h | — | 8h, 12h, 19h |
| Sáb | — (dia mais fraco) | 11h | 11h, 19h |
| Dom | — | 19h | 19h |

Prioridade: **terça a quinta**, janelas de **11h–13h** e **18h–21h**.

### Como a automação vai refinar isso
1. Cada post é publicado com horário registrado.
2. A automação coleta as métricas de cada post (alcance, salvamentos, compartilhamentos, comentários).
3. Mensalmente, o relatório compara os horários e ajusta a grade para os que realmente performam melhor na sua conta.

## 2. Regras e tendências atuais do algoritmo

**Confirmado (anúncio oficial):**
- **Máximo de 5 hashtags por post e Reels** (desde dez/2025, anunciado por Adam Mosseri).
  Hashtag ajuda na busca, mas não aumenta alcance por si só → usar 3 a 5 hashtags bem relevantes.
- **Originalidade**: desde 30/04/2026, contas que publicam majoritariamente conteúdo de terceiros
  deixam de ser recomendadas. Conteúdo deve ser próprio.

**Consenso entre especialistas (sem número oficial):**
- **Compartilhamentos (principalmente via Direct) e salvamentos** são os sinais mais fortes; curtida é o mais fraco.
  → Criar conteúdo "enviável" e "salvável": dicas, listas, antes/depois, ofertas para mandar a um amigo.
- **Reels**: o fator principal é a taxa de visualização até o fim. Gancho nos primeiros 3 segundos.
  Reels de até 3 minutos podem ser recomendados para não seguidores.
- **Carrosséis** estão performando no nível dos Reels em engajamento com seguidores. Até 20 imagens;
  carrosséis educativos de 7–10 imagens são o ponto ideal.
- **Primeira hora** após a publicação é decisiva → publicar quando o público está online e responder comentários rápido.

## 3. Mix de conteúdo sugerido (semanal)
- 2–3 Reels (alcance / novos seguidores)
- 2 carrosséis (salvamentos / autoridade)
- 1 post de oferta ou promoção
- Stories diários (relacionamento e vendas)

## 4. Pontos técnicos da API (impactam a automação)
- **Não é mais obrigatório ter Página do Facebook**: o "Instagram API with Instagram Login" funciona direto com a conta do Instagram.
- **Stories pela API só funcionam em conta Comercial (Business)**, não em conta de Criador.
- Stickers interativos (enquete, link, música) não são suportados pela API.
- Limite de publicações por API em 24h é consultado em tempo real pela automação (endpoint `content_publishing_limit`).

## 5. Monitoramento contínuo de tendências
- Relatório semanal: novidades do Instagram, formatos em alta, áudios/temas do nicho.
- Relatório mensal: desempenho da conta + ajuste automático da grade de horários.

## Fontes
- Buffer — https://buffer.com/resources/when-is-the-best-time-to-post-on-instagram/
- Sprout Social — https://sproutsocial.com/insights/best-times-to-post-on-instagram/
- Hootsuite — https://blog.hootsuite.com/best-time-to-post-on-instagram/
- Later — https://later.com/blog/best-time-to-post-on-instagram/
- Ravia (Opinion Box) — https://blog.ravia.app/melhor-horario-instagram/
- Air — https://air.com.vc/blog/melhores-horarios-para-postar-no-instagram/
- Nuvemshop — https://www.nuvemshop.com.br/blog/melhores-horarios-postar-fotos-instagram/
- Social Media Today (limite de hashtags) — https://www.socialmediatoday.com/news/instagram-implements-new-limits-on-hashtag-use/808309/
- Later (algoritmo) — https://later.com/blog/how-instagram-algorithm-works/
- Meta — Content Publishing — https://developers.facebook.com/docs/instagram-platform/content-publishing/
- Meta — Instagram API with Instagram Login — https://developers.facebook.com/documentation/instagram-platform/instagram-api-with-instagram-login
