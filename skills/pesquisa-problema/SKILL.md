---
name: pesquisa-problema
description: Ajuda a equipe de um hackathon a escolher o desafio e a entender a dor real do público, com evidências, antes de pensar em solução. Use no começo do hackathon ou quando a equipe disser "qual desafio escolher", "pesquisar o problema", "entender a dor", "criar persona", "buscar dados do mercado", ou colar o texto de um desafio ou do regulamento.
---

# Pesquisa do problema

Objetivo: terminar esta etapa com **um problema específico, de um público concreto, com evidências e ligado diretamente ao desafio escolhido**. Tudo o que vem depois (solução, protótipo, pitch) se apoia aqui.

Tempo sugerido: cerca de 15–20% do tempo total do hackathon.

## Antes de começar: o registro do projeto

As skills de hackathon compartilham um **registro do projeto**: um único documento com as seções Regras, Problema, Solução, Protótipo, Pitch e Revisões. Cada etapa lê o que as anteriores escreveram e acrescenta a sua seção.

**Onde fica o registro.** Use o lugar mais durável disponível neste ambiente, nesta ordem de preferência:
1. O lugar que a equipe indicou (arquivo, documento, link). Se a equipe ainda não indicou e há mais de uma pessoa trabalhando, pergunte se existe um lugar compartilhado.
2. Se você tem acesso a arquivos ou a um repositório: um arquivo `PROJETO.md` na raiz.
3. Se você pode criar ou editar documentos (num drive conectado, numa área de documentos ou artefatos, num canvas): um documento chamado "Registro do projeto".
4. Se nada disso estiver disponível: entregue a sua seção no fim da resposta, em Markdown, num único bloco, e peça que a equipe salve e cole na próxima conversa.

Sempre diga à equipe onde o registro ficou salvo.

**Ler o registro.** Procure o registro no lugar indicado pela equipe ou nos lugares que você consegue acessar e leia-o inteiro. Se não encontrar, peça que a equipe cole ou anexe.

Se o registro não existir, ou não tiver a seção `## Regras`, peça à equipe o regulamento (edital) e o texto dos desafios e crie a seção com o modelo abaixo. Extraia só o que muda decisões. Se a equipe não tiver o regulamento, pergunte cada item e marque o que ficar sem resposta como `a confirmar`.

```markdown
# Registro do projeto

## Regras
- Prazo final de entrega: <data e hora, fuso>
- Entregáveis e formato: <ex.: vídeo de até N min, link do protótipo, repositório>
- Canal oficial de envio: <onde e como; o que é proibido>
- Envios múltiplos: <permitido? vale o último?>
- Critérios de avaliação: <lista, com pesos se houver>
- Formato do julgamento: <ex.: confrontos diretos, banca com notas, apresentação ao vivo>
- Elementos obrigatórios do pitch: <lista na ordem do regulamento>
- Regras que desclassificam: <ex.: link privado, plágio, projeto feito só por IA>
- Uso de IA: <permitido? com que condições?>
- Equipe: <tamanho mínimo e máximo, papéis>
```

## Passos

### 1. Mapear os desafios
Para cada desafio disponível, escreva uma linha:
- quem propõe o desafio (empresa, organização, banca);
- quem sofre o problema no dia a dia;
- o que quem propôs espera ver no fim.

### 2. Escolher o desafio
Compare os desafios com a equipe usando estas perguntas:
- Alguém da equipe conhece ou tem acesso ao público afetado?
- Dá para demonstrar algo funcionando no tempo disponível?
- A equipe consegue ser específica nesse tema, ou só genérica?
- Que solução óbvia a maioria das equipes vai propor? Dá para fugir dela?

Recomende um desafio e diga por quê, mas **a decisão é da equipe**. Registre quem decidiu e o motivo.

### 3. Decompor a dor
Faça a equipe responder, de forma concreta:
- **Quem exatamente?** Persona com contexto: tipo e tamanho de negócio ou perfil de pessoa, rotina, ferramentas que já usa, nível de familiaridade com tecnologia.
- **Quando dói?** Em que momento da rotina o problema aparece.
- **Como resolve hoje?** A gambiarra atual: planilha, caderno, WhatsApp, não resolve.
- **Quanto custa?** Tempo perdido, dinheiro, vendas perdidas, clientes que não voltam.

Pergunte se alguém da equipe conhece uma pessoa desse público. Uma conversa de 10 minutos, mesmo por mensagem, vale mais que uma hora de pesquisa genérica e vira uma ótima história para o pitch.

### 4. Buscar evidências
Reúna de 3 a 5 dados que sustentem o tamanho e a gravidade do problema: pesquisas de mercado, estatísticas oficiais, relatórios de associações, notícias recentes.
- Se você tiver busca na web, use-a. Se não tiver, sugira ferramentas com busca (por exemplo, Perplexity, Gemini ou ChatGPT com busca) e diga exatamente o que procurar.
- **Sempre indique fonte e ano.** Nunca invente números. Um dado sem fonte deve ser marcado como `hipótese`.
- Prefira dados locais e recentes, ligados ao público do desafio.

### 5. Escrever a declaração do problema
Use o formato:

> **[Persona]** precisa **[tarefa]**, mas **[obstáculo]**, o que causa **[consequência mensurável]**.

Teste a frase:
- Cabe em uma frase?
- Não menciona a solução?
- Quem propôs o desafio concordaria com ela?

### 6. Listar as hipóteses arriscadas
O que precisa ser verdade para esse problema valer a pena? Liste de 2 a 3 hipóteses e diga como cada uma poderia ser verificada.

## Armadilhas comuns
- **Começar pela solução** ("vamos fazer um app com IA"). Volte para a dor.
- **Problema genérico demais** ("pequenos negócios vendem pouco"). Afunile até uma situação concreta.
- **Dados sem fonte** ou números arredondados demais. A banca percebe.
- **Deixar a IA decidir tudo.** Muitos regulamentos desclassificam projetos sem autoria da equipe. A IA pesquisa e propõe; a equipe decide e registra.

## Saída
Acrescente ao registro do projeto:

```markdown
## Problema
- Desafio escolhido: <nome> — por quê: <motivo> (decidido por: <nomes>)
- Persona: <descrição concreta>
- Declaração do problema: <frase>
- Como resolvem hoje: <gambiarra atual>
- Evidências:
  - <dado> — <fonte, ano>
- Hipóteses arriscadas:
  - <hipótese> — como verificar: <forma>
```

## Pronto quando
- [ ] O desafio foi escolhido e o motivo está registrado.
- [ ] A persona é específica o bastante para imaginar uma pessoa real.
- [ ] A declaração do problema cabe em uma frase e não fala da solução.
- [ ] Há pelo menos 3 evidências com fonte.

Próxima etapa: **desenho-solucao**.
