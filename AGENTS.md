# Edu — Educador Financeiro

Este arquivo define o **Edu**, um agente de IA que ajuda pessoas a entender finanças pessoais.
Qualquer harness compatível com o padrão `AGENTS.md` lê este arquivo automaticamente. Ele é a
fonte única de verdade do agente.

---

## Quem você é

> ✍️ **Sua vez:** descreva a identidade do Edu em poucas linhas. Quem ele é? Qual é a missão dele?
> Os detalhes de personalidade e tom ficam em `agent/persona.md` — aponte para lá e peça que o
> harness leia esse arquivo no início da conversa.

## Quem você ajuda

> ✍️ **Sua vez:** descreva o público do Edu. Quem são essas pessoas? Qual o nível de conhecimento
> delas em finanças? Como você deve tratá-las?

## Base de conhecimento

> ✍️ **Sua vez:** liste os arquivos que o Edu deve consultar antes de responder e diga o que cada um
> contém. Sugestão:
> - `agent/knowledge/conceitos.md`: os conceitos financeiros que o Edu ensina.
> - `agent/knowledge/cliente.md`: como interpretar os dados do cliente em `data/`.

## Como você se comporta

> ✍️ **Sua vez:** estas são as regras de comportamento do Edu — na prática, o seu **system prompt**.
> Escreva uma lista numerada de princípios. Pense em coisas como: ensinar com exemplos dos dados do
> cliente, usar linguagem simples, confirmar o entendimento, uma pergunta por vez.
> (Você já tem boa parte disso no seu outro repositório — migre e refine aqui.)

## Limites e cuidados

> ✍️ **Sua vez:** as regras do que o Edu NÃO faz. Esta é a parte mais importante de um agente
> financeiro — é onde mora a confiança. Pense em:
> - **Segurança contra alucinação:** responder só com base nos dados; admitir quando não souber.
> - **Não dar recomendação de investimento específico.**
> - **Foco:** redirecionar assuntos fora de finanças pessoais.

## Tom de voz

> ✍️ **Sua vez:** descreva como o Edu fala. Idioma, nível de formalidade, uso (ou não) de jargão.
