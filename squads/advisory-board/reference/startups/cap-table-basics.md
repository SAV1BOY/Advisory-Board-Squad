# Cap Table Structure and Dilution

## What Is a Cap Table

A capitalization table (cap table) is the definitive record of who owns what in a company. It lists every shareholder, the type and number of shares they hold, the price paid, and the percentage of total ownership. For startups, the cap table is a living document that evolves with every funding round, option grant, and conversion event. A clean, well-maintained cap table is a prerequisite for fundraising, M&A, and any transaction involving equity.

## Core Components

### Share Classes
- **Common Stock:** Held by founders, employees, and sometimes early advisors. Common stock sits at the bottom of the liquidation preference stack — last to get paid in a sale or liquidation.
- **Preferred Stock:** Held by investors. Preferred shares carry special rights: liquidation preference, anti-dilution protection, board seats, information rights, and protective provisions. Each funding round typically creates a new series (Series A Preferred, Series B Preferred, etc.).
- **Options (Unexercised):** Rights to purchase common stock at a fixed strike price. Not yet shares, but they represent future dilution and must be tracked on the cap table.
- **Warrants:** Similar to options but typically issued to lenders, strategic partners, or in connection with debt financing.
- **Convertible Instruments:** SAFEs and convertible notes that will convert into preferred stock at a future priced round. These sit "above" the cap table until conversion but represent committed future dilution.

### Key Cap Table Fields

| Field | Description |
|---|---|
| Shareholder | Name of the individual or entity |
| Share Class | Common, Series A Preferred, Series B Preferred, etc. |
| Shares Held | Number of shares owned |
| Fully Diluted Shares | Shares including all options, warrants, and convertibles as if exercised/converted |
| Ownership % (Issued) | Percentage of currently issued shares |
| Ownership % (Fully Diluted) | Percentage including all potential dilution sources |
| Investment Amount | Total capital invested by this shareholder |
| Price Per Share | Price paid per share in the relevant round |
| Vesting Status | For options/restricted stock: vested vs. unvested shares |

## How Dilution Works

### The Dilution Equation
When new shares are issued (in a funding round, option grant, or conversion), existing shareholders' percentage ownership decreases even though their number of shares stays the same. This is dilution.

**Pre-money ownership = Shares held / Total shares before new issuance**
**Post-money ownership = Shares held / (Total shares before + New shares issued)**

### Typical Dilution by Stage

| Stage | Typical Dilution | Post-Round Founder Ownership (Cumulative) |
|---|---|---|
| Co-founder split | N/A | 100% (split among founders) |
| Option pool creation | 10-20% | 80-90% |
| Seed round | 15-25% | 60-75% |
| Series A | 20-30% | 40-55% |
| Series B | 15-25% | 30-45% |
| Series C+ | 10-20% | 25-35% |
| Pre-IPO (cumulative) | — | 10-25% (typical founder range) |

### The Option Pool Shuffle
Investors typically require that the option pool be created or expanded before their investment (from the pre-money valuation), meaning existing shareholders bear the dilution, not the new investors. A 20% option pool created pre-money on a $10M pre-money valuation effectively reduces the true pre-money valuation for founders. Understanding this mechanic is critical for negotiation.

## Key Concepts

### Fully Diluted vs. Issued
- **Issued shares** count only shares that have been formally issued and are outstanding.
- **Fully diluted** includes issued shares plus all shares that would exist if every option were exercised, every warrant converted, and every SAFE/note converted. Investors always discuss ownership on a fully diluted basis.

### Liquidation Preferences
- **1x Non-participating preferred:** Investors get their money back first (1x their investment) or convert to common and share pro rata — whichever is greater. This is the most founder-friendly standard structure.
- **1x Participating preferred:** Investors get their money back first AND share in the remaining proceeds pro rata. This is a "double dip" that significantly reduces common shareholder payout.
- **Multiple preferences (2x, 3x):** Investors get 2x or 3x their investment back before common shareholders see anything. These are aggressive terms, typically seen in down rounds or distressed situations.

### Anti-Dilution Protection
- **Weighted average:** Adjusts the conversion price of preferred shares based on the amount and price of new shares issued in a down round. Standard and fair.
- **Full ratchet:** Adjusts the conversion price to the lowest price at which any new shares are issued, regardless of amount. Highly punitive to founders and common holders.

### Vesting
- **Standard schedule:** 4-year vesting with 1-year cliff. After the cliff, 25% vests; remaining 75% vests monthly or quarterly over 36 months.
- **Acceleration:** Single-trigger (accelerates on acquisition) or double-trigger (accelerates on acquisition + termination). Double-trigger is standard; single-trigger is founder-friendly but buyer-unfriendly.

## Board Application

- Review the cap table quarterly to understand ownership dynamics and dilution trajectory
- Before any fundraise, model the post-round cap table and assess founder/team dilution
- Monitor the option pool — insufficient remaining pool creates hiring friction; excessive pool signals over-dilution
- Ensure all convertible instruments (SAFEs, notes) are tracked and their potential dilution modeled
- In exit scenarios, run waterfall analyses to understand how proceeds distribute across share classes and preference stacks
- Flag any unusual terms (participating preferred, multiple liquidation preferences, full ratchet anti-dilution) that may misalign incentives between investors and the operating team
