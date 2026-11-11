---
name: avaliacao-jurado
description: Avalia o projeto de hackathon como um jurado faria, dando nota em cada critério do regulamento, apontando lacunas, riscos de desclassificação e as ações de maior retorno para o tempo restante, e conduz o checklist final de entrega. Use em qualquer etapa ou quando a equipe disser "avalie nosso projeto", "o que o jurado acharia", "estamos prontos?", "revisar o pitch", "checklist de entrega", "vamos enviar".
---

# Avaliação de jurado

Objetivo: dar à equipe **uma avaliação honesta, do ponto de vista da banca**, e dizer exatamente o que fazer com o tempo que resta. Pode ser usada depois de qualquer etapa e, obrigatoriamente, antes do envio.

## Antes de começar: o registro do projeto

As skills de hackathon compartilham um **registro do projeto**: um único documento com as seções Regras, Problema, Solução, Protótipo, Pitch e Revisões. Cada etapa lê o que as anteriores escreveram e acrescenta a sua seção.

**Onde fica o registro.** Use o lugar mais durável disponível neste ambiente, nesta ordem de preferência:
1. O lugar que a equipe indicou (arquivo, documento, link). Se a equipe ainda não indicou e há mais de uma pessoa trabalhando, pergunte se existe um lugar compartilhado.
2. Se você tem acesso a arquivos ou a um repositório: um arquivo `PROJETO.md` na raiz.
3. Se você pode criar ou editar documentos (num drive conectado, numa área de documentos ou artefatos, num canvas): um documento chamado "Registro do projeto".
4. Se nada disso estiver disponível: entregue a sua seção no fim da resposta, em Markdown, num único bloco, e peça que a equipe salve e cole na próxima conversa.

Sempre diga à equipe onde o registro ficou salvo.

**Ler o registro.** Procure o registro no lugar indicado pela equipe ou nos lugares que você consegue acessar e leia-o inteiro. Se não encontrar, peça que a equipe cole ou anexe.

- Os critérios de avaliação e as regras que desclassificam vêm de `## Regras`. Se essa seção não existir, peça o regulamento. Sem regulamento, use os critérios comuns (inovação, funcionalidade, aderência ao desafio, impacto e viabilidade) e **diga que está supondo**.
- Pergunte quanto tempo falta até o prazo final. As recomendações dependem disso.
- Avalie também o que a equipe enviar na conversa: link do protótipo, roteiro, transcrição ou arquivo do vídeo, slides.

## Passos

### 1. Assuma o papel do jurado
Avalie como alguém da banca: representante de quem propôs o desafio, mentor ou especialista do setor, que já viu dezenas de projetos, tem pouco tempo e é cético. Seja **direto e honesto**: notas infladas não ajudam a equipe a ganhar.

Avalie apenas o que existe. Diga em que etapa o projeto está e o que ainda não dá para avaliar.

### 2. Nota por critério
Para cada critério do regulamento:

| Critério | Nota (1–5) | Evidência | O que falta | Ação de maior retorno (tempo estimado) |
|---|---|---|---|---|

- **Evidência:** cite o trecho concreto do material que justifica a nota.
- **O que falta:** o que faria a nota subir um ponto.
- **Ação:** uma ação concreta, com estimativa de tempo.

Se o regulamento tiver pesos, calcule a nota ponderada.

### 3. Testes rápidos da banca
- **Aderência:** o projeto responde diretamente ao desafio escolhido, com as palavras do desafio? Ou responde a um problema vizinho?
- **15 segundos:** se o julgamento compara projetos lado a lado ou se há muitos inscritos, os primeiros 15 segundos do pitch fariam este projeto ganhar do concorrente médio?
- **Memória:** que frase o jurado lembraria depois de ver 30 projetos? Se não houver uma, sugira.
- **Pergunta difícil:** qual a pergunta que a banca mais provavelmente faria e que a equipe ainda não respondeu (geralmente viabilidade, diferencial ou dados)?

### 4. Riscos de desclassificação
Passe por cada regra que desclassifica em `## Regras` e marque **OK**, **risco** ou **não verificado**. Fique atento principalmente a:
- link privado, quebrado ou que exige login;
- duração acima do limite;
- elementos obrigatórios faltando;
- envio fora do canal oficial;
- plágio ou falta de autoria da equipe (projeto feito só por IA);
- composição da equipe fora da regra.

### 5. Prioridades
Liste as **3 ações** com maior impacto por tempo restante, em ordem. Se faltar pouco tempo, priorize evitar desclassificação e deixar a demo e o pitch claros, não novas funcionalidades.

### 6. Checklist de entrega (perto do prazo)
Quando a equipe estiver perto de enviar, conduza o checklist item por item e peça confirmação de cada um:

- [ ] O vídeo ou a apresentação está dentro da duração máxima.
- [ ] Todos os elementos obrigatórios do regulamento aparecem.
- [ ] Links (vídeo, protótipo, repositório) abrem em janela anônima, sem login e sem pedir permissão.
- [ ] A visibilidade do vídeo é a exigida (por exemplo, "não listado" em vez de "privado", quando o regulamento pede link aberto).
- [ ] O envio é feito **somente pelo canal oficial**, nunca por mensagem, e-mail ou rede social se o regulamento proibir.
- [ ] Se o regulamento permite vários envios, uma **versão de segurança foi enviada com folga** (por exemplo, 30 a 45 minutos antes do prazo), e o envio final será feito antes do horário-limite.
- [ ] Nomes dos integrantes, título e descrição estão como o regulamento pede.
- [ ] Capturas de tela da confirmação de envio foram salvas.
- [ ] Existe cópia local do vídeo e dos materiais.

## Saída
Acrescente ao registro do projeto (uma entrada por avaliação, a mais recente no topo):

```markdown
## Revisões
### <data e hora> — etapa: <pesquisa/solução/protótipo/pitch/entrega>
- Notas: <critério: nota> … (total: <x>)
- Riscos de desclassificação: <item — OK/risco/não verificado>
- Prioridades:
  1. <ação — tempo>
  2. <ação — tempo>
  3. <ação — tempo>
- Checklist de entrega: <itens pendentes, se houver>
```
