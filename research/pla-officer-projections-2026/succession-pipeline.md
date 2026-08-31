# The Succession Pipeline: who is below the top, and why we mostly cannot see them

Companion to [`README.md`](README.md) §4 and §5.3. The main report projects the 2031 and 2036 leadership from officers already visible at theater and service level. The 2041 leadership is a different problem: those officers are today at brigade, division and corps level, a layer the PLA stopped publishing around 2021. This file records what could be recovered about them, by what method, and — equally important — measures the size of the hole.

---

## 1. Method: inverting the question

Asking "who commands the 78th Group Army?" fails, because the PLA no longer says. The technique that worked inverts it: **ask which PLA-affiliated people of a given birth year the open record knows about at all**, by intersecting Chinese Wikipedia's birth-year categories with military affiliation through the MediaWiki search API, then batch-fetching the resulting biographies.

This has two virtues. It is exhaustive over the Chinese-language open record rather than dependent on which unit pages happen to be current. And because the returned set can be counted, **it measures the collection gap instead of merely suffering from it.**

### The counts

PLA-affiliated persons in the open record, by birth year:

| Birth year | Hits with PLA affiliation | In a command/staff billet | In a **corps-grade or higher** billet |
|---|---|---|---|
| 1966 | ~12 | 9 | **8** |
| 1967 | 28 | 12 | 5 |
| 1968 | 50 | 14 | 6 |
| 1969 | 34 | 13 | 3 |
| 1970 | 31 | 11 | 3 |
| 1971 | 21 | 3 | 1 |
| 1972 | 19 | 3 | **1** |
| 1973 | 20 | 5 | 1 |
| 1974 | 15 | 3 | **0** |
| 1975 | 15 | 4 | 0 |
| 1976 | 12 | 3 | 0 |
| 1977 | 23 | 6 | 0 |
| 1978 | 19 | 2 | 0 |
| 1979 | 19 | 6 | 1 |
| 1980 | 20 | 0 | 0 |

**The cliff falls between 1972 and 1974.** Below 1973, the open record contains essentially nobody holding a command billet above brigade.

---

## 2. The leading edge: officers born 1970 or later

### The three that matter

**Gu Zhong (顾中), b. 1972 — Commander, 72nd Group Army.**
Appointed December 2022; promoted major general in June 2019 at roughly 47, which is exceptionally young. Previously deputy chief of staff of the Eastern Theater Command. **He is the only officer born 1972 or later confirmed in a corps-leader command billet anywhere in the PLA.** The 72nd Group Army, garrisoned at Huzhou in Zhejiang, is the Eastern Theater's principal amphibious-capable formation — the corps that would carry a Taiwan landing. If any single name belongs in a 2041 projection, it is this one, and it was not in the first draft of this report.

**Zhu Chuansheng (祝传生), b. April 1970 — presiding over the CMC Joint Staff Department.**
The most successful career in the cohort and the model path: soldier → company commander in the 121st Division → division commander (2012) → 14th Group Army deputy commander (2016) → **Marine Corps deputy commander (2017), taking navy rank** → parade formation commander at the 2019 National Day parade → **Marine Corps commander (Dec 2021 – Mar 2025)** → Eastern Theater deputy commander and theater army commander, with promotion to lieutenant general (Mar 2025) → deputy chief of the Joint Staff (Sept 2025) → presiding over the department (Jan 2026). Army → Marines → Army → Joint Staff, with an amphibious specialism, at 56.

**Zhang Zheng (张峥), b. September 1969 — running the PLA Navy.**
Covered in README §4.2. For pipeline purposes the salient fact is structural: **a 1969-born officer running a service is the strongest single indicator in this dataset that the generational handover is already underway**, and it happened without a promotion ceremony.

### The negative case that disciplines the others

**Huo Jiangang (霍建刚), b. October 1970.** Commanded the 79th Group Army (2019–21), then president of the Joint Operations College at NDU, then **deputy commander of the Central Theater Command with promotion to lieutenant general in June 2022** — on track to be the PLA's youngest theater commander. **He was demoted in 2023** to deputy-theater grade and major general.

This is the only documented *demotion* in the dataset, and it matters twice over: the purge has reached the 1970-born cohort, and it does not always take the form of disappearance. **Succession modelling that assumes attrition happens only at the top is wrong.**

### The rest of the 1970+ cohort in senior billets

| Born | Name | Service | Post |
|---|---|---|---|
| 1971-08 | **Dai Mingmeng** 戴明盟 | Navy | Vice admiral; Southern TC Navy deputy commander — **the youngest confirmed serving three-star officer in the PLA** |
| 1970-12 | **Liu Zhe** 刘喆 | Navy | Vice admiral; deputy director, CMC Joint Operations Command Centre; second *Liaoning* captain |
| 1970-12 | Liang Yang 梁阳 | Navy | Rear admiral |
| 1970-12 | Su Rong 苏荣 | Army | Deputy commander, 83rd Group Army (from 2017) — *distinct from the disgraced civilian official of the same name* |
| 1970-03 | Liu Riming 刘日明 | Army | Director, Political Work Department, 76th Group Army — a deputy-corps-grade political officer born 1970; the clearest PC-track watch item |
| 1971-04 | Hao Yunkun 郝云昆 | Navy | Commander, Yangzhou Military Sub-district — a navy officer in a territorial billet |

