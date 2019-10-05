# serverless-nextjs-antd

A Serverless Nextjs Ant Design with Less and Typescript project starter.

The app gets deployed with the <a href="https://github.com/danielcondemarin/serverless-next.js" target="_blank">serverless-next.js component</a> with Next.js ^9.0 config to support Ant Design custom less variables, Typescript and serverless as the target for SSR.

## Getting started

You will require an AWS account and setting your aws credentials either using the <a href="https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html" target="_blank">AWS CLI</a> or in a `.env`:

```bash
AWS_ACCESS_KEY_ID=xxx
AWS_SECRET_ACCESS_KEY=xxx
```

Clone this repository and install:

```bash
npm i
```

That's it, now simply run locally:

```bash
npm run dev
```

And when ready deploy to AWS:

```bash
npm run deploy
```
