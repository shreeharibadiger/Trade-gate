TRADE GATE — FUNDINGPIPS $5K 2-STEP PRO
========================================

Files:
- index.html: main app
- manifest.json: installable web app metadata
- sw.js: basic offline cache for HTTPS hosting

Features:
- Home dashboard for a $5,000 2-Step Pro evaluation
- 10-item XAUUSD pre-trade checklist and no-trade gate
- XAUUSD position-size estimate using entry, stop-loss, dollar risk, contract size and costs
- Closed-trade journal and estimated profitable-day counter
- Rules reference for evaluation and Master Account
- Phase settings, reward-cycle date estimate, local storage and JSON backup/restore

Defaults configured for this plan:
- Starting balance: $5,000
- Phase targets: 6% ($300) each, subject to the rules shown in your exact account dashboard
- Daily loss reference: 3% ($150) of the applicable daily baseline
- Maximum loss reference: 6% ($300), static floor $4,700
- Selected personal risk: $25 per trade (0.5%); personal daily stop defaults to $50; stop after two losses
- XAUUSD only; published evaluation metals leverage was listed as 1:30 in the prior rules reference; verify in your account

Use:
1. Open index.html in a browser for a standalone version.
2. For installable Android/PWA mode, host these files on HTTPS, open in Chrome and choose Install app / Add to Home screen.
3. Data is stored only in this browser's local storage. Export a JSON backup regularly.
4. This is an independent personal tool, not affiliated with FundingPips. It cannot read your live balance, execute trades or connect to the live news calendar.

IMPORTANT:
- The figures are a quick-reference based on the prior 2-Step Pro rules summary, not a guarantee of current terms. Verify exact limits, news restrictions, server time, leverage, Master Account rules and reward eligibility in FundingPips' official dashboard before trading.
- Daily loss calculations may use the higher of opening balance or opening equity and include floating losses.
- Lot size is an estimate; verify XAUUSD contract size, tick value, volume step, commission, spread and slippage in MT5.
- The app is not financial advice and cannot prevent losses or rule breaches.
