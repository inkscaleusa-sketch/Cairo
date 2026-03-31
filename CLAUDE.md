# Ink Scale — Fluxo de Producao de Scripts

## VISAO GERAL

Este repositorio contem 3 agentes especializados para producao de scripts para tatuadores americanos.

---

## FLUXO DE PRODUCAO

```
TEMA/ANGULO
    |
    v
[Hook Agent]  -->  3 opcoes de hook  -->  Usuario aprova 1
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
Diga o tema. O sistema vai carregar `agents/hook-agent.md` e te dar 3 opcoes.
Aprove uma (A, B ou C).

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

- Hooks e roteiros SEMPRE em ingles americano (ICP e americano)
- Conversa em PT-BR
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
