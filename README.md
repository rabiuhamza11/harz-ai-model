# HARZ AI — Our Own Model (v3)

Fine-tuned SmolLM2-135M on HARZ Digital Services data.

## Training Data v3: 270 Examples
- Identity (10) — who HARZ AI is
- Products (15) — all 12 books, ebooks, games, bundles
- Payments (10) — UBA, Paystack, GDEG, USDT, Gumroad, Paddle
- Stores (5) — all store links
- Support (10) — orders, refunds, downloads
- Marketing (15) — ad copy, email, Facebook, WhatsApp, Telegram templates
- Platforms (10) — all 63+ ecosystem platforms
- AI Agents (5) — 7 agent descriptions
- Nigerian Business (20) — Instagram, Facebook, Twitter, WhatsApp, domains, taxes
- Business Advice (15) — entrepreneurship, pricing, funnels, trust
- Health (15) — malaria, immunity, fever, diabetes, hypertension, burns, sleep
- Security (5) — passwords, 2FA, phishing, WhatsApp security
- Education (10) — coding, jobs, CV, interviews, study skills
- General Knowledge (15) — crypto, blockchain, AI, economy
- Finance (10) — budgeting, cash flow, ROI, taxes, loans
- Code/Tech (15) — Python, JavaScript, Git, APIs, hosting, security
- Real Estate (5) — land, building costs, investment
- Hausa Conversations (15) — full Hausa dialogues
- Conversational (12) — greetings, thank you, goodbye, small talk

## How to Train
1. Open harz-finetune-colab.ipynb in Google Colab (free GPU)
2. Runtime → Change runtime type → T4 GPU
3. Run each cell in order
4. Enter HuggingFace token when asked
5. Wait ~15 minutes
6. Model saves as harz-ai on your HuggingFace account

## Owner
Rabiu Hamza Mohammed — HARZ Digital Services
CAC RC: 321424 | TIN: 24550860
