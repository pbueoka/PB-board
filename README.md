# PB-board

PB 掲示板

## 開発方式

実践ドメイン駆動設計（DDD）
[参考：DDD 概要](https://note.com/shift_tech/n/n1e91c68b1473)
[参考：DDD 実践](https://qiita.com/APPLE4869/items/d210ddc2cb1bfeea9338)

## 技術要素

・Next.js（[& Vercel を利用](https://vercel.com/)）
・TypeScript
・TailwindCSS
・daisyUI
・Socket.io
・NextAuth
・Prisma

## 環境構築メモ

---

[参考](https://mo-gu-mo-gu.com/create-next-app-typescript/)

#### yarn をインストール

`npm install -g yarn`

#### next-js(TypeScript ver.)をインストール

`npx create-next-app@latest --typescript`

#### eslint をインストール

`yarn add -D eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser`

#### prettier をインストール

`yarn add -D prettier eslint-config-prettier eslint-plugin-prettier`

[参考](https://zenn.dev/grinch1252/articles/931b2ff058ef62)

#### Tailwind CSS をインストール

`yarn add tailwindcss@latest postcss@latest autoprefixer@latest`

`npx tailwindcss init -p`

#### daisyUI をインストール

`yarn add daisyui@latest`

#### NextAuth をインストール

`yarn add next-auth`
`yarn add nodemailer sqlite3 prisma @prisma/client @next-auth/prisma-adapter`

[参考](https://zenn.dev/fehde/articles/4be665551fd0d9)
[参考](https://zenn.dev/shimabukuromeg/scraps/51ea9b884fc607)

---

#### ES7+ React/Redux/React-Native snippets を VSCode にインストール

アプリ公式：[参考](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
スニペット：[参考](https://github.com/chillios-ts/vscode-react-javascript-snippets/blob/HEAD/docs/Snippets.md)
