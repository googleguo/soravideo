# SoraVideo
SoraVideo is an open-source project that simplifies video creation by allowing users to generate videos online with OpenAI's Sora model using text, featuring easy one-click website deployment.
👉 [SoraVideo](https://www.soravideo.ltd)

English | [简体中文](https://github.com/googleguo/soravideo/blob/main/README.zh-CN.md)




## Quick Started

### Deploy on Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fgoogleguo%2Fsoravideo&project-name=soravideo&repository-name=soravideo&external-id=https%3A%2F%2Fgithub.com%2Fgoogleguo%2Fsoravideo%2Ftree%2Fmain)

### 1. Clone project

```bash
git clone git@github.com:googleguo/soravideo.git
```

### 2. Install dependencies

```bash
cd soravideo && yarn
#or
cd soravideo && npm install
#or
cd soravideo && pnpm install
```

### 3. copy .env.example and rename it to .env.local

```bash
# website URL
NEXT_PUBLIC_SITE_URL=http://localhost

# openai config
OPENAI_API_KEY=sk-XXXXXX
OPENAI_API_BASE_URL=http://localhost:8081
OPENAI_API_MODEL=sora-1.0-turbo
```

### 4. Run it

```bash
yarn dev
#or
npm run dev
#or
pnpm dev
```

### 5. Open [http://localhost](http://localhost) with your browser to see it.
![success_deploy.jpg](/public/success_deploy.jpg)

# 学习交流群
![mp1.jpg](https://www.51cy.top/chat/customer/mp1.jpg)


