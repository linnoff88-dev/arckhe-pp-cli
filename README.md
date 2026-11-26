ï»¿# pp-cli ê¢â¬â Curso prêÂ¡tico de Printing Press

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso em portuguêÂªs sobre **Printing Press** ê¢â¬â a ferramenta que transforma sites e APIs em CLIs otimizadas para agentes de IA (Claude Code).

> **Por que isso importa?** Em benchmarks oficiais, MCP usa **35êâ mais tokens** que CLI na mesma tarefa, e a confiabilidade cai de 100% para 72%. CLIs sêÂ£o a forma mais eficiente de agentes conversarem com ferramentas externas.

## ê°Å¸âÅ¡ Curso

Acesse a versêÂ£o web (servida pelo GitHub Pages na raiz do `main`):

**https://inematds.github.io/pp-cli/**

### Estrutura

- [`index.html`](index.html) ê¢â¬â landing geral
- [`curso/printing-press/index.html`](curso/printing-press/index.html) ê¢â¬â trilha completa (mapa + 7 mêÂ³dulos)
- MêÂ³dulos:
  1. [Conceitos: CLI vs API vs MCP](curso/printing-press/modulo-1-1.html)
  2. [InstalaêÂ§êÂ£o completa](curso/printing-press/modulo-1-2.html)
  3. [Primeiros passos com o starter-pack](curso/printing-press/modulo-1-3.html)
  4. [Criando sua prêÂ³pria CLI](curso/printing-press/modulo-1-4.html)
  5. [Caso prêÂ¡tico: BrasilAPI](curso/printing-press/modulo-1-5.html)
  6. [IntegraêÂ§êÂµes: n8n + Supabase](curso/printing-press/modulo-1-6.html)
  7. [Publicando no library oficial](curso/printing-press/modulo-1-7.html)

Cada mêÂ³dulo tem 6 têÂ³picos com seêÂ§êÂµes "O que êÂ© / Por que aprender / Conceitos-chave" e exemplos prêÂ¡ticos reais.

## ê°Å¸Å¡â¬ Quick start

```bash
# PrêÂ©-requisitos: Go 1.26.3+, Node 18+, Claude Code 2.0+

# 1. Instalar binêÂ¡rio factory
go install github.com/mvanhorn/cli-printing-press/v4/cmd/printing-press@latest

# 2. Instalar starter-pack (4 CLIs prontas)
npx -y @mvanhorn/printing-press install starter-pack

# 3. Listar CLIs instaladas
npx -y @mvanhorn/printing-press list
```

Depois, no Claude Code, peêÂ§a em linguagem natural:

> _"quais jogos da NBA têÂªm hoje?"_ ê¢â â invoca `pp-espn`
> _"voos baratos GRUê¢â âLIS em julho"_ ê¢â â invoca `pp-flight-goat`

## ê°Å¸âºÂ ê¯Â¸Â Servir localmente

```bash
# Qualquer servidor estêÂ¡tico funciona, ex:
python3 -m http.server 8000
# Abra http://localhost:8000/
```

## ê°Å¸ââ Links oficiais

- Site Printing Press: https://printingpress.dev
- Repo factory: https://github.com/mvanhorn/cli-printing-press
- Biblioteca de CLIs: https://github.com/mvanhorn/printing-press-library
- INEMA.CLUB: https://inema.club

## ê°Å¸âÂ LicenêÂ§a

Material do curso: MIT. Printing Press e CLIs derivadas seguem licenêÂ§as dos repositêÂ³rios oficiais.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>