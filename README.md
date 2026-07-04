# 🚀 AI-Powered Conversion Rate Optimizer (CRO) Agent

An automated **n8n workflow** designed to audit landing pages, analyze copywriting, detect conversion friction, and provide data-driven A/B testing ideas using advanced AI.

---

## 🛠️ How It Works

The workflow automatically processes a landing page through a 4-step pipeline:

1. **🌐 Landing Page URL:** Takes the target website link as an input.
2. **🕷️ Scrape Website:** Extracts all raw text, content, and layout structure from the page.
3. **🤖 CRO AI Agent:** Acts as a professional CRO expert, evaluating elements like headlines, CTAs, and layout flow to identify conversion leaks.
4. **🧠 OpenAI Model:** Powers the AI Agent's reasoning engine (Requires an OpenAI API Key).

---

## 📸 Workflow Preview

<img width="566" height="334" alt="image" src="https://github.com/user-attachments/assets/f2c69d81-9b0b-4ef7-baa0-482a8d8fd285" />


---

## 🎯 Key Features & Insights Generated

* **📝 Copywriting Audit:** Evaluates if the value proposition is clear and speaks to the target audience.
* **⚡ CTA Optimization:** Analyzes Call-to-Action buttons for placement, visibility, and copy effectiveness.
* **🔍 Friction Detection:** Points out confusing messaging, complex forms, or areas where users might drop off.
* **💡 A/B Testing Ideation:** Generates concrete, actionable hypotheses for your next split tests.

---

## 🚀 How to Use This Workflow

### Prerequisites
* An active **n8n** instance (Cloud or Self-Hosted).
* An **OpenAI API Key** (with access to GPT-4o or equivalent models).

### Installation Steps
1. **Download the Workflow:** Download the `.json` file from this repository.
2. **Import to n8n:** Open your n8n canvas, click on the top-right menu (`...`), and select **Import from File**.
3. **Configure OpenAI Credentials:** Click on the `OpenAI Chat Model` node and add your OpenAI API Key.
4. **Test it out:** Paste any landing page URL in the first node and click **Execute Workflow**!


