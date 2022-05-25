# NASA Pics - Today
Site de busca de fotos feitas pela NASA até hoje (site feito com uma API da NASA), você terá acesso a fotos atualizadas das misões da NASA e algumas informações dessas fotos.

## Conteudo

- [Visão geral](#visao-geral)
  - [Rascunho](#rascunho)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Feito com](#feito-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
  - [Recursos úteis](#recursos-uteis)
- [Autor](#autor)

## Visão geral

### Rascunho

![](/src/imagens/NasaPics.jpg)

### Links

- Codigo na web URL: [GitHub](https://github.com/Akherox/nasa_pics)
- Site ao vivo URL: [Vercel Pages](https://akherox.github.io/nasa_pics/)

## Meu processo

### Feito com

- Semântica de HTML5 linguagen de marcação, a ferramenta de Bootstrap e JavaScript.

### O que eu aprendi (até agora)

Fazer coneção com APIs usando uma API-KEY.

```js
class ApiConnection {
    get API_URL() {
      return "https://api.nasa.gov/planetary/apod"
    }
  
    get API_KEY() {
      return "DEMO_KEY"
    }
  
    get API_URL_WITH_KEY() {
      return this.API_URL + "?api_key=" + this.API_KEY
    }
}
```

### Desenvolvimento contínuo

Focarei em melhorar meu trabalho com APIs para os proximos projetos.

### Recursos úteis

- [Recurso da API](https://api.nasa.gov/)
- Usei esse site para desenvolver este projeto de busca de imagens.

## Autor

- Website - [Bryan Bravo](https://www.linkedin.com/in/alex-bravo-008-mk)