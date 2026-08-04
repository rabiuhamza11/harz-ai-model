# HARZ AI — Our Own Model (v2)

Fine-tuned SmolLM2-135M on HARZ Digital Services data.

## Training Data v2: 170 Examples
- Identity (10) — who HARZ AI is, who created it
- Products (15) — all 12 books, ebooks, games, bundles
- Payments (10) — UBA, Paystack, GDEG, USDT, Gumroad, Paddle
- Stores (5) — all store links, which to use
- Support (10) — orders, refunds, downloads, contact
- Marketing (10) — ad copy in English, Hausa, Pidgin
- Platforms (10) — all 63+ ecosystem platforms
- AI Agents (5) — 7 agent descriptions
- Business Advice (15) — entrepreneurship, pricing, marketing
- Health (10) — wellness, nutrition, exercise, sleep
- Security (5) — passwords, 2FA, phishing, WhatsApp security
- Education (10) — learning programming, Excel, study tips
- General Knowledge (15) — crypto, blockchain, AI, economy
- Finance (10) — budgeting, cash flow, ROI, taxes, loans
- Greetings (10) — English, Hausa, Pidgin
- Code/Tech (5) — Python, HTML, websites, databases
- Real Estate (5) — land, building costs, investment
- Hausa Conversations (10) — full Hausa dialogues

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
