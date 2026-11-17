# Progresso da automação — @altopulando

> Última atualização: 17/11/2026 (madrugada)
> Negócio: decoração de festas (infantis, casamentos e eventos em geral)

## ✅ Já concluído

| # | Etapa | Status |
|---|---|---|
| 1 | Conta do Instagram **@altopulando** como **Comercial** | ✅ |
| 2 | Conta de desenvolvedor no Meta for Developers | ✅ |
| 3 | App **"Altopulando Automação"** criado (caso de uso: *Gerenciar mensagens e conteúdo no Instagram*) | ✅ |
| 4 | @altopulando adicionado como **Testador do Instagram** e convite aceito | ✅ |
| 5 | Portfólio empresarial **"Altopulando Decorações"** criado (verificação adiada — não é necessária) | ✅ |
| 6 | Configuração de login criada a partir do modelo: **"API do Instagram (login unificado)"** — token de usuário do sistema, **nunca expira** | ✅ |
| 7 | @altopulando adicionado na Etapa 2 ("Gerar tokens de acesso") do app | ✅ |
| 8 | Login no GitHub descoberto: botão **"Continue with Google"** com o Gmail da conta do GitHub | ✅ |
| 9 | Levantamento técnico de horários e tendências (`docs/levantamento-tecnico.md`) | ✅ |

## ⏳ Onde paramos

Ao clicar em **"Gerar token"**, a Meta pediu para escolher a conta do Instagram dentro do
portfólio "Altopulando Decorações" — mas o portfólio ainda **não tem o Instagram adicionado**.
A tentativa de adicionar (Configurações do portfólio → "Add Instagram profile") **travou no Firefox**.

## ▶️ Próximos passos (amanhã, ~10 min)

1. Abrir o **Microsoft Edge** (não o Firefox).
2. Acessar https://business.facebook.com/settings → selecionar **Altopulando Decorações**.
3. Pesquisar **"Instagram"** → **"Adicionar conta do Instagram"** → **"Add Instagram profile"** → login com **@altopulando**.
   - Se avisar que a conta já pertence a outro portfólio (ex.: "Pulando Alto Decorações"): **não remover nada**, mandar print para o Claude.
   - Plano B: fazer pelo app **Meta Business Suite** no celular.
4. Voltar em https://developers.facebook.com/apps/ → **Altopulando Automação** → Casos de uso → Personalizar →
   **API setup with Unified login** → Etapa 2 → **"Gerar token"** → escolher @altopulando → **Copiar**.
5. Colar no cofre do GitHub (no **mesmo navegador**):
   https://github.com/pulandoalto273-maker/Instagram-/settings/secrets/actions/new
   - **Name:** `INSTAGRAM_ACCESS_TOKEN`
   - **Secret:** colar o token (Ctrl+V) → **Add secret**
6. 🛑 Nunca mandar o token no chat nem em foto.

## 🗂️ Informações de referência (não são segredos)

- **App da Meta:** Altopulando Automação — ID `1460023502901489`
- **Portfólio empresarial:** Altopulando Decorações — ID `2117551192282367`
- **Instagram:** @altopulando — ID da conta `17841404292664010`
- **Portfólios antigos que já existiam:** "Pulando Alto", "Pulando Alto Decorações", "Andrea Melo"
- **Itens que NÃO precisam ser feitos:** URL de redirecionamento, webhooks (só para respostas automáticas no futuro),
  análise do app, verificação da empresa

## 🔑 Qual login usar em cada lugar

| Onde | Como entrar |
|---|---|
| Facebook / Meta for Developers / Business | Facebook pessoal da Andrea (e-mail Hotmail) |
| E-mail de contato do app da Meta | Gmail "profissional" criado para isso |
| GitHub | Botão **"Continue with Google"** com o Gmail da conta do GitHub |

## ❓ Perguntas pendentes para montar o robô e o calendário

1. Quantos posts por semana (feed, Reels e stories)?
2. Alguma promoção ou data chegando (Natal, Réveillon, temporada de festas de janeiro)?
3. Aprovar cada post antes de publicar, ou publicar direto?
4. Dia e horário para receber o relatório semanal de tendências.
