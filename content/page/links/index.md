---
title: Links
links:
  - title: GitHub
    description: GiThub es la plataforma de desarrollo de software más grande del mundo.
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
menu:
    main: 
        weight: 4
        params:
            icon: link

comments: false
---

Para usar esta función, agregue `links` a la sección frontal.
La primera pagina de este sitio:
```yaml
links:
  - title: GitHub
    description: GitHub es la plataforma de desarrollo de software más grande del mundo.
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: TypeScript
    description: TypeScript es un superconjunto escrito de JavaScript que compila a JavaScript simple.
    website: https://www.typescriptlang.org
    image: ts-logo-128.jpg
```

`image` Field acepta imágenes locales y externas.