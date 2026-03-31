# Ink Scale — Fluxo de Producao de Scripts

## VISAO GERAL

Este repositorio contem 3 agentes especializados para producao de scripts para tatuadores americanos.

---

## METODOLOGIA INK SCALE — 6 PILARES

Toda producao de conteudo deve estar conectada a um pilar da metodologia.
O Hook Agent SEMPRE pergunta qual pilar antes de gerar hooks (a menos que o usuario ja informe).

| Pilar | Nome |
|-------|------|
| **1** | Exposicao e Posicionamento |
| **2** | Pre-Vendas e Qualificacao |
| **3** | Ofertas e Aumento do Ticket Medio |
| **4** | Processos Comerciais / Conversao |
| **5** | Follow-up e Gestao de Agenda |
| **6** | Gestao Completa do Sistema |

---

## FLUXO DE PRODUCAO

```
TEMA/ANGULO + PILAR
    |
    v
[Hook Agent]  -->  5 opcoes de hook  -->  Usuario aprova 1
    |
    v
[Script Agent]  -->  Roteiro completo (sem CTA)  -->  Usuario aprova/ajusta
    |
    v
[Isca Agent]  -->  3 opcoes de isca  -->  Usuario escolhe 1  -->  Isca desenvolvida + CTA final
    |
    v
CONTEUDO PRONTO PRA PUBLICAR
```

---

## COMO USAR

### Passo 1 — Hook
Diga o tema. O sistema vai perguntar qual pilar da metodologia, depois te dar 5 opcoes.
Aprove uma (A, B, C, D ou E).

### Passo 2 — Roteiro
Com o hook aprovado, o sistema carrega `agents/script-agent.md`.
Se voce tiver um roteiro de referencia (um video seu, um texto bruto), envie junto — o agente vai modelar a partir dele.
Se nao tiver, so o hook + tema ja bastam.

### Passo 3 — Isca
Com o roteiro pronto, o sistema carrega `agents/isca-agent.md`.
Voce recebe 3 opcoes de isca. Escolhe uma. O agente desenvolve o conteudo completo e embuteo CTA no roteiro.

---

## ATALHOS

- **Trocar hook:** "quero outro hook" — volta pro Hook Agent
- **Ajustar roteiro:** "encurta o corpo" / "mais agressivo" / "muda o formato pra carrossel" — o Script Agent ajusta
- **Pular isca:** "sem isca" — roteiro fica sem CTA de lead magnet
- **Roteiro de referencia:** Cole qualquer texto/transcricao e diga "modela a partir disso"

---

## REGRAS GLOBAIS

- TUDO em PT-BR — hooks, roteiros, iscas, CTAs, tudo
- Nunca soar como anuncio
- Sempre entregar micro-vitoria concreta
- Cada agente faz SO sua funcao — nao invade o escopo do outro

---

## ARQUIVOS

| Arquivo | Funcao |
|---------|--------|
| `agents/hook-agent.md` | Seleciona e adapta hooks da base de 99 |
| `agents/script-agent.md` | Monta roteiro completo a partir de hook aprovado |
| `agents/isca-agent.md` | Gera opcoes de isca e desenvolve a escolhida |
