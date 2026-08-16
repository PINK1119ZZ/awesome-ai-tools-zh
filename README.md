# Awesome AI 工具中文清單 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 為華語開發者與小企業整理的 2026 年 AI 工具清單。每個項目都實際試用過、有持續維護、有明確使用情境。

不收錄:已棄坑專案、營銷導向但無實質、需要付費才能評估的封閉產品。

## 目錄

- [LLM API & 平台](#llm-api--平台)
- [AI 寫程式](#ai-寫程式)
- [AI Agents 框架](#ai-agents-框架)
- [RAG / 向量資料庫](#rag--向量資料庫)
- [文件問答 / 知識庫](#文件問答--知識庫)
- [內容生成](#內容生成)
- [圖像 / 影片](#圖像--影片)
- [語音 / TTS](#語音--tts)
- [自動化 / 工作流](#自動化--工作流)
- [中文 NLP 專用](#中文-nlp-專用)
- [本地部署](#本地部署)
- [實用工具站](#實用工具站)

## LLM API & 平台

- [OpenAI](https://platform.openai.com/) — GPT-4o / GPT-4o-mini,通用首選,生態最完整
- [Anthropic Claude](https://www.anthropic.com/api) — Claude Opus / Sonnet / Haiku,長文 + 程式能力強
- [Google Gemini](https://ai.google.dev/) — 免費額度大方,中文 + 多模態
- [Groq](https://groq.com/) — 推理速度最快,免費 tier 適合 PoC
- [Together AI](https://www.together.ai/) — 多開源模型 API,Mixtral/Llama
- [Fireworks AI](https://fireworks.ai/) — 開源模型 serverless,延遲低
- [DeepSeek](https://www.deepseek.com/) — 中國團隊,中文表現好,價格低
- [OpenRouter](https://openrouter.ai/) — 一個 API key 切換 100+ 模型,方便比價

## AI 寫程式

- [Cursor](https://cursor.sh/) — VSCode fork,Composer 多檔改,目前個人開發首選
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) — Anthropic CLI agent,自跑指令
- [GitHub Copilot](https://github.com/features/copilot) — GitHub 原生整合,團隊版完整
- [Windsurf](https://codeium.com/windsurf) — Codeium 出品,有免費版,Cascade agent
- [Aider](https://aider.chat/) — 開源 CLI pair-programmer,git-aware
- [Continue](https://continue.dev/) — 開源 IDE 外掛,支援自架模型
- [Cline](https://github.com/cline/cline) — 開源 VSCode agent,可接任何 API

## AI Agents 框架

- [LangChain](https://www.langchain.com/) — 最大生態,Python/JS 雙版本
- [LlamaIndex](https://www.llamaindex.ai/) — 文件 RAG 首選
- [CrewAI](https://www.crewai.com/) — 多 agent 協作框架,簡潔
- [AutoGen](https://github.com/microsoft/autogen) — 微軟出品,多 agent 對話
- [Pydantic AI](https://ai.pydantic.dev/) — 型別安全的 agent 框架
- [Smolagents](https://github.com/huggingface/smolagents) — Hugging Face 出品,輕量
- [OpenAI Swarm](https://github.com/openai/swarm) — OpenAI 官方輕量編排
- [Mastra](https://mastra.ai/) — TypeScript agent 框架,Vercel 風格

## RAG / 向量資料庫

- [Chroma](https://www.trychroma.com/) — 開源,自架最簡單,適合 PoC
- [Qdrant](https://qdrant.tech/) — Rust 寫的,效能好,有 cloud
- [Weaviate](https://weaviate.io/) — 開源 + 內建混合搜尋
- [Pinecone](https://www.pinecone.io/) — 商用領頭羊,免費 tier 夠用
- [Milvus](https://milvus.io/) — 大型部署選擇
- [pgvector](https://github.com/pgvector/pgvector) — Postgres 擴充,既有 DB 直接加
- [LanceDB](https://lancedb.com/) — Embedded,本地檔案就能跑

## 文件問答 / 知識庫

- [NotebookLM](https://notebooklm.google.com/) — Google 出品,丟文件直接問,免費
- [Perplexity](https://www.perplexity.ai/) — 帶引用的 AI 搜尋
- [Khoj](https://khoj.dev/) — 開源個人知識庫 AI
- [Danswer](https://www.danswer.ai/) — 企業內部 ChatGPT 開源版
- [RAGFlow](https://github.com/infiniflow/ragflow) — 開源企業 RAG,UI 完整

## 內容生成

- [Jasper](https://www.jasper.ai/) — 行銷文案專門
- [Copy.ai](https://www.copy.ai/) — 行銷模板豐富
- [Notion AI](https://www.notion.so/product/ai) — Notion 內建,工作流順
- [Gamma](https://gamma.app/) — AI 簡報生成
- [Tome](https://tome.app/) — AI 簡報替代

## 圖像 / 影片

- [Midjourney](https://www.midjourney.com/) — 美感最強,Discord 介面
- [Stable Diffusion (ComfyUI)](https://github.com/comfyanonymous/ComfyUI) — 開源,本地可跑
- [Flux](https://blackforestlabs.ai/) — Stable Diffusion 原團隊新模型
- [Ideogram](https://ideogram.ai/) — 文字渲染最強
- [Runway](https://runwayml.com/) — AI 影片
- [Pika](https://pika.art/) — AI 影片生成
- [HeyGen](https://www.heygen.com/) — AI 主播 / 數位人
- [videos.social](https://videos.social/?utm_source=pink1119zz-awesome-ai-tools-zh&utm_medium=directory&utm_campaign=listing-wave-d) — 部落格 / PDF / prompt 轉可編輯無臉影片

## 語音 / TTS

- [ElevenLabs](https://elevenlabs.io/) — 商用 TTS 品質最高
- [OpenAI TTS](https://platform.openai.com/docs/guides/text-to-speech) — 便宜,品質夠用
- [Whisper](https://github.com/openai/whisper) — 開源語音辨識,中文支援好
- [Faster-Whisper](https://github.com/SYSTRAN/faster-whisper) — Whisper 加速版

## 自動化 / 工作流

- [n8n](https://n8n.io/) — 開源 Zapier 替代,可自架,AI 節點完整
- [Make](https://www.make.com/) — 圖形化自動化,LINE/Slack 整合多
- [Zapier](https://zapier.com/) — 業界標準,模板最多
- [Pipedream](https://pipedream.com/) — 開發者導向,程式碼自由度高
- [Activepieces](https://www.activepieces.com/) — 開源 + AI 友善

## 中文 NLP 專用

- [DeepSeek](https://chat.deepseek.com/) — 中文表現好,價格極低
- [通義千問 Qwen](https://qwen.ai/) — 阿里出品,開源版可本地跑
- [Yi (01.AI)](https://01.ai/) — 開源,中英雙語強
- [GLM](https://chatglm.cn/) — 智譜,開源 + 商用 API

## 本地部署

- [Ollama](https://ollama.com/) — 一行指令跑開源 LLM,Mac/Linux/Windows
- [LM Studio](https://lmstudio.ai/) — GUI 跑 LLM,小白友善
- [vLLM](https://github.com/vllm-project/vllm) — 生產級 LLM serving
- [Text Generation Inference](https://github.com/huggingface/text-generation-inference) — Hugging Face 出品

## 實用工具站

- [LangSmith](https://www.langchain.com/langsmith) — LLM 應用觀測 / debug
- [Helicone](https://www.helicone.ai/) — LLM API 監控代理
- [PromptLayer](https://promptlayer.com/) — Prompt 版本管理
- [Vellum](https://www.vellum.ai/) — Prompt + workflow 平台

---

## 貢獻

歡迎 PR。請確認:(1) 持續維護 (2) 中文用戶用得到 (3) 你實際試過。

## 授權

[CC0](LICENSE)

---

> **想看 2026 AI 趨勢評測?** [AI Tools TW](https://pink1119zz.github.io/ai-tools-tw/)
> **要客製化 LINE Bot / AI 整合?** [AutoDev AI](https://autodev-ai.com)
