# Coinsnap for DigiMember

![Coinsnap for DigiMember](https://coinsnap.io/wp-content/uploads/2024/03/digimember-plugin.png)

**Planned Bitcoin payment integration for DigiMember and WordPress.**

Coinsnap is **Bitcoin payment software for merchants** and a brand of **Onlineshop24 d.o.o., Serbia**.

## Repository status

This repository currently contains **documentation only**.

There is no installable WordPress plugin package or DigiMember integration source code in the current `main` branch. A corresponding public plugin listing in the WordPress.org Plugin Directory could not be verified during the current documentation review.

For that reason, this repository should currently be treated as a **placeholder / planned integration**, not as a production-ready Coinsnap plugin.

## Intended integration

The repository was originally created for a **Coinsnap for DigiMember** integration with the goal of enabling Bitcoin and Lightning payments for DigiMember-based membership and protected-content workflows.

Before publishing or promoting this integration, the implementation should be completed and verified against the current DigiMember version and the current Coinsnap payment architecture.

## Before release

A future production release should include and verify at least:

- an installable WordPress plugin
- DigiMember dependency and compatibility checks
- Bitcoin and Lightning payment flow
- Coinsnap merchant connection
- payment confirmation and membership-access handling
- webhook or payment-status verification
- secure handling of credentials and callbacks
- current WordPress and PHP compatibility metadata
- installation and configuration documentation
- changelog and versioning
- WordPress.org-ready `readme.txt`, if the plugin is to be distributed through WordPress.org

Any additional functionality — for example BTCPay Server support, on-chain payment behavior, recurring-payment handling, discounts or settlement options — should only be documented once it is implemented or explicitly defined for the DigiMember product.

## Coinsnap

Coinsnap provides Bitcoin payment software for online merchants, e-commerce, WordPress and point-of-sale use cases.

- Website: https://coinsnap.io/
- Merchant account: https://app.coinsnap.io/register
- Coinsnap Wallet: https://coinsnap.io/wallet/
- API documentation: https://docs.coinsnap.io/
- GitHub: https://github.com/Coinsnap/
- Telegram: https://t.me/coinsnap

> **Brand note:** Coinsnap is Bitcoin payment software for merchants and is not the provider of the similarly named coin identifier app "CoinSnap".
