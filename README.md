# RTA GenAI Creative Work Ethics

Repositório de rastreabilidade metodológica do estudo qualitativo sobre percepções éticas de profissionais criativos em relação ao uso de inteligência artificial generativa no trabalho criativo.

## Objetivo do repositório

Este repositório documenta a trilha de auditoria da Análise Temática Reflexiva (Reflexive Thematic Analysis — RTA) aplicada a entrevistas de profissionais criativos sobre o uso de IA generativa.

O objetivo não é redistribuir o corpus bruto, mas tornar transparente o percurso analítico que levou dos dados qualitativos aos códigos, temas candidatos, temas revisados e subtemas finais usados no artigo.

## Tema do estudo

O estudo investiga como profissionais criativos com visões otimistas e pessimistas divergem na percepção das tensões éticas associadas ao uso da IA generativa no trabalho criativo.

As dimensões analíticas centrais são:

- IA como apoio ao trabalho criativo;
- autoria e autenticidade em risco;
- controle humano sobre a IA;
- confiança limitada nas respostas da IA;
- medo de substituição e desvalorização profissional.

## Pergunta de pesquisa

**Como profissionais criativos com visões otimistas e pessimistas divergem na percepção das tensões éticas associadas ao uso da IA generativa no trabalho criativo?**

## Corpus

O corpus original deriva da base pública **AnthropicInterviewer**, associada ao estudo:

> *Introducing Anthropic Interviewer: What 1,250 professionals told us about working with AI*.

A base completa contém entrevistas com diferentes grupos profissionais. Este estudo analisa apenas o recorte referente aos **profissionais criativos**.

Fonte original do dataset:  
https://huggingface.co/datasets/Anthropic/AnthropicInterviewer

Página da pesquisa:  
https://www.anthropic.com/research/anthropic-interviewer

## Observação ética

Este repositório **não redistribui as entrevistas completas** nem o corpus bruto. Essa decisão segue o princípio de minimização de risco, pois entrevistas qualitativas podem conter detalhes profissionais, biográficos ou contextuais que aumentam a possibilidade de reidentificação dos participantes.

Os arquivos publicados são derivados analíticos e devem ser usados apenas para fins de rastreabilidade metodológica.

Não devem ser publicados neste repositório:

- transcrições completas;
- excertos longos dos participantes;
- dados brutos do corpus;
- metadados profissionais ou biográficos específicos;
- combinações de informações que possam tornar participantes identificáveis.

## Método

O estudo utiliza **Análise Temática Reflexiva (RTA)**, conforme Braun e Clarke.

A RTA entende os temas como construções interpretativas produzidas ativamente pela pesquisadora, e não como categorias que simplesmente “emergem” dos dados.

A análise foi organizada em seis fases:

1. **Familiarização intensiva com o corpus**  
   Leitura panorâmica das entrevistas e produção de memos iniciais.

2. **Codificação inicial**  
   Codificação sistemática de blocos de significado, com preferência por códigos em gerúndio para capturar práticas em ação.

3. **Construção de temas candidatos**  
   Agrupamento interpretativo dos códigos em padrões mais amplos de sentido.

4. **Revisão dos temas**  
   Teste dos temas em relação aos excertos originais, aos códigos e ao corpus como um todo.

5. **Definição e nomeação dos temas**  
   Refinamento do tema central, do eixo comparativo e dos subtemas finais.

6. **Redação analítica**  
   Construção da narrativa temática, articulando interpretação, evidências e diálogo com a literatura.

## Tema central, eixo comparativo e subtemas

**Tema central:**  
Percepções éticas sobre o uso da IA generativa no trabalho criativo.

**Eixo comparativo:**  
Visões otimistas e pessimistas sobre a IA.

**Subtemas finais:**

1. IA como apoio ao trabalho criativo;
2. autoria e autenticidade em risco;
3. controle humano sobre a IA;
4. confiança limitada nas respostas da IA;
5. medo de substituição e desvalorização profissional.

## Estrutura do repositório

## Estrutura do repositório

