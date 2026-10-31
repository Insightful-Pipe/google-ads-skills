# InsightfulPipe Skills for Google Ads

**36 free Claude skills for Google Ads: account audits, search term mining, negative keywords, Quality Score, Performance Max, bid strategy, budgets, pacing and reports. Changes only after you confirm.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills/google-ads); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/google-ads-skills
/plugin install insightfulpipe-google-ads@insightfulpipe-google-ads
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/google-ads-skills
```

Add `--skill google-ads-account-audit` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (36)

| Skill | What it does | |
|---|---|---|
| [Ad Copy Performance Ranker](skills/ad-copy-performance-ranker/) | Ranks Google Ads responsive search ads and each headline and description by clicks and conversions, with head-to-heads per ad group and an ad strength reality check. | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/ad-copy-performance-ranker) |
| [AI Max for Search Reviewer](skills/ai-max-search-reviewer/) | Decides whether a Google Ads Search campaign should turn on AI Max, then reviews it by match source, added search terms, landing pages and generated headlines, and… |  |
| [Bid Strategy Auditor](skills/bid-strategy-auditor/) | Audits Google Ads Smart Bidding per campaign and sets target CPA or ROAS, value-based and profit bidding, data exclusions and seasonality adjustments. | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/bid-strategy-auditor) |
| [Budget Allocation Optimizer](skills/budget-allocation-optimizer/) | Moves Google Ads budget between campaigns for more conversions from the same total, using marginal CPA, budget simulations and impression share lost to budget. | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/budget-allocation-optimizer) |
| [Competitor Keyword Campaign Planner](skills/competitor-keyword-campaign-planner/) | Plans a Google Ads competitor campaign on rival brand names, rating each rival go, test or skip and drafting paused ad groups, negatives, comparison ads without rival… |  |
| [Display Video Demand Gen Auditor](skills/display-video-demand-gen-auditor/) | Audits running Google Ads Display, YouTube and Demand Gen campaigns, builds a paste-ready placement exclusion list from spend and clicks, reports video view rates and… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/display-video-demand-gen-auditor) |
| [GAQL Query Builder](skills/gaql-report-builder/) | Writes and fixes GAQL (Google Ads Query Language) queries from a plain reporting question, runs them read-only when Google Ads is connected, and adds API, Google Ads… |  |
| [Geo Performance Optimizer](skills/geo-performance-optimizer/) | Finds which Google Ads locations, devices and hours waste or earn money, grades each slice against its own campaign CPA and picks the lever the bid strategy actually… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/geo-performance-optimizer) |
| [Google Ad Grants Manager](skills/google-ad-grants-manager/) | Checks a nonprofit's Google Ad Grants account against every compliance rule, plans keyword pauses to get back over the 5% CTR line and builds a plan to spend more of… |  |
| [Google Ads Account Audit](skills/google-ads-account-audit/) | Runs a full Google Ads account audit across tracking, wasted spend, structure, Quality Score, ads, assets, bidding, settings and change history, scores eight areas and… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/google-ads-account-audit) |
| [Google Ads Account Restructure Planner](skills/google-ads-account-restructure-planner/) | Plans a Google Ads restructure that merges or splits Search campaigns so each clears its bid strategy volume, keeps brand apart and writes a week-by-week migration with… |  |
| [Google Ads Audience Analyzer](skills/google-ads-audience-analyzer/) | Analyzes Google Ads audience segments, remarketing lists, Customer Match and age, gender, income and parental status against each campaign, after a personalized ads… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/google-ads-audience-analyzer) |
| [Google Ads Bulk Ad and URL Updater](skills/google-ads-bulk-updater/) | Finds and replaces a price, offer, year, phone number, final URL or tracking template everywhere in a Google Ads account, paused items included, checks lengths, policy… |  |
| [Google Ads Campaign Builder](skills/google-ads-campaign-builder/) | Builds a Google Ads Search campaign from a short brief with a launch checklist, keywords, negatives, ads and paused payloads, plus keyword budget forecasts and Smart… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/google-ads-campaign-builder) |
| [Google Ads Click Fraud Check](skills/google-ads-click-fraud-check/) | Checks a Google Ads account for click fraud, reading invalid clicks first, then testing search partner, placement, off-area, night and device clicks against GA4… |  |
| [Google Ads Delivery Troubleshooter](skills/google-ads-delivery-troubleshooter/) | Finds why Google Ads campaigns, keywords or ads are not showing or not spending, reading status reasons, billing, policy, blocking negatives, settings and lost share… |  |
| [Google Ads Disapproval and Suspension Fixer](skills/google-ads-disapproval-suspension-fixer/) | Fixes Google Ads disapproved and limited ads, keywords and assets with plain policy reasons and compliant rewrites, and drafts proof lists and appeals for suspensions… |  |
| [Google Ads Extensions and Assets Auditor](skills/google-ads-assets-auditor/) | Audits every Google Ads asset or extension by campaign, from sitelinks, callouts and snippets to call, price and image assets, flags gaps, override traps, disapproved… |  |
| [Google Ads Hacked Account Check and Recovery](skills/google-ads-hacked-account-recovery/) | Checks a Google Ads account for takeover signs such as unknown users, manager links, new campaigns, edited URLs, spend spikes and billing changes, then sets out the… |  |
| [Google Ads Recommendations Reviewer](skills/google-ads-recommendations-reviewer/) | Reviews open Google Ads recommendations with an accept, adapt or dismiss verdict tested on the account's own numbers, plus auto-apply and asset automation settings. |  |
| [Google Ads Scripts and Automated Rules Writer](skills/google-ads-scripts-rules-writer/) | Writes, explains and fixes Google Ads scripts and automated rules for budget caps, broken URL checks, zero-conversion keywords, search terms to Sheets and spend jump… |  |
| [Google Ads Weekly Brief](skills/google-ads-weekly-brief/) | Writes the weekly Google Ads brief for a client, boss or team as an email, Slack post or slides, and reviews 90 days of change history for edits that helped or hurt. | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/google-ads-weekly-brief) |
| [Google App Campaigns Planner and Reviewer](skills/google-app-campaigns-manager/) | Plans and reviews Google App campaigns (UAC) for installs, in-app actions, value or pre-registration, checking budget and event volume, writing assets from the store… |  |
| [Google Shopping and Retail PMax Review](skills/google-shopping-retail-pmax-review/) | Reviews Google Shopping and retail Performance Max structure product by product against target, splits unserved products into not eligible, not targeted or outbid, and… |  |
| [Impression Share Analyst](skills/impression-share-analyst/) | Analyzes Google Ads search impression share lost to budget or rank, with a 12-week trend, top of page detail, Auction Insights exports and a weekly brand defense… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/impression-share-analyst) |
| [Keyword Performance Analyzer](skills/keyword-performance-analyzer/) | Analyzes Google Ads keywords into stars, bleeders and Quality Score victims, checking CPA or ROAS, match types, Migrate to Exact, duplicates, cannibalisation, low… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/keyword-performance-analyzer) |
| [Month End Report Generator](skills/month-end-report-generator/) | Writes the month-end Google Ads report against last month, last year and goals, with a graded scorecard, campaign tiers, changes that worked and next month's plan, plus… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/month-end-report-generator) |
| [Negative Keyword Implementer](skills/negative-keyword-implementer/) | Adds Google Ads negative keywords safely, checking existing negatives for conflicts with live keywords, building new ones from search terms, rolling lists to campaigns… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/negative-keyword-implementer) |
| [PMax Asset Group Analyzer](skills/pmax-asset-group-analyzer/) | Reviews Google Ads Performance Max campaigns by asset group, asset, audience signal, search term and channel split, and drafts a first PMax campaign when none exists. | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/pmax-asset-group-analyzer) |
| [Quality Score Fixer](skills/quality-score-fixer/) | Diagnoses low Google Ads Quality Score by expected CTR, ad relevance and landing page experience, then ranks fixes across keyword to ad match, ad strength, pinned… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/quality-score-fixer) |
| [Rsa Ad Copy Writer](skills/rsa-ad-copy-writer/) | Writes Google Ads responsive search ad headlines and descriptions from converting keywords and the landing page, plus sitelinks, callouts, keyword insertion… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/rsa-ad-copy-writer) |
| [Scaling Roadmap Builder](skills/scaling-roadmap-builder/) | Plans how to scale Google Ads spend in phases, checking readiness, marginal CPA headroom and new keywords, with daily budgets and pause triggers. | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/scaling-roadmap-builder) |
| [Search Term Gold Miner](skills/search-term-gold-miner/) | Mines Google Ads search terms into gold, garbage and grey zone with n-grams and returns safe negatives, exact keywords to promote and keyword ideas. | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/search-term-gold-miner) |
| [Shopping Feed Optimizer](skills/shopping-feed-optimizer/) | Audits product feeds for Google Shopping, Merchant Center and Meta Catalog from an export, scoring attributes, GTINs, titles, images, prices and custom labels. | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/shopping-feed-optimizer) |
| [Spend Pacing Monitor](skills/spend-pacing-monitor/) | Checks Google Ads month-to-date spend pacing, projects where the month will land against a target or budget ceiling, flags capped or stopped campaigns and drafts… | [Page](https://insightfulpipe.com/marketing-claude-skills/google-ads/spend-pacing-monitor) |
| [YouTube, Demand Gen and Display Campaign Builder](skills/youtube-demand-gen-campaign-builder/) | Plans a Google Ads YouTube, Demand Gen or Display campaign from a goal and budget, choosing bidding, audiences, videos by retention and exclusions, and checking asset… |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