### Below corps grade: the officers the PLA chose to publicise

These are not projections; they are the handful of 1973–1979-born officers who exist in the open record at all, and every one is there because the PLA made them famous:

- **Qi Fabao** (祁发宝, b. March 1979) — commander of the Urumqi Garrison. The regimental commander severely wounded at Galwan Valley in June 2020, named "Hero Regimental Commander" in 2021 and a Beijing 2022 torchbearer. The youngest officer identified in a named garrison-command billet.
- **Man Guangzhi** (满广志, b. March 1974) — commander of the Zhurihe OPFOR "Blue Force" brigade, the PLA's most famous training officer and the man whose unit repeatedly defeats visiting formations. NUDT and AMS educated. The canonical operator-riser.
- **Wu Qian** (吴谦, b. 1973) — defence attaché in Cairo; former director of the MND Information Bureau and its spokesman. **The youngest confirmed major general in the open record** — though on a political-work and foreign-affairs track, not a command one.
- **Chen Xiaoqian** (陈小前, b. September 1975) — vice president of the Academy of Military Sciences, spacecraft-systems specialist, Chinese Academy of Sciences academician. **The most senior 1975-born officer found anywhere**, and the strongest evidence that the technical-education route is the fastest for this generation.
- **Wei Huixiao** (韦慧晓, b. November 1977) — captain of the destroyer *Shaoxing* (DDG-134); **the first woman to command a PLAN principal surface combatant.** A lateral entrant who joined the navy in 2012 at 34 with a doctorate.
- **Zhao Yanquan** (b. March 1977) — destroyer captain (*Harbin*, *Shijiazhuang*), Gulf of Aden escort veteran.
- The astronaut cadre — **Cai Xuzhe** (b. 1976), **Zhang Lu** (b. 1976), **Tang Hongbo** (b. 1975) — all senior colonels in the Aerospace Force lineage.

---

## 3. What the collection channels yield

### 3.1 Group armies: 19% coverage

Of the 26 principal billets across the 71st–83rd Group Armies, **20 named holders have no biography and therefore no recoverable birth year.** Five of the thirteen unit pages are materially stale, trailing off in 2021–22 mid-roster.

| GA | Theater | Commander | Since | Born |
|---|---|---|---|---|
| 72 | Eastern | **Gu Zhong** 顾中 | Dec 2022 | **1972** |
| 73 | Eastern | Ding Laifu 丁来富 | Apr 2022 | 1968-04 — *purged Feb 2026* |
| 74 | Southern | Hong Jiangqiang 洪江强 | Aug 2018 | 1965-02 |
| 75 | Southern | Gai Limin 盖立民 | 2022 | — |
| 76 | Western | Yang Yi 杨毅 | Jun 2018 | 1966 |
| 77 | Western | Wang Suocheng 王锁成 | Mar 2021 | — |
| 80 | Northern | Hao Xingchen 郝兴晨 | 2022 | — |
| 82 | Central | Fu Xianxue 付先学 | 2023 | — |
| 83 | Central | Tan Hailin 谭海林 | 2023 | — |
| 71, 78, 79, 81 | — | *pages stale* | — | — |

**A warning about staleness.** These pages did not stop being edited; they stopped being *updated*, which is more dangerous. The 78th Group Army page still lists Wu Yanan as commander "from March 2017" — a man who went on to command the Southern Theater in July 2024 and has since vanished. **Treat any unit-page leadership entry without a post-2022 date as presumptively stale.**

### 3.2 Provincial military districts: the workaround that holds

The single most useful collection channel, and it works for a structural reason unlikely to change: **provincial MD commanders and political commissars sit on provincial party standing committees, whose composition civilian provincial organs must publish.** Military opacity is defeated by civilian disclosure requirements. Sixteen-plus provincial-level billets have a named current holder, refreshed on a civilian publication cycle, while group-army billets stay dark.

Named holders with recoverable birth years include Shi Huajie (Shandong MD commander, b. Jan 1966), Li Jun (Guangdong MD political commissar, b. June 1968), Ming Zunqiang (Shaanxi, b. 1969), Tian Yue (Shanxi, b. Oct 1968), Wang Yanqi (Chongqing Garrison, b. April 1966), Tian Xiaowei (b. June 1966), plus the Beijing, Shanghai and Tianjin garrison leaderships.

