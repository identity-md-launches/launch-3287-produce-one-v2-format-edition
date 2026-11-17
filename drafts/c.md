OPEN INTEREST: EDITION, 17 November 2026 (format v2)

LEAD
A hijacked analytics vendor served wallet-swapping malware to 178 organizations.

Researchers found crypto-stealing code inside Optimizely scripts on sites including Zoom, CNN and Salesforce on 16 November 2026. The vendor says an attacker entered through its account signup flow.

Security researcher Scott Helme's team reported the compromise on 16 November 2026. They analyzed 1,611 Optimizely scripts and found 188 infected files belonging to 178 organizations [https://bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites]. Affected sites included Zoom, CNN, Fox News, BBC, Salesforce and GitLab, according to the same report.

The injected code loaded a script called track.js from an attacker domain. BleepingComputer reports it tried to replace cryptocurrency wallet addresses, capture card numbers and security codes, collect cookies and screenshots, and deliver iOS exploit kits named Coruna and DarkSword [https://bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites]. Ledger was among the affected brands, per Bitcoin.com [https://news.bitcoin.com/security/optimizely-hack-ledger-178-brands-crypto-address-swap/].

Optimizely said an unauthorized party "exploited a vulnerability in the Experimentation account signup flow" to add malicious JavaScript to some customer projects. It blocked the vulnerable path, removed the code, ended sessions, revoked tokens and blocked delivery through Cloudflare [https://bleepingcomputer.com/news/security/optimizely-supply-chain-attack-delivers-malware-to-cnn-fox-news-bbc-salesforce-sites]. As of 21:52 UTC on 16 November 2026, one of the 188 files still held malicious code. Salesforce disabled Optimizely scripts across its preview and production instances.

The theft so far is small. Attacker wallets had received about $7,000 by the evening of 16 November 2026, according to Bitcoin.com [https://news.bitcoin.com/security/optimizely-hack-ledger-178-brands-crypto-address-swap/]. That figure counts only addresses researchers have identified. It cannot rule out other wallets.

The reach is the story. The attacker did not need to breach 178 companies. It breached one vendor whose script those companies load on every page view. A person who pasted a destination address from a trusted site could have sent funds to the attacker. Hardware wallet users who verify the address on the device screen are protected from this class of swap. Whether any user lost funds beyond the $7,000 is unanswered. Optimizely has not published a count of affected visitors.

NEWS

[NEWS] A federal judge acquits the Peraire-Bueno brothers in the $25 million Ethereum MEV case.
Judge Jessica Clarke of the Southern District of New York granted a judgment of acquittal on 16 November 2026 on wire fraud and two conspiracy counts. She found prosecutors had not shown a material misrepresentation, and described Ethereum as a "trustless, highly adversarial environment with no terms of use" [https://decrypt.co/383408/judge-acquits-mit-brothers-in-25m-ethereum-mev-case-ending-prosecution]. The first trial ended in a mistrial in November 2025, and this ruling closes the case without a second trial [https://www.theblock.co/news/regulation/2026-11-16-peraire-bueno-brothers-acquitted-ethereum-mev-wire-fraud-441425]. The ruling did not decide whether the conduct was unethical. We have not read the opinion; this item rests on press accounts.

[NEWS] The Supreme Court ends Custodia Bank's fight for a Fed master account.
The Court denied certiorari in docket 26-62 on 16 November 2026, without explanation [https://www.cryptotimes.io/2026/11/16/supreme-court-rejects-custodia-banks-bid-for-fed-master-account/]. The Tenth Circuit's 31 October 2025 ruling stands: regional Reserve Banks may reject even eligible applicants. Custodia applied to the Kansas City Fed in October 2020 and was rejected on 27 January 2023 [https://bitcoinmagazine.com/news/supreme-court-ends-custodia-fed-master]. A denial is not a Supreme Court holding on the question.

[NEWS] Binance says it finished replenishing assets taken in the 29 October 2026 breach.
Binance said on 13 November 2026 that it had completed replenishment of affected assets using corporate resources, and its 12 November proof-of-reserves snapshot covered 198 tokens. A 14 November update said withdrawals were restored on 87 networks [https://crypto.news/binance-he-yi-ai-pro-transfer-hack-claims/]. Chainalysis calls the roughly $6.4 billion theft the largest on record and attributes it to North Korean-linked hackers, per Cointelegraph; crypto.news puts the figure at $6.3 billion [https://cointelegraph.com/news/binance-hack-institutional-crypto-custody-falconx]. We could not reach Binance's own posts, so the figures rest on those outlets.

TECH

[TECH] Vitalik Buterin reverses and backs leanPCS as a faster route to quantum-safe Ethereum.
Buterin wrote on 16 November 2026 that he went "from thinking leanPCS is total bull to being a total bull" [https://en.cryptonomist.ch/2026/11/16/quantum-safe-ethereum-upgrade/]. The scheme uses polynomial commitments to compress quantum-safe signatures and proofs into compact proofs. He said post-quantum signatures grow from 65 bytes to 1 to 6 KB, and proofs to about 128 KB, which he called unsustainable on chain. A June ethresear.ch benchmark puts verification of one SPHINCS- signature near 150,000 gas, against roughly 3,000 for ECDSA on an earlier Buterin estimate. His thread is at [https://x.com/VitalikButerin/status/2122233780371083553]; we read it only through the Cryptonomist summary.

[TECH] Ethlabs proposes rebuilding the 2027 Hegotá fork around post-quantum security.
The group posted "pqai27" on Ethereum Magicians on 11 November 2026 [https://ethereum-magicians.org/t/an-ethlabs-view-on-post-quantum-and-post-ai-timelines-pqai27/30351]. It withdraws Quick Slots from Hegotá, pushing it to 2028, and keeps Frame Transactions (EIP-8141) as a priority. Full-capacity targets need EIP-8288 and EIP-8479. Core developers have not approved the timeline, and the Ethereum Foundation's own target is December 2029 [https://crypto.news/ethereum-quantum-security-2027-ethlabs-proposal/]. We did not open the primary post directly.

CULTURE

[CULTURE] Coin Center frames the MEV acquittal as a defeat for an "honest validator" theory.
Peter Van Valkenburgh, a masthead voice, called the ruling "excellent news." He argued that the government's theory would let prosecutors set conduct standards on an open network through wire fraud law [https://decrypt.co/383408/judge-acquits-mit-brothers-in-25m-ethereum-mev-case-ending-prosecution]. The judge wrote that the scheme may have frustrated the spirit of MEV-Boost without being fraud. The dispute over who defines acceptable validator behavior now returns to developers and forums.

[CULTURE] Online accusations against Binance co-CEO Yi He meet a 30-day account summary.
Users including Web3 Dao Ge and Crypto Suy alleged on social media that she withdrew funds on the day of the breach. On 16 November 2026 she posted a summary for 17 October to 16 November showing a change of negative $101.32 million. She said she had moved assets to a sub-account to test Binance AI Pro [https://crypto.news/binance-he-yi-ai-pro-transfer-hack-claims/]. The summary shows 30-day changes, not realized losses or external transfers, and the posts supplied no transaction records. The accusation is unproven and so is its rebuttal.

READING LIST
- https://vitalik.ca/ : Buterin's own writing, where the leanPCS argument may be expanded.
- https://ethereum-magicians.org/t/an-ethlabs-view-on-post-quantum-and-post-ai-timelines-pqai27/30351 : the full Ethlabs timeline proposal.
- https://blog.ethereum.org/2026/09/07/protocol-priorities : the Foundation's stated protocol priorities, the baseline Ethlabs argues against.
- https://coincenter.org/people/peter-van-valkenburgh/ : the Coin Center view on code, fraud and open networks.

METHOD
We swept press and web search results for 15 to 17 November 2026, covering roughly 48 hours, and fetched the style guide, the masthead CSV and the rehearsal page. The previous rehearsal leads were the Hoodi delay, stateless workers, signature-free authorization, the Binance withdrawal schedule, the FinCEN MEXC order and Chainalysis; none led this edition. Claims resting on secondary sources: the Optimizely details (BleepingComputer, Bitcoin.com), the Binance figures (Cointelegraph, crypto.news), the acquittal and Custodia items (Decrypt, The Block, Crypto Times, Bitcoin Magazine), and both TECH items, whose primary posts we did not read directly. We cut a reported MSCI decision on Strategy and the nominations for the SEC and CFTC because the source page returned an error and we could not verify them. We cut a Trezor shipping-partner breach for lack of a fetched source. Two items cited above were found only through search summaries, and the CryptoQuant Binance outflow figures were left out because the source says their link to the breach is unclear.
