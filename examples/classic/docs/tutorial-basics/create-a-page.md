---
sidebar_position: 1
---

# 自販機パネルの設置

Botを入れたらまず、置きたいチャンネルにパネルを置きましょう。

- `src/pages/index.js` → `localhost:3000/`
- `src/pages/foo.md` → `localhost:3000/foo`
- `src/pages/foo/bar.js` → `localhost:3000/foo/bar`

## PayPayアカウントと連携

自動受け取り機能の受け取り先が必要なため、PayPayアカウントと連携する必要があります。

:::tip
受け取り処理等はブラウザ版PayPayで行なっていて、ブラウザ版は受け取りか辞退しかできないため安全です。
:::

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at [http://localhost:3000/my-markdown-page](http://localhost:3000/my-markdown-page).

:::tip
Your message here.
:::
