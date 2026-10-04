# Vídeos do site

Coloque aqui os vídeos que aparecem na seção "Vídeos" da página inicial.

## Regras

- Formato **.mp4**. Nome sem espaços nem acentos, por exemplo: `patrulha-noturna.mp4`.
- Tamanho máximo: **25 MB** se for enviar pelo site do GitHub e **100 MB** se for enviar pelo Git.
  Prefira clipes curtos (até ~1 minuto). Vídeos longos ficam melhores no YouTube.

## Como enviar pelo site do GitHub

1. Abra esta pasta no GitHub e clique em **Add file → Upload files**.
2. Arraste o vídeo, escreva uma descrição curta e clique em **Commit changes**.

## Como fazer o vídeo aparecer no site

Depois de enviar, abra o `index.html` e procure a lista `VIDEOS`. Acrescente uma linha assim:

```js
["patrulha-noturna.mp4", "Patrulha noturna do Choque"],
```

Salve e envie a alteração. Em uns 30 segundos o site atualiza.
