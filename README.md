### 👋 Oi, sou Valter

Estrategista de marketing que aprendeu a programar pra parar de depender de quem não entendia o que eu precisava entregar. Hoje toco a [NodusHub](https://nodushub.com.br) — uma operação enxuta no Brasil que cuida de tráfego pago, atendentes de IA no WhatsApp e CRM pra clínicas odontológicas.

No dia a dia, eu:

- 🏗️ Construo e mantenho 14 apps Next.js + 13 serviços Python num monorepo privado
- 🤖 Opero `iris-bot` (atendente IA WhatsApp 24/7), `dentist-prospector` (engine de prospecção B2B) e o `Olympus CRM` (NestJS multi-tenant)
- 📐 Decido stack, faço deploy (Hetzner Docker + Vercel) e debugo produção sozinho
- ✍️ Documento tudo no Obsidian Vault e refatoro continuamente

### 🛠️ Open source

Os repos abaixo são padrões reais que extraí da operação, sanitizei e abri pra outros builders forkarem em vez de reinventar. Cada um resolve um problema específico que eu vivi em produção.

- **[claude-skills](https://github.com/valterjuniorsilv/claude-skills)** — Como meu Claude Code virou um time. 13 skills custom (PT-BR + EN) incluindo brutal honesty mode, pipeline de copy anti-IA, continuidade entre sessões. Era o "patchwork" que eu copiava entre projetos — virou repo público.
- **[claude-whatsapp-template](https://github.com/valterjuniorsilv/claude-whatsapp-template)** — Boilerplate de bot WhatsApp em produção. Resolve os problemas reais que ninguém documenta: debounce de mensagens consecutivas, contatos protegidos (não atender o número pessoal do dono), fallback quando a API do Claude cai, prompt caching pra cortar 90% do custo. Stack: n8n + Evolution + Redis + Postgres.
- **[local-business-prospector](https://github.com/valterjuniorsilv/local-business-prospector)** — Pipeline B2B multi-nicho. Vai do scraping do Google Maps ao lead qualificado com score do Claude, passando por enriquecimento de email/IG/Meta Ads. Custa ~$0,50 por 1000 leads enriquecidos (vs Apollo $300+/mês).
- **[nodus-agents](https://github.com/valterjuniorsilv/nodus-agents)** — 8 agents do Claude Code que rodam a operação real da NodusHub (5 engenharia + 3 comercial). Não é template genérico — é a config real, aberta pra outros founders forkarem e adaptarem.
- **[antigravity-lab](https://github.com/valterjuniorsilv/antigravity-lab)** — Laboratório de backend em Go. Clean Architecture + DDD + CQRS documentados em `.claude/rules/`. Fase de design — o repo entrega o contrato arquitetural antes do código.

### ⚡ Stack do dia a dia

**Diária:** Python · TypeScript · n8n · Anthropic Claude · FastAPI · Next.js · PostgreSQL · Docker · Evolution API
**Confortável:** Go · Supabase · Vercel · Hetzner Cloud · Meta Ads API · GA4

### 📡 Disponível pra

- **Vagas remotas** — AI Automation Engineer, Workflow Engineer, Backend (Python). CLT, PJ ou contractor.
- **Discussão técnica** sobre n8n em produção, prompts Claude pra atendimento, arquitetura de stack pra agência pequena.
- **Café virtual** se você tá começando uma operação parecida e quer trocar ideia.

### 📫 Como falar comigo

📍 Maringá, PR · UTC-3
✉️ valterjuniorsilv@gmail.com
🔗 [linkedin.com/in/valterjuniorsilv](https://linkedin.com/in/valterjuniorsilv)
🌐 [nodushub.com.br](https://nodushub.com.br)
