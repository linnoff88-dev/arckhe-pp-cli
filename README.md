# pp-cli â€” Curso prÃ¡tico de Printing Press

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso em portuguÃªs sobre **Printing Press** â€” a ferramenta que transforma sites e APIs em CLIs otimizadas para agentes de IA (Claude Code).

> **Por que isso importa?** Em benchmarks oficiais, MCP usa **35Ã— mais tokens** que CLI na mesma tarefa, e a confiabilidade cai de 100% para 72%. CLIs sÃ£o a forma mais eficiente de agentes conversarem com ferramentas externas.

## ðŸ“š Curso

Acesse a versÃ£o web (servida pelo GitHub Pages na raiz do `main`):

**https://inematds.github.io/pp-cli/**

### Estrutura

- [`index.html`](index.html) â€” landing geral
- [`curso/printing-press/index.html`](curso/printing-press/index.html) â€” trilha completa (mapa + 7 mÃ³dulos)
- MÃ³dulos:
  1. [Conceitos: CLI vs API vs MCP](curso/printing-press/modulo-1-1.html)
  2. [InstalaÃ§Ã£o completa](curso/printing-press/modulo-1-2.html)
  3. [Primeiros passos com o starter-pack](curso/printing-press/modulo-1-3.html)
  4. [Criando sua prÃ³pria CLI](curso/printing-press/modulo-1-4.html)
  5. [Caso prÃ¡tico: BrasilAPI](curso/printing-press/modulo-1-5.html)
  6. [IntegraÃ§Ãµes: n8n + Supabase](curso/printing-press/modulo-1-6.html)
  7. [Publicando no library oficial](curso/printing-press/modulo-1-7.html)

Cada mÃ³dulo tem 6 tÃ³picos com seÃ§Ãµes "O que Ã© / Por que aprender / Conceitos-chave" e exemplos prÃ¡ticos reais.

## ðŸš€ Quick start

```bash
# PrÃ©-requisitos: Go 1.26.3+, Node 18+, Claude Code 2.0+

# 1. Instalar binÃ¡rio factory
go install github.com/mvanhorn/cli-printing-press/v4/cmd/printing-press@latest

# 2. Instalar starter-pack (4 CLIs prontas)
npx -y @mvanhorn/printing-press install starter-pack

# 3. Listar CLIs instaladas
npx -y @mvanhorn/printing-press list
```

Depois, no Claude Code, peÃ§a em linguagem natural:

> _"quais jogos da NBA tÃªm hoje?"_ â†’ invoca `pp-espn`
> _"voos baratos GRUâ†’LIS em julho"_ â†’ invoca `pp-flight-goat`

## ðŸ› ï¸ Servir localmente

```bash
# Qualquer servidor estÃ¡tico funciona, ex:
python3 -m http.server 8000
# Abra http://localhost:8000/
```

## ðŸ”— Links oficiais

- Site Printing Press: https://printingpress.dev
- Repo factory: https://github.com/mvanhorn/cli-printing-press
- Biblioteca de CLIs: https://github.com/mvanhorn/printing-press-library
- INEMA.CLUB: https://inema.club

## ðŸ“ LicenÃ§a

Material do curso: MIT. Printing Press e CLIs derivadas seguem licenÃ§as dos repositÃ³rios oficiais.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>