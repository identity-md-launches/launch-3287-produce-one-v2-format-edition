OPEN INTEREST - EDITION, 17 November 2026 (format v2)

LEAD

Attackers turned Optimizely's content network into a crypto clipper on 16 November 2026.

The malicious script reached visitors of 178 organisations, including Ledger, the BBC and Zoom. The haul in crypto was small, and the access route is still unexplained.

Scott Helme's Report URI team found that attackers wrote malicious code into the Project JavaScript field of customer projects on Optimizely Web [https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/]. The code was still served from cdn.optimizely.com, so a trusted domain carried it. Report URI says the CDN "served exactly what it was given" and was not cache-poisoned [https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/].

Report URI counted 188 infected snippets belonging to 178 organisations, from a sweep of 1,611 scripts [https://www.bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites/]. BleepingComputer confirmed the script loaded or tried to load on CNN, Fox News, BBC, Salesforce, GitLab and Zoom [https://www.bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites/]. Ledger's site was also affected, and its snippet was cleaned at about 20:41 UTC on 16 November [https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/].

The payload did four things. It swapped crypto addresses, skimmed payment cards, collected cookies and screenshots, and delivered the Coruna and DarkSword iOS exploit kits [https://www.bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites/]. Report URI timed the first injection at 04:21 UTC and the first clipper build at 08:10 UTC [https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/].

Known crypto losses are modest. Report URI counted about $7,040 received by the attacker's wallets at 19:25 UTC on 16 November, and about $7,150 in its later update [https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/]. BleepingComputer notes that some of those wallets were active before the attack, so the figure for new theft is uncertain [https://www.bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites/]. Card and cookie theft has no public tally.

Optimizely told BleepingComputer it blocked the vulnerable path, removed the injected code, revoked tokens and reset affected accounts [https://www.bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites/]. Report URI's update says all infected files were clean by 23:11 UTC and that the company acknowledged the incident on its status page [https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/]. Salesforce said it disabled Optimizely scripts across its instances as a precaution [https://www.bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites/].

Two questions remain open. Nobody has said how the attacker gained write access, and nobody has said how long the flaw existed. Report URI says the first question belongs to Optimizely [https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/].

The crypto lesson is narrow. A clipper that rewrites a pasted address works on any site that loads third-party script, including sites users trust. Report URI found that of the hosts it crawled, 24 blocked the payload with a Content Security Policy, and 68 had no policy at all [https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/].

NEWS

[NEWS] Lighter lost about $10.4 million to reused signing nonces.

The perpetuals exchange paused withdrawals on 16 November 2026 after an attacker drained funds through a trader's API key. Lighter's postmortem says the trader's custom signing software reused nonces, which let the attacker compute private keys from public signatures; Lighter says its protocol and smart contracts were not affected [https://cointelegraph.com/news/lighter-dex-pauses-withdrawals-10m-exploit]. Bitquery traced 10,393,057 USDC leaving Lighter's Ethereum contract at 10:11 UTC and reported most of it swapped into ETH through CoW Swap [https://cointelegraph.com/news/lighter-dex-pauses-withdrawals-10m-exploit]. Lighter's Security Council recovered about $5 million in USDC, and withdrawals have resumed [https://cointelegraph.com/news/lighter-dex-pauses-withdrawals-10m-exploit]. Some outlets report losses up to $15.5 million, which Lighter has not confirmed [https://www.altcoinbuzz.io/lighter-blames-leaked-api-key-for-reported-15-5m-drain]. Lighter's first public statement on the incident is on X [https://x.com/Lighter_xyz/status/2122311006604984497].

[NEWS] A federal judge says the CFTC likely overstepped on stock perpetuals.

The CFTC announced on 3 November 2026 that perpetual futures on individual stocks may trade on registered exchanges, and Kalshi filed 54 such contracts the next day [https://www.techtimes.com/articles/330893/20261117/kalshi-stock-trading-plan-surfaces-judge-says-cftc-likely-overstepped-stock-perps.htm]. The Capital Markets Alliance, whose members include Cboe and Citadel Securities, sued, arguing perpetuals are security-based swaps under SEC jurisdiction [https://www.techtimes.com/articles/330893/20261117/kalshi-stock-trading-plan-surfaces-judge-says-cftc-likely-overstepped-stock-perps.htm]. On 3 November the court denied a temporary restraining order for lack of irreparable harm, but found the plaintiff likely to succeed on its claim that the CFTC exceeded its authority [https://www.lowenstein.com/news-insights/newsletters/crypto-brief-november-12-2026]. The SEC filed a brief backing the CFTC on 9 November [https://www.lowenstein.com/news-insights/newsletters/crypto-brief-november-12-2026]. TechTimes reports no ruling on the preliminary injunction had been issued as of 16 November [https://www.techtimes.com/articles/330893/20261117/kalshi-stock-trading-plan-surfaces-judge-says-cftc-likely-overstepped-stock-perps.htm].

[NEWS] The Supreme Court declines Custodia Bank's Federal Reserve account case.

On 16 November 2026 the U.S. Supreme Court declined to review Custodia Bank's challenge over access to a Federal Reserve master account, according to The Crypto Basic [https://thecryptobasic.com/2026/11/16/tcb-daily-edition-what-happened-in-crypto-on-november-16-2026/]. The denial leaves in place the lower-court ruling that the Fed has discretion over such accounts [https://thecryptobasic.com/2026/11/16/tcb-daily-edition-what-happened-in-crypto-on-november-16-2026/]. Custodia, a crypto-focused bank, therefore stays without direct access to Fed payment rails. This item rests on secondary reporting; the Court's order list was not retrieved.

TECH

[TECH] Solana drops the "mainnet beta" label and calls the network 1.0.

The Solana Foundation announced on 16 November 2026 that the network now has a protocol version, 1.0, separate from validator client versions [https://www.theblock.co/news/ecosystems/2026-11-16-solana-drops-mainnet-beta-label-and-adopts-protocol-version-1-0-440885]. The beta label had stood since launch on 16 March 2020 [https://decrypt.co/383322/solana-drops-mainnet-beta-after-six-years]. Agave and Firedancer keep their own release numbers, and users need take no action [https://www.theblock.co/news/ecosystems/2026-11-16-solana-drops-mainnet-beta-label-and-adopts-protocol-version-1-0-440885]. The Foundation warns that a protocol version does not switch on every improvement at once, and The Block reports Alpenglow went live on mainnet in October 2026 [https://www.theblock.co/news/ecosystems/2026-11-16-solana-drops-mainnet-beta-label-and-adopts-protocol-version-1-0-440885].

[TECH] Proprietary AMMs reach 5 to 10 percent of Ethereum swap volume.

A post on the Ethereum Research forum by mikeneuder dated 12 November 2026 estimates that proprietary market makers handle 5 to 10 percent of mainnet swap volume [https://ethresear.ch/t/ethereum-propamms-today-and-tomorrow/26129]. For 14 to 20 September 2026 it counts $280 million on Fermi and $178 million on Metric, against $6.0 billion on Uniswap [https://ethresear.ch/t/ethereum-propamms-today-and-tomorrow/26129]. The post says these venues depend on block builders for ordering, and that in a 30-day Titan sample builders without maker deals carried almost none of roughly 87,000 relevant fills [https://ethresear.ch/t/ethereum-propamms-today-and-tomorrow/26129]. The authors list builder concentration and uneven execution as risks, and leave open how much liquidity will migrate [https://ethresear.ch/t/ethereum-propamms-today-and-tomorrow/26129].

CULTURE

[CULTURE] Molly White finds the industry's election win rate rests on safe bets.

Writing on 13 November 2026, Molly White counts about $250 million spent by crypto and AI super PACs in the midterms, roughly $170 million by crypto groups [https://www.citationneeded.news/crypto-ai-lost-the-midterms/]. Fairshake went 74 for 74 where its candidates were clear favorites and 10 for 18 in competitive races, by her count [https://www.citationneeded.news/crypto-ai-lost-the-midterms/]. Fairshake's spokesperson cited a 92 percent success rate, 86 of 93 races, which White says counts races rather than dollars [https://www.citationneeded.news/crypto-ai-lost-the-midterms/]. Coinbase's Kara Calvert said the election "wasn't a referendum on crypto" [https://www.citationneeded.news/crypto-ai-lost-the-midterms/].

[CULTURE] Banks ask Treasury to regulate DeFi controllers like financial institutions.

In a letter dated 6 November 2026, the Bank Policy Institute asked FinCEN and OFAC to treat digital asset service providers, including those controlling DeFi arrangements, as financial institutions under the Bank Secrecy Act [https://bpi.com/bpi-letter-on-aml-cft-safeguards-in-the-digital-asset-ecosystem/]. The letter argues that "the same activity presenting the same risks merits the same regulation" [https://bpi.com/bpi-letter-on-aml-cft-safeguards-in-the-digital-asset-ecosystem/]. It also asks Treasury to seek legislation where its authority falls short, and cites FinCEN's withdrawal of three proposed digital asset rules [https://www.lowenstein.com/news-insights/newsletters/crypto-brief-november-12-2026]. No crypto trade group response was found.

READING LIST

1. Report URI's Optimizely timeline, with wallet addresses and CSP findings: https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/
2. Lighter's first statement on the incident, useful for comparing against the later postmortem: https://x.com/Lighter_xyz/status/2122311006604984497
3. The PropAMM post, for its numbers and its open questions: https://ethresear.ch/t/ethereum-propamms-today-and-tomorrow/26129
4. Molly White's midterms tally, which shows its counting method: https://www.citationneeded.news/crypto-ai-lost-the-midterms/
5. The SEC's fiscal 2026 enforcement results, 348 actions against 456 a year earlier: https://www.sec.gov/newsroom/press-releases/2026-113-sec-announces-enforcement-annual-results-fiscal-year-2026

METHOD

This edition swept search results, Report URI, BleepingComputer, Citation Needed, the Ethereum Research forum, Lowenstein's Crypto Brief and The Block, covering roughly 10 to 17 November 2026. The prior editions on the rehearsal page were checked; none led with these stories, and the FinCEN MEXC order was skipped because rehearsal 08 already covered it. Items cut: the Mercado Bitcoin loss and the MORE Markets exploit, which rested on one search summary each, and price and treasury-purchase items, which are not events. Secondary sources carry these claims: the Custodia denial (The Crypto Basic), the stock perpetuals case (TechTimes and Lowenstein), Lighter's postmortem and Bitquery tracing (Cointelegraph), and Solana 1.0 (The Block and Decrypt; the Foundation's own post returned an error). Lighter's loss ranges from $10.4 million to $15.5 million across outlets, and the primary figure is unconfirmed. Several pages returned errors and were not read directly.
