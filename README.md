# DOSE — jogo de carga de treinamento

Jogo de cartas da disciplina de **Fisioterapia Esportiva** (PUC Minas Betim).
Vôlei, oito rodadas, dois jogos. Dois grupos jogam no mesmo aparelho, revezando.

No ar em **https://doseesportiva.netlify.app**

## O que tem aqui

Este repositório é só o **site publicado** — HTML estático e as 41 artes das cartas.
Sem build, sem dependência, sem servidor.

```
index.html     o jogo inteiro
arte/          41 imagens
```

A fonte de verdade é o `dose.html` do diretório da disciplina; esta pasta é gerada a
partir dele por `gerar site e qr.py`, que troca as URLs das imagens por arquivos locais
e acrescenta o cabeçalho de documento (doctype, charset e viewport).

## Publicação

A Netlify está ligada a este repositório: **todo push na branch principal publica.**

> A regra de ouro do jogo: **lesão é sempre consequência, nunca jogada.**
