# 🧠 Miniguia de Estudos: UX e Vieses Cognitivos Aplicados ao Design

Caderno temático construído no **NotebookLM** como projeto prático do desafio da DIO.
Autor: **Gustavo Cesar Cioni** · Designer

---

## 🎯 Contexto e Objetivos

### Por que este tema
Trabalho com design há quase cinco anos e, nesse tempo, percebi que muitas decisões de interface funcionam (ou falham) menos por estética e mais por psicologia: o usuário não decide de forma puramente racional. Vieses cognitivos explicam por que um botão, um preço ou uma lista de opções muda o comportamento das pessoas. Estudar esse assunto me ajuda a projetar melhor e, igualmente importante, a reconhecer quando uma interface cruza a linha entre **orientar** e **manipular**.

### Objetivos de estudo
1. Entender e explicar com minhas palavras 8 vieses cognitivos centrais para o design de produtos.
2. Reconhecer cada viés em interfaces reais.
3. Saber propor uma aplicação ética de cada viés e apontar o risco de uso abusivo (*dark patterns*).
4. Aprender a extrair respostas úteis e verificáveis de uma IA baseada em fontes (NotebookLM).

### Como vou saber que aprendi
Conseguir analisar uma tela qualquer e listar, com justificativa, quais vieses ela ativa e se o uso é ético. A análise final deste repositório é esse teste.

---

## 📚 Curadoria de Fontes

Fontes abertas carregadas no NotebookLM. Escolhi perspectivas diferentes de propósito (prática, ética e científica) para poder pedir comparações entre elas.

| # | Fonte | Tipo | Link | Por que escolhi |
|---|-------|------|------|-----------------|
| 1 | Laws of UX | Site / princípios | https://lawsofux.com/ | Traduz princípios psicológicos em regras de design, em linguagem direta. |
| 2 | Nielsen Norman Group (artigos sobre psicologia e comportamento) | Artigos | https://www.nngroup.com/ | Referência de pesquisa em UX, com base empírica. |
| 3 | Deceptive Design | Catálogo | https://www.deceptive.design/ | Mostra o lado ético: como vieses são explorados em *dark patterns*. |
| 4 | Interaction Design Foundation (artigos abertos sobre vieses e comportamento) | Artigos | https://www.interaction-design.org/ | Visão didática e organizada por tema. |
| 5 | Artigo acadêmico aberto sobre heurísticas e vieses | PDF | *[inserir link]* | Base científica para contrastar com a visão prática. |

> Observação: o livro *Enviesados* (Rian Dutra) inspirou o recorte do tema, mas por ser obra protegida **não foi carregado** no NotebookLM. As fontes acima são todas abertas.

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

Aqui documento o raciocínio por trás dos resultados: o que perguntei, o que veio, o que falhou e como ajustei. As respostas abaixo foram obtidas no NotebookLM com as 5 fontes acima.

### Prompt 1: Mapeamento dos vieses
- **Prompt usado:** "Liste os vieses cognitivos mencionados nas fontes e agrupe por tema (decisão, atenção, memória, influência social). Cite a fonte de cada um."
- **Resposta obtida (resumo):** *[PREENCHER]*
- **Referências citadas pelo NotebookLM:** *[PREENCHER]*
- **Dificuldade / troubleshooting:** *[PREENCHER]*

### Prompt 2: Definição com exemplo em interface
- **Prompt usado:** "Explique ancoragem em até 3 linhas e dê um exemplo em uma tela de e-commerce, citando em qual fonte isso aparece."
- **Resposta obtida (resumo):** *[PREENCHER]*
- **Referências citadas pelo NotebookLM:** *[PREENCHER]*
- **Dificuldade / troubleshooting:** *[PREENCHER]*

### Prompt 3: Comparação entre fontes
- **Prompt usado:** "Onde as fontes concordam e onde divergem sobre aversão à perda? Aponte as diferenças de abordagem."
- **Resposta obtida (resumo):** *[PREENCHER]*
- **Referências citadas pelo NotebookLM:** *[PREENCHER]*
- **Dificuldade / troubleshooting:** *[PREENCHER]*

### Prompt 4: Limite ético
- **Prompt usado:** "Segundo as fontes, em que ponto o uso de escassez e urgência deixa de ser boa prática e vira dark pattern? Dê critérios."
- **Resposta obtida (resumo):** *[PREENCHER]*
- **Referências citadas pelo NotebookLM:** *[PREENCHER]*
- **Dificuldade / troubleshooting:** *[PREENCHER]*

