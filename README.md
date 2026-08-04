# HARZ AI — Our Own Model (v4)

Fine-tuned SmolLM2-135M on HARZ Digital Services data.

## Training Data v4: 443 Examples
- Identity (10), Products (15), Payments (10), Stores (5), Support (10)
- Marketing (25) — ads, email, WhatsApp, Telegram, Facebook, blog, SMS, press release
- Platforms (10), AI Agents (5), Nigerian Business (20)
- Business Advice (15), Health (20) — malaria, typhoid, pregnancy, diabetes, stroke
- Security (5), Education (10), General Knowledge (20)
- Finance (20) — budgeting, investing, T-bills, ROI, cash flow, debt
- Code/Tech (20) — Python, Node.js, Docker, REST, JWT, WebSocket, CDN
- Real Estate (5), Hausa Deep Dive (25) — full Hausa business conversations
- Personal Development (20) — confidence, habits, time management, resilience
- Product-Specific (15) — detailed table of contents for each book
- Conversational (15) — jokes, small talk, languages, humor

## How to Train
1. Open harz-finetune-colab.ipynb in Google Colab (free GPU)
2. Runtime → T4 GPU
3. Run each cell in order
4. Enter HuggingFace token
5. Wait ~15 minutes
6. Model saves as harz-ai

## Owner
Rabiu Hamza Mohammed — HARZ Digital Services
CAC RC: 321424 | TIN: 24550860
