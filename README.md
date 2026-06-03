# Edu — Educador Financeiro Inteligente

> ✍️ **Sua vez:** escreva aqui, em 2 ou 3 linhas, o que é o Edu e o problema que ele resolve.
> Exemplo de estrutura (não copie, adapte com as suas palavras): "O Edu é um agente de IA que ensina
> finanças pessoais de forma simples, usando os próprios dados do cliente como exemplos."

## Como funciona

Este projeto segue o padrão aberto **[AGENTS.md](https://agents.md)**: toda a definição do agente vive
em arquivos de texto (Markdown). Não há um "app" tradicional — o agente ganha vida quando você abre
esta pasta em um **harness** compatível (Claude Code, Cursor, Gemini CLI, Antigravity e outros).

O harness lê o `AGENTS.md` automaticamente e passa a se comportar como o Edu.

## Como rodar

> ✍️ **Sua vez:** descreva o passo a passo pra alguém testar o Edu. Algo como:
> 1. Clone este repositório.
> 2. Abra a pasta em um harness compatível com `AGENTS.md`.
> 3. Comece a conversar.

## Estrutura do projeto

```
.
├── AGENTS.md            # Fonte única da verdade: quem é o Edu e como ele age
├── CLAUDE.md            # Importa o AGENTS.md (para o Claude Code)
├── agent/
│   ├── persona.md       # O "caráter" do Edu: personalidade e tom
│   └── knowledge/       # O que o Edu sabe
│       ├── conceitos.md # Conceitos de finanças que ele ensina
│       └── cliente.md   # Como ler os dados do cliente
└── data/                # Dados mockados do cliente (perfil, transações...)
```
