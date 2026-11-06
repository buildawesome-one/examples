---
permalink: /
tags: [11ty, buildawesome, micro, starter]
---

# [One¹](//buildawesome.one/) Examples

<!-- to copy-paste w/o formatting use any plain text input field, i.e. browser address bar -->

Example starters showcasing [Build Awesome One¹](//buildawesome.one/) kit with:

<figure><!-- <img src> breaks shields w/ emojis on GitHub, but ![]() works (urlencoding?) -->

| [1] [Blades CSS (default)](//examples.buildawesome.one/) | ![](https://img.shields.io/netlify/41df6bc0-3b91-48f7-903a-3511ca3652a8?logo=&label=🥷)                                           |
| -------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| [2] [Bootstrap](//bootstrap.buildawesome.one/)           | ![](https://img.shields.io/netlify/e58db8aa-94b7-4637-80cc-50e03cff45b0?logo=bootstrap&logoColor=lavender&label=&labelColor=gray) |
| [3] [Web Awesome](//webawesome.buildawesome.one/)        | ![](https://img.shields.io/netlify/40dc0253-7a90-4970-ba8d-80a1ec52093c?logo=webawesome&label=&labelColor=gray)                   |
| [4] Sveltia CMS                                          |                                                                                                                                   |
| [5] [Tailwind](//tailwind.buildawesome.one/)             | ![](https://img.shields.io/netlify/a980220a-630d-4022-9496-fb83b5db7c6b?logo=tailwindcss&label=&labelColor=gray)                  |

<!--{.striped .borderless}-->

</figure>

---

## Local development

### Blades CSS (default)

As simple as:

```sh
npm install    # dependencies
npm start      # development
npm run stage  # serve production version locally
               # ready to deploy! 🚀
```

### Bootstrap

```sh
IN=bootstrap npm start
```

### Web Awesome

```
IN=webawesome npm start
```

Then you should see this <wa-button variant="brand">[Web Awesome button]</wa-button>

### Sveltia CMS

```
IN=sveltiacms npm start
```

Then open http://localhost:8080/admin/.

### Tailwind

Tailwind example has its own `package.json`:

```sh
npm -C tailwind start
```
