# ⚙️ Slack + Clay Account Intelligence Bot

Automates **company lookup, enrichment, and record creation directly from Slack** using intelligent “find or create” logic — ensuring no duplicates and maintaining data privacy.

---

## 📊 Workflow Overview

![Workflow](https://raw.githubusercontent.com/parvez-revops/slack-clay-account-intelligence-bot/main/account%20research.png)

---

## ⚙️ How It Works

1. **Slack Trigger**

   * SDR/AE enters a company domain in Slack

2. **Formatter (Zapier)**

   * Cleans and structures input

3. **Clay Lookup**

   * Checks if company already exists

4. **Conditional Logic (Paths)**

**🟢 Path A — Record Found**

* Fetches existing enriched company data
* Sends results via private Slack DM

**🟠 Path B — Record Not Found**

* Creates new record in Clay
* Enriches company data automatically
* Returns enriched insights via Slack DM

---

## 🤖 Key Capabilities

* Intelligent **find vs create** automation
* Prevents duplicate company records
* Real-time enrichment via Clay
* Private Slack delivery (compliance-safe)
* End-to-end automation with zero manual effort

---

## 📈 Impact

* ⚡ Eliminates manual account research
* 🔁 Unified workflow for lookup + enrichment
* 🔒 Ensures data privacy & compliance
* 🚀 Faster SDR execution

---

## 🛠 Tech Stack

Slack · Clay · Zapier (Formatter, Paths, Delay)

---
