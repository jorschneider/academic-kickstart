# Forecasting Model: timing, eligibility, and falsifiable predictions

Companion to [`README.md`](README.md). This file does three things the main report only gestures at: it derives an **empirical timing model** from the purge record, computes the **age-eligibility arithmetic** that constrains every projection, and commits to a register of **dated, falsifiable predictions** with resolution criteria.

---

## 1. The disappearance-to-announcement lag

### 1.1 Why this matters

In the PLA, the state almost never announces an investigation when it begins. The observable sequence is:

**(1) officer stops appearing** → (2) *the post is quietly reassigned or left acting* → (3) first official action (investigation announcement, NPC seat recall/termination, or removal from post) → (4) party/military expulsion → (5) prosecution → (6) sentence.

Steps 1–2 are visible to open sources months before step 3. If the lag between them is regular, disappearance becomes a **leading indicator with a computable horizon** — which converts "these officers have vanished" into "expect confirmation in month X."

### 1.2 The data

Lag measured from the last credible public appearance (or the removal-from-duty signal) to the **first official action** of any kind. Dates from [`purge-tracker.md`](purge-tracker.md).

| Officer | Last seen / removed from duty | First official action | Lag (months) |
|---|---|---|---|
| Li Shangfu | ~29 Aug 2023 (last public appearance) | 24 Oct 2023 (removed as Defense Minister) | ~2 |
| Li Yuchao | ~Jul 2023 (replaced as RF commander) | 29 Dec 2023 (NPC seat terminated) | ~5 |
| Miao Hua | (28 Nov 2024 suspension *was* the official action) | 30 Apr 2025 (NPC seat) | 5 |
| He Weidong | 11 Mar 2025 (NPC closing session) | 17 Oct 2025 (expulsion) | ~7 |
| Lin Xiangyang | ~Mar 2025 | 17 Oct 2025 (expulsion) | ~7 |
| Wang Houbin | ~Mar–Apr 2025 (reported detained) | 17 Oct 2025 (expulsion) | ~6–7 |
| Qin Shutong | Dec 2024 (replaced as Army PC) | 17 Oct 2025 (expulsion) | ~10 |
| Wang Chunning | Jul 2025 (replaced by acting commander) | 25 Jul 2025 (NPC recall) | ~0–1 |
| Gao Daguang | ~mid-2025 | 21 Jul 2025 (NPC recall) | ~2 |
| Zhang Hongbing | ~2025 | 30 Oct 2025 (recall decision) | ~4 |
| Xu Xueqiang | ~13 Dec 2025 (reported taken away) | 26 Jun 2026 (NPC seat) | ~6.5 |
| Guo Puxiao | ~Nov–Dec 2025 (absent from 22 Dec ceremony) | 26 Jun 2026 (NPC seat) | ~7 |
| Zhang Youxia | 22 Dec 2025 (announced promotion orders) | 24 Jan 2026 (investigation announced) | ~1 |
| Liu Zhenli | 22 Dec 2025 (attended ceremony) | 24 Jan 2026 (investigation announced) | ~1 |
| Zhong Shaojun | ~Oct 2025 (removed as NDU political commissar) | 28 Aug 2026 (NPC seat) | ~10 |
| Li Qiaoming | Dec 2024 (dismissed as Army commander) | 26 Feb 2026 (NPC seat) | ~14 |

**Central tendency: median ≈ 6–7 months; interquartile range ≈ 2–10 months.**

A second, tighter lag governs what follows: **first official action → formal expulsion or removal ≈ 5–8 months** (Miao Hua: suspension Nov 2024 → expulsion Oct 2025, 11 months; Zhang Youxia/Liu Zhenli: investigation Jan 2026 → CMC removal Aug 2026, 7 months; Li Shangfu: removal Oct 2023 → expulsion Jun 2024, 8 months). And expulsion → sentencing runs longer: Li Shangfu and Wei Fenghe were expelled in June 2024 and sentenced in May 2026 — **~23 months**.

### 1.3 Two important qualifications

1. **Rank compresses the lag at the top.** Zhang Youxia and Liu Zhenli went from last public appearance to *announced investigation* in about one month — far faster than the median. Removing a sitting CMC vice chairman apparently could not be done quietly, so the regime front-ran the rumor mill. Conversely, mid-ranking officers (Li Qiaoming, 14 months) can be left in limbo indefinitely.
2. **The NPC Standing Committee calendar is the pacing mechanism.** Most terminations are announced at NPCSC sessions, which meet roughly **bimonthly in even months**. The 2026 sessions that carried military names: **late Feb (26th), late Apr, late Jun (26th), late Aug (28th)**. This quantizes the timing: an officer whose case matures in September waits for the **late-October** session.

