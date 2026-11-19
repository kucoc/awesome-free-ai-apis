# 🆓 Awesome Free AI APIs [2026]

> 完全免费的 AI API 大全 — 无需信用卡，注册即领，持续更新

[![Stars](https://img.shields.io/github/stars/kucoc/awesome-free-ai-apis?style=social)](https://github.com/kucoc/awesome-free-ai-apis/stargazers)

> **最后核验**: 2026-11-19 | **本列表不含已过期或需要付费方式的资源**

---

## 🏆 推荐指数排序

### ⭐⭐⭐⭐⭐ 强烈推荐（大额度 + 无限制）

| 平台 | 免费额度 | 模型 | 注册方式 | 备注 |
|---|---|---|---|---|
| **[Groq](https://console.groq.com)** | 30 RPM / 14,400 RPD | GPT-OSS-120B, Qwen 3.8 27B, Whisper | Google OAuth | 超快推理 (~0.13s) |
| **[Cloudflare Workers AI](https://dash.cloudflare.com)** | 10,000 Neurons/天 (~8000 调用) | Llama 3.1 8B/70B, Qwen, Mistral | Cloudflare 账号 | 永久免费层 |
| **[Google Gemini](https://aistudio.google.com)** | 免费层 (RPM/RPD 限制) | Gemini 2.5 Flash/Pro | Google 账号 | 部分地区限制 |
| **[OpenRouter](https://openrouter.ai)** | 20 RPM / 50 RPD (付费$10→1000 RPD) | 多家 :free 模型 | Google/GitHub OAuth | 聚合平台 |

### ⭐⭐⭐⭐ 推荐（新用户赠送）

| 平台 | 免费额度 | 模型 | 有效期 | 备注 |
|---|---|---|---|---|
| **[阿里云百炼 Qwen](https://bailian.console.aliyun.com)** | 100万 Token/模型 | Qwen 系列 | 90 天 | 需实名，北京地域 |
| **[Cerebras](https://cloud.cerebras.ai)** | $5 试用金 | Llama 3.1 等超快推理 | 30 天 | 需支付方式 |
| **[Cohere](https://dashboard.cohere.com)** | 1000 次/月 | Command R+ | 永久 | Evaluation Key |

### ⭐⭐⭐ 可用（部分免费）

| 平台 | 免费额度 | 模型 | 备注 |
|---|---|---|---|
| **[硅基流动 SiliconFlow](https://siliconflow.cn)** | 部分模型免费 + 新人体验金 | Qwen, DeepSeek 等 | 国内平台，需实名 |
| **[Mistral](https://console.mistral.ai)** | 免费层 | Mistral Large/Small | 需验证手机 |
| **[Hugging Face](https://huggingface.co)** | Free 积分 | 全开源模型 | Inference Providers |

### ⭐⭐ 有限免费

| 平台 | 额度 | 备注 |
|---|---|---|
| **[GitHub Models](https://github.com/marketplace/models)** | 有限 RPD | 需 GitHub 账号，GPT-4o/Claude |
| **[Together AI](https://api.together.xyz)** | $1 试用金 | 需手机验证 |
| **[Fireworks AI](https://fireworks.ai)** | $1 试用金 | 需手机验证 |

---

## 🛠 一键部署免费 AI 网关

使用 [Free AI Gateway](https://github.com/kucoc/free-ai-gateway) 把以上平台变成自己的 API 服务：

```bash
# Cloudflare Workers 部署（1 分钟）
git clone https://github.com/kucoc/free-ai-gateway
cd free-ai-gateway
npx wrangler deploy
```

## 📊 额度对比

```
Cloudflare Workers AI ████████████████████ 8000 调用/天
Groq                  ████████████████████████████ 14400 调用/天
Gemini                ████████ ~1500 请求/天
OpenRouter            ███ 50-1000 请求/天
```

## ⚠️ 常见坑

1. **"注册送 500 万 Token"** — DeepSeek 老活动，已失效
2. **"免费网页聊天 ≠ 免费 API"** — 两个独立产品
3. **地区限制** — Gemini/OpenAI 对部分地区有 IP 限制
4. **手机验证** — 部分平台需要（Groq/Cohere 可跳过）
5. **429 限流** — 使用退避重试，不要并发轰炸

## 🔗 相关资源

- [FreeToken](https://github.com/AIPMAndy/FreeToken) — 中文免费额度导航
- [Free-LLM](https://github.com/nejib1/Free-LLM) — 34+ 免费 LLM API
- [free-ai-apis](https://github.com/OuterSpacee/free-ai-apis) — 100+ APIs 集合
- [free-ai-gateway](https://github.com/kucoc/free-ai-gateway) — 一键部署 AI 网关

## 🤝 贡献

发现新平台或额度变化？提交 PR！

## 📄 License

MIT
