# Skills para Hackathon

Skills para o Claude que ajudam equipes a passar por cada etapa de um hackathon: da pesquisa do problema até a entrega. Elas são genéricas: as regras de cada evento (prazos, critérios, entregáveis, o que desclassifica) vêm do regulamento que a própria equipe fornece.

## As skills

| Skill | Etapa | O que entrega | Tempo sugerido |
|---|---|---|---|
| `pesquisa-problema` | Pesquisa | Desafio escolhido, persona, declaração do problema, evidências com fonte | ~15–20% |
| `desenho-solucao` | Modelagem | Proposta de valor, diferencial, momento "uau", fluxo de telas, escopo mínimo, viabilidade | ~15–20% |
| `prototipo` | Protótipo | Abordagem, prompts para geradores de app, dados de demonstração, testes da demo | ~30–35% |
| `roteiro-pitch` | Pitch | Roteiro cronometrado, abertura forte, plano de slides e gravação | ~20–25% |
| `avaliacao-jurado` | Qualquer etapa e entrega | Nota por critério, riscos de desclassificação, prioridades, checklist de entrega | — |

Reserve os minutos finais (cerca de 5–10%) para a entrega, com uma versão de segurança enviada antes do prazo.

## Como as skills se conectam

Todas leem e escrevem um arquivo `PROJETO.md` na raiz do projeto da equipe:

```
## Regras      ← criada pela primeira skill usada, a partir do regulamento
## Problema    ← pesquisa-problema
## Solução     ← desenho-solucao
## Protótipo   ← prototipo
## Pitch       ← roteiro-pitch
## Revisões    ← avaliacao-jurado
```

Assim a equipe não precisa repetir o contexto em cada conversa. No chat (sem acesso a arquivos), as skills devolvem o bloco em Markdown para a equipe guardar e colar na próxima conversa.

**Dica:** comece colando o regulamento do hackathon. As skills usam os critérios de avaliação e as regras de desclassificação dele em todas as etapas.

## Instalação

### Claude Code (plugin)

```bash
/plugin marketplace add arantespp/hackathon-skills
```

```bash
/plugin install hackathon@hackathon-skills
```

### Claude Code (cópia manual)

Copie as pastas de `skills/` para `~/.claude/skills/` (todas as suas sessões) ou para `.claude/skills/` dentro do projeto da equipe.

### Claude.ai (app ou web)

Compacte cada pasta de `skills/` em um `.zip` (por exemplo, `pesquisa-problema.zip` contendo `pesquisa-problema/SKILL.md`) e envie em **Configurações → Capacidades → Skills**.

## Uso

As skills são acionadas pelo que a equipe pede. Exemplos:

- "Aqui está o regulamento e os desafios. Qual desafio devemos escolher?"
- "Vamos desenhar o fluxo de telas da solução."
- "Escreva o prompt para o Lovable criar o protótipo."
- "Monte o roteiro do vídeo de 3 minutos."
- "Avalie nosso projeto como um jurado. Faltam 2 horas."
- "Vamos enviar. Passe o checklist de entrega."

## Princípio: a IA ajuda, a equipe decide

Muitos regulamentos desclassificam projetos sem autoria da equipe. As skills propõem opções e fazem perguntas, mas deixam as decisões com a equipe e as registram no `PROJETO.md`.
