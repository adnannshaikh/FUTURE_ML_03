
# Telegram Bot Integration with Dialogflow ES

This guide helps you integrate your Dialogflow FAQ chatbot with Telegram in a few simple steps.

---

##  Prerequisites
- A working Dialogflow ES agent
- A Telegram account
- Internet access

---

##  Step-by-Step Setup

### 1. Create a Bot on Telegram
1. Open Telegram and search for **BotFather**
2. Start a chat and run the command:  
   ```
   /newbot
   ```
3. Provide a **name** and a **unique username** (e.g., `FutureInternMLBot`)
4. Copy the **Bot Token** – you’ll need this in Dialogflow.

---

### 2. Enable Telegram Integration in Dialogflow
1. Go to your Dialogflow console → select your agent
2. Navigate to **Integrations** (left sidebar)
3. Click **Telegram** → **Enable**
4. Paste your **Telegram Bot Token**
5. Click **Start** and **Authorize**

>  If successful, Dialogflow will connect your agent to Telegram using a webhook.

---

## Testing
Open Telegram → search for your bot by username → start chatting!

Try these:
- `Where is my order?`
- `My account was suspended`
- `When will I get my refund?`

---

##  Troubleshooting
- **No response?** Make sure your bot is started manually from the user side.
- **"Sorry, what was that?"** means fallback intent is triggered – verify your intents have proper training phrases.
- **Error while enabling Telegram?** Double-check the token and make sure your bot is not set to private.

---

##  Notes
- You must create **intents** before enabling Telegram so Dialogflow knows how to respond.
- Telegram only works with **Dialogflow Essentials (ES)**, not CX.

---
