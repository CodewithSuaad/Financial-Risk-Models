# Financial-Risk-Models
# CDO Tranche Waterfall Loss Calculator

An interactive financial modelling tool built to illustrate 
the mechanics of CDO tranche waterfall loss absorption — 
comparing pre-GFC, post-GFC minimum compliance, and 
post-GFC robust capital structures.

Built as part of MSc Project work on Securitization at University of Birmingham 
| Module Risk Management in Financial Markets

## What it does

The calculator models how losses cascade sequentially through 
equity, mezzanine, and senior tranches in a standard 
Asset-Backed Securities (ABS) structure. It allows users to 
compare three regulatory scenarios side by side and observe 
how tranche sizing directly determines which investors absorb 
losses and at what point.

---

## Three presets

| Scenario | Equity | Mezzanine | Senior | Context |
|---|---|---|---|---|
| Pre-GFC (2005–07) | 3% | 7% | 90% | Non-compliant — typical CDO structure before the Global Financial Crisis |
| Post-GFC Minimum | 5% | 10% | 85% | Meets the 5% retention floor under Dodd-Frank (2010) and EU Securitisation Regulation (2017) |
| Post-GFC Robust | 12% | 13% | 75% | Well-capitalised — fully absorbs a 25% loss rate without senior tranche impact |

Default loss rate: 25% — reflecting realised subprime pool 
losses by 2009 (IMF, 2008).

---

## Key features

- Three scenario presets for direct regulatory comparison
- Adjustable pool size, loss rate, and tranche allocations
- Real-time waterfall bar chart showing loss absorption 
  across all loss rates from 0% to 60%
- Dynamic compliance indicator on the equity slider — 
  flags structures below, at, and above the 5% regulatory 
  minimum
- Contextual insight messages that update with regulatory 
  commentary depending on the equity tranche selected
- Dark mode support

---

## Live tool

https://superlative-haupia-92b7bf.netlify.app/

---

## The analytical insight

5% retention requirement introduced post-GFC is a necessary but not sufficient condition for  structural safety. 
At a 25% loss rate, even the minimum compliant structure (5% equity) still transmits $100M of losses into the senior tranche 
on a $1,000M pool. Only a robustly capitalised structure with combined buffers matching or exceeding the loss rate fully protects 
senior holders — which is precisely why Basel III capital charges and STS transparency requirements were needed alongside the retention rule.

---

## References

- Brunnermeier, M.K. (2009) 'Deciphering the liquidity and 
  credit crunch 2007–2008', Journal of Economic Perspectives, 
  23(1), pp.77–100.
- Gorton, G. and Souleles, N.S. (2006) 'Special purpose 
  vehicles and securitization', in Stulz, R.M. and Carey, M. 
  (eds.) The Risks of Financial Institutions. Chicago: 
  University of Chicago Press, pp.549–602.
- IMF (2008) Global Financial Stability Report: Financial 
  Stress and Deleveraging. Washington D.C.: IMF Publications.
- Machado, P. (2025) 'Securitisation: you can never tranche 
  the same portfolio twice', Keynote speech, European 
  Financial Institutions Conference, 30 September. ECB 
  Banking Supervision.
---
