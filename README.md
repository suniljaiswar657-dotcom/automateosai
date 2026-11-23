# AutomateOS AI

A mobile-first business command center MVP for India and global small businesses.

## Features
- Dashboard: paid revenue, outstanding balances, customers and open invoices
- Invoice creation, search, status tracking and mark-paid action
- Payment recovery queue with copyable reminder text
- Customer CRM
- Workflow tracking board
- Built-in rule-based business assistant using local workspace records
- Workspace settings and JSON backup export
- Responsive dark interface for mobile and desktop

## Run
Open `index.html` in a modern browser. No build step or paid API key is required.

## MVP boundaries
Data is stored only in this browser using localStorage. It is not synced across devices. This version has no login, cloud database, automatic email/WhatsApp sending, payment processing, scheduled background execution or connected generative AI model. The assistant uses built-in rules and playbooks, not a live LLM.

Do not enter passwords, card numbers, bank credentials or other sensitive information. Before production use, add secure authentication, server-side storage and validation, access controls, backups, privacy/terms documents and applicable compliance reviews.
