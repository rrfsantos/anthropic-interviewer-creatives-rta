# Fonte dos dados brutos

Esta pasta documenta a origem do corpus utilizado no estudo. O corpus bruto **não é redistribuído** neste repositório.

## Dataset original

O estudo utiliza como fonte empírica a base pública **AnthropicInterviewer**, associada à pesquisa:

> *Introducing Anthropic Interviewer: What 1,250 professionals told us about working with AI*.

Fonte original do dataset:  
https://huggingface.co/datasets/Anthropic/AnthropicInterviewer

Página da pesquisa:  
https://www.anthropic.com/research/anthropic-interviewer

## Recorte analítico utilizado

A base AnthropicInterviewer contém entrevistas com diferentes grupos profissionais. Para este estudo, foi utilizado apenas o recorte referente a **profissionais criativos**.

Recorte analítico:

```text
creative_transcripts / professionals creatives
N = 125 entrevistas
```

O artigo analisa percepções éticas de profissionais criativos sobre o uso da IA generativa no trabalho criativo, com foco nas divergências entre visões otimistas e pessimistas.

## Por que o corpus bruto não está neste repositório?

As entrevistas completas não são incluídas no GitHub por razões éticas e metodológicas.

Embora o dataset original seja público, entrevistas qualitativas podem conter detalhes profissionais, biográficos ou contextuais que aumentam o risco de reidentificação dos participantes, especialmente quando combinadas com outras fontes públicas.

Por esse motivo, este repositório segue o princípio de minimização de risco e disponibiliza apenas derivados analíticos, como:

- livro de códigos;
- matriz códigos-temas;
- mapa analítico refinado;
- matriz de fusão e rebaixamento de temas;
- síntese dos subtemas finais.

## Como obter o corpus original

Pesquisadores interessados em acessar o corpus completo devem consultar diretamente a fonte original:

```text
https://huggingface.co/datasets/Anthropic/AnthropicInterviewer
```

Antes de reutilizar os dados, recomenda-se verificar os termos de uso do dataset, a licença vigente e as orientações éticas associadas.

## Cuidados éticos na reutilização

Ao trabalhar com entrevistas qualitativas derivadas do AnthropicInterviewer, recomenda-se:

1. evitar republicar transcrições completas;
2. reduzir o uso de excertos longos;
3. não combinar informações ocupacionais, biográficas e contextuais específicas;
4. remover ou generalizar detalhes que possam facilitar reidentificação;
5. documentar as decisões de anonimização;
6. tratar os dados como sensíveis, mesmo quando publicamente disponíveis.

## Relação com os arquivos processados

Os arquivos derivados deste estudo estão na pasta:

```text
data/processed/
```

Esses arquivos documentam a trilha analítica da Análise Temática Reflexiva, sem redistribuir o corpus bruto.