```text
anthropic-interviewer-creatives-rta/
├── .gitignore
├── LICENSE.md
├── README.md
├── data/
│   ├── processed/
│   │   ├── livro_codigos_inicial.xlsx
│   │   ├── mapa_analitico_refinado.xlsx
│   │   ├── matriz_codigos_temas_creatives.xlsx
│   │   ├── matriz_fusao_rebaixamento_temas.xlsx
│   │   └── sintese_subtemas_finais.xlsx
│   └── raw/
│       └── README_source.md
└── paper/
    ├── main.tex
    └── references.bib
```

### Descrição dos diretórios

| Diretório/arquivo           | Descrição                                                                                                         |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| `.gitignore`                | Define arquivos e pastas que não devem ser enviados ao GitHub, especialmente dados brutos e arquivos temporários. |
| `LICENSE.md`                | Informa a licença de uso do repositório.                                                                          |
| `README.md`                 | Apresenta o objetivo do projeto, método, corpus e estrutura do repositório.                                       |
| `data/raw/README_source.md` | Documenta a origem do corpus bruto sem redistribuir as entrevistas completas.                                     |
| `data/processed/`           | Contém arquivos derivados da análise, usados para rastreabilidade metodológica.                                   |
| `paper/main.tex`            | Arquivo principal do artigo em LaTeX.                                                                             |
| `paper/references.bib`      | Arquivo BibTeX com as referências usadas no artigo.                                                               |

```
```




## Arquivos de rastreabilidade

| Arquivo | Função |
|---|---|
| `livro_codigos_inicial.csv` | Documenta códigos iniciais, definições operacionais e critérios de uso. |
| `matriz_codigos_temas_creatives.csv` | Mostra a relação entre códigos iniciais e temas candidatos. |
| `mapa_analitico_refinado.csv` | Apresenta tema central, eixo comparativo e subtemas após revisão. |
| `matriz_fusao_rebaixamento_temas.csv` | Registra decisões de fusão, rebaixamento e refinamento dos temas. |
| `sintese_subtemas_finais.csv` | Resume os subtemas finais e sua função interpretativa no artigo. |

## Rigor e reflexividade

Este estudo não utiliza métricas de concordância intercodificador, como índice Kappa, porque a RTA não se fundamenta em uma lógica positivista de replicação mecânica dos códigos.

O rigor é sustentado por:

- familiarização intensiva com o corpus;
- produção de memos;
- documentação das decisões analíticas;
- construção de uma trilha de auditoria;
- revisão dos temas em relação ao corpus;
- explicitação da postura interpretativa da pesquisadora;
- atenção ética à anonimização e à minimização de risco.

## Limitações

O estudo utiliza um corpus produzido por entrevistas conduzidas por um sistema automatizado de IA. Essa característica oferece escala e padronização, mas pode limitar dimensões intersubjetivas próprias de entrevistas qualitativas conduzidas por pesquisadores humanos.

Além disso, a publicação de derivados analíticos exige cautela, pois bases qualitativas ricas podem conter informações que facilitem reidentificação quando combinadas com outras fontes públicas.

## Referências principais

As referências centrais do artigo incluem:

- Braun & Clarke (2006, 2019, 2021), para Análise Temática Reflexiva;
- AnthropicInterviewer, para o corpus empírico;
- Kyi et al. (2025) e Caramiaux et al. (2025), para IA generativa no trabalho criativo;
- Samuelson (2023) e Lemley & Casey (2021), para direitos autorais e IA;
- Gillespie (2014) e Seaver (2017), para estudos críticos de algoritmos;
- Bender et al. (2021), para riscos e limites de modelos de linguagem;
- Suchman (1995) e Star & Strauss (1999), para trabalho visível/invisível;
- Li (2026), para risco de reidentificação no AnthropicInterviewer Dataset.

## Como citar este repositório

Use o arquivo `CITATION.cff`, quando disponível. Na ausência dele, cite como:

```text
Santos, Renata. RTA GenAI Creative Work Ethics: trilha de auditoria metodológica para análise temática reflexiva de percepções éticas sobre IA generativa no trabalho criativo. GitHub, 2026.
```

## Licença

Defina a licença conforme o objetivo do repositório.

Para textos e derivados analíticos, uma opção recomendada é:

```text
Creative Commons Attribution 4.0 International (CC BY 4.0)
```

Para scripts, uma opção simples é:

```text
MIT License
```

O corpus original não é redistribuído neste repositório e permanece sujeito aos termos da fonte original.
