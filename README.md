# ChainBill

ChainBill is a no-signup, browser-local invoice builder for receiving stablecoin payments.

**Live app:** [chainbill.fairy-cow-6895.chatgpt.site](https://chainbill.fairy-cow-6895.chatgpt.site/)

## What it does

- Creates professional invoices without uploading invoice data to an application server.
- Supports native USDC on Base and USDT on TRON (TRC20).
- Generates payment QR codes and wallet-deep-link payloads.
- Accepts a transaction hash and verifies the recipient, token contract, and minimum amount on-chain.
- Produces a print-ready invoice that can be saved as PDF.

## Security model

ChainBill is non-custodial. It never requests or stores a seed phrase or private key. Payers transfer directly to the invoice recipient's wallet, and verification uses public blockchain data.

Always confirm the selected network and recipient address before sending funds. Blockchain transfers are generally irreversible.

## Commercial integration and support

Custom integrations, branded deployments, and ongoing implementation support are available for **200 USDC per month**.

To discuss a scoped engagement, [open a commercial inquiry](https://github.com/moti4k/chainbill/issues/new?title=Commercial%20inquiry&body=Public%20project%20URL%3A%0ARequested%20integration%3A%0ATarget%20network%20and%20token%3A%0AAcceptance%20criteria%3A%0A). Do not include private keys, seed phrases, credentials, personal documents, or other secrets.

## Feedback

Public bug reports and feature requests are welcome in [GitHub Issues](https://github.com/moti4k/chainbill/issues).

## Provenance

ChainBill was implemented and is maintained with an AI coding agent operating under the repository owner's authorization. Product behavior and payment verification remain publicly inspectable through the live application.

This repository is the public product page and issue tracker. It does not currently contain the application source code.
