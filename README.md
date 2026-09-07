# YNAB Rules Check

Mailbox for household YNAB rules the API cannot see.

Not an MCP. Nothing to install. Keep the connector you already have.

**[Open the form](https://github.com/gfsantamarina/ynab-rules-check/issues/new?template=rules.yml)** and paste 5+ rules. Say how you talk to YNAB.

## Who this is for

You already pull YNAB into Claude, Cursor, an MCP, or a script. You asked if the month was okay. You got Age of Money.

The tools see the budget. They do not know your house: when a deposit is income, when a card gets paid, when a placeholder is real.

If you have never argued about that, this repo is not for you.

## What you get

1. A reply on your Issue. Your lines rewritten as pass/fail checks. That is the only thing that happens now.
2. Your list sits with the others. If they rhyme, I may bind the pattern into one small month check. If they don’t, this stays a mailbox and then it goes quiet.

Filing does not hook up YNAB. It does not change tonight’s chat.

Optional scratch paper if you want a reminder in the assistant you already use:

```
Here are our household YNAB rules:
[paste your five+]

Using my connected YNAB data, list only the rules we broke this month.
Do not restate the Four Rules. Do not praise Age of Money.
```

## Rules that count

Specific enough that someone could mark this month pass or fail.

From my file (anonymized). Do not send these back.

- Don’t treat expected money as cash. Book income when it lands.
- Don’t pay the card from a reimbursement category until the expense report is filed.
- If a subscription can bill a gift card, check the merchant before you clear the YNAB placeholder. Gift card: delete the placeholder.

Not a rule: “Give every dollar a job.” “Cover overspending.” “Reconcile sometimes.”

## How I talk to YNAB

Official API plus a markdown file. No YNAB MCP. Claude reads the file.

## How to file

1. [Open the form](https://github.com/gfsantamarina/ynab-rules-check/issues/new?template=rules.yml)
2. Paste five or more household rules. One sentence per line.
3. Pick how you talk to YNAB (API + file, MCP, assistant not connected, or none of these). Name the MCP or script if you have one.
4. Do not paste a Personal Access Token, a budget export, account numbers, or people’s names.

## What this is not

- A YNAB MCP server
- A replacement for [oliverames/ynab-mcp-server](https://github.com/oliverames/ynab-mcp-server) or the other API wrappers
- A hosted app, Skill pack, or paid product

Token questions belong on those other repos.