### 1.4 Predicted confirmation windows for the officers currently missing

Applying a 6–11 month lag from each officer's disappearance, then rounding to the next NPCSC session. **These are model outputs, not claims about guilt** — an officer can vanish for illness, quiet retirement, or reassignment, and several of these will resolve that way.

| Officer | Vanished | Model window | Status vs. model |
|---|---|---|---|
| **Hu Zhongming** (Navy commander) | ~May 2025 | Nov 2025 – Apr 2026 | **OVERDUE by ~4–9 months** — see §1.5 |
| **Wang Qiang** (ex-Central TC commander) | ~Jul 2025 | Jan – Jun 2026 | **OVERDUE by ~2–7 months** |
| **Wu Yanan** (Southern TC) | ~Oct 2025 | Apr – Sep 2026 | In window; **due now** → watch late Oct 2026 |
| **Wang Haijiang** (Western TC) | ~Sep 2025 | Mar – Aug 2026 | In window; **due now** |
| **Huang Ming** (Northern TC) | ~Sep 2025 | Mar – Aug 2026 | In window; **due now** |
| **Zheng Xuan / Xu Deqing / He Ping** (theater PCs) | ~Sep–Oct 2025 | Mar – Sep 2026 | In window |
| **Fang Yongxiang** (CMC General Office) | ~Oct 2025 | Apr – Sep 2026 | In window |
| **Chang Dingqiu** (PLAAF commander) | ~Nov 2025 | May – Oct 2026 | In window (replacement gazetted Jul 2026 with no charge) |
| **Yu Qingjiang** (PLAAF deputy) | ~Oct 2025 | Apr – Sep 2026 | In window |
| **Chen Hui** (Army PC) — *disputed, see README §2.2* | ~Dec 2025 (if real) | Jun – Nov 2026 | In window |
| **Xu Xisheng** (Rocket Force PC) | ~Oct 2025 (sidelined) | Apr – Sep 2026 | In window |

**The model's sharpest claim: the late-October and late-December 2026 NPCSC sessions should carry a large batch of military names — plausibly the largest yet — drawn from the theater commanders and political commissars who vanished in the September–October 2025 sweep.** If those sessions pass with few or no military terminations, the model is wrong and the "September 2025 sweep" was something other than a purge (rotation, retirement, or a decision to handle it outside the NPC mechanism).

### 1.5 The Hu Zhongming anomaly

The Navy commander has been missing longest relative to the model — roughly 16 months with no official action of any kind, and no announced successor, while a vice admiral runs the service in his place. Three readings, in rough order of plausibility:

1. **Sensitivity delay.** Removing a sitting service chief during a carrier commissioning year (the *Fujian* entered service November 2025) may be judged too damaging to announce; the regime is content to let him fade.
2. **Not a purge at all.** Illness or quiet retirement would produce the same observable pattern — no charge, no successor announced, duties devolved to the chief of staff. Note that no émigré report of his detention has ever been corroborated.
3. **Case still building**, with the announcement bundled into a larger batch (the model would then expect him in the same October/December 2026 window as the theater commanders).

This is the single most informative unresolved case in the dataset: it discriminates between "everything that looks like a purge is a purge" and "the PLA also has ordinary, unannounced attrition that OSINT systematically misreads as purging." **I flag it as the main risk to this report's Tier-1 framing.**

---

## 2. Age-eligibility arithmetic

### 2.1 The constraint

PLA senior appointments are age-gated. Working norms (bent under Xi but never abolished): theater-leader-grade billets are normally vacated by ~65; CMC members have entered as late as 67; only exceptionally trusted figures serve past 70 as vice chairmen (Zhang Youxia was retained at 72 in 2022 — a decision that ended in his purge). A useful rule: **to be seated at a Party Congress, an officer normally needs to be ~65 or under; to serve a full five-year term, ~62 or under.**

### 2.2 The table

Ages at each relevant milestone. **Bold** = inside the normal CMC-entry window (≤67) at that congress.

