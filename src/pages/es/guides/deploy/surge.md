---
title: Despliega tu proyecto de Astro en Surge
description: Cómo desplegar tu proyecto de Astro usando surge.sh
layout: ~/layouts/DeployGuideLayout.astro
i18nReady: true
---

Puedes desplegar tu proyecto de Astro en [Surge](https://surge.sh/), una plataforma diseñada para desarrolladores front-end para publicar sitios web usando solo un comando.

## Cómo desplegar

1. Instala [la CLI de Surge](https://www.npmjs.com/package/surge) de forma global desde la Terminal, si aún no lo has hecho.

    ```shell
    npm i -g surge
    ```

2. Construye tu sitio de Astro desde el directorio raíz de tu proyecto.

    ```shell
    npm run build
    ```

3. Despliega en Surge usando la CLI.

    ```shell
    surge dist
    ```

    Puedes usar un [dominio personalizado](http://surge.sh/help/adding-a-custom-domain) al hacer despliegues ejecutando `surge dist tudominio.com`.
