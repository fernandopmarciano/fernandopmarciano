# Fernando Marciano

**Data Scientist & AI Engineer** | Rio de Janeiro, Brasil
*M.Sc. em Engenharia Elétrica (IA & Machine Learning) [COPPE - UFRJ] · Bacharelado em Física [UERJ]*

> 📂 **Portfólio com estudo de caso e resultados:** [github.com/fernandopmarciano/Portfolio](https://github.com/fernandopmarciano/Portfolio)

---

## O que eu faço

**Machine Learning & Deep Learning** — Classificação, NLP, Computer Vision e séries temporais.

**Sistemas de IA local** — Assistentes e agentes com LLMs rodando no próprio hardware, RAG híbrido e síntese de voz: privacidade e custo zero de API.

**Produtos de IA full-stack** — Plataformas completas com chatbots inteligentes, Text-to-Speech, autenticação e conformidade LGPD.

---

## Projetos em destaque

### 🤖 AVTP — Assistente Virtual Totalmente Privado
> Assistente de IA conversacional rodando 100% no hardware local — LLM, RAG, voz e 30+ tools criadas, sem cloud e sem custo de API.

- LLM local servido com llama.cpp/Vulkan numa RX 6600 (8 GB) [ :( ], RAG híbrido, interface voice-first e defesa contra prompt injection.

**Destaques de engenharia:**
- TTFT **~32–140 ms** e **~37 tok/s** em GPU de consumo (RX 6600);
- **Speculative decoding** com ganho de **+40,9%** na produção de tok/s;
- **~975 testes** (E2E, smoke test e de segurança);
- Custo operacional **R$ 0/mês** (tudo local).

### 💬 Hermes — Assistente Pessoal no Telegram
> Agente pessoal operando 24/7 com controle financeiro, agenda e automações.

- 12 skills, 8 cron jobs e 124 testes E2E.

### 🚀 FM IA Solutions — Plataforma Comercial de IA
> Site comercial completo com chatbot inteligente (LLM), Text-to-Speech e painel administrativo.

- Chatbot com streaming em tempo real, rate limiting progressivo e armazenamento de conversas;
- Text-to-Speech com Google Cloud WaveNet (voz natural pt-BR);
- Arquitetura server-side para proteção de API keys;
- LGPD compliant.

---

## Machine Learning & Data Science

| Projeto | Área | Stack | Resultado |
|---------|------|-------|-----------|
| **Market Forecast** | Séries temporais / Finanças | Stacking Ensemble, Time-Series CV | 60,2% acc (±1,4%), Sharpe 2,31, +1368% retorno (IBOVESPA 2017–2024) |
| **Fraud Detection** | Classificação desbalanceada | Random Forest, XGBoost, LightGBM | RF PR-AUC 0,9987 (PaySim Kaggle database, 6,3M transações, 0,13% de fraude) |
| **Logo Forgery Detection** | Computer Vision | Siamese Networks, EfficientNetV2-S, FAISS | AUC-ROC 0,97, Recall@1 0,95 (FlickrLogos-27 Kaggle database) |
| **NLP Sentiment** | NLP / Finanças | TF-IDF → Word2Vec → BERT → FinBERT | 4 níveis comparados no Financial PhraseBank Kaggle database (4.846 sentenças, 3 classes) |
| **Rocket Landing RL** | Reinforcement Learning | simulação 6DOF criada do zero, Neuroevolução (GA), Gymnasium | Pouso autônomo, currículo de 8 fases, 353 testes |

> Resultados de backtest/simulação são educacionais e não constituem recomendação de investimento.

---

## Stack

**ML / DL:** Python, PyTorch, scikit-learn, XGBoost, Hugging Face, FAISS

**IA local:** llama.cpp, Vulkan, speculative decoding, RAG híbrido, quantização GGUF

**IA Generativa:** Groq (Llama 3.3 70B), Google Gemini, Google Cloud TTS, streaming SSE

**Web & Full-Stack:** Next.js, React, TypeScript, Node.js, Tailwind CSS, Supabase

**Infra:** Docker, Railway, Vercel, Google Cloud, GitHub

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-fernandopmarciano-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fernandopmarciano/)
[![Email](https://img.shields.io/badge/Email-fe.pmarciano%40gmail.com.br-EA4335?logo=gmail&logoColor=white)](mailto:fe.pmarciano@gmail.com)
