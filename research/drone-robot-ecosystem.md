# China's Drone & Robot Ecosystem

*A deep map of the PLA's unmanned and embodied-intelligence supply chain — the platforms, the commercial giants, the component chokepoints almost nobody names, the humanoid-robot wave, and the counter-drone other side. The vertical where China's defense-industrial advantage is most total.*

*Working draft — August 30, 2026. Companion to the [PLA Supplier Atlas](./chinese-military-supplier-map.md) and the interactive drone/robot map (`drone-robot-map.html`).*

---

## Why this is the sharpest edge of the whole board

In aviation, China's binding constraint is engines. In compute, it's lithography. In drones and robots, there is no equivalent gap — China owns the platforms *and* the supply chain beneath them, from the airframe down to the neodymium in the motor. This is the one defense-adjacent vertical where the United States and its allies are the dependent party.

The number that captures it: Chinese firms supply an estimated [80–90% of the global market for FPV drone motors](https://static.rusi.org/rp-drone-supply-chains-china-nov-2025_0.pdf), and comparable shares of the ESCs, flight controllers, cameras, batteries, radios, and carbon-fiber airframes that go with them. When Ukraine set out to build a "China-free" drone in 2025–26, it took years and it still couldn't replace the cameras. The PLA doesn't have that problem — it sits on top of the arsenal that everyone else is trying to escape.

Two structural features make this ecosystem different from the rest of the defense-industrial base:

1. **It is bottom-up, not SOE-down.** The aviation and shipbuilding worlds are organized around state conglomerates and numbered institutes. The drone/robot world runs on a dense mesh of private Shenzhen and Shanghai firms — many of them consumer-electronics companies whose products are dual-use by default. The state buys *from* this ecosystem rather than owning it.
2. **The military and civilian versions are the same product.** A DJI Mavic, a T-Motor motor, a Unitree quadruped — the "military supplier" question is definitionally unanswerable because there is no separate military SKU. This is military-civil fusion in its purest form, and it is why US sanctions keep expanding to swallow ever-larger swaths of China's commercial tech sector.

The map below runs top to bottom: the flying platforms, the commercial dual-use core, the component chokepoint layer (the heart of it), the ground/humanoid robot wave, the counter-drone other side, and the autonomy brain tying it together.

---

## Layer A — Aerial platforms, by class

**Strategic ISR / HALE.** At the top sit the high-altitude, long-endurance reconnaissance platforms: the **WZ-7 Soaring Dragon** (a distinctive joined-wing HALE ISR drone, AVIC/Guizhou) and the rocket-boosted **WZ-8** high-speed recon drone air-launched from H-6 bombers. Newest is CASC's **CH-7 (Rainbow-7)** — an ~8-tonne flying-wing stealth HALE UCAV that flew its [maiden flight in late November 2025 at Pucheng](https://www.globalsecurity.org/military/world/china/ch-7.htm), closing a category (stealthy penetrating ISR/strike) the US fills with the RQ-180.

**MALE armed reconnaissance — the export workhorses.** This is where China conquered the global market the US ceded. Two rival state lineages dominate:
- **Wing Loong family** (AVIC, via the Chengdu Aircraft Design Institute / CADI) — the GJ-1/GJ-2 in PLA service and the **Wing Loong-3**, [introduced in 2025](https://www.defensenews.com/global/asia-pacific/2026/02/12/chinas-new-maritime-combat-drone-poised-for-global-success-analysts/) as an intercontinental-range UCAS, with a maritime ASW variant carrying sonobuoys and lightweight torpedoes.
- **CH / Cai Hong "Rainbow" family** (CASC's 11th Academy, CAAA, via Aerospace Rainbow) — the **CH-4** and **CH-5** (MQ-9-class) that armed half the Middle East, plus improved blocks. Rainbow spans 10+ fixed-wing models and remains the export volume leader.

**Stealth UCAV / loyal wingman / collaborative combat aircraft.** The fast-moving frontier:
- **GJ-11 "Sharp Sword"** (Hongdu/AVIC) — an operational flying-wing stealth UCAV, [shown flying in formation with the J-20](https://milmag.pl/en/chinese-gj-11-loyal-wingman-accompanied-by-j-20/) and paraded in navalized form for the Type 076 drone carrier.
- **FH-97A** (Feihong, a CASC-linked house) — an MQ-28 Ghost Bat-analogue loyal wingman shown at Zhuhai 2022/2024, [pitched to carry ~8 air-to-air munitions](https://en.wikipedia.org/wiki/Feihong_FH-97A) as a missile magazine for a crewed fighter.
- **J-20S** — the world's first twin-seat stealth fighter, whose second crewman is the [drone-swarm command node](https://www.flightglobal.com/military-uavs/inside-the-plas-push-for-collaborative-combat-aircraft/166398.article) for GJ-11s and FH-97As. The controller, not the drone, is the hard part — and China now flies it.

**Swarm motherships.** AVIC's **Jiutian SS-UAV** ("High Sky") flew its [maiden flight on December 11, 2025 at Pucheng](https://theaviationist.com/2025/12/11/china-jiutian-drone-mothership/): a 16-tonne, 25-meter-span jet designed to carry 100+ small drones or a 6-tonne payload, with a 7,000 km ferry range — a flying aircraft carrier for saturation swarms, unveiled at Zhuhai 2024 and airborne barely a year later.

**Loitering munitions / one-way attack.** The category Ukraine made famous, and China industrialized early. CASC's **CH-901 / FH-901** (export name BG-201) is a 9 kg, tube-launched Switchblade-class weapon with a 15 km radius and 120-minute loiter; the larger **WS-43** is a ~500 lb, 60 km cruise-type loitering munition. China [demonstrated a Dongfeng Mengshi truck with 48 CH-901 tubes](https://nationalinterest.org/blog/reboot/chinas-quest-loitering-munitions-aka-suicide-drones-168566) in 2020 — massed precision one-way attack as a truck-mounted system. Below these sit the numberless FPV kamikaze tier drawn straight from the commercial supply chain.

---

## Layer B — The commercial dual-use giants

- **DJI (Shenzhen)** — the center of gravity of the entire global drone world, with a [~70% global market share](https://finance.yahoo.com/news/connected-commercial-drones-report-2025-080800223.html) and ~80% of the US market by units. Entity-Listed, investment-banned, and on 1260H — and, as of the [FCC's December 22, 2025 Covered List update](https://knowledge.wingtra.com/en/dji-ban-ndaa-compliance) under Section 1709 of the FY25 NDAA, blocked from bringing new models to the US market. Ubiquitous on both sides in Ukraine despite that. There is no functional substitute at DJI's price-performance point, which is the whole strategic problem.
- **Autel Robotics (Shenzhen)** — the number-two, on 1260H, sharing DJI's Covered-List fate; its enterprise drones show up in the same conflict zones.
- **Agricultural crossover — DJI Agras & XAG.** DJI's **Agras** line (T100/T70P/T25P) holds ~30% of the global agricultural-drone market; **XAG** (~9%) has expanded into ground rovers. These heavy-lift spray drones are trivially convertible to logistics and dispersal roles — the clearest "civilian platform, military utility" case.
- **EHang (Guangzhou)** — eVTOL / autonomous passenger drones; holder of the historical 1,000+ drone light-show swarm records that double as a demonstration of coordinated-flight software.

---

## Layer C — The component chokepoint layer *(the heart of the map)*

This is the layer the user asked for and the layer outside coverage skips: the unheralded Shenzhen and Shanghai component houses that the entire world's small-drone industry — Western and Ukrainian included — is built on. Almost none are sanctioned. That is precisely why they matter.

**Motors & ESCs.** Chinese firms hold [an estimated 80–90% of the global FPV motor market](https://static.rusi.org/rp-drone-supply-chains-china-nov-2025_0.pdf):
- **T-Motor (江西新拓 / Nanchang)** — the category king in brushless motors, ESCs, and propellers; in Western, Ukrainian, and PLA drones alike.
- **MAD Components, SunnySky, BrotherHobby, EMAX** — the rest of the motor oligopoly.
- **Hobbywing (Shenzhen)** — the dominant ESC / electronic-speed-controller maker, also the drivetrain supplier creeping into robotics.

**Flight controllers & autopilots.** The "cerebellum" that keeps the aircraft stable:
- **CUAV, JIYI (极翼), Holybro** — industrial autopilots and the PX4/ArduPilot-compatible flight-controller hardware base. JIYI in particular is a default agricultural-drone brain.

**Datalinks & ground control.** The RF spine:
- **SIYI (思翼) and Skydroid (天罡)** — integrated remote-control + datalink + HD-video units with [adaptive frequency-hopping](https://www.worldronemarket.com/product-category/brand/siyi/), the standard control link for a huge fraction of the world's industrial and FPV drones.

**FPV cameras & video transmission.** **Foxeer, RunCam, Caddx, Walksnail** — the FPV camera and VTX makers. Cameras are, per Ukrainian producers, [the single hardest component to de-China](https://dronelife.com/2026/03/11/ukraine-drone-industry-chinese-parts-supply-chain/) — the last dependency to fall.

**EO/IR payloads, gimbals & thermal cores.** The ISR eye, and a genuine strategic node:
- **DJI Zenmuse, Viewpro, Topxgun, GDU** — stabilized EO/IR gimbal payloads.
- **Thermal detectors** are the deep one. **Raytron (睿创微纳, Yantai, SSE-listed)** is [one of the largest thermal-sensor suppliers to the PLA](https://www.vermilionchina.com/p/evasion-fraud-and-americas-degrading), maker of the world's first 6μm VGA uncooled detector (2024); its affiliate **InfiRay / IRay** dominates commercial thermal optics; **Wuhan Guide Infrared (高德红外)** builds uncooled IR modules for UAVs and missile seekers. Uncooled microbolometer cores are what put night vision on a cheap drone — and China now makes them at scale.
- **Lidar** — **Hesai** and **RoboSense** (both on 1260H) supply the ranging sensors migrating from robotaxis into drones and ground robots.

**Batteries.** **Grepow / Tattu / Gens Ace (Shenzhen)** and **GNB / Gaoneng** produce the bulk of the world's drone-grade LiPo pouch cells (Grepow's semi-solid packs reach ~380 Wh/kg). Behind them stand the cell giants **CATL, EVE, BYD** — which the 2024 NDAA [bars DoD from buying from beginning October 2027](https://www.tycorun.com/blogs/news/top-10-drone-battery-manufacturers-in-china), a rare case where the drone-battery chokepoint got explicit legislative attention.

**Compute — the drone/robot "brain."** Edge-AI SoCs and flight-stack silicon:
- **Rockchip (RK3566/RK3576) and Allwinner** — the embedded AI processors that host onboard vision and autonomy on companion computers.
- **Horizon Robotics (Beijing)** — Baidu-alumni-founded automotive-AI chip house whose edge inference silicon is migrating toward robotics and autonomy. The bridge between the drone/robot layer and the [broader Huawei/SMIC/Cambricon compute stack](./chinese-military-supplier-map.md).

**Materials & magnets — the master chokepoint.** Every motor and actuator turns on a permanent magnet, and China [processes ~90% of the world's heavy rare earths](https://www.gerra.com/insights/humanoid-robot-supply-chain) and dominates **NdFeB** sintered-magnet production. Beijing's [April 2025 rare-earth-magnet licensing regime](https://static.rusi.org/rp-drone-supply-chains-china-nov-2025_0.pdf) turned this into an active lever — it is now scrutinizing Ukraine's magnet access directly. Add carbon-fiber airframes (see the [materials tier](./chinese-military-supplier-map.md): Guangwei, Zhongfu Shenying) and the airframe-to-magnet stack is Chinese end to end.

---

## Layer D — Ground & humanoid robots (embodied intelligence)

China declared **2026 the "mass-production year one" for embodied intelligence**, and the numbers are not hype: [288 robotics financings worth ~¥46B (~$6.8B) in H1 2026 alone](https://eu.36kr.com/en/p/3887956055636481), and the country's [first Humanoid Robotics & Embodied Intelligence Standard System](https://eu.36kr.com/en/p/3887956055636481) issued early in the year. The military relevance is not speculative — the PLA is already exercising with these machines.

**Quadrupeds ("robot dogs").**
- **Unitree (宇树, Hangzhou)** — the global quadruped leader, ~$9B valuation ahead of a STAR Market IPO, [~18,000 quadrupeds and ~5,500 humanoids sold last year](https://kathmandupost.com/world/2026/08/19/how-us-military-funding-propelled-china-s-robot-dogs), 20,000-unit target this year. Its $1,600 Go2 democratized the category; Chinese state TV has shown its **B1/B2** models [armed with a mounted rifle and accompanying PLA troops](https://www.kharon.com/brief/unitree-robotics-china-pla). Unitree publicly insists its products are civilian and signed a 2022 no-weaponization pledge — even as the demonstrations mount. A pointed irony: the underlying quadruped-locomotion research was [seeded by US DEVCOM Army Research Laboratory funding](https://www.militarytimes.com/industry/techwatch/2026/08/18/how-us-military-funding-propelled-chinas-robot-dogs/).
- **DEEP Robotics (云深处, Hangzhou)** — the number-two quadruped house, strong in industrial inspection and increasingly in defense/security patrol roles.

**Humanoids.** The wave that turned in 2025–26:
- **AgiBot / Zhiyuan (智元, Shanghai)** — Alibaba- and Tencent-backed, and by H1 2026 shipments the volume leader with a [~44% global humanoid share and its 15,000th unit](https://interestingengineering.com/ai-robotics/china-agibot-humanoid-robot) off the line; four new models at WAIC 2026.
- **UBTech (优必选, Shenzhen)** — the industrial-humanoid front-runner, first to deliver 1,000+ industrial units and [targeting ~5,000 in 2026, 10,000 by 2027](https://global.chinadaily.com.cn/a/202509/09/WS68bf7e39a3108622abc9f971.html).
- **Unitree (G1/H1), Fourier (GR-3), EngineAI, Galbot** — the rest of a crowded, fast-consolidating field of 20+ serious players.

**The robot component layer — same chokehold, one level down.** Humanoids are ~30–60% actuators by bill of materials, and the actuator is a magnet-plus-reducer problem China increasingly owns:
- **Leaderdrive / Green Harmonic (绿的谐波)** — [broke Japan's harmonic-reducer monopoly](https://humanoid.guide/leaderdrive-harmonic-reducers-surge-as-humanoid-demand-lifts-shares/) at ~40% lower cost (~$4.7B market cap), a primary strain-wave-reducer supplier even to Tesla; **Laifu** is the mid-tier alternative. Japan (Harmonic Drive) still leads the very top tier.
- The same **NdFeB magnet** dependence from Layer C reappears here: roughly [70% of Tesla Optimus's gen-3 component value is Chinese-sourced](https://www.gerra.com/insights/humanoid-robot-supply-chain), and China controls ~63% of key humanoid-component manufacturing. The embodied-AI supply chain is being born Chinese.

---

## Layer E — Counter-UAS (the other side of the board)

China is simultaneously the world's drone arsenal and one of its most invested counter-drone actors — because it expects to face swarms too. The September 3, 2025 parade was a counter-UAS showcase:
- **Lasers.** The **LY-1**, a large ship-mounted (and land-capable) high-energy laser [unveiled at the parade](https://www.twz.com/news-features/chinas-imposing-ly-1-high-power-laser-weapon-unveiled-at-huge-military-parade); and the export-proven **Silent Hunter** (China Poly Technologies), a [30 kW fiber laser effective to ~4 km](https://en.wikipedia.org/wiki/Silent_Hunter_(laser_weapon)) that Saudi Arabia has used against Houthi drones.
- **High-power microwave.** The **Hurricane 3000** mobile HPM system (revealed 2026), purpose-built for saturated swarm attacks — area effects against many cheap drones at once.
- **Interceptors & jammers.** AI-assisted autonomous interceptor drones and RF jammers round out a [layered anti-swarm doctrine](https://www.defenseone.com/technology/2025/05/chinas-counter-uav-efforts-reveal-more-technological-advancement/). The counter-UAS market is itself a supplier ecosystem worth its own map.

---

## Layer F — The autonomy brain

What ties it all together is software and edge compute: swarming autonomy, computer-vision targeting, and the vision-language-action (VLA) models now driving both the humanoids and the drone swarms. This layer overlaps directly with the [AI-compute stack](./chinese-military-supplier-map.md) — Huawei Ascend accelerators, Cambricon, and the domestic-model ecosystem (including PLA experimentation with DeepSeek-class models on Ascend hardware) — plus the edge silicon (Rockchip, Horizon) from Layer C. The platforms are increasingly commodities; the swarm-coordination and autonomy software is where the next advantage is being contested, and China is pushing hard on VLA models as the common brain for drones and robots alike.

---

## The unheralded ten (drone & robot edition)

Below the DJIs and Unitrees, these are the load-bearing, mostly-unsanctioned nodes worth an analyst's attention:

1. **T-Motor** — 80–90% of the world's FPV drone motors run through this and a handful of peers.
2. **Hobbywing** — the dominant ESC/drivetrain maker, now crossing into robotics.
3. **Raytron / InfiRay / Guide Infrared** — uncooled thermal detector cores; night vision on a cheap drone, and missile seekers.
4. **SIYI & Skydroid** — the control-and-datalink spine of the global industrial/FPV fleet.
5. **Grepow / Tattu** — the drone-grade LiPo pouch cell the whole world flies on.
6. **Leaderdrive / Green Harmonic** — broke Japan's harmonic-reducer monopoly; the humanoid actuator's core part.
7. **Rockchip / Horizon Robotics** — the edge-AI brains hosting onboard autonomy.
8. **CUAV / JIYI** — the flight controllers inside industrial and agricultural drones.
9. **AgiBot / Zhiyuan** — the humanoid volume leader almost no Western reader can name.
10. **NdFeB magnet supply (rare-earth processing)** — the master chokepoint under every motor and actuator on this page.

---

## Chokepoints & the reverse lever

The strategic punchline runs opposite to every other chapter of the defense-industrial story. Elsewhere China is the dependent party (engines, lithography, EDA). Here *the West is* — and Beijing has begun to use it:

- **Magnets and rare earths.** The [April 2025 magnet-licensing regime](https://static.rusi.org/rp-drone-supply-chains-china-nov-2025_0.pdf) lets Beijing meter the single most irreplaceable input to everyone else's drones and robots. It is already scrutinizing Ukraine's access.
- **The Ukraine decoupling test.** Ukraine went from [~5,000 FPVs in 2022 to 4.5 million in 2025](https://en.clickpetroleoegas.com.br/ukraine-manufactures-fpv-drone-circuit-boards-and-motors-in-basements-to-reduce-dependence-on-china-after-restrictions-in-2023-and-2024-jump-ctl01/) and stood up domestic motor lines (Motor-G at ~200k/month, ~27% of demand) — and still can't make its own cameras. That is the best real-world measure of how deep the dependency goes.
- **US countermeasures.** The FCC Covered List (DJI/Autel), the 1260H expansions, and the NDAA battery-procurement bans are the policy response — but they restrict *purchasing*, not China's *production*, and they keep having to widen because the dual-use surface is so large.

The uncomfortable synthesis: on drones and robots, export controls are a tool China wields more effectively than the US, because for once China is upstream.

---

## Sources & further reading

- RUSI, [*Decoupling Drone Supply Chains from China*](https://static.rusi.org/rp-drone-supply-chains-china-nov-2025_0.pdf) (November 2025) — the flagship component-layer analysis
- Flight Global, [inside the PLA's collaborative-combat-aircraft push](https://www.flightglobal.com/military-uavs/inside-the-plas-push-for-collaborative-combat-aircraft/166398.article); The War Zone on [China's air-combat drones](https://www.twz.com/air/glimpses-of-chinas-new-air-combat-drones-emerge-ahead-of-massive-military-parade) and the [LY-1 laser](https://www.twz.com/news-features/chinas-imposing-ly-1-high-power-laser-weapon-unveiled-at-huge-military-parade)
- The Aviationist / Army Recognition on the [Jiutian SS-UAV maiden flight](https://theaviationist.com/2025/12/11/china-jiutian-drone-mothership/); GlobalSecurity on the [CH-7](https://www.globalsecurity.org/military/world/china/ch-7.htm)
- Kharon and Military Times on [Unitree's PLA connections](https://www.kharon.com/brief/unitree-robotics-china-pla) and the [DEVCOM-funding origin](https://www.militarytimes.com/industry/techwatch/2026/08/18/how-us-military-funding-propelled-chinas-robot-dogs/)
- 36Kr on [China's humanoid mass-production year](https://eu.36kr.com/en/p/3887956055636481); Interesting Engineering on [AgiBot/Zhiyuan at WAIC 2026](https://interestingengineering.com/ai-robotics/china-agibot-humanoid-robot); CS Monitor on the [embodied-AI push](https://www.csmonitor.com/World/Asia-Pacific/2026/0828/china-ai-humanoid-robots-strategy)
- Gerra and Morgan Stanley ("Humanoid 100") on the [humanoid value chain](https://www.gerra.com/insights/humanoid-robot-supply-chain); Humanoid.guide on [Leaderdrive harmonic reducers](https://humanoid.guide/leaderdrive-harmonic-reducers-surge-as-humanoid-demand-lifts-shares/)
- DroneLife and DroneXL on [Ukraine's de-China effort](https://dronelife.com/2026/03/11/ukraine-drone-industry-chinese-parts-supply-chain/); Vermilion China on [Raytron/thermal sensors and the PLA](https://www.vermilionchina.com/p/evasion-fraud-and-americas-degrading)
- Wingtra / Commercial UAV News on the [FCC Covered List and the DJI/Autel ban](https://knowledge.wingtra.com/en/dji-ban-ndaa-compliance)
- DoD *Military and Security Developments Involving the PRC*, December 2025; DoD Section 1260H list, June 2026

*Caveats: market-share figures for component categories come from industry trackers and the RUSI report and are best treated as orders of magnitude, not precise counts. Company-to-PLA links range from documented (DJI, Raytron, Unitree state-TV demos) to inferential (many component makers simply sell into a supply chain the PLA also draws on); the text flags which is which. The robotics field is consolidating monthly — shipment and share figures are a mid-2026 snapshot.*
