# China's Robot Ecosystem

*The flagship deep-dive on the embodied-intelligence wave — humanoids, quadrupeds, military ground robots, and the component chain beneath them. China ships ~97% of the world's humanoids; the interesting question is what it still can't make itself.*

*Working draft — August 30, 2026. Part of the [China Defense-Industrial Atlas](./defense-industrial-atlas.md); a companion to the robot layer of the [Drone & Robot Ecosystem](./drone-robot-ecosystem.md), taken much deeper here.*

---

## 2026: "mass-production year one"

China's government and industry both christened 2026 the **"mass-production year one"** for embodied intelligence, and the numbers back the slogan: **~¥46B (~$6.8B) raised across 288 robotics financings in H1 2026 alone**, the country's first **Humanoid Robotics & Embodied Intelligence Standard System** issued early in the year, and Chinese makers shipping [**~97% of the world's humanoid robots** in H1 2026](https://www.eweek.com/news/china-humanoid-robots-agibot-unitree-apac/) as global volume jumped 272% year-on-year.

The atlas rates robots **Dominant** on volume and ecosystem — and that rating is correct but incomplete. China owns the platforms, most of the supply chain, the manufacturing base, and increasingly the software. What it does *not* yet own are a handful of the hardest components — top-tier reducers, high-end force and tactile sensors, and the AI compute — and those are where the real dependency, and the real story, sit. As with drones, this is a domain where military-civil fusion makes "military supplier" an unanswerable question: the same robot ships to a warehouse or an infantry squad.

---

## The humanoids — a duopoly at the top, a deep bench below

The humanoid race consolidated into a two-horse lead in 2026, and both went public:

- **AgiBot / Zhiyuan (智元, Shanghai)** — the new volume leader. Alibaba- and Tencent-backed, it shipped its **10,000th humanoid by March 2026** (the fastest ramp in the industry's history), led H1 2026 with roughly **8,400 units / ~44% global share**, and is pursuing a **Hong Kong IPO at a ~$5–6B valuation**. Its **GO-1 foundation model** and **AgiBot World dataset** make it as much an embodied-AI company as a hardware one.
- **Unitree (宇树, Hangzhou)** — the household name, and the first pure-play humanoid company to go public *anywhere*: its Shanghai STAR Market IPO on **August 19, 2026 surged ~629% intraday to close around a $53B valuation** (priced at ~$9B, oversubscribed 8,000×). Humanoids (G1/H1/H2) overtook its robot dogs as the biggest business in 2025 (~5,500 humanoids shipped); H1 2026 shipments ~5,900 (~31%). It is now **1260H-listed** (below).
- **The bench.** **UBTech (优必选, Shenzhen)** leads industrial humanoids (Walker S; first to ship 1,000+ industrial units; ~5,000 target in 2026, 10,000 by 2027); **Galbot** (~900 H1 units), **Leju** (Kuavo, ~600), **Fourier** (care-oriented GR-3), **EngineAI** (athletic bipeds), and **Xpeng** (Iron) round out a field of 20+ serious players. TrendForce projects **~62,500 Chinese humanoid shipments in 2026, +94% YoY**, with AgiBot and Unitree together near 80%.

## Quadrupeds — and the "war wolf" pipeline

- **Unitree** also leads quadrupeds (the $1,600 Go2 democratized the category; the industrial B2 competes with Boston Dynamics' Spot at a fraction of the price), with **DEEP Robotics (云深处, Hangzhou)** the strong #2 (Lynx, X30), plus **Weilan (AlphaDog)** and **Xiaomi (CyberDog)**.
- **The military handoff.** A rifle-toting robot dog was demonstrated in the **2024 "Golden Dragon" China–Cambodia joint exercise**, and Kharon has documented Unitree sales into Chinese universities with PLA-contracting track records; FDD's "War Wolves" work traces how commercial robot dogs migrate straight into PLA squads — the clearest MCF pipeline on the board, because the platform ships from the same factory either way. A pointed irony: the underlying quadruped-locomotion research was [seeded by US DEVCOM Army Research Lab funding](https://www.militarytimes.com/industry/techwatch/2026/08/18/how-us-military-funding-propelled-chinas-robot-dogs/) (via MIT's Mini Cheetah). Unitree insists its products are civilian and cites a 2022 no-weaponization pledge. (Note: armed "Machine Wolf"/"Wolf Robot" quadrupeds shown at Zhuhai are often loosely attributed to the now-dissolved China South Industries Group; that attribution is unreliable — the safer framing is commercial platforms weaponized by NORINCO and third-party vendors.)

## Military ground robots & exoskeletons — already fielded

The commercial humanoid wave gets the headlines, but the PLA's *deployed* ground robots are more prosaic and further along:
- **NORINCO Sharp Claw** tracked recon/strike UGVs are reportedly fielded in Tibet at battalion scale; the rocket-armed **ZRY222** appeared on state TV in January 2026; the **Swarm-2** ground combat vehicle debuted at Zhuhai 2024.
- The tracked **Mule-200** logistics UGV (~200 kg / 50 km) is deployed in Tibet by the dozen — the unglamorous "last tactical mile" role.
- **Exoskeletons** from NORINCO (passive) and CASIC (powered "Portable Ammunition Support Assist") are in selective use in Tibet and Xinjiang at 4,500–5,500 m.

*(These are mapped in detail in the [Drone & Robot Atlas](./drone-robot-ecosystem.md).)*

---

## The component chokepoint — where China still depends

Humanoids are ~**30–60% actuators by bill of materials**, and the actuator is a magnet-plus-reducer-plus-sensor problem. This is the layer that decides the domain's real dependency:

- **Reducers (the joint's precision heart).** **Leaderdrive / Green Harmonic (绿的谐波)** broke Japan's monopoly in **harmonic** (strain-wave) reducers, taking **~30–40% of China's harmonic market** (J.P. Morgan) at **20–40% below** Japanese pricing, and supplying even Tesla; **Laifu, Zhongdali De, and Shuanghuan** fill out the domestic field. But in **RV (cycloidal) reducers for heavy-load joints, Japan's Nabtesco still leads**, and Harmonic Drive owns the very top precision tier — a narrowing but real reducer dependency.
- **Linear actuators (planetary roller screws) — the missed chokepoint.** The humanoid boom exposed a second Western-held dependency the reducer story obscures: the precision **planetary/satellite roller screws** that drive linear leg actuators are still dominated by Swiss and European makers (**Rollvis, GSA, Ewellix**), with Chinese suppliers only beginning to qualify. Alongside top reducers and force/tactile sensors, this is where China genuinely still depends.
- **Force/tactile sensors & dexterous hands (the hardest gap).** **Tactile sensing is the single largest technical bottleneck** in a dexterous hand. China's six-axis force/torque-sensor market is small and **~60% import-dependent** (ATI of the US holds ~40% globally; Kistler leads the high end), with domestic challengers **Kunwei, Yuli, Xinjingcheng, and Keli** climbing. **Inspire Robots** is China's first mass-producer of dexterous hands (linear-drive, 0.2 mm precision). This sensing layer is where China is furthest behind.
- **Magnets & compute.** The actuator's motor turns on **NdFeB magnets** — where China processes ~90% of heavy rare earths (the leverage, not the dependency) — and the "brain" runs on **Horizon Robotics, Rockchip, and Huawei Ascend** edge silicon (the compute domain's constraint reaching in). **Orbbec** supplies much of the 3D vision.

The synthesis analysts keep reaching: roughly **70% of Tesla's Optimus gen-3 component value is Chinese-sourced**, and China controls ~63% of key humanoid-component manufacturing. The embodied-AI supply chain is being born Chinese — with the sensor/reducer top tier the last holdout.

## The brain — VLA models and a national data effort

The 2025–26 shift from teleoperated demos to autonomous work runs on **vision-language-action (VLA)** models and the data to train them:
- **AgiBot's GO-1** foundation model and **AgiBot World** dataset are the commercial frontier.
- **X-Humanoid — the Beijing Humanoid Robot Innovation Center** — is the state's play: a **national-local co-built embodied-intelligence center** (MIIT-designated) running a **data-and-training base that drills 120+ robot models across 30+ scenarios**, with a professional motion-capture venue setting national benchmarks. Its **Tien Kung (天工)** open platform reached 3.0 in February 2026, and it raised **¥700M in February 2026** with Baidu among the investors. It is one of **six** such national humanoid innovation centers — a coordinated, state-backed data-and-standards push with no US equivalent.
- **The big-tech VLA labs.** Beyond the platform makers, China's AI giants are piling into the robot brain: **ByteDance's Seed lab** (the GR-series VLA), **Alibaba's Qwen-VLA / RynnVLA**, **DeepSeek's** reasoning models as a high-level planner, and the state **BAAI** lab's open **RoboBrain**. A depth of foundation-model talent feeding embodied AI that few countries can match — and the layer where the domain's next advantage will actually be decided.

## The industrial-robot base — the dual-use foundation

Beneath the humanoid glamour sits the arm-robot base that underpins all of China's manufacturing (and defense production):
- **Estun (埃斯顿)** has **overtaken Fanuc and ABB as China's market leader**; **Inovance (汇川)** shipped **5M+ robotic joint servo motors in 2025** and co-developed force-control robots with BYD; **Siasun, EFORT, JAKA, Dobot, and AUBO** fill the field. **Domestic brands passed 50% of China's own market for the first time**, and China now installs more industrial robots per year than Europe and North America combined. (KUKA, one of the "big four" globally, is Chinese-owned via Midea.) This is the manufacturing muscle that makes the humanoid ramp physically possible.

## Policy, clusters & the state's hand

The push is coordinated from the top: MIIT's **"mass-production year one"** framing (with a **~100,000-unit 2026 production target**), the first national **embodied-intelligence standard system** (HEIS 2026), embodied intelligence's debut in the March 2025 Government Work Report and its priority in the **15th Five-Year Plan**, national guidance funds, and dense clusters in **Beijing (Yizhuang), Shanghai (Zhangjiang), Shenzhen, Hangzhou (the "Six Little Dragons"), and Chongqing**. Robotics sits at the center of China's bid to define the next general-purpose technology platform.

## PLA, MCF & the sanctions wall

- **Unitree hit the 1260H list on June 8, 2026** — the Pentagon citing its indirect SASAC ownership, its "Little Giant" state support, and (per Kharon) partner-network ties to the PLA's **"Robot Wolf"** weapons platform. Days around it, the **FCC added Unitree to its Covered List** (late July 2026) over documented hardware-backdoor concerns, and a bipartisan **House Select Committee** pushed to add it to the Entity List outright — even as Unitree launched in Europe and its dogs turned up in US police departments.
- The **sanctions wall keeps widening** for the same reason it does across the atlas: with no separate military SKU, the dual-use surface is the whole sector. Unitree denies selling to the PLA; the militarized demos, it says, are third-party work. Whether that distinction survives contact with a 1260H designation is the open question.

---

## Assessment

China dominates robots on every axis that scales — shipments (~97% of humanoids), the platform field, the industrial-robot base, the state data-and-standards machinery, and most of the supply chain — while a modest but real dependency persists at the very top of the reducer and force/tactile-sensor tiers, and in AI compute. The military pathway is not hypothetical: robot dogs, UGVs, and exoskeletons are already fielded, and the MCF pipeline is the most direct on the board. Dominant on volume and ecosystem, with the hardest components the last thing left to localize — and the sanctions regime racing to catch a surface that is, definitionally, the entire commercial sector.

---

## Sources & further reading

- CNBC and Value Add VC on the [Unitree IPO and ~$53B valuation](https://valueaddvc.com/unitree-ipo-tracker); TrendForce, Digitimes and eWeek on [H1 2026 humanoid shipments and the AgiBot/Unitree lead](https://www.eweek.com/news/china-humanoid-robots-agibot-unitree-apac/)
- 36Kr on [China's humanoid mass-production year](https://eu.36kr.com/en/p/3887956055636481); Interesting Engineering on [AgiBot at WAIC 2026](https://interestingengineering.com/ai-robotics/china-agibot-humanoid-robot)
- Kharon, "[At Unitree Robotics, the Military Connections Keep Mounting](https://www.kharon.com/brief/unitree-robotics-china-pla)"; Military Times on the [DEVCOM funding origin](https://www.militarytimes.com/industry/techwatch/2026/08/18/how-us-military-funding-propelled-chinas-robot-dogs/); TheNextWeb on the [1260H additions](https://thenextweb.com/news/pentagon-1260h-alibaba-baidu-byd-unitree-chinese-military)
- Humanoid.guide on [Leaderdrive harmonic reducers](https://humanoid.guide/leaderdrive-harmonic-reducers-surge-as-humanoid-demand-lifts-shares/); TechBuzz China robotics tracker on [robot hands](https://robotics.techbuzzchina.com/reports/robot-hands-china.html) and [actuators](https://robotics.techbuzzchina.com/reports/actuators-motors.html); Gerra / Morgan Stanley on the [humanoid value chain](https://www.gerra.com/insights/humanoid-robot-supply-chain)
- Xinhua and PR Newswire on the [Beijing Humanoid Robot Innovation Center / X-Humanoid data base and Tien Kung](https://www.prnewswire.com/news-releases/x-humanoid-showcases-fully-autonomous-and-more-useful-robotics-solutions-at-ces-2026-302656056.html); Yicai on [Chinese industrial-robot domestic share](https://www.yicaiglobal.com/news/chinese-industrial-robot-makers-share-of-domestic-market-climbs-to-record-in-first-half)
- FDD, "[China's War Wolves](https://www.fdd.org/analysis/2026/05/03/chinas-war-wolves-from-commercial-tech-to-combat-power/)"; DoD *Military and Security Developments Involving the PRC*, December 2025

*Caveats: shipment, valuation and market-share figures come from industry trackers (TrendForce, J.P. Morgan, Morgan Stanley) and vary by methodology — read them as directional. The robotics field consolidates monthly; this is a mid/late-2026 snapshot. Company-to-PLA links range from documented (Unitree's 1260H designation, state-TV armed demos) to inferential, and are flagged as such. A dedicated interactive Robot Ecosystem map, built on a multi-agent research sweep, is in progress and will join the atlas.*
