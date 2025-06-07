# 💼 Portfolio – B. Cobra Systems

A look inside our custom automation arsenal. This repo highlights some of our most effective low-code + AI solutions using platforms like:

- [n8n](https://n8n.io/) – Open-source workflow automation
- [Power Automate](https://flow.microsoft.com/)
- [Power Apps](https://powerapps.microsoft.com/)

> 🚫 Actual flows and proprietary logic are stored securely.  
> ✅ These examples have been anonymized and simplified to give you a taste of our work.

---

## 🔁 Automated Lead Assignment (n8n)

**Problem**: Sales teams were manually routing leads based on zip code and product.

**Solution**: We built a webhook-triggered workflow that:
- Parses lead data
- Applies routing logic using `IF`/`Switch` nodes
- Sends Slack alerts and creates CRM entries

![n8n Screenshot](media/n8n-lead-flow.png)

---

## 📱 Internal Ticketing (PowerApps + Automate)

**Goal**: Replace shared inbox with a self-serve support app.

- Employees submit tickets via PowerApps
- Power Automate parses and routes requests
- Escalation logic built in for high-priority tags

![PowerApp UI](media/powerapp-form.png)

---

## 🧠 Smart Email Classifier (n8n + OpenAI)

**Scenario**: Customer emails need smart categorization.

- Extract intent using OpenAI's API
- Label and tag in Helpdesk
- Generate auto-replies based on detected tone

![Flow diagram](media/ai-email-pipeline.png)

---

## 🔐 Note

We never publish sensitive data or client-specific IP. These examples are conceptual, anonymized, or rebuilt with sample data.

---

## 🤝 Ready to Escape Busywork?

📧 info@bcobrasystems.com  
🌐 [bcobra.systems](https://bcobra.systems)  
🧠 More about us: [@Bcobra-Systems](https://github.com/Bcobra-Systems)
