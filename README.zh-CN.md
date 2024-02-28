# SoraVideo
SoraVideo 是一个开源项目，允许用户使用 OpenAI 的 Sora 模型使用文本在线生成视频，从而简化视频创建，并具有轻松的一键网站部署功能。
👉 [SoraVideo](https://www.soravideo.ltd)

[English](https://github.com/googleguo/soravideo/blob/main/README.md) | 简体中文 



## 快速开始

### 在 Vercel 上部署
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fgoogleguo%2Fsoravideo&project-name=soravideo&repository-name=soravideo&external-id=https%3A%2F%2Fgithub.com%2Fgoogleguo%2Fsoravideo%2Ftree%2Fmain)

### 1. 克隆项目

```bash
git clone git@github.com:googleguo/soravideo.git
```

### 2. 安装依赖

```bash
cd soravideo && yarn
#or
cd soravideo && npm install
#or
cd soravideo && pnpm install
```

### 3. 复制 .env.example 并将其重命名为 .env.local

```bash
# website URL
NEXT_PUBLIC_SITE_URL=http://localhost

# openai config
OPENAI_API_KEY=sk-XXXXXX
OPENAI_API_BASE_URL=http://localhost:8081
OPENAI_API_MODEL=sora-1.0-turbo
```

### 4. 运行

```bash
yarn dev
#or
npm run dev
#or
pnpm dev
```

### 4. 在浏览器打开 [http://localhost](http://localhost)
![success_deploy.jpg](/public/success_deploy.jpg)


# 学习交流群
![mp1.jpg](https://www.51cy.top/chat/customer/mp1.jpg)
