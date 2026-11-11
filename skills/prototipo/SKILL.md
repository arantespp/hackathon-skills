---
name: prototipo
description: Ajuda a equipe de um hackathon a construir um protótipo navegável ou MVP que funcione na demo, escolhendo a abordagem certa, escrevendo prompts para geradores de app com IA, criando dados de demonstração e testando o caminho feliz. Use quando a equipe disser "construir o protótipo", "MVP", "criar as telas", "prompt para o Lovable/v0/Bolt", "dados de exemplo", "colocar no ar", ou estiver programando o projeto do hackathon.
---

# Protótipo

Objetivo: ter **um protótipo que percorre o caminho feliz de ponta a ponta sem falhar**, com um link que a banca consegue abrir. Funcionar bem no que importa vale mais do que ter muitas funcionalidades.

Tempo sugerido: cerca de 30–35% do tempo total. É a etapa mais longa e a que mais atrasa: defina um horário de congelamento logo no início.

## Antes de começar: o arquivo PROJETO.md

As skills de hackathon compartilham um arquivo `PROJETO.md` na raiz do projeto. Cada etapa lê o que as anteriores escreveram e acrescenta a sua seção.

1. Se `PROJETO.md` existir, leia-o inteiro, principalmente `## Regras` (o que o regulamento exige do protótipo) e `## Solução` (fluxo, telas, escopo).
2. Se não houver `## Regras`, pergunte à equipe: prazo final, que tipo de protótipo é exigido (navegável, funcional, código-fonte), se o link precisa ser público e o que desclassifica.
3. Se não houver `## Solução`, peça o caminho feliz, a lista de telas e o escopo mínimo. Se nada disso existir, sugira a skill **desenho-solucao** antes de construir.
4. Sem acesso a arquivos, trabalhe na conversa e entregue no fim o bloco em Markdown para a equipe salvar.

## Passos

### 1. Escolher a abordagem
Escolha conforme as habilidades da equipe e o que o regulamento exige. As ferramentas abaixo são exemplos; use as que a equipe já conhece.

| Abordagem | Exemplos | Bom para | Cuidado |
|---|---|---|---|
| Protótipo clicável, sem código | Figma, Canva, slides interativos | Equipes sem programador; foco em UX | Pode valer menos em "funcionalidade" |
| Gerador de app com IA | Lovable, v0, Bolt | App real e bonito em pouco tempo | Fica difícil de corrigir quando cresce; faça em passos pequenos |
| Código com assistente de IA | Cursor, Claude Code, Copilot | Controle total, lógica própria | Exige alguém que saiba depurar |

Recomende a abordagem que **a equipe consegue consertar sozinha** quando algo quebrar às pressas.

### 2. Defina o horário de congelamento
Marque um horário a partir do qual só se corrigem erros, sem novas funcionalidades. Ele deve deixar tempo para a gravação do pitch (em geral, ao menos 25–30% do tempo total restante). Anote no `PROJETO.md`.

### 3. Dados de demonstração
Crie dados fictícios realistas e coerentes com a persona: nomes, produtos, valores e datas plausíveis. Dados realistas deixam a demo crível; "Teste 1, Teste 2" derruba a impressão. Gere um arquivo de seed (JSON ou CSV) ou uma lista para colar na ferramenta.

### 4. Prompt inicial (para geradores de app com IA)
Monte o primeiro prompt com esta estrutura e entregue pronto para copiar:

```text
Contexto: <o problema em 1–2 frases e quem é a persona>
Objetivo do app: <proposta de valor>
Telas (nesta ordem):
1. <tela> — <objetivo> — ação principal: <botão/ação>
2. ...
Fluxo: <caminho feliz passo a passo>
Dados de exemplo: <colar seed ou descrever>
Estilo visual: <ex.: limpo, cores X e Y, mobile first, idioma português>
Não fazer: <login real, pagamento, telas fora do escopo>
```

Depois, construa em **passos pequenos**: uma tela ou um ajuste por prompt, testando após cada um. Prompts gigantes geram erros difíceis de desfazer.

### 5. Ordem de construção
1. Caminho feliz de ponta a ponta, mesmo feio.
2. Momento "uau" funcionando de verdade.
3. Coloque no ar cedo (link público) e teste o link.
4. Visual e textos.
5. Só então, extras.

### 6. Integrações e IA dentro do produto
- Integrações arriscadas (APIs externas, pagamentos) podem ser simuladas. Seja honesto no pitch sobre o que é simulado.
- Se o produto chama um modelo de IA ao vivo, prepare uma alternativa (resposta salva) caso a API falhe ou demore na gravação.
- Nunca coloque chaves de API no código público nem no front-end.

### 7. Se você estiver programando junto (com acesso ao código)
- Prefira uma stack simples e conhecida pela equipe, um único repositório e deploy automático (por exemplo, Vercel, Netlify ou o próprio gerador de app).
- Faça commits pequenos e frequentes; antes do congelamento, marque a última versão que funciona.
- Rode o caminho feliz depois de cada mudança relevante.

### 8. Teste da demo
Antes do congelamento:
- [ ] Percorra o caminho feliz 3 vezes do zero, sem erros.
- [ ] Abra o link em uma janela anônima e em outro dispositivo (celular, se fizer sentido). Ele não pode exigir login ou permissão, se o regulamento pedir link aberto.
- [ ] Os dados de demonstração estão carregados e coerentes.
- [ ] Os tempos de carregamento são aceitáveis para gravar.
- [ ] Existe um plano B: vídeo de tela gravado ou capturas, caso algo caia na hora.

### 9. Registrar a autoria
Anote o que a equipe decidiu e construiu e onde a IA ajudou. Muitos regulamentos exigem autoria da equipe e desclassificam projetos feitos só por IA; esse registro também ajuda no pitch.

## Armadilhas comuns
- **Começar pelo login, cadastro ou configurações.** Ninguém julga isso. Comece pelo momento "uau".
- **Adicionar funcionalidades depois do congelamento.** É assim que a demo quebra na gravação.
- **Testar só no computador de quem fez.** O link precisa funcionar para a banca.
- **Esconder o que é simulado.** Diga "nesta versão os dados são simulados"; é aceito, mas ser pego não é.

## Saída
Acrescente ao `PROJETO.md`:

```markdown
## Protótipo
- Link: <url pública> — testado em janela anônima: <sim/não>
- Abordagem e ferramentas: <…>
- Horário de congelamento: <hora>
- Status das telas: <tela — pronta/parcial/simulada>
- Real x simulado: <lista>
- Roteiro da demo (cliques): 1. <…> 2. <…>
- Plano B: <vídeo de tela / capturas — onde estão>
- Autoria: <o que a equipe fez; onde a IA ajudou>
```

## Pronto quando
- [ ] O caminho feliz funciona 3 vezes seguidas, do zero.
- [ ] O link abre em janela anônima.
- [ ] O roteiro de cliques da demo está escrito.
- [ ] Existe plano B.

Próxima etapa: **roteiro-pitch**. Para uma avaliação crítica do protótipo, use **avaliacao-jurado**.