A second, structurally important observation falls out of this channel: **cross-service territorial posting is now routine.** Navy officers command the Guangdong Military District, the Xiamen Garrison and the Yangzhou sub-district; Air Force officers hold the Shanghai and Chongqing Garrisons and the Beijing and Tianjin Garrison commissarships; a Rocket Force officer held the Fujian MD. The territorial system is being used as **joint-seasoning rotation** for officers of all services — a succession-relevant change, and one that makes provincial standing-committee rosters a cross-service collection line rather than an Army-only one.

### 3.3 Military education: the fast track for this generation

The only channel that puts a 1975-born officer into a deputy-service-grade billet. Chen Xiaoqian (b. 1975) is vice president of the Academy of Military Sciences; Zhang Sibing (b. 1969) heads the Air Force Medical University; Li Xiang (b. September 1967) ran NUDT from 2019 and is also recorded as an NDU president. NUDT itself changed hands recently — Lei Yongjun became president in June 2026, Zhang Zhan political commissar in December 2025.

### 3.4 The carrier community, again

The carrier programme is the best-documented officer pipeline in the PLA, because the PLA publicises it:

| Ship | Captains |
|---|---|
| *Liaoning* (CV-16) | Zhang Zheng (b. 1969, 2012–16) → Liu Zhe (b. 1970, 2016–) → Cui Yonggang (current) |
| *Shandong* (CV-17) | Lai Yijun (b. 1970s, from 2018) |
| *Fujian* (CV-18) | Chen Zhiguo (first captain, designated June 2022; commissioned Nov 2025); deputy captains include Qian Shumin (b. 1979) |

Two of the three *Liaoning* captains are now vice admirals running a service and the CMC's joint operations centre respectively. **No other single billet in the PLA has that record**, which is why the current *Fujian* leadership deserves tracking even though their birth years are unpublished.

---

## 4. Where the record is genuinely dark

**The Rocket Force below service headquarters.** Not one commander or political commissar of Bases 61–69 has been named in open sources since 2017. Meanwhile the order of battle *below* those bases is comparatively rich — Base 61's brigades are listed with garrison towns and missile types (DF-21A, DF-15B, DF-11A, DF-16, DF-17), Base 67's with its warhead-storage role. **China's nuclear order of battle is better documented in open sources than the identities of the officers who command it.** For succession analysis this is close to total failure: the force that most needs it is the one that can least be done.

**Air Force aviation brigades and theater air forces.** Not one brigade or division commander is named. For a service whose leadership pipeline runs through flying billets, the entire feeder layer is missing.

**Group army leadership**, as above — nameable but not dateable.

**The Marine Corps commandership** since Zhu Chuansheng's departure in March 2025 is unnamed.

---

## 5. The publicity bias, and what it means for the whole report

**The visible part of the PLA is exactly the part the PLA has chosen to publicise.** Carrier captains, test pilots, astronauts, spokesmen, hero-unit commanders, NPC delegates. The invisible part is the ordinary command chain. Qi Fabao's birth date is known to the day because he was made a national hero; the officer commanding the base that stores China's nuclear warheads has no name in the public record at all.

Two consequences the reader should carry into §5 of the main report:

1. **Any list of "most promising officers" built from open sources over-weights the publicised and under-weights the operational.** This report's risers are disproportionately carrier officers, aviators and staff officers with media profiles, because those are the officers who exist in the record. The next chief of the Joint Staff may well be someone no Western analyst has heard of.
2. **The 1973 cliff is probably real, not merely an artefact.** Below Gu Zhong the record does contain senior colonels in sub-district and garrison deputy billets — Xie Wenhua (b. 1972), Hou Dianhui (b. 1973), Zhang Guangzeng (b. 1973), Hao Yunkun (b. 1971) — which is roughly where a 1972–73 cohort *should* be. The distribution is consistent with a genuine age structure rather than missing data. **Working inference: the officers who will hold theater commands in the late 2030s are today at brigade command and division/sub-district deputy level, holding the rank of senior colonel — a grade at which the PLA has never published systematically, purge or no purge.**

---

## 6. Recommended standing collection lines

For anyone maintaining this assessment:

1. **The birth-year category sweep**, re-run annually. It is the only method that measures its own coverage.
2. **Provincial party standing committee announcements** — the durable workaround, cross-service, on a civilian publication cycle.
3. **NPC and CPPCC delegate rosters and their termination gazettes.** Roughly 25 officers in this study's junior table are known *only* because they were NPC delegates. The 13th NPC military delegation is individually catalogued and is the richest single source of 1973–79 birth years available.
4. **Protocol and seating analysis** (README §3.5), which is what identified Zhang Zheng.
5. **Track Gu Zhong, Zhu Chuansheng, Zhang Zheng and Dai Mingmeng individually** — and watch whether Huo Jiangang's demotion is reversed, since a restored officer would tell us something about how the system treats its own mistakes.
