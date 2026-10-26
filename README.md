# Paywall Audit — Scate AI (Mozart AI)

**Live:** https://bterzic123.github.io/scate-paywall-audit/

Four ranked ideas for the Mozart AI onboarding paywall, each backed by a number from Adapty's State of Paywalls 2026, plus a clickable rebuild of the paywall and the close moment in Mozart's own design (Today / Proposed switch, numbered report pins).

| # | Idea | Report anchor | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Open the onboarding paywall on 1 Year | 2.4, table I: 90% keep a pre-selected weekly plan, 46% a pre-selected annual one; conversion holds | Report finding (no range in 5.3) |
| 2 | Ask once more when they close (1 Year with a 7-day free trial, then the Welcome Bonus) | 4.5: 4% of apps do it; converts at 0.88× the main paywall; beats it in 45% of apps. 2.6: 7-day trials convert better on annual | ARPU +10–15%, based on Adapty data |
| 3 | Put your 4.3 stars on the paywall | 3.1: 27% of top paywalls show social proof; 5.3 social proof on the paywall | CR +10–30%, observed in winning A/B tests |
| 4 | Hold the close button for 3 seconds | 3.7: 22% of apps delay; 3–5 s is the most common delay; 5.3 delay before the close button | CR +8–15%, observed in winning A/B tests |

**Benchmark slice:** all categories (Mozart's App Store category is Music, which the report does not cover), US (its largest App Store market by revenue). App Store data, Oct 2025–Sep 2026.

**The report:** [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=scate-ai)

**Grounding:** Prices (€5.99 / €49.99 / €79.99) and every screen come from Mozart's live onboarding paywall, recorded on a European storefront in October 2026. The 4.3 rating and 32K ratings come from the US App Store listing. The “#1 AI Music App” laurels are Mozart's own splash art. Mozart has no free trial today; idea 2 needs an introductory offer on the annual product. The light mode is our approximation; the app ships dark.

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Scate AI.

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
