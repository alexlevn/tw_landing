# README

Bài tập cho học viên:

- [pro landing](https://themes.haravan.com/pages/demo?id=landing-page.myharavan.com&pro=landing)

1. Init project

```bash
npm init -y
git init
```

copy ".gitignore" from another project

```bash
npm install tailwindcss@1.4
```

create base file:

- public/index.html
- src/styles.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

```bash
npm run build-css
live-server ./public --watch
```

use full config & rebuild

```bash
npx tailwindcss init --full
npm run build-css
```

<!-- https://alexlevn.github.io/tw_landing/ -->

Step 1: public the repo
Step 2: Settings -> Pages

- Source: select Branch, folder '/docs' (or public)
- Save
- Waiting in 5 minutes: & [test](https://alexlevn.github.io/tw_landing/)