| Officer | Born | 21st Cong. 2027 | 2031 | 22nd Cong. 2032 | 2036 | 23rd Cong. 2037 | 2041 |
|---|---|---|---|---|---|---|---|
| Zhang Shengmin | 1958 | **69**\* | 73 | 74 | 78 | 79 | 83 |
| Dong Jun | 1961 | **66** | 70 | 71 | 75 | 76 | 80 |
| Hao Weizhong (ASF) | 1961 | **66** | 70 | 71 | 75 | 76 | 80 |
| Wu Yanan | 1962 | **65** | 69 | 70 | 74 | 75 | 79 |
| Xu Qiling | 1962 | **65** | 69 | 70 | 74 | 75 | 79 |
| Yang Zhibin | 1963 | **64** | 68 | 69 | 73 | 74 | 78 |
| Han Shengyan | 1963 | **64** | 68 | 69 | 73 | 74 | 78 |
| Hu Zhongming | 1964 | **63** | 67 | 68 | 72 | 73 | 77 |
| **Zhang Shuguang** | 1964 | **63** | **67** | 68 | 72 | 73 | 77 |
| Xu Xisheng | 1964 | **63** | **67** | 68 | 72 | 73 | 77 |
| Kong Jun | 1964 | **63** | **67** | 68 | 72 | 73 | 77 |
| **Wang Gang** | 1965 | **62** | **66** | **67** | 71 | 72 | 76 |
| Wu Junbao | 1965 | **62** | **66** | **67** | 71 | 72 | 76 |
| Bi Yi (ISF) | 1965 | **62** | **66** | **67** | 71 | 72 | 76 |
| Mei Wen | 1965 | **62** | **66** | **67** | 71 | 72 | 76 |
| Cao Qingfeng | 1966 | **61** | **65** | **66** | 70 | 71 | 75 |
| Jing Jianfeng | 1966 | **61** | **65** | **66** | 70 | 71 | 75 |
| Zhang Like | 1967 | **60** | **64** | **65** | 69 | 70 | 74 |
| Wang Hongli | 1967 | **60** | **64** | **65** | 69 | 70 | 74 |
| **Huang Xucong** | 1968 | **59** | **63** | **64** | 68 | 69 | 73 |
| **Zhang Zheng** | 1969 | **58** | **62** | **63** | **67** | 68 | 72 |
| **Zhu Chuansheng** | 1970-04 | **57** | **61** | **62** | **66** | **67** | 71 |
| **Liu Zhe** | 1970 | **57** | **61** | **62** | **66** | **67** | 71 |
| **Dai Mingmeng** | 1971 | **56** | **60** | **61** | **65** | **66** | 70 |
| **Chen Zhiguo** | 1976 | **51** | **55** | **56** | **60** | **61** | **65** |

\* Zhang Shengmin is already past the normal ceiling; he holds his seat as the trusted exception, exactly as Zhang Youxia did.

### 2.3 What the arithmetic forces

- **The 21st Congress (2027) CMC must be built from the 1962–1970 cohort.** Almost everyone currently holding a theater or service command qualifies — but only just, and most of them can serve only one term.
- **The 22nd Congress (2032) CMC must be built from the 1967–1975 cohort.** Look at who that is: Zhang Like, Wang Hongli, Huang Xucong, Zhang Zheng, Zhu Chuansheng, Liu Zhe, Dai Mingmeng — *precisely the caretaker-and-riser set now running services and departments in acting capacities*. The men filling today's vacancies are not stopgaps; on the age math they are the 2032 leadership.
- **The 23rd Congress (2037) CMC must be built from the 1972–1980 cohort** — a generation almost entirely invisible in open sources today. Of every officer this study could name, **only Chen Zhiguo (b. 1976) sits comfortably inside that window.** That is not a finding about Chen Zhiguo's brilliance; it is a measure of how dark the pipeline is.
- **Three officers can plausibly span all three horizons:** Zhang Zheng (68 in 2037), Zhu Chuansheng (67), Dai Mingmeng (66) — each could take a CMC seat in 2032 and a vice-chairmanship in 2037 without breaking any norm. This is the structural reason the report ranks them where it does.

### 2.4 The counter-consideration

Xi has broken age norms when he wanted to (Zhang Youxia at 72), and the purge has already produced two-grade jumps (Han Shengyan: theater air-force commander → theater commander + full general in months; Zhang Zheng: staff billet → running a service). **Under continued attrition, the age table is a soft constraint on the downside and no constraint at all on the upside** — officers can arrive earlier than the table predicts, but rarely later.

---

## 3. Falsifiable predictions

Committing to these makes the report checkable. Each has a resolution date and a clear failure condition. Probabilities are my estimates, not derived from a formal model except where §1 applies.

