# Segundo Cérebro — IA Generativa

## Tema e objetivo

**Tema:** Inteligência Artificial Generativa.

**Objetivo:** Utilizar um notebook como um "segundo cérebro" para estudar Inteligência Artificial Generativa, organizando informações de diferentes fontes confiáveis em um único local.

O estudo aborda conceitos, funcionamento, aplicações, benefícios, limitações, riscos e uso responsável da IA generativa.

## Notebook

O notebook foi utilizado para consultar as fontes selecionadas, fazer perguntas sobre o tema e gerar materiais de estudo.

[🔗 Acessar o Gemini Notebook](https://notebook.google.com/notebook/d64a45f5-dcc4-4caf-b05c-ede7cc5f348e)

## Fontes utilizadas e por que confio nelas

Foram selecionadas fontes de diferentes formatos e instituições para reunir informações sobre diferentes aspectos da IA generativa.

- **IBM — "O que é a IA generativa?":** empresa de tecnologia com atuação e pesquisa próprias em IA, com material didático e atualizado. Utilizada para conceitos, funcionamento, aplicações e benefícios.
- **NIST — NIST.AI.600-1 (Generative AI Profile):** órgão oficial de padrões e tecnologia dos EUA, com publicação técnica sobre IA generativa. Utilizada para a definição técnica, riscos, limitações e confiabilidade.
- **NIST — Artificial Intelligence Risk Management Framework: Generative AI Profile:** do mesmo órgão, voltada à governança e ao gerenciamento de riscos. Utilizada para o contexto de governança.
- **Google Cloud — "Generative AI":** documentação oficial de uma das empresas que desenvolvem essa tecnologia. Utilizada para conceitos fundamentais e aplicações práticas.

As informações e links completos das fontes estão disponíveis em:
[📚 Ver fontes utilizadas](fontes/fontes.md)

## Diretriz de comportamento do notebook

O notebook foi configurado para utilizar somente as fontes adicionadas como base para as respostas.

A orientação utilizada foi:

> Atue como um especialista em Inteligência Artificial Generativa e como meu auxiliar de estudos.
> Utilize somente as fontes adicionadas ao notebook como base para responder às perguntas.
> Indique claramente de qual fonte cada informação foi retirada.
> Não invente informações que não estejam apoiadas pelas fontes.
> Quando mais de uma fonte tratar do mesmo assunto, compare as informações apresentadas e deixe claras possíveis diferenças.
> Explique os conceitos de maneira simples e objetiva.
> Priorize as informações presentes nas fontes adicionadas.

## Perguntas e evidências

Cada resposta do notebook foi longa, por isso os prints completos de cada uma estão organizados em uma pasta própria.

### 1. O que é Inteligência Artificial Generativa?

**Pergunta:** conceito de IA Generativa e seu funcionamento, com uma explicação simples e outra mais técnica.

**O que o notebook respondeu:**
- **Conceito:** é um ramo da IA capaz de criar conteúdos inéditos (texto, imagem, vídeo, áudio, código) a partir de um comando em linguagem natural, o *prompt*. Tecnicamente, é uma classe de modelos de *Deep Learning* que emula a estrutura estatística dos dados de entrada para gerar conteúdo sintético.
- **Funcionamento:** três fases: treinamento (aprende padrões a partir de grandes volumes de dados), ajuste (*fine-tuning* e RLHF) e geração (prevê a resposta mais provável). Por ser estatística, pode gerar falsas afirmações com confiança, chamadas de *alucinação* (IBM) ou *confabulação* (NIST). A técnica RAG ajuda a reduzir isso consultando bases externas.
- **Evolução das arquiteturas:** VAEs (2013), GANs (2014), modelos de difusão (2014) e Transformers (2017).
- **Aplicações em software:** geração e autocompletamento de código, modernização de sistemas legados e agentes de IA.

**Fontes citadas:** IBM, NIST (AI 600-1 e AI RMF Generative AI Profile) e Google Cloud. Foram usadas as 4 fontes do notebook.

![Pergunta 1](evidencias/pergunta-01.png)

📂 [Ver prints completos da resposta](evidencias/resposta-01/)

### 2. Quais são as principais aplicações da IA Generativa?

**Pergunta:** aplicações em diferentes áreas, como texto, imagem, áudio, vídeo e programação.
**O que o notebook respondeu:** apresentou aplicações da IA generativa em diferentes áreas, indicando a fonte de cada uma.
**Fontes citadas:** IBM e Google Cloud.

![Pergunta 2](evidencias/pergunta-02.png)

📂 [Ver prints completos da resposta](evidencias/resposta-02/)

### 3. Quais são os principais riscos e limitações?

**Pergunta:** principais riscos e limitações da IA Generativa, usando principalmente o material do NIST e comparando com as demais fontes.
**O que o notebook respondeu:** listou riscos e limitações, com base principalmente no NIST, e comparou com o que as outras fontes dizem.
**Fontes citadas:** NIST, com comparações com IBM e Google Cloud.

![Pergunta 3](evidencias/pergunta-03.png)

📂 [Ver prints completos da resposta](evidencias/resposta-03/)

### 4. Comparação entre as fontes

**Pergunta:** comparação entre IBM, NIST e Google Cloud, com pontos em comum e diferenças de abordagem.
**O que o notebook respondeu:** apontou o que as três fontes têm em comum e como cada uma aborda o tema de forma diferente.
**Fontes citadas:** IBM, NIST e Google Cloud.

![Pergunta 4](evidencias/pergunta-04.png)

📂 [Ver prints completos da resposta](evidencias/resposta-04/)

## Materiais gerados

Durante o estudo foram utilizados os recursos de geração de materiais disponíveis no notebook.

- [🧠 Mapa mental](materiais/mapa-mental.png): principais conceitos estudados, incluindo conceito, funcionamento, aplicações, benefícios, limitações, riscos e uso responsável.
- [📊 Slides (PDF)](materiais/slides.pdf): apresentação com os principais conteúdos estudados sobre IA Generativa.

![Mapa mental](materiais/mapa-mental.png)

## Estrutura do projeto

```
segundo-cerebro-ia-generativa/
│
├── README.md
│
├── fontes/
│   └── fontes.md
│
├── materiais/
│   ├── mapa-mental.png
│   └── slides.pdf
│
└── evidencias/
    ├── pergunta-01.png
    ├── pergunta-02.png
    ├── pergunta-03.png
    ├── pergunta-04.png
    ├── resposta-01/
    ├── resposta-02/
    ├── resposta-03/
    └── resposta-04/
```
