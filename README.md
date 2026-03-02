# ATLAS Module 02: The Book v1.3

Wirehouse/Broker-Dealer Advisor Career Simulation

## Overview

This is a single-file HTML simulation of advisor career progression at a wirehouse/broker-dealer firm. It models the structural mechanics that separate the "grind" phase from the "enterprise" phase of an advisory career.

## v1.3 Features

### Grid Cap
- Maximum grid payout capped strictly at 40%, regardless of trailing 12-month revenue
- Grid increases from 35% to 40% when T-12 reaches $250k+

### Trimester Bonus (Golden Handcuffs)
- Payout occurs every 4 months (months 4, 8, 12...)
- Only triggers if AUM >= $50M
- Base bonus = (AUM / $200M) × $40,000
- Full payout requires 100% Firm Alignment

### Firm Alignment System
- Decays by 3% monthly without intervention
- Restored by spending time on "Firm Initiatives" (insurance, lending, etc.)
- Directly impacts trimester bonus payouts

## Game Mechanics

- **Time Allocation**: Balance your 100 (or more with staff) hours between Prospecting, Closing, Servicing, Admin/Compliance, and Firm Initiatives
- **AUM Growth**: Build fee-based (recurring) vs. A-shares (front-loaded) revenue streams
- **Firm Patience**: Maintain AUM targets and alignment to avoid termination
- **Staffing**: Hire Branch Office Administrator (+50hrs at $4k/mo) and Junior Associate (+100hrs at $10k/mo)

## Deployment

Simply open `index.html` in any modern web browser.

## Development Status

✅ v1.3 - Grid Cap & Golden Handcuffs implemented