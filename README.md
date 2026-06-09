# Inteligência Artificial na Música — Análise Exploratória da plataforma Suno

Projeto Final da disciplina **Introdução a Ciência de Dados** (IESB) — Prof. Alexandre Roriz.

## O que é

Análise exploratória de dados (EDA) sobre **64.932 músicas reais geradas na plataforma Suno**,
investigando como uma IA "pensa" para entregar música já validada para o ouvido humano e como
ela mistura estilos a partir de um prompt. Inclui 10 perguntas com gráficos e comentários, além
de um bloco final comparando músicas-tema de Copa do Mundo e a "receita" de prompt usada para
compor uma música ao vivo.

## Vídeo de apresentação

[![Vídeo de apresentação do projeto](https://img.youtube.com/vi/hlsJ44ksWX4/maxresdefault.jpg)](https://youtu.be/hlsJ44ksWX4)

▶️ [Assista ao vídeo de apresentação no YouTube](https://youtu.be/hlsJ44ksWX4)

## Arquivos

- `Projeto_Final_Suno_IA_Musica.ipynb` — notebook com toda a análise.
- `suno_music.csv` — base de dados (amostra de metadados do dataset *Suno AI Music Prompts*, Kaggle).
- `requirements.txt` — bibliotecas necessárias.

## Como rodar

```bash
pip install -r requirements.txt
jupyter notebook Projeto_Final_Suno_IA_Musica.ipynb
```

Ou abra a pasta no VS Code e execute o notebook célula a célula.

## Fonte dos dados

Dataset *Suno AI Music Prompts* (`rafyaa/suno-ai-music-prompts`) no Kaggle. Período coberto pela
amostra: nov/2023 a ago/2024. A linha do tempo dos modelos recentes (até o v5.5 Pro) usa fontes
oficiais do Suno e está documentada na Pergunta 9.
