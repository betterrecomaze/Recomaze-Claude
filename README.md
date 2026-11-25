# Recomaze for Claude

Recomaze is a marketing and sales platform for small businesses and online stores. This plugin connects Claude to your Recomaze account, so you can read what your customers and leads did, prepare work and approve it in the chat.

## What you can do

- Follow up leads and keep your sales CRM up to date.
- Draft product descriptions, articles and social posts from your own catalog and business profile.
- See how AI search engines describe your business, and what is missing.
- Set up your website's AI chatbot and read what visitors asked it.
- Get one short brief, on demand or every morning, if you turn it on.

Try:

- "Which leads need a follow-up today?"
- "Draft a product description using my connected catalog."
- "What questions did visitors ask my website chatbot?"

## What is in the plugin

- One remote MCP server, `https://agent.recomaze.ai/mcp`, operated by Recomaze.
- Four skills: `get-started` (setup), `daily-brief` (the brief), `completion-report` (what was saved, read back from the account) and `get-help` (a support message you review and send yourself).

The plugin holds no scripts, hooks or other code and runs nothing on your computer.

## Sign-in and data

You sign in with your Recomaze account through OAuth and choose which areas Claude may use. You can disconnect at any time in Claude or in Recomaze.

- **Sent to Recomaze:** the arguments of the Recomaze tools Claude calls, such as a search, a draft you approved or a note about a lead. These can include personal data you give, such as a lead's name and contact details.
- **Received from Recomaze:** data of your account that a tool returns, such as your business profile, products, leads and analytics.
- **Nothing else:** the plugin sends data to no other service. When you ask for it, Recomaze itself can publish to the store, blog and social accounts you connected to it.

See the [privacy policy](https://recomaze.ai/privacy-policy) and the [terms of service](https://recomaze.ai/terms-of-service).

## Approval and costs

Publishing, going live, writing to your store, deleting and spending credits wait for your yes. Some actions use Recomaze credits; the price is shown before you approve. If you set a weekly budget, work within it can run without asking each time. Orders with a supplier are prepared as a cart and placed and paid by you in the supplier's own shop.

## Requirements

A Recomaze account. You can create one while connecting.

## Help

Read the [guide](https://recomaze.ai/integration-guides/claude-chatgpt) or write to better@recomaze.ai. If the tools stop answering, reconnect Recomaze in Claude's settings and start a new chat.