### Near-term (resolve by mid-2027)

| # | Prediction | P | Resolves | Falsified if |
|---|---|---|---|---|
| 1 | The Oct and/or Dec 2026 NPCSC sessions terminate the seats of **three or more** PLA officers at theater-leader grade or above | 0.70 | Jan 2027 | Fewer than three such terminations |
| 2 | At least one of {Wu Yanan, Wang Haijiang, Huang Ming, Chen Hui, Chang Dingqiu} receives a formal official action | 0.75 | Jun 2027 | None of the five is officially actioned |
| 3 | **Zhang Zheng** is formally appointed PLA Navy commander and/or promoted to admiral | 0.55 | Dec 2027 | Another officer is named Navy commander |
| 4 | The CMC gains at least one new member (beyond Xi and Zhang Shengmin) before the 21st Congress convenes | 0.60 | 21st Congress | The CMC still has two members at the congress |
| 5 | **Dong Jun** receives a CMC seat and/or State Councilor rank | 0.40 | 21st Congress | He retires or is replaced without either |
| 6 | A permanent Rocket Force commander is gazetted | 0.50 | Dec 2027 | The post remains acting/vacant |
| 7 | The PLA Ground Force gets a gazetted commander | 0.55 | Dec 2027 | Still no named commander |
| 8 | At least one officer promoted to full general during 2024–2026 (Chen Hui, Yang Zhibin, Han Shengyan, Zhang Shuguang, Wang Gang) is purged or disappears | 0.45 | Dec 2028 | All five remain in good standing — note Chen Hui may already have resolved this |
| 9 | A new corruption case is announced involving the **naval equipment / shipbuilding** chain | 0.45 | Dec 2028 | No naval-equipment case surfaces |
| 10 | Further Rocket Force procurement cases are announced (following the Aug 2026 tip solicitation) | 0.65 | Dec 2027 | No new RF cases |

### Medium-term (the 21st Congress, ~autumn 2027)

| # | Prediction | P | Falsified if |
|---|---|---|---|
| 11 | The 21st Congress CMC contains at least one officer whose career is primarily in **discipline inspection** | 0.75 | No discipline-lineage member |
| 12 | At least one **Navy** officer sits on the 21st CMC | 0.65 | No naval member |
| 13 | **Zhang Shuguang** holds a CMC seat (member or vice chairman) | 0.55 | He does not |
| 14 | **Wang Gang** holds a CMC seat | 0.45 | He does not |
| 15 | At least one CMC vice-chairmanship goes to an officer born 1963 or later (a generational break) | 0.60 | Both VCs born before 1963 |
| 16 | Xi remains CMC chairman | 0.92 | He does not |
| 17 | No heir-apparent with a military portfolio is publicly designated | 0.70 | One is designated |

### Long-horizon (resolve 2032 / 2037)

| # | Prediction | P | Falsified if |
|---|---|---|---|
| 18 | At least one of {Zhang Zheng, Zhu Chuansheng, Dai Mingmeng, Liu Zhe} sits on the 22nd Congress CMC (2032) | 0.55 | None does |
| 19 | The 22nd CMC has a majority of members from Navy / Air Force / strategic-information forces (i.e., a non-ground-force majority) | 0.55 | Ground force retains the majority |
| 20 | **Chen Zhiguo** (b. 1976) reaches flag rank by end-2029 | 0.60 | He does not |
| 21 | At least one 2037-era CMC member is an officer not identifiable in open sources as of 2026 | 0.85 | Every member was publicly identifiable today |
| 22 | The PLA holds a full-general promotion ceremony elevating an officer born 1970 or later before end-2030 | 0.50 | No such promotion |

**Scoring note.** If these resolve at roughly their stated probabilities, the model is calibrated. The predictions most diagnostic of the report's core thesis are **#1, #2 (the timing model), #3 and #18 (the Zhang Zheng call), and #21 (the pipeline-opacity claim)**. If #1 and #2 both fail, §1's timing model is broken and the Tier-1 "vanished = purged" inference in the main report should be discounted heavily.

---

## 4. How to use this file

- To **test the report**, check the §3 register against events after each NPCSC session and each Party Congress.
- To **update the report**, re-run §1.4 with new disappearance dates; the model is a lookup, not a judgment.
- To **calibrate confidence in any individual name**, read §2.2 first: an officer outside the age window at a given congress cannot hold a seat regardless of how promising the résumé looks, and this constraint has a far better track record than any patronage read.
