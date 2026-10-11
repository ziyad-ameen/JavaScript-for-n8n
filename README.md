## 🤖 WhatsApp Bot n8n Code Node

This script powers an n8n Code node for a WhatsApp bot, designed for efficiency and natural conversation flow.

### Key Features
* **Context-Aware AI Assistant:** The bot remembers recent context without hallucinations or repeating greetings in every single message.
* **Token & Cost Optimization:** Intentionally limits the memory window to 15 minutes to keep LLM token consumption low, lowering operational API costs for high-volume channels.
* **Timezone-Aware Logging:** Handles UTC-to-local timezone normalization so conversation timestamps match your business hours.