### Prompt 5: Aplicação em um fluxo
- **Prompt usado:** "Considere um fluxo de checkout. Para cada etapa, indique quais vieses estão em jogo e se a prática é ética segundo as fontes."
- **Resposta obtida (resumo):** *[PREENCHER]*
- **Referências citadas pelo NotebookLM:** *[PREENCHER]*
- **Dificuldade / troubleshooting:** *[PREENCHER]*

### Prompt 6: O prompt que falhou (cicatriz)
- **Prompt usado (versão 1):** "Fale sobre vieses no design."
- **Resposta obtida:** *[PREENCHER: descreva o resultado real, por exemplo, genérico, sem foco, misturando conceitos]*
- **Diagnóstico:** o pedido não tinha escopo, formato nem exigência de fonte, então a IA devolveu um panorama raso.
- **Versão melhorada:** "Com base apenas nas fontes carregadas, explique 3 vieses que afetam decisões de compra em interfaces. Para cada um: definição em 1 frase, exemplo em tela e fonte citada. Se as fontes não cobrirem algo, diga explicitamente."
- **Resultado da versão melhorada:** *[PREENCHER]*

### Lições sobre prompts
- Delimitar o escopo ("com base apenas nas fontes") reduz respostas genéricas.
- Pedir formato fixo (definição, exemplo, fonte) deixa a resposta comparável e revisável.
- Pedir que a IA diga quando a fonte não cobre algo reduz invenções.
- Sempre conferir as citações: clicar na referência e checar se o trecho realmente sustenta a afirmação.

---

## 📖 Miniguia de Estudo

### Resumos estruturados (fichas dos vieses)

> Formato: definição · onde aparece · aplicação ética · risco de abuso.

#### 1. Ancoragem
- **Definição:** tendência de depender demais da primeira informação recebida (a "âncora") ao fazer um julgamento.
- **Onde aparece:** preço "de R$ 599 por R$ 399"; plano intermediário ao lado de um plano caro.
- **Aplicação ética:** mostrar um preço de referência real e comparações honestas entre planos.
- **Risco:** inflar artificialmente o preço original.

#### 2. Efeito de enquadramento (framing)
- **Definição:** a mesma informação gera decisões diferentes conforme a forma como é apresentada.
- **Onde aparece:** "90% de aprovação" versus "10% de reprovação"; "economize R$ 50" versus "você perde R$ 50".
- **Aplicação ética:** enquadrar de forma clara e precisa, sem omitir custos relevantes.
- **Risco:** esconder custos ou riscos por trás de um enquadramento positivo.

#### 3. Aversão à perda
- **Definição:** perdas costumam pesar mais do que ganhos do mesmo tamanho.
- **Onde aparece:** "seu teste termina em 2 dias e você perderá seus projetos".
- **Aplicação ética:** lembrar o usuário de benefícios reais que ele deixaria de ter.
- **Risco:** culpa no cancelamento e mensagens de *confirmshaming*.

#### 4. Escassez e urgência
- **Definição:** damos mais valor ao que parece limitado em quantidade ou tempo.
- **Onde aparece:** "restam 2 quartos", contadores regressivos.
- **Aplicação ética:** comunicar limites reais de estoque ou prazo.
- **Risco:** contadores falsos e escassez inventada.

#### 5. Viés do status quo (defaults)
- **Definição:** preferência por manter a opção padrão em vez de mudar.
- **Onde aparece:** opções pré-selecionadas, configurações padrão, *opt-in* versus *opt-out*.
- **Aplicação ética:** defaults que protegem o usuário (ex.: privacidade ativada por padrão).
- **Risco:** caixas pré-marcadas que inscrevem o usuário em algo sem que ele perceba.

#### 6. Excesso de escolhas e complexidade (Lei de Hick)
- **Definição:** quanto mais opções e mais complexas, maior o tempo e o esforço para decidir. Observação: a Lei de Hick e o "paradoxo da escolha" são ideias relacionadas, mas distintas, e nem todas as fontes tratam como "viés" no sentido estrito. *[Validar na análise das fontes.]*
- **Onde aparece:** menus longos, tabelas de planos com muitas variações.
- **Aplicação ética:** reduzir opções, agrupar e usar divulgação progressiva.
- **Risco:** esconder opções importantes (como cancelar) sob o pretexto de simplificar.

