# OKX US Review: What 0.20% Maker and 0.35% Taker Cost on a $1,000 Trade, How Withdrawals Behave After a New Deposit, and Who Should Skip the US Account

OKX US charges **0.2000% maker and 0.3500% taker** on regular spot trades, which comes to **$2.00 or $3.50 on a $1,000 order** before any spread. The fee is easy to price. Withdrawal access after a fresh deposit is the harder part, and it decides whether this account suits you, particularly if your habit is to buy and immediately send the coins to your own wallet.

OKX's US business runs through OKX Inc., formerly OKCoin USA Inc., and it keeps its own account terms and its own rate card. Every number below comes from that US schedule. The 0.08% / 0.10% figures quoted on most "OKX fee" pages belong to the global exchange and do not apply to an OKX Inc. account.

## The short version

> **Worth it if:** you fund with dollars, trade spot, and are content to leave cash on the exchange and build a position over weeks.
>
> **Skip or wait if:** you withdraw to self-custody after every purchase, or you want US perpetuals, the global API menu, or products that only exist on the international platform.
>
> **Key numbers:** 0.2000% maker / 0.3500% taker on regular spot; VIP 1 from $100,001 in assets or 30-day volume; zero commission on USDC-USDT and PYUSD-USDT.

👉 [Open an OKX US account and check which fee tier your balance lands in](https://okx.com/join/CASH20)

## OKX US fees: one rate card, three carve-outs

OKX does not sell subscription plans. On US crypto exchanges, "packages" or "tiers" mean fee levels you reach by holding assets or trading volume, and OKX US follows that pattern. Your cost per order depends on three things: whether you're on the regular or VIP schedule, whether your order adds or removes liquidity, and whether the pair sits on the stablecoin exception list.

| Fee tier and who gets it | Maker | Taker | Cost on a $1,000 order | Rate check |
| --- | --- | --- | --- | --- |
| **U.S. Regular Spot** (default below VIP 1) | 0.2000% | 0.3500% | $2.00 maker / $3.50 taker | [ Check current OKX US rates](https://okx.com/join/CASH20) |
| **USDC-USDT, PYUSD-USDT** | 0 | 0 | $0 commission; spread still applies | [ Check current OKX US rates](https://okx.com/join/CASH20) |
| **USDT-USD, USDG-USDT, RLUSD-USDT** | 0 | 0.05% | $0 maker / $0.50 taker | [ Check current OKX US rates](https://okx.com/join/CASH20) |
| **U.S. VIP 1** ($100,001 in assets or 30-day volume) | Not published publicly | Not published publicly | Rate comes from the live US schedule | [ Check current OKX US rates](https://okx.com/join/CASH20) |

The VIP 1 threshold is **$100,001 in account assets or $100,001 in 30-day volume**. OKX runs VIP levels up to 9, but the per-level maker and taker numbers for the US schedule were not in the public documentation reviewed for this piece. If you're near the threshold, confirm the rate inside your account before you route volume through it.

The stablecoin carve-outs matter more than the headline rates suggest. USDC-USDT and PYUSD-USDT show zero maker and zero taker fees, while USDT-USD, USDG-USDT and RLUSD-USDT show zero maker with 0.05% taker. Zero commission still leaves the bid-ask spread, so a "free" stablecoin swap can cost a few basis points in the fill.

## What a $1,000 trade actually costs

| Rate card | Maker on $1,000 | Taker on $1,000 |
| --- | --- | --- |
| OKX US regular spot (0.20% / 0.35%) | $2.00 | $3.50 |
| Global OKX regular spot (0.08% / 0.10%) | $0.80 | $1.00 |

Both sets of numbers are accurate for the entity that publishes them. Global OKX regular spot starts at 0.08% maker and 0.10% taker; the US exchange charges roughly two and a half to three and a half times that for the same order size. Anyone quoting the global rate as "the OKX fee" is describing an account you can't open from the United States.

You can lower the effective cost without touching the rate card. A debit-card instant buy runs through a quoted price with a spread baked in, while a bank transfer plus an order-book trade keeps you on the published 0.20% / 0.35%. You still pay the spread, slippage and the eventual withdrawal fee, so the saving is real but not free. One detail on limit orders: maker pricing applies only when the order adds liquidity to the book. If it crosses and fills immediately, it's charged as a taker order.

## Withdrawals after a new deposit

OKX US lets you withdraw, including ACH and domestic wire for bank payouts when you qualify, but practical withdrawal access is set by identity checks and risk controls rather than by a published table. A fresh deposit is where that becomes visible, especially if you plan to sweep the purchase straight to a self-custody wallet.

OKX doesn't publish how long a new deposit is held, and it doesn't commit to a fixed resolution window when a transfer is reviewed. Government ID plus a selfie or facial check opens normal exchange use; bank verification and enhanced review follow separate rules and can run on a different clock. Large transfers, unusual activity, document mismatches, a changed security setting or a payment partner's own rules can all push a withdrawal into review.

Practical consequences: depositing less often and moving larger amounts is easier on this account than frequent deposit-and-withdraw cycles. Keeping the name on your bank account, ID and OKX profile consistent avoids the most common mismatch trigger. And budget hours for a withdrawal you intend to complete the same day, not minutes.

👉 [Start the OKX US sign-up and read the withdrawal and verification terms before you fund it](https://okx.com/join/CASH20)

## What the US menu includes, and what it leaves out

US dollar spot traders get two execution routes: a **quoted purchase** and an **order-book trade**. The quoted route is simpler and prices the spread in. The order-book route gives you limit orders and the published maker/taker rates, which is what larger or more patient accounts tend to use.

API access follows the US product menu. OKX documents REST and WebSocket connections plus public market data globally, but a working global endpoint for a perpetual contract doesn't mean an OKX Inc. account can place that order. If your strategy depends on instruments that only exist on the international platform, the US account won't run it.

**USD to USDC order-book migration.** OKX asked US users to move affected USD orders and bots to the matching USDC pairs between **September 23 and 30, 2026**. Remaining affected USD orders and bots were canceled on September 30, and Grid and Smart Portfolio positions were sold, while designated other bot positions were kept. USDT-USD was outside the change. That window has closed; if you held anything in those products, check the account for leftover balances or orphaned bot settings rather than assuming they carried over.

**Yield on USDG.** The US USDG page advertises up to **3.5% APY for standard users and 4.1% for VIP users**, but the comparison table carrying those figures is dated March 2026. Treat them as a ceiling from last spring, not a current quote, and check the live rate in your account before you move stablecoin balances.

**Event products.** The US menu also carries **Event Contracts**, a USDT-margined order-book product tied to specific event outcomes, and **Outcomes**, an app-only prediction product that pays in non-cash points. Eligibility depends on the account and the jurisdiction, and Outcomes currently excludes at least Florida and Rhode Island. These are not the global derivatives or margin products, and the global terms don't transfer.

**Card.** OKX's US help center documents an OKX Card for eligible US customers in select states, excluding Massachusetts, New York, American Samoa, Guam, the Northern Mariana Islands, Puerto Rico and the US Virgin Islands as of late October 2026. It requires completed exchange KYC and an OKX Pay account holding USDC, USDT or USDG. It is separate from the EEA and Australian card programs and follows its own cardholder agreement.

👉 [See which products and fee tiers your OKX US account can actually access](https://okx.com/join/CASH20)

## Licences, the $84 million penalty, and the protection you don't get

OKX Inc. is registered with FinCEN as a money services business under **NMLS #1767779**, and it holds a portfolio of state money transmitter licences. Two things follow from that, and neither is as broad as it sounds.

First, FinCEN registration is not a state licence, and a state licence is not a product permission. OKX's own US licences page lists individual state authorisations (the District of Columbia under MTR1767779, Illinois under MT.0000366, Maryland under 1767779, among others) with consumer complaint contacts, and it flags at least one carve-out: the Louisiana money transmission licence "does not cover the exchange or transmission of virtual currency." A licence list tells you which regulator will take a complaint. It doesn't tell you which products are switched on for your account.

Second, there is no deposit insurance. OKX's own US disclosure states that virtual currency is not legal tender, is not backed by the US government, and that **accounts and value balances are not subject to FDIC or SIPC protection**. If the exchange failed, your balance would not be covered the way a bank deposit would.

On the enforcement record: an OKX affiliate, **Aux Cayes FinTech Co. Ltd.**, agreed in **February 2025** to an **$84 million penalty plus roughly $421 million in forfeiture** for operating an unlicensed money-transmitting business. The settlement names that affiliate; it doesn't establish that every OKX account holder contracts with it. Some write-ups add a multi-year compliance monitor to the deal. First-party descriptions of the follow-on monitoring conflict, so treat the monitor's existence and term as unconfirmed rather than as a fact you can rely on.

OKX's brand description on Trustpilot also states **1:1 reserves** with a verifiable Proof of Reserves. That's the platform's claim about its own holdings, not an audit conclusion you can independently check from a US account statement.

## What users report

**G2: 4.6 out of 5 across 54 reviews.** The recurring positives are cost and range: users trading two or three times a week notice the commission difference against their previous exchange, and reviewers describe spot and futures fees as competitive. Earn and staking tools, built-in bots, a free demo account and a 400+ asset catalogue come up repeatedly. The recurring negatives are support and access: poor customer service, limited regulatory coverage compared with top-tier licensed venues, occasional deposit or balance-sync delays, fiat funding that can take up to two business days, and one reviewer who says funds were blocked for nearly a year with KYC repeatedly rejected and only automated replies.

**Trustpilot** reviews describe orders filling at the set price, the app holding up during busy market hours, withdrawals landing in minutes on most networks, P2P escrow working as expected and same-day verification. The complaints centre on P2P advertising restrictions, the OKX Wallet displaying incorrect USD prices, and support ignoring formal complaints.

Two caveats on that evidence. Both samples mix global OKX users with US users, and neither is broken out by entity, so they describe the brand more than the US account. And a widely shared Trustpilot narrative about escalating "internal confirmation fees" followed by a paid recovery service reads like a pig-butchering and refund-recovery script, not an exchange custody dispute. It shouldn't be counted as evidence that OKX US takes customer funds.

## Who should use OKX US, and who shouldn't

Use it if you wire or ACH dollars in, trade spot, and treat the exchange balance as working capital you'll deploy over several weeks. The published 0.20% / 0.35% is easy to model against your expected turnover, the stablecoin pairs are cheap for rebalancing, and VIP 1 is reachable at $100,001 if you keep meaningful balances on the platform.

Think twice if any of these describe you:

- You buy and immediately withdraw to a hardware wallet. New-deposit withdrawal access is the documented friction point, and it hits exactly that habit.
- You need US perpetual futures, margin, or a global API instrument set. Those sit outside the US account menu.
- You trade a few hundred dollars a month. At that size the fee difference between exchanges is smaller than the spread you'll pay on a quoted purchase, and a simpler venue may cost less in total.
- You want one exchange for both US and international activity. The global and US businesses are separate legal entities with separate terms, and an account on one doesn't carry permissions on the other.

## FAQ

**Is OKX US the same as global OKX?**
No. OKX Inc. is a separate US entity with its own account terms, fee schedule and product menu. Global rates, global API examples and global derivatives terms don't apply to it.

**Can I get VIP pricing below $100,001?**
The published VIP 1 entry point is $100,001 in assets or $100,001 in 30-day volume. Below that, the regular 0.20% / 0.35% applies.

**Are USDC-USDT and PYUSD-USDT really free?**
Commission is zero on both sides. The bid-ask spread is not waived, so the fill still costs something.

**Can I withdraw right after depositing?**
Access can be restricted on a new deposit, and OKX doesn't publish hold durations or a guaranteed resolution time. Plan for review if you intend to move funds out quickly.

**Does the US account support the same API and bots as the global site?**
API access follows the US product menu, so global endpoints for restricted instruments won't execute here. Bots tied to migrated USD pairs were affected by the September 2026 order-book change.

**Which states can open an account?**
OKX doesn't publish a single current state-availability list, and its global restricted-territory list isn't a US state list. Eligibility is checked during sign-up, so run that before you plan around the account. Individual products have their own limits on top, including the Outcomes exclusions for Florida and Rhode Island.

## Before you fund the account

Two checks decide whether OKX US is the right venue for you. Confirm your current fee tier inside the account, because the regular rate is public but the VIP ladder isn't. Then read the withdrawal and verification terms for your situation, especially if a self-custody transfer is part of your routine.

If you deposit dollars, trade spot and can leave the balance working on the exchange, the cost is predictable and the fee schedule is one of the clearer ones in the US market. If you need same-day exit after every buy, size the account accordingly or keep the deposit frequency low.

👉 [Open an OKX US account and review the live fee tier and withdrawal rules before your first deposit](https://okx.com/join/CASH20)
