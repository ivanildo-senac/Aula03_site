# Laboratório — Meu card favorito (UC15 · Aula 3)

Pasta pronta no formato do roteiro:

```
card-favorito/
├── index.html
├── css/estilo.css
└── img/capa.jpg   ← você coloca a imagem aqui
```

## O que falta (obrigatório)

1. Baixe a capa/pôster/escudo do seu tema.
2. Otimize em https://squoosh.app (largura ~1200px, WebP ou JPG qualidade 75, meta < 100 kB).
3. Salve em `img/capa.jpg` (ou `capa.webp` / `capa.png`).
4. Se o arquivo não for `.jpg`, ajuste o `src` e, se souber, o `width`/`height` reais.

## Tornando seu (passo 5 do roteiro)

No `index.html`, troque só o texto entre as tags:

- título (`<h1>` e `<title>`)
- linha do header
- `alt` e `figcaption` (o alt descreve a imagem; a legenda traz o que a imagem não diz)
- parágrafo “Por que eu gosto”
- quatro linhas da tabela + `caption`
- nome no `<footer>`

No `css/estilo.css`, troque as cores hex se quiser (fundo da página, fundo do card, `h1`, `h2`, linhas da tabela).

## Ligação HTML ↔ CSS

Já está no `<head>`:

```html
<link rel="stylesheet" href="css/estilo.css">
```

Caminho relativo, **sem** barra na frente.

## Abrir

Abra a pasta no VS Code e use Live Server (Go Live), como o roteiro pede.

## Observação de acessibilidade

A tabela usa `<th scope="row">` de propósito: o leitor de tela anuncia o nome do dado junto com o valor.
