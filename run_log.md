# Run log

## 2026-09-24 — Cycle 16, checkpoint 1 (sources_refresh)
- Started cycle 16 (cycle 15 completed all 17 batches).
- Processed 3 pending flags: IXL Learning APM (unavailable), Google APM University Grad (good -> liked), Disney AFRP Financial Analyst (bad_link -> fixed to stable program page).
- LINK UPGRADE: cleared the crisis-era backlog down to 0 unverified/bad_link postings (verified 9 via WebSearch corroboration since direct WebFetch to career-site domains is blocked by this environment's network policy; fixed 1 bad link: Disney AFRP -> disneycareers.com/en/accounting-finance-rotation-program; replaced 1 stale Delaware North job-ID link with a confirmed-live TeamWork Online listing for the same Boston Bruins role).
- NOTE: this environment's network egress policy blocks WebFetch to company/ATS career domains (atlassian.com, google.com, jobs.lever.co, boards.greenhouse.io, disneycareers.com, etc. all returned EGRESS_BLOCKED); only github.com/raw.githubusercontent.com and the WebSearch backend are reachable. Substituted targeted WebSearch as the verification method going forward, and leaned on GitHub tracker data (authoritative by construction) for new postings to minimize reliance on blocked WebFetch.

## 2026-09-24 — Cycle 16, checkpoint 2 (apm_rotational_tech)
- Added 13 new APM postings via tracker_cache (GitHub trackers): Globus Medical, Owens & Minor, Red Ventures (x2), PlanetArt, IDeaS, Kyndryl, L3Harris, Lowe's, Stanley Black & Decker, Hard Rock Digital, Solace Health, Alto-Shaam. All link_verified=true (authoritative ATS source).
- Existing Roblox/Disney/Databricks/Meta/Visa/Google APM postings already tracked and current, no changes needed.

## 2026-09-24 — Cycle 16, checkpoint 3 (product_management) — final for this run
- Added 25 new product_management postings via tracker_cache: GlobalFoundries, Cisco, Uncountable, Micron, Workday, Amazon (2027 ALA), NXP, TikTok (x6 distinct PM Graduate roles), CSI, EBSCO, Procter & Gamble, Tesla, FourKites, Aptiv, Halma, FieldPulse, FIS, Ernst & Young, Harper Group.
- Skipped Figma "Early Career APM (2026)" greenhouse link — title suggested a stale/redirected posting ("Back to jobs"), could not confirm live, so left out per verification rules.
- Top picks recomputed and appended to top_picks_history (final checkpoint of this run).
- Budget of 3 batches for this run reached (sources_refresh, apm_rotational_tech, product_management). Remaining batches this cycle: strategy_bizops, consulting, corporate_rotational, quant_trading, pe_investing, venture_capital, entertainment, energy, financial_services, space, sports, aviation, alumni_outreach, supplemental_search_and_cleanup — next run resumes from strategy_bizops.
