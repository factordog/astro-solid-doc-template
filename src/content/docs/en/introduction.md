---
title: "Introduction"
description: "Docs intro"
---

**Welcome to Astro!**

This is the `docs` starter template. It contains all of the features that you need to build a Markdown-powered
documentation site, including:

- ✅ **Full Markdown support**
- ✅ **Responsive mobile-friendly design**
- ✅ **Sidebar navigation**
- ✅ **Search (powered by Algolia)**
- ✅ **Multi-language i18n**
- ✅ **Automatic table of contents**
- ✅ **Automatic list of contributors**
- ✅ (and, best of all) **dark mode**

## Getting Started

To get started with this theme, check out the `README.md` in your new project directory. It provides documentation on
how to use and customize this template for your own project. Keep the README around so that you can always refer back to
it as you build.

Found a missing feature that you can't live without? Please suggest it [on our Discord](https://astro.build/chat) and
even consider adding it yourself on GitHub! Astro is an open source project and contributions from developers like you
are how we grow!

Good luck out there, Astronaut. 🧑‍🚀

```ts title="examples/index.ts"
interface IdLabel {id: number, /* some fields */ }
interface NameLabel {name: string, /* other fields */ }
type NameOrId<T extends number | string> = T extends number ? IdLabel : NameLabel;
// This comment should not be included

// ---cut---
function createLabel<T extends number | string>(idOrName: T): NameOrId<T> {
  throw "unimplemented"
}

let a = createLabel("typescript");
```
