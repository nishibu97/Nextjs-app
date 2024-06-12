# Next.js 新規プロジェクト作成手順
Next.jsの新規プロジェクトを作成する手順を以下に示します。

1. Node.jsのインストール: まず、コンピュータにNode.jsをインストールしてください。Node.jsの公式ウェブサイト（https://nodejs.org/）から、最新バージョンのNode.jsをダウンロードしてインストールします。

2. Next.jsのインストール: コマンドライン（ターミナル）を開き、次のコマンドを入力してNext.jsをグローバルにインストールします。
$npm install -g create-next-app

3. 新しいNext.jsプロジェクトの作成: コマンドラインで、プロジェクトを作成したいディレクトリに移動し、次のコマンドを入力します。
$npx create-next-app my-next-app
このコマンドは、my-next-app という名前の新しいディレクトリを作成し、その中にNext.jsプロジェクトを作成します。my-next-app の部分は、任意のプロジェクト名に置き換えてください。


4. プロジェクトディレクトリに移動: 作成されたプロジェクトディレクトリに移動します。

$cd my-next-app

# 開発サーバーの起動: プロジェクトディレクトリで、次のコマンドを入力して開発サーバーを起動します。

$npm run dev
これで、Next.jsアプリケーションがローカルサーバーで実行され、ブラウザで http://localhost:3000 にアクセスするとアプリケーションを確認できます。


これで、Next.jsの新規プロジェクトが作成されました。必要に応じてプロジェクトをカスタマイズして、開発を始めることができます。




This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
