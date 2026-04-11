# 🤝 Contributing to n8n Workflows

Thank you for your interest in contributing! 🚀
We welcome all kinds of workflows that can help others automate tasks using n8n.

---

## 📌 How to Contribute

1. Fork the repository

2. Create a new branch:

   ```
   git checkout -b feature/your-workflow-name
   ```

3. Add your workflow JSON file to the appropriate folder:

   * `/workflows/ai`
   * `/workflows/telegram`
   * `/workflows/automation`
     *(create a new category if needed)*

4. Commit your changes:

   ```
   git commit -m "Add: your workflow name"
   ```

5. Push and create a Pull Request

---

## 📂 File Requirements

* Format: `.json` (exported from n8n)
* File name: `kebab-case.json`

  * ✅ `telegram-auto-reply.json`
  * ❌ `MyWorkflow.JSON`

---

## 🧾 Workflow Guidelines

Please ensure your workflow:

* ✅ Is tested and working
* ✅ Has a clear purpose
* ✅ Does not contain sensitive data (API keys, tokens, credentials)
* ✅ Uses generic placeholders where needed

---

## 🏷️ Naming Convention

Use descriptive names:

* `telegram-notifications.json`
* `openai-email-generator.json`

---

## 📝 Description (IMPORTANT)

When creating a Pull Request, include:

* What the workflow does
* Required services (Telegram, OpenAI, etc.)
* Setup instructions (if needed)

---

## 📸 (Optional but Recommended)

* Add a screenshot or GIF of your workflow
* Helps others understand it faster

---

## 🚫 What NOT to Submit

* Broken workflows
* Duplicate workflows
* Workflows with hardcoded personal data

---

## ❤️ Thank You

Your contributions help make automation easier for everyone!
