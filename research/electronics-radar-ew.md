# China's Electronics, Radar & Electronic Warfare

*The domain that decides whether every other system can see and shoot — and the one where a single conglomerate, CETC, sits closest to the world's frontier. The radar leap, the gallium-nitride foundation beneath it, and the physics behind the marketing.*

*Part of the [China Defense-Industrial Atlas](https://claude.ai/code/artifact/ecc69e75-bcc3-46cf-a303-3b95f8ac9b4c); CETC's numbered institutes are mapped in the [PLA Supplier Atlas](https://claude.ai/code/artifact/9ba26611-80ca-456b-b489-06bce1b350ed). Updated 31 August 2026.*

---

## The invisible domain that ties the atlas together

Radar, electronic warfare, secure communications and C4ISR are the connective tissue of "informatized warfare" — the sensors and datalinks that let a missile find a carrier, a fighter cue a wingman, or a swarm coordinate. Nothing else in the atlas works without this layer. A hypersonic glide vehicle with no targeting picture is an expensive firework; a Type 055 with no air-search radar is a target.

It is also the domain where China's national champion, **CETC (China Electronics Technology Group)**, sits closest to the global frontier. The atlas rates it **Competitive** — world-class in parts, still dependent in a few — and the story is really the story of one conglomerate's numbered institutes.

The underappreciated fact is that China's radar leap of the last decade was, underneath, a **compound-semiconductor leap** — a shift to gallium-nitride transmit/receive modules — executed by institutes most people have never heard of. And in a twist that ties back to the atlas's reverse-leverage theme, China also controls the **gallium supply** those modules depend on.

---

## The company nobody can name

CETC is the most consequential Chinese defense enterprise that has no public profile, and its shape explains why. It is not a company that designs things; it is a **holding structure over roughly fifty numbered research institutes**, each a substantial design house in its own right, many with their own fabs, listed subsidiaries and export arms. "CETC designs nothing; its institutes design everything" is only a slight exaggeration.

Two acquisitions widened it further: **China Putian** (telecoms) folded in during 2021, and **China Hualu** (data storage and recording) in 2023. Listed vehicles like Guorui provide public windows into slices of the portfolio; historically Hikvision sat in the same orbit. The conglomerate is 1260H-listed and OFAC-sanctioned, with several institutes — including the 14th, 38th, 13th and 55th — on the Commerce Entity List.

For an analyst the practical consequence is that **institute numbers, not the corporate name, are the unit of analysis.** A sanctions action against "CETC" means far less than one against the 55th Institute, and a program attribution to CETC tells you almost nothing until you know which institute drew it.

### The customer reorganized too

In April 2024 the PLA restructured the organizations that buy and operate this equipment. On 19 April the **Strategic Support Force was dissolved** — after just over eight years — and replaced by three bodies reporting directly to the Central Military Commission: an **Aerospace Force**, a **Cyberspace Force**, and an **Information Support Force**, the last elevated to deputy-theater-command grade. Flattening these into direct CMC subordination signals that information support is treated as a foundational joint enabler rather than a service specialty — which is precisely the integration problem discussed below, and worth watching as a structural attempt to solve it.

---

## The radar portfolio

- **Fighter AESAs — now combat-credentialed.** The **14th Institute (Nanjing)** builds fire-control AESAs for Chinese fighters, and the exported **KLJ-7A** acquired a real-world résumé in May 2025: mounted on Pakistan's J-10CE, it was [credited with a central role in downing Indian aircraft](https://defencesecurityasia.com/en/china-klj-7a-radar-j-10ce-rafale-india-pakistan-air-war/) in the India–Pakistan air clash. That is the first high-visibility combat test of a Chinese AESA against Western-supplied jets — and, given how thin combat evidence is across this entire atlas, one of the very few data points of its kind. The details remain contested; the marketing value did not depend on them.
- **Shipborne AESAs.** The 14th's **Type 346** family arms the Type 055 cruiser and the fleet's air-defense combatants — the naval radar backbone (see the [naval essay](./naval-undersea-suppliers.md)).
- **Counter-stealth early warning — the signature bet.** The **38th Institute (Hefei)** anchors the anti-stealth push. The **JY-27V** (unveiled May 2025) is a large, rapidly deployable low-frequency AESA that [claims to detect "extremely stealthy" targets and cue precision strikes](https://www.scmp.com/news/china/military/article/3311054/china-aims-new-jy-27v-radar-stealthy-targets-such-americas-fifth-gen-fighters), improving on the JY-27A with a bigger antenna, lower band, larger power aperture and better signal processing; the **SLC-7** adds a multifunction, anti-jam set tracking everything from stealth aircraft to artillery shells.

---

## Why low-band radar works against stealth — and why it isn't enough

This is the most important technical point in the domain, and it explains both China's bet and its limit.

Stealth aircraft are not invisible; they are **optimized against a particular slice of the spectrum**. Shaping and radar-absorbent materials are designed to defeat the centimetric-wave fire-control radars that actually guide missiles — X-, C- and S-band, wavelengths of a few centimetres. Against those, faceting redirects energy away from the emitter and coatings absorb what remains.

Drop the frequency far enough and the physics changes. When the radar wavelength becomes comparable to the *physical dimensions of airframe features* — wing edges, control surfaces, tail structures — scattering leaves the optical region and enters the **resonance region**, where the returns are governed by structural dimensions rather than surface shaping. VHF and UHF radars, with wavelengths measured in metres rather than centimetres, sit squarely there. Shaping advantages collapse, and radar-absorbent material tuned for X-band does comparatively little. This is real physics, not propaganda, and it is why low-band counter-stealth is a coherent strategy rather than a stunt.

**The catch is angular resolution.** Beamwidth scales with wavelength divided by aperture, so a metre-wavelength radar needs an enormous antenna to achieve even mediocre angular precision. In practice a large VHF array still produces beamwidths measured in degrees — and a few degrees of angular error at a couple of hundred kilometres is a positional uncertainty of kilometres. That is more than adequate to know *something stealthy is out there and roughly where*, and nowhere near enough to put a missile's seeker basket on it.

Hence the distinction the honest version of this analysis turns on: **detection is not a weapons-quality track.** Low-band gives you early warning and cueing. Killing requires handing that cue to a higher-frequency fire-control sensor, or fusing multiple geometrically separated sensors into a track tight enough to shoot on — under jamming, in real time, across services.

Which lands exactly on China's acknowledged weakness. The counter-stealth problem is not really a radar problem for China any more; it is an **integration problem**, and integration is the part that does not parade well. Note also the strategic asymmetry: this same physics means the emerging Chinese counter-stealth belt degrades the value of the US stealth investment without China needing stealth parity of its own — a cheaper counter than the thing it counters.

---

## The gallium-nitride foundation — and the gallium lever

- **The T/R modules.** A modern AESA is thousands of small transmit/receive modules, and **GaN** delivers roughly five to ten times the RF power density of the older gallium-arsenide devices — more power per module means longer detection range, better jam resistance and more graceful degradation. China's **13th and 55th Institutes (Shijiazhuang / Nanjing)** are the compound-semiconductor houses behind those modules: genuinely unheralded, genuinely load-bearing. The radar leap is downstream of them, and so is much of the EW hardware.
- **A useful asymmetry.** Defense RF electronics do not need leading-edge silicon. GaN devices are built on mature process nodes, which means this part of the Chinese defense-electronics base is **structurally insulated from the lithography chokepoint** that dominates the [semiconductor essay](./semiconductor-chokepoint.md). Export controls aimed at 7nm logic simply do not reach a GaN foundry — a distinction that often gets lost when "chip controls" are discussed as though they constrain everything.
- **The reverse-leverage twist.** GaN starts with gallium, and China [dominates global gallium supply](https://features.csis.org/hiddenreach/china-critical-mineral-gallium/) at roughly 80% of refined output — a chokepoint it began weaponizing with export licensing in 2023 and hardened into an outright US ban in December 2024 (see [critical minerals](./critical-minerals-materials.md)). China builds the radar modules *and* meters the raw material every other radar industry needs.

---

## Electronic warfare and the kill chain

The **29th Institute (Chengdu)** is China's airborne-EW center of gravity — the jamming and spectrum-warfare suite on the **J-16D**, and much of the PLA's electromagnetic arsenal, traces here. The **54th Institute (Shijiazhuang)** supplies the other half: military satellite communications, ground stations and the datalinks that stitch sensors to shooters.

Together they constitute the "systems-destruction warfare" toolkit that PLA doctrine explicitly favors — see the adversary first, blind their sensors and sever their links, then strike the resulting fragments. It is worth noticing that this doctrine is *itself* a bet on the integration layer: destroying an opponent's networked picture only wins if yours survives, which puts CETC's datalink and satcom work at the center of the theory rather than the periphery.

Beyond the headline five, the institute system runs deep: the **10th (Chengdu)** in avionics and airborne communications, the **20th (Xi'an)** in navigation and datalinks, the **41st** in electronic test and measurement instrumentation — that last one quietly important, since high-end RF test gear is itself a Western-dominated niche and a real dependency for anyone building microwave hardware at volume. Meanwhile the 14th Institute has been pushing into in-house **AI accelerators** through its Huachuang Micro arm, with tape-outs reported in February 2026: a radar house building its own inference silicon, because signal processing is where radar advantage increasingly lives.

One structural point often missed: CETC is not a monopoly. **AVIC's 607 (Leihua) Institute** competes directly for fighter fire-control radar work. Genuine internal competition between two capable design houses is unusual in the Chinese defense enterprise and is plausibly part of why airborne radar improved as fast as it did.

---

## The reality gap — the honest hedge

The marketing runs ahead of the proof. A [January 2026 report on Venezuela's Chinese-made JY-27A radars](https://asiatimes.com/2026/07/chinas-anti-stealth-shield-has-a-radar-reality-gap/) during a US operation cited maintenance problems, limited readiness and weak integration. Exported readiness is a genuine signal — it reflects training, sustainment and systems engineering, not just hardware — though it is an imperfect proxy for how the PLA operates the same equipment at home with far better support.

Layer that on the physics above and the honest position is clear: China's radar hardware is excellent and in some respects world-leading; the claims about what that hardware *delivers operationally* rest on assertions nobody outside can verify. This is precisely the pattern the [methodology page](./methodology-and-confidence.md) grades B rather than A — strong documented capability, inferential operational conclusions.

---

## Where it's competitive, not dominant

- **High-end EDA.** Advanced RF and mixed-signal design still leans on Western design software — the semiconductor domain's chokepoint reaching into this one. The May 2025 Synopsys/Cadence/Siemens cutoff, reversed within weeks as part of the rare-earths truce, showed both the leverage and how readily it gets traded.
- **Test and measurement.** High-end RF instrumentation remains a Western-dominated niche; you cannot characterize what you cannot measure.
- **Systems integration and data fusion.** Turning many excellent sensors into one coherent, resilient, weapons-quality picture — under jamming, across services — is the harder, less-visible edge, and where Western C4ISR retains an advantage. The April 2024 Information Support Force reorganization reads as an institutional attempt to attack exactly this.
- **Proven performance.** Combat evidence is thin outside the contested Pakistan example, and the Venezuela case cuts the other way.

---

## Assessment

CETC has taken Chinese radar and EW from generations behind to genuinely competitive — world-leading in some areas (low-band counter-stealth, GaN module volume) while holding a raw-material chokepoint over everyone else's radar industry. Its GaN base is also, unusually, insulated from the lithography controls that constrain the rest of Chinese electronics.

What separates competitive from dominant is the part that does not parade well: weapons-quality integration under fire, and residual dependence on Western design tools and test equipment. The counter-stealth bet is physically sound and strategically clever — it devalues the US stealth investment more cheaply than matching it would — but it converts into kills only through the fusion layer where China is weakest and where the evidence is thinnest.

A strong domain with an asterisk, and the asterisk is an integration problem rather than a hardware one.

---

## Sources & further reading

- SCMP on the [JY-27V counter-stealth radar](https://www.scmp.com/news/china/military/article/3311054/china-aims-new-jy-27v-radar-stealthy-targets-such-americas-fifth-gen-fighters); Asia Times, "[China's anti-stealth shield has a radar reality gap](https://asiatimes.com/2026/07/chinas-anti-stealth-shield-has-a-radar-reality-gap/)"
- Defence Security Asia on the [KLJ-7A and the India–Pakistan air war](https://defencesecurityasia.com/en/china-klj-7a-radar-j-10ce-rafale-india-pakistan-air-war/); EurasianTimes on [GaN and Chinese military tech](https://www.eurasiantimes.com/china-gallium-nitride-game-for-pla/)
- CSIS Hidden Reach, "[China's Control over Gallium](https://features.csis.org/hiddenreach/china-critical-mineral-gallium/)"
- Jamestown Foundation, "[A Disturbance in the Force: The Reorganization of PLA Command and Elimination of the Strategic Support Force](https://jamestown.org/a-disturbance-in-the-force-the-reorganization-of-peoples-liberation-army-command-and-elimination-of-chinas-strategic-support-force/)"; Defense News on the [SSF dissolution](https://www.defensenews.com/global/asia-pacific/2024/04/23/china-dissolves-strategic-support-force-focused-on-cyber-and-space/), April 2024
- GlobalSecurity and the PLA Supplier Atlas (this corpus) for the CETC institute breakdown; DoD *Military and Security Developments Involving the PRC*, December 2025

*Caveats: counter-stealth performance claims are Chinese-sourced and contested; the resonance-region physics is well established, but "detect" does not equal "weapons-quality track," and no open source establishes what track quality these systems actually achieve. The KLJ-7A combat account rests on partial and disputed reporting. Institute role attributions carry the usual open-source uncertainty. A 2026 snapshot.*
