# China's Counter-Drone Ecosystem

*The other side of the board. China is simultaneously the world's drone arsenal and one of its leading counter-drone vendors — it profits from both ends of the same problem. A map of the PLA's counter-UAS kill chain (detect → decide → defeat) and the systems and vendors behind each stage.*

*Working draft — August 30, 2026. Companion to the [Drone & Robot Ecosystem](./drone-robot-ecosystem.md) and its interactive map; see also the standalone Counter-Drone Kill Chain map (`counter-uas-map.html`).*

---

## Why this is its own map

Everything in the [drone/robot deep dive](./drone-robot-ecosystem.md) is about putting cheap autonomous mass into the air. This document is about taking it back down — and it is a genuinely different problem, organized not by supply-chain depth but by a **kill chain**: you have to *detect* a small, slow, low-flying target, *decide* which threats to engage and cue an effector, and *defeat* it either softly (electronic warfare) or hard (directed energy or kinetics). China builds vendors and systems at every stage, and the September 2025 and January 2026 parades were, as much as anything, counter-UAS showcases.

The strategic frame that makes this urgent is the **cost-exchange problem**. A $10,000 FL-300D loitering drone or a $400 FPV is not worth a $2 million interceptor missile; win the engagement, lose the economics. Whoever controls the cost curve — deep magazines, low cost-per-shot, resilience under jamming — wins a saturation fight. That is why China is pushing hard into **directed energy** (lasers and high-power microwave: near-zero cost-per-shot, effectively unlimited magazine) and openly displaying it, which signals Beijing now regards these weapons as mature and operational rather than experimental. The [Taiwan Strait framing is explicit in Chinese writing](https://asiatimes.com/2026/01/chinas-hurricane-3000-casts-an-electric-storm-in-the-taiwan-strait/): the drone-vs-counter-drone contest is becoming a battle of cost, resilience, and control of the electromagnetic spectrum.

And the deepest irony of the whole ChinaTalk beat: **China arms both sides of the drone problem.** It sells Saudi Arabia the Wing Loong-3 (a [reported $5B local-production deal, ~48 aircraft/year](https://www.al-monitor.com/originals/2026/06/how-iran-war-giving-china-opening-gulf-drone-market)) *and* the Silent Hunter laser meant to shoot down everyone else's drones. The arsenal and the counter-arsenal ship from the same industrial base.

---

## Stage 1 — Detect & Track (find the target)

The hardest part of counter-UAS is not killing the drone; it is *seeing* it. Small quadcopters have tiny radar cross-sections, fly low and slow in ground clutter, and increasingly use fiber-optic control that emits no RF at all. China's answer is multi-sensor fusion.

- **Radar.** Phased-array and PESA search/track radars are the backbone — the FK-3000 alone carries one large plus three small AESA panels for 360° coverage from [150 m out to ~30 km](https://www.armyrecognition.com/news/army-news/2025/chinas-new-fk-3000-air-defense-system-carries-96-missiles-to-protect-key-sites-from-drone-swarms). CETC and NORINCO institutes (see the [radar tier of the DIB atlas](./chinese-military-supplier-map.md): CETC 14th/38th) supply the arrays.
- **RF detection / passive radar.** Firms like **Novasky** market RF scanners (SC-S3000/5000/8000) that detect drones by analyzing their control and datalink signals — passive, no emissions, all-weather. The commercial C-UAS export tier is dense with these.
- **Electro-optical / infrared.** EO/IR turrets provide the precise visual track before engagement — and rely on the same [uncooled thermal cores (Raytron, InfiRay, Guide Infrared)](./drone-robot-ecosystem.md) that go into the drones themselves. The sensor supply chain is shared across offense and defense.
- **The fiber-optic-drone problem.** FPV drones on fiber-optic spools — now common in Ukraine — emit no RF and can't be jammed, defeating the RF-detection and RF-defeat layers at once. This is pushing the whole field back toward radar and optical detection and hard-kill, and it is the single biggest live challenge for the "detect" stage.

## Stage 2 — Command & Decide (fuse, prioritize, cue)

The glue layer: AI-enabled command-and-control that fuses radar, RF, and EO/IR into a single track picture, prioritizes among many simultaneous threats, and cues the right effector at the right moment. Integrated platforms like **Hunter Pro** (shown at Expodefensa 2025) bundle RF sensing, radar, optical tracking and focused jamming into one managed system. This is the counter-UAS mirror of the [CETC "Atlas" swarm C2](./drone-robot-ecosystem.md) on the offensive side — and, like it, the part hardest for an adversary to buy off the shelf.

## Stage 3 — Defeat, soft-kill (electronic warfare)

Non-kinetic defeat: cheaper per shot, reversible, but increasingly evaded.

- **RF jamming.** Multiband jammers (the **Hunter Pro** class) sever the control and video links of RF-guided drones. The workhorse of counter-FPV, and the layer fiber-optic drones are designed to beat.
- **GNSS jamming & spoofing.** Denying or falsifying satellite navigation to strand or redirect drones — multi-constellation systems target GPS, Galileo, GLONASS and BeiDou at once.
- **The BeiDou flip side.** The same expertise runs offensively. When Israel jammed GPS during the [June 2025 "12-Day War," Iran switched to China's BeiDou-3 B3A military signal](https://defencesecurityasia.com/en/iran-beidou-satellite-navigation-twelve-day-war-gps-jamming-israel-electronic-warfare/) — reportedly ~98% positioning reliability under jamming versus >70% failure rates for GPS-guided systems. China both defeats others' navigation and offers a hardened alternative to its own. Counter-UAS EW is inseparable from the navigation-warfare story.
- **Protocol takeover.** The emerging edge: hijacking a drone's control protocol to seize it rather than merely jam it.

## Stage 4 — Defeat, hard-kill: directed energy

The counter-swarm answer, and the category China is most conspicuously racing on. Near-zero cost-per-shot and a magazine limited only by power — exactly what a saturation attack demands.

- **Lasers.** The **LY-1** high-energy laser rode through the [September 3, 2025 parade](https://www.twz.com/news-features/chinas-imposing-ly-1-high-power-laser-weapon-unveiled-at-huge-military-parade) on an 8×8 truck, billed as a shipborne "last line of defense" against drones, cruise missiles and aircraft; by [November 30, 2025 it was photographed on a civilian Ro-Ro doing sea trials](https://www.armyrecognition.com/news/navy-news/2025/china-converts-civilian-cargo-ship-into-maritime-directed-energy-platform-with-ly-1-laser-weapon). The export-proven **Silent Hunter** (China Poly Technologies) is a fiber laser [reportedly ">30 kW but <100 kW,"](https://en.wikipedia.org/wiki/Silent_Hunter_(laser_weapon)) derived from the LASS / "Low-Altitude Guardian" system. Vehicle-mounted 30 kW-class lasers like the **LW-30** (CASIC) round out a line China says is entering mass production.
- **High-power microwave.** The **Hurricane 3000** — a truck-mounted HPM weapon revealed at the [January 2026 parade and described as operationally deployed](https://www.armyrecognition.com/news/army-news/2026/china-deploys-hurricane-3000-microwave-weapon-for-operational-counter-drone-warfare) — disables drones out to >3 km by frying flight controllers, sensors and datalinks with pulsed bursts that let it engage many targets in quick succession. That pulsed, multi-target profile is purpose-built for swarms; the **NI-HP1000** is an export-market HPM shown at DSA 2026. HPM is the clearest expression of the cost-exchange logic: an effectively unlimited magazine against cheap mass.

## Stage 5 — Defeat, hard-kill: kinetic

When directed energy isn't enough or isn't ready, guns and missiles — increasingly integrated into single anti-swarm vehicles.

- **The FK-3000 (CASIC)** is the flagship: a 6×6 vehicle with a 30 mm autocannon, phased-array radars, a jammer, and [up to 96 micro-missiles](https://www.twz.com/land/check-out-chinas-short-range-air-defense-vehicle-capable-of-packing-a-whopping-96-mini-interceptors) — explicitly an anti-swarm, anti-cluster system, fielded and paraded in September 2025. Deep kinetic magazine as the answer to numerical saturation.
- **Gun CIWS.** NORINCO's **LD-2000 / LD-3000** are the land versions of the naval **Type 730** close-in weapon system — a seven-barrel 30 mm gatling firing [~5,600 rounds/minute](http://www.army-guide.com/eng/product4174.html) — with the naval **Type 730/1130** doing the same shipboard last-ditch job. Cheap ammunition, but shallow effective magazine against true saturation.
- **SHORAD.** Short-range SAMs like the **HQ-11** and the exported **HQ-17AE** are being adapted to the drone threat, blurring into traditional point air defense.
- **Interceptors & nets.** Drone-on-drone interceptors, net-capture systems, and micro-missile swarms (the 96-round SHORAD concept) are the emerging kinetic edge — using cheap mass to defeat cheap mass, the only kinetic approach whose economics survive a swarm.

---

## Export & proliferation — arming both sides

China's counter-UAS industry is also an export business, and the Middle East is the shop window. **Silent Hunter is [reportedly in service in the UAE, Saudi Arabia and Russia](https://www.unmannedairspace.info/counter-uas-systems-and-policies/chinas-silent-hunter-laser-c-uas-system-now-in-use-in-uae-saudi-arabia-and-russia/)**, procured in part to protect expensive US-made Patriot batteries from cheap drones. Gulf states took [over 80% of Chinese Middle East defense exports from 2016–2025](https://www.al-monitor.com/originals/2026/06/how-iran-war-giving-china-opening-gulf-drone-market), and the June 2025 Iran war supercharged regional demand for anti-drone kit.

But the export story carries a warning the marketing doesn't: **performance in the field has lagged the brochure.** Saudi Arabia [reportedly found both its Chinese HQ-17AE and Silent Hunter systems failing to intercept](https://www.globaldefensecorp.com/2025/09/08/saudi-arabia-says-chinese-made-hq-17ae-and-silent-hunter-laser-weapon-failed-to-intercept-drones-and-missiles/) drones and missiles, and Silent Hunter has [struggled in desert heat and dust](https://defencesecurityasia.com). Directed energy is punishing to operationalize — atmospherics, thermal management, and dwell time are unforgiving — and China's systems are meeting the same physics that slow everyone else's.

The through-line for a ChinaTalk audience: China is monetizing **both** the drone saturation problem and its solution, and using counter-UAS exports (like drone exports) to deepen Gulf defense relationships that were until recently American-exclusive. Whether the hardware delivers is a separate question from what the sales are buying diplomatically.

---

## The unheralded / watch list

1. **Directed-energy cost curve.** LY-1, Silent Hunter, LW-30, Hurricane 3000 — whether China can make cost-per-shot and magazine depth real at operational reliability is the single most important counter-swarm variable.
2. **The fiber-optic-drone gap.** FO-guided FPVs beat the entire RF detect-and-defeat stack; the side that solves detection-and-defeat against them first gains a real edge, and neither has yet.
3. **FK-3000 (CASIC)** — the integrated anti-swarm vehicle that best captures China's "deep kinetic magazine" doctrine.
4. **BeiDou navigation warfare** — the offense/defense duality where counter-UAS EW meets a hardened sovereign GNSS China sells abroad.
5. **Novasky and the passive-detection tier** — the unheralded commercial RF/passive-radar vendors filling the export market.
6. **China Poly Technologies** — the OFAC-sanctioned state trader that is the export face of Chinese directed-energy C-UAS.

---

## Sources & further reading

- The War Zone on the [LY-1 laser](https://www.twz.com/news-features/chinas-imposing-ly-1-high-power-laser-weapon-unveiled-at-huge-military-parade) and the [96-micro-missile SHORAD vehicle](https://www.twz.com/land/check-out-chinas-short-range-air-defense-vehicle-capable-of-packing-a-whopping-96-mini-interceptors)
- Army Recognition on the [Hurricane 3000 HPM deployment](https://www.armyrecognition.com/news/army-news/2026/china-deploys-hurricane-3000-microwave-weapon-for-operational-counter-drone-warfare), the [FK-3000](https://www.armyrecognition.com/news/army-news/2025/chinas-new-fk-3000-air-defense-system-carries-96-missiles-to-protect-key-sites-from-drone-swarms), and [Hunter Pro at Expodefensa 2025](https://www.armyrecognition.com/archives/archives-defense-exhibitions/2025-archives-defense-exhibitions/expodefensa-2025/expodefensa-2025-chinese-hunter-pro-fpv-jammer-strengthens-layered-protection-against-small-drones)
- Asia Times on the [Hurricane 3000 and the Taiwan Strait cost-exchange framing](https://asiatimes.com/2026/01/chinas-hurricane-3000-casts-an-electric-storm-in-the-taiwan-strait/); Wikipedia on [Silent Hunter](https://en.wikipedia.org/wiki/Silent_Hunter_(laser_weapon)) and [FK-3000](https://en.wikipedia.org/wiki/FK-3000)
- Al-Monitor on [China's opening in the Gulf drone/counter-drone market](https://www.al-monitor.com/originals/2026/06/how-iran-war-giving-china-opening-gulf-drone-market); Unmanned Airspace on [Silent Hunter in the UAE/Saudi/Russia](https://www.unmannedairspace.info/counter-uas-systems-and-policies/chinas-silent-hunter-laser-c-uas-system-now-in-use-in-uae-saudi-arabia-and-russia/); Global Defense Corp on the [Saudi interception failures](https://www.globaldefensecorp.com/2025/09/08/saudi-arabia-says-chinese-made-hq-17ae-and-silent-hunter-laser-weapon-failed-to-intercept-drones-and-missiles/)
- Defence Security Asia on [Iran's BeiDou-3 switch during the 12-Day War](https://defencesecurityasia.com/en/iran-beidou-satellite-navigation-twelve-day-war-gps-jamming-israel-electronic-warfare/); Army-Guide on the [LD-2000 CIWS](http://www.army-guide.com/eng/product4174.html)
- DoD *Military and Security Developments Involving the PRC*, December 2025; IISS *Military Balance 2026*

*Caveats: directed-energy specs are almost all Chinese-disclosed or estimated and should be read as claims, not verified performance — the Saudi field reports are a useful corrective. Vendor attributions for the export/commercial C-UAS tier (Novasky, Hunter Pro) rest on exhibition marketing and are lower-confidence than the state SOE systems (CASIC FK-3000, NORINCO LD-2000, Poly Silent Hunter). A 2026 snapshot of a fast-moving contest.*
