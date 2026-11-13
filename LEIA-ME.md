# Pacote de marca SouzaX

Organizado na mesma ordem do quadro de referência.

| Pasta | Conteúdo |
|---|---|
| 00-logo-principal | Logo horizontal (símbolo + SouzaX + slogan): SVG, PNG transparente, PNG com fundo escuro e versão para fundo claro |
| 01-icone-principal | Símbolo SX transparente: 512, 256, 128, 64 e 32 px + SVG |
| 02-favicon-e-apps | App escuro 512 (PNG e ICO), branco 512, laranja 512, redondo preto 180, redondo branco 180, favicon.ico (16/32/48), favicons PNG e apple-touch-icon |
| 03-banner-redes-sociais | OG Image 1200x630, Twitter/X 800x418, Instagram 1080x1080, LinkedIn 400x400 |
| 04-marcas-versoes | Logo empilhada 400x400 (escura, branca, laranja) e símbolo transparente, em PNG e SVG |
| 05-versoes-de-cores | Colorida, branca, preta e laranja (PNG 512 e SVG) + colorida para fundo claro |
| 06-programas-e-sistema | Windows: ICO e PNG de 16 a 256 px · macOS: ICNS e PNG 1024 |
| 07-pwa | Ícones 72 a 512 px, versões maskable e manifest.json |
| 08-outros-formatos | SVG, PNG, ICO e ICNS do símbolo |

## Cores
- Laranja: #FFC21A → #FF9500 → #FF6200
- Prata do S: #FFFFFF → #B4B4B4
- Fundo: #0A0A0A

## Fontes
Nome "SouzaX": Audiowide. Slogan: Exo 2 Medium. Nos SVGs os textos estão convertidos em curvas.

## No site
Copie `02-favicon-e-apps/favicon.ico`, `apple-touch-icon.png` e a pasta `07-pwa` para o projeto:

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<link rel="manifest" href="/manifest.json">
<meta name="theme-color" content="#0A0A0A">
<meta property="og:image" content="https://SEU-DOMINIO/og-image-1200x630.png">
```