#### 7. Prova social
- **Definição:** tendemos a seguir o comportamento e a opinião de outras pessoas, sobretudo sob incerteza.
- **Onde aparece:** avaliações, "1.200 pessoas compraram hoje", depoimentos.
- **Aplicação ética:** exibir dados reais e verificáveis.
- **Risco:** avaliações falsas ou números inflados.

#### 8. Efeito de posição serial
- **Definição:** lembramos melhor dos primeiros e dos últimos itens de uma sequência.
- **Onde aparece:** itens principais nas pontas de uma barra de navegação ou lista.
- **Aplicação ética:** posicionar as ações mais importantes ao usuário nas extremidades.
- **Risco:** relativamente baixo, mas pode enterrar opções relevantes no meio.

> Todas as fichas foram conferidas contra as fontes carregadas no NotebookLM. *[Ajuste qualquer ponto em que as fontes divergirem desta síntese.]*

### Glossário

| Termo | Definição |
|-------|-----------|
| Viés cognitivo | Desvio sistemático do julgamento racional causado por atalhos mentais. |
| Heurística | Regra prática que simplifica uma decisão, rápida mas sujeita a erros. |
| Sistema 1 e Sistema 2 | Modelo de pensamento rápido e intuitivo (1) versus lento e analítico (2). |
| Arquitetura de escolhas | Forma como as opções são organizadas e apresentadas ao decisor. |
| Nudge | Pequeno empurrão no ambiente de decisão que orienta sem proibir opções. |
| Dark pattern (design enganoso) | Prática de interface que induz o usuário a agir contra seu próprio interesse. |
| Confirmshaming | Texto que faz o usuário se sentir culpado por recusar uma oferta. |
| Default (padrão) | Opção pré-selecionada que vale se o usuário não fizer nada. |
| Opt-in / Opt-out | Participar só se o usuário escolher / participar a menos que ele saia. |
| Âncora | Informação inicial que influencia julgamentos seguintes. |
| Framing (enquadramento) | Forma de apresentar uma informação que altera sua percepção. |
| Aversão à perda | Tendência de sentir perdas mais intensamente que ganhos equivalentes. |
| Prova social | Influência do comportamento de outras pessoas sobre a decisão. |
| Escassez | Percepção de que algo é raro ou limitado, aumentando seu valor. |
| Carga cognitiva | Esforço mental exigido para usar uma interface ou tomar uma decisão. |
| Fricção | Obstáculo que torna uma ação mais difícil ou demorada. |
| Lei de Hick | O tempo de decisão aumenta com o número e a complexidade das opções. |
| Paradoxo da escolha | Ideia de que muitas opções podem gerar paralisia ou insatisfação. |

### Prompts reutilizáveis para revisão

1. **Análise de tela:** "Analise esta interface [descrição ou print] e liste os vieses cognitivos ativados, com justificativa e se o uso parece ético ou manipulativo. Use apenas as fontes carregadas."
2. **Explicação por nível:** "Explique [viés] para um iniciante em 3 linhas e depois para um designer sênior em 1 parágrafo, citando as fontes."
3. **Quiz de revisão:** "Crie 10 perguntas de múltipla escolha sobre os vieses estudados, com gabarito e justificativa baseada nas fontes."
4. **Do viés à decisão de design:** "Para o problema [descrever], quais vieses são relevantes e que alternativas de design éticas as fontes sugerem?"
5. **Auditoria ética:** "Revise este fluxo [descrição] e aponte onde pode haver dark patterns, indicando o viés explorado e como corrigir."

---

## 🔍 Aplicação prática: análise de uma interface real

**Interface analisada:** *[PREENCHER: nome do app ou site]*

| Tela / elemento | Viés ativado | Uso ético ou manipulativo? | Como eu melhoraria |
|-----------------|--------------|----------------------------|--------------------|
| *[PREENCHER]* | *[PREENCHER]* | *[PREENCHER]* | *[PREENCHER]* |

*(Adicione prints na pasta `/imagens`.)*

---

## 💡 Aprendizados finais

- **O que funcionou:** *[PREENCHER]*
- **O que faria diferente:** *[PREENCHER]*
- **Limitações da IA que percebi:** *[PREENCHER]*
- **Como isso muda meu trabalho como designer:** *[PREENCHER]*

---

## 📁 Estrutura do repositório

```
├── README.md
└── imagens/     # prints do NotebookLM e da interface analisada
```
