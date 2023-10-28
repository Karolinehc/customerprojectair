---
title: "Pretty-print dates"
date: 2021-04-01T00:00:00+01:00
author: Equipo de Contenido de Marketing
image: "images/blog/blog-post-1.jpg"
bg_image: "images/feature-bg.jpg"
categories: ["Visualizacion de la data"]
tags: ["Python", "Tecnologia"]
draft: false
type: "post"
---

Para escribir una marca de tiempo [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) en el idioma actual, puede usar el código abreviado `date_l10n`:

Escribiendo

```
{{%/* date_l10n "2020-10-20" */%}}
```

El resultado

```
{{% date_l10n "2020-10-20" %}}
```

Opcionalmente, puede especificar un [diseño de formato] diferente (https://gohugo.io/functions/dateformat/#datetime-formatting-layouts):

Por ejemplo, el siguiente

```
{{%/* date_l10n "2020-10-20" ":date_short" */%}}
```

est

```
{{% date_l10n "2020-10-20" ":date_short" %}}
```
