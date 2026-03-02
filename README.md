# ATLAS Module 02: The Book v1.4

Wirehouse/Broker-Dealer Advisor Career Simulation

## Overview

This is a single-file HTML simulation of advisor career progression at a wirehouse/broker-dealer firm. It models the structural mechanics that separate the "grind" phase from the "enterprise" phase of an advisory career.

## v1.4 Realism Improvements (New!)

### A-Shares Mechanics
- Fixed to reflect realistic front-load + trail structure  
- Changed from misleading "0.25% yield" to accurate description: **Front Load + 0.5% Trail**
- Updated financial calculations to match wirehouse compensation structures

### Time Allocation Clarity
- Changed label from "TIME_ALLOCATION" to **"PRODUCTION CAPACITY"**  
- Added explanatory text: "(Monthly revenue-generating time)"
- Clarifies that this represents revenue-producing capacity, not total working hours

### Dynamic Staffing Efficiency
- BOAs now add +50-80 hrs/month depending on book size (scales with AUM)
- Associates now add +80-150 hrs/month depending on book size  
- Staff become more valuable at higher AUM levels due to better systems and delegation

## v1.3 Features (Original Core Mechanics)

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

- **Production Capacity**: Balance your monthly revenue-generating hours between Prospecting, Closing, Servicing, Admin/Compliance, and Firm Initiatives
- **AUM Growth**: Build fee-based (recurring) vs. A-shares (front-loaded + trail) revenue streams  
- **Firm Patience**: Maintain AUM targets and alignment to avoid termination
- **Staffing**: Hire Branch Office Administrator (+50-80 hrs at $4k/mo) and Junior Associate (+80-150 hrs at $10k/mo)

## Deployment

Simply open `index.html` in any modern web browser.

## Development Status

✅ v1.4 - Realism improvements (A-shares, time allocation clarity, dynamic staffing)