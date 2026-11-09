# GZW crafting / production data (rebuilt from scratch)

Amounts are per 1 craft. Vendor prices are per single item (x1), regardless of stack size (confirmed by user). Chemicals/medical prices are from Lab Rat, electronics prices from Artisan.

## Laboratory - Production

| Product | Ingredients | Time |
|---|---|---|
| Low-Quality Morphine Base | Opium Gum 1, Garden Lime 1, Ammonium Chloride 1, Purified Water 1 | 1h 0s (0.5.1.0 lab screen; was 2h) |
| 10% Morphine Solution | Low-Quality Morphine Base 1, Citric Acid 1, Purified Water 1 | 1h 30m 0s (0.5.1.0 lab screen; was 5h 30m) |
| Medium-Quality Morphine Base | Opium Gum 1, Garden Lime 1, Ammonium Chloride 1, Purified Water 1 | 1h 30m 0s (0.5.1.0; was 2h) |
| High-Quality Morphine Base | Opium Gum 1, Garden Lime 1, Ammonium Chloride 1, Purified Water 1 | 2h 0s |
| Stabilized Morphine Sulfate Liquid | Medium-Quality Morphine Base 1, Sulfuric Acid 1, Methylparaben 1, Saline 1 | 2h 0s (0.5.1.0; was 5h 30m) |
| USP Morphine Sulfate (NEW, 5 kg) | High-Quality Morphine Base 1, Sulfuric Acid 1, Sodium Citrate 1, Edetate Disodium 1 | 2h 30m 0s (no sell price seen yet) |

## Laboratory - Crafting (all 1s)

| Product | Ingredients |
|---|---|
| Fenethylline | Glucose 1, Theophylline 1 |
| Methylphenidate | Glucose 1, Bromopyridine 1 |
| EPO | Empty Autoinjector 1, Vitamin B12 1, Iron Sucrose 1 |
| ORI-12 | Empty Autoinjector 1, Bone Density Stimulant 1 |
| DT-0X | Empty Autoinjector 1, Methylene Blue 1 |
| HPR 3-S | Empty Autoinjector 1, Human Growth Hormone 1 |
| Morphine | Empty Autoinjector 1, High-Quality Morphine Base 1, Saline 1 |
| Strychnine | Empty Autoinjector 1, Aniline 1, Methanol 1 |

## Electronics Workshop - Crafting (all 1s)

| Product | Ingredients |
|---|---|
| Basic Tracking Tag | Electrical Parts 1, Civilian Software 1 |
| Basic Hacking Tool | Multi-Bus Converter 1, CPU Card 1, Spoofing ASIC Module 1 |
| Tracking Tag | Electrical Parts 1, Civilian Software 1, Circuit Board 1 |

## Short name -> long name -> vendor sell price

Match basis: A = abbreviation clearly derives from the long name AND icon matches; I = matched by icon/item art only (abbreviation alone is ambiguous).

| Short name | Long name | Sell price | Basis |
|---|---|---|---|
| OGum | Opium Gum | $150 | A |
| Lime | Garden Lime | $15 | A |
| AmChl | Ammonium Chloride | $45 | A |
| PWat | Purified Water | $30 | A |
| CAcid | Citric Acid | $15 | confirmed by user |
| Acid | Sulfuric Acid | $39 | confirmed by user |
| HAcid | Hydrochloric Acid | $150 | confirmed by user (not used in any recipe seen) |
| AcAnh | Acetic Anhydride | $75 | confirmed by user (not used in any recipe seen) |
| Ether | Ether | $90 | confirmed by user (not used in any recipe seen) |
| Ethanol | Ethyl Alcohol | $90 | confirmed by user (not used in any recipe seen) |
| Chlor | Chloroform | $45 | confirmed by user (not used in any recipe seen) |
| SodCar | Sodium Carbonate | $36 | confirmed by user (not used in any recipe seen) |
| SodCit | Sodium Citrate | $45 | confirmed by user (not used in any recipe seen) |
| EDTA | Edetate Disodium | $75 | confirmed by user (not used in any recipe seen) |
| MePa | Methylparaben | $90 | A |
| Saline | Saline | $15 | A |
| StMSL | Stabilized Morphine Sulfate Liquid | $6,000 (shown as $6K, exact) | A |
| 10MS | 10% Morphine Solution | $4,000 (shown as $4K, exact) | A (tooltip confirms name) |
| Gluc | Glucose | $15 | A |
| Theoph | Theophylline | $30 | A |
| Brompyr | Bromopyridine | $30 | A |
| EAInj | Empty Autoinjector | $15 | A |
| B12 | Vitamin B12 | $30 | A |
| IronSuc | Iron Sucrose | $30 | A |
| BoneDS | Bone Density Stimulant | $30 | A |
| Metblue | Methylene Blue | $30 | A |
| HGH | Human Growth Hormone | $30 | A |
| Anil | Aniline | $30 | A |
| Methol | Methanol | $30 | A |
| Fenethyl | Fenethylline | $29 | A |
| Methyl | Methylphenidate | $63 | A |
| ORI-12 | ORI-12 | $255 | A |
| DT-0X | DT-0X | $180 | A |
| HpR 3-S | HPR 3-S | $285 | A |
| Strych | Strychnine | $180 | A |
| EPO | EPO | $219 | A (seen in Injector Case) |
| CivSoft | Civilian Software | $75 | A (icon matches recipe tile) |
| PCB | Circuit Board | $45 | I (abbreviation = printed circuit board; icon matches recipe tile) |
| LQMB | Low-Quality Morphine Base | $2,000 (shown as $2K at Lab Rat and Vulture) | A (short name seen in locker; label on item reads "MORPH LOW Q") |
| (no short name seen) | Medium-Quality Morphine Base | $2,500 (shown as $2.5K at Vulture; label on item reads "MORPH. MED Q") | A (item label) |
| Morph | Morphine (injector) | $135 (Lab Rat) | A |
| HQMB | High-Quality Morphine Base | $3,000 (shown as $3K at Lab Rat and Vulture) | 2026-11-03 18:48/20:07 batch |
| DSLog | Deep-Space Observation Data Drive (RSP disassembly) | $12K at Handshake, Gunny, Lab Rat, Artisan, Turncoat, Banshee; Vulture cut off ($12.…) | 20:46 batch |
| DPBoard | High-Speed Digital Processor Board (RSP disassembly) | $1.2K at Lab Rat only | 20:46 batch |
| GRing | (short name only) | $615 at most vendors, Turncoat $820, Vulture $656 | 20:07 batch |
| GCCard | (short name only) | $1.6K at most vendors, Artisan $2.2K, Vulture $1.8K | 20:07 batch |
| LPhone | (short name only) | $750 at most vendors, Lab Rat $1K, Vulture $800 | 20:07 batch |
| DriBit | (short name only) | $60 at Artisan only | 20:07 batch |
| B Hack | Basic Hacking Tool | no price shown (greyed out at Artisan, not sellable there) | A (item art matches) |

## Not matched

Production/crafting names with no inventory item seen: High-Quality Morphine Base, Electrical Parts, Multi-Bus Converter, CPU Card, Spoofing ASIC Module, Basic Tracking Tag, Tracking Tag.

Electronics items seen in the Rush 72 2.0 backpack that do not match any of the missing ingredient icons (checked side by side; not guessed): SSteel $45, PSU $75, RAM $90, EKLog $9K, EWLog $12K, MilSoft $75, Pipette $150, DSE (no price shown), FPGA (no price shown). FPGA looks like a long expansion card but its art differs from the CPU Card tile, and DSE differs from the Multi-Bus Converter tile.

Inventory short names with no matching production/crafting name (long name unknown; not guessed): LHem $63, SurKit $195, Splint $17, Ibalin $7, Moxiflox $37, KI $18, LBlood $294, MBlood $225, SBlood $84, Gauze $2, Bandage $9, SBand $16.

Gear seen without a visible price or no match attempted: Steel, Rush (backpack), AK-74N, AMP12 (backpack), Trekstars.

## Injector prices (Lab Rat, per item, from Injector Case views)

Strychnine $180, HPR 3-S $285, ORI-12 $255, EPO $219, DT-0X $180 (locker view). Morphine ($135 at Lab Rat) was found in the 2026-11-03 locker views. LHem ($63, injector-looking item in locker) has no recipe and stays unmapped.

## Images analyzed (146)

Production/crafting: 20261102142056, 142059, 142100, 142102, 142104, 142109, 142110, 142112, 142113, 142116, 142117, 142121, 142123, 142127, 142129, 142131 (all `_1.jpg`)

Inventory: 20261102142625_1.jpg (names, locker), 20261102142629_1.jpg (prices, locker), 20261102142652_1.jpg (prices, AMP12 popup), 20261102142701_1.jpg (names, AMP12 popup), 20261102143249_1.jpg (names, Rush 72 2.0 popup), 20261102143253_1.jpg (prices, Rush 72 2.0 popup, Artisan), 20261102144738_1.jpg (names, Injector Case popups), 20261102144821_1.jpg (prices, Injector Case popups, Lab Rat), 20261102155632_1.jpg (prices, 10% Morphine Solution), 20261102155636_1.jpg (prices + tooltip name), 20261102155638_1.jpg (names, 10MS), 20261102203207_1.jpg (Vulture vendor, weapons list + locker; only price on a recipe item: Medium-Quality Morphine Base $2.5K), 20261102205916_1.jpg (Lab Rat, locker; nothing new), 20261102224938_1.jpg (Lab Rat, locker; Low-Quality Morphine Base $2K), 20261102224940_1.jpg (Vulture, locker; Low-Quality Morphine Base $2K)

Note: vendors pay different amounts for the same item (e.g. camera $960 at Lab Rat vs $1K at Vulture, card $450 vs $480). Medium-Quality Morphine Base's $2.5K was seen at Vulture only.

## Quest hand-ins

| Quest | Items | Payout (user-provided) | Cost | Time | Profit | Profit/h |
|---|---|---|---|---|---|---|
| Lab Rat: hand in 5x 10% Morphine Solution | 5 crafts of 10% Morphine Solution | $30,000 | $10,225 (5 x $2,045, Low-Quality base at $2,000 sell value) | 27h 30m (5 x 5h 30m, one at a time) | +$19,775 | about +$719/h |

2026-11-03 batch (28 images, all locker views at each vendor): 20261103093042, 093044, 093106, 093115, 093121, 093155, 093157, 093159, 093200, 093201, 093203, 093205, 093212, 093213, 093214_1, 093214_2, 093215, 093216, 093217, 093221, 093222_1, 093222_2, 093223, 093224, 093225, 093226 (all `_1.jpg` unless noted). Names-only views: 093044, 093106, 093115, 093121. Vendor price views: the rest.

2026-11-03 12:16 batch (8 images, locker view at each of the 7 vendors plus a names view): 20261103121614, 121616, 121617, 121619, 121620, 121621, 121622 (vendors in tab order Handshake to Vulture), 121624 (names, Character > Gear tab). Nothing new for crafts. 13 new matrix items, all checked at all 7 vendors:
- Weapon parts, bought by Gunny, Artisan, Turncoat and Banshee at identical prices (Handshake, Lab Rat, Vulture do not buy): M-Lok 3 $8, FAST... $354, BCM M... $174, G36 Stock $95, AK CR... $121, AK GA... $102, G36 HG $142, G36 12... $138. Names with ... are truncated by the game UI; full names unknown.
- The two Crusher helmets ($6.1K and $2.8K at Handshake and Turncoat) were removed from the data and matrix on request.
- HF2 Hut: Artisan $60 only. Ring: $112 at five vendors, Turncoat $150, Vulture $120. BLPhone: $1.1K, Lab Rat $1.5K, Vulture $1.2K. DriverLic: $262, Handshake and Banshee $350, Vulture $280.
- Not bought anywhere, so not in the matrix: Wallet, PROP SC, Inj C (injector case), Trekstars and AMP12 backpacks. USD (571) shows a faded $1 label with the cross at every vendor, so it is treated as not bought.
- All other prices in the batch match the saved data.

## Workshop disassembly (2026-11-03 12:56 batch, 13 images)

Images: 20261103125613, 125617, 125627, 125629, 125635, 125637 (Electronics Workshop > Disassembly queue and item dialogs), 125705 to 125723 (vendor views, one per vendor in tab order, with the disassembly components in a Rush 72 2.0 backpack popup).

Disassembly materials give two components each (the dialog shows one icon per component, so one of each is assumed):
| Material | Time | Components |
|---|---|---|
| Radar Signal Processor (RSP) | 7h 50m | Deep-Space Observation Data Drive, High-Speed Digital Processor Board (neither found in the backpack, no price yet) |
| Manpack Tactical Radio (TacRad) | 12h | Encryption Key Drive (= EKLog icon, $9K, Vulture $9.6K), FPGA Module ($900 at Lab Rat only) |
| ST1122 Storage Computer (StComp) | 6h (0.5.1.0; was 12h) | Incriminating Data Drive (grey drive, $9K, Vulture $9.6K), Server RAM Module (no price found; the RAM item at Artisan $90 has a green board where the dialog icon is blue, so it was not assumed to be the same) |

Valuation rule (user): disassembly material is valued raw (best vendor price for the item) and disassembled (sum of the best vendor price for each component). The page shows both in a table under the matrix. Result so far: TacRad raw $3K (Artisan) vs $10.5K disassembled; StComp raw $3K vs at least $9.6K. RSP raw price unknown.

Other findings: EKLog, IncrDD (new), EWLog $12K (Vulture price cut off in the screenshot, shown as ?), DSE $1.2K at Lab Rat, FPGA $900 at Lab Rat. The two backpack items seen at Lab Rat are now identified: the jug is PWat (Purified Water, already tracked at $30), and the 2x2 board is the Avionics Processor (AvProc, $900 at Lab Rat), a disassembly product of the Baget-53-31 Onboard Computer (not owned yet; its other components, raw price and time are unknown).

## Vendor price tracking

Full per-vendor price data is in `vendor_prices.json` (404 price rows, 7 vendors, 116 items; 29 rows come from the 2026-11-02 screenshots where only one vendor was looked at). The page's Vendor sell matrix tab embeds this data. An item with no row for a vendor shows a cross if it was checked at all vendors in the 2026-11-03 batch, otherwise a question mark. Craft-relevant findings from the 2026-11-03 batch:
- Low-Quality Morphine Base $2K and Medium-Quality Morphine Base $2.5K at both Lab Rat and Vulture. Handshake, Gunny, Artisan, Turncoat and Banshee do not buy them.
- Stabilized Morphine Sulfate Liquid $6K at Lab Rat only. No other vendor showed a price.
- Morphine injector $135 at Lab Rat. High-Quality Morphine Base is $3K at Lab Rat and Vulture (18:48 batch), so the Morphine injector costs $3,030 to craft and sells for $135 (-$2,895 per craft; the base is worth more sold raw).
- Ammo and magazines in the 18:48/20:07 screenshots were deliberately not added (many stacks with truncated names); pending the user's decision.
- All chemicals, injectors and medical items were priced at Lab Rat only; Civilian Software $75, MilSoft $75 and RAM $90 at Artisan only.
- Items with uses left (SurKit, SutKit, Ibalin, bandages) are priced by uses left, so a full kit shows more than a used one.

## Standing rules (from the user)

- Vendor sell matrix icons: for every new item encountered in a screenshot, crop its icon from the screenshot (the short-name label may stay in the crop) and use it in the Vendor sell matrix. Image id is `vp_<short name>` (lowercase, non-alphanumerics to `_`), for example `vp_ekLog` becomes `vp_eklog`; the page picks it up automatically. Recipe items keep their existing icons.
- Only craft and production information is added to the Want list, Full list and Backend data tabs. Vendor data for everything else goes into `vendor_prices.json` and the matrix.
- Ignore helmets and weapons in screenshots going forward (do not add them to the matrix or the price data). Weapon parts (grips, stocks, handguards, sights, barrels, rails) are still tracked. The two Crusher helmets that were in the data were removed on request.

- Do not track ammo or magazines (user decision 2026-11-03).
- Server RAM Module is a disassembly product of the ST1122 Storage Computer (StComp). The green "RAM" sold at Artisan for $90 is separate loose loot; do not equate the two.

- 2026-11-03 20:46/20:49 batches: the RSP disassembly components are in-game short names DSLog (Deep-Space Observation Data Drive) and DPBoard (High-Speed Digital Processor Board), so the RSP disassembled value is at least $13,200. Second batch only re-showed HQMB ($3K Lab Rat and Vulture) plus a G36 rifle (ignored).

## 2026-11-03 21:15 batch (8 images: names + 7 vendors)
New items added to the Vendor sell matrix only (no craft relevance), with icons:
- Weapon parts (Gunny, Artisan, Turncoat, Banshee pay the same; Handshake, Lab Rat, Vulture do not buy): EXPS2 $165, RMR $190, NcStar... $105, CQBL-1 $405, PERST-4 $660, STS M... $150, FTC O... $204, AEMS... $36, LS Mou... $67, AK12 Sport $375.
- LBoonie $4 (Handshake, Turncoat only). Perfume $112 (Gunny $150, Vulture $120). Tzintzi... $1.5K (Gunny $2K, Vulture $1.6K). Azart $825 (Vulture $880). ENeckl... $4K (Turncoat $5.3K, Vulture $4.2K). Neckla... $135 (Turncoat $180, Vulture $144). LWatch $450 (Turncoat $600, Vulture $480). DCRing $3.9K (Turncoat $5.3K, Vulture $4.2K). PCCard $4.5K (Artisan $6K, Vulture $4.8K). AFRKit $285 (Gunny and Lab Rat only).
- Ignored on purpose: Crusher helmet, VMAX ammo, MP7 mags, M67/F-1 grenades (weapons), USD stacks, Rush/Trekstars backpacks. Items already known were not re-added.

## 2026-11-04 batches (26 images)
Added to the Vendor sell matrix only, with icons:
- Weapon parts: MP7 Rotex $357 and MCX G... $61 (Gunny, Artisan, Turncoat, Banshee only).
- Spirits and valuables: Breda $2.9K (Gunny $3.8K, Vulture $3K), Allanach $4.1K (Gunny $5.5K, Vulture $4.4K), Goodlad $337 (Gunny $450, Vulture $360), ANPY... $3.2K (Vulture $3.4K), GDRing $5.8K (Turncoat $7.7K, Vulture $6.2K), SWatch $1.3K (Turncoat $1.7K, Vulture $1.4K), LS KLab $90 (Artisan only).
- GHer (Gray Heroin, Laboratory Supplies, 1.000 kg): only Vulture buys it, $7K. No recipe uses it so far.
- The 11:04 batch (bottom of locker) showed nothing new. Ignored: ammo, magazines, grenades, helmets, weapons, USD stacks, backpacks (AMP12).

- HVL watchlist: `hvl_watchlist.md` lists high value loot from whereisvulture.com/loot that we have not seen in screenshots. Names only, never use the site's prices. Add an item to the matrix only once it appears in a screenshot (use in-game prices), then remove it from the watchlist.

## Steam folder batch (read-only folder, 2026-11-02..04)
Files: 20261102160213, 160216, 160228, 160231, 160456, 185650, 185655, 20261103003228, 003901, 121142, 20261104115524, 115530-115536.
- NEW recipe (Electronics Workshop, 1s): Advanced Hacking Tool (Hacking Tool, 1.000 kg) = FPGA Module x1 + Avionics Processor Board x1 + Server RAM Module x1.
- NEW recipe (1s): Advanced Tracking Tag (Tracking Tag, 0.014 kg) = Electrical Parts x1 + Military Software x1 + CPU x1.
- Disassembly: Baget-53-31 Onboard Computer 11h 57m, parts: Flight D… (truncated, unpriced) + Avionics Processor Board. Optical Seeker 9h 31m 32s, part: Missile… (truncated, unpriced). Optical Seeker raw: $10K Turncoat only.
- 11:55 4-Nov locker + 7 vendor views: identical to already-logged prices, no new items.
- Still unpriced: Server RAM Module, CPU (no vendor shows them yet), Electrical Parts.
- Images analyzed: 146 + 18 = 164.

## Steam folder batch 2 (2026-11-04 13:08 to 22:32, 40 files, read-only folder)
Files: 20261104 130826-130832 (6), 164555-164629 (8), 192205-192236 (16), 192312, 223143-223227 (9).
- 13:08 set: lower part of locker, only 5 vendors captured (no Banshee/Vulture) -> those two shown as ? for BAC, SPend…, SCPU, SWine, HGCS30.
- NEW items (price per vendor in vendor_prices.json): SATCOM (Portable Satcom Terminal, Artisan $4.5K only), X400 $240, EXPS3 $204, AEMS (2) $210 (label shown untruncated; different from the $36 "AEMS…"), PTK $68 (all four at Gunny/Artisan/Turncoat/Banshee), RLSL S… (Artisan $60 only), NR Arm (Artisan $90 each), ReLaptop (Reinforced Military Laptop), Grot-M (GLONASS Grot-M), BTD, DigiCam, CMeal (Lab Rat $17 only), BAC ($2K), SPend… (Sapphire Pendant), SCPU (Artisan $180 only), SWine (Snake Wine), HGCS30, PBG01, Lamberts (Lambert Cigars), Moutai (display truncated "$11…" at most vendors; Gunny $15K, Vulture $12K), PPEarr… (Perfect Pearl Earrings), DAEarr… (Diamond Earrings).
- Removed from HVL watchlist (now in screenshots with in-game prices): PBG01, HGCS30, GLONASS Grot-M, DEarrings, PPEarrings, SPendant, ReLaptop, DigiCam, Moutai, SWine, LCigars.
- Disassembly: Portable Satcom Terminal 11h 59m 56s (12.2 kg) -> Uplink Credentials Drive + Oven-Controlled Crystal Oscillator (both unpriced). Optical Seeker 9h 31m 32s -> Missile Seeker Head (name from the later queue label; 1h 24m 6s shown on 192312 is most likely remaining time on the same job, not a new time).
- Not tracked on purpose: Sub SX/VMAX/AP/SR ammo, F-1/M67/RGD-5 grenades, Crusher helmets, 1911/MCX/Glock weapons, USD, Rush/Trekstars/AMP12 backpacks.
- Images analyzed: 164 + 40 = 204.

## Steam folder batch 3 (2026-11-04 23:21, 8 files: 232115, 232119-232131)
- NEW matrix items: Melox (Lab Rat $4, 2/2), ERing ($3.3K, Turncoat $4.4K, Vulture $3.5K), IDBusi… Businessman ID Card ($937-1.3K), IDTouri… Tourist ID Card ($112-150), AK308 Sup ($510 at Gunny/Artisan/Turncoat/Banshee), Razor (Handshake/Turncoat $70), BeltB (Handshake/Turncoat $44), Antigen Vial of Antigens ($947, Vulture $1K), MTablet ($1.2K everywhere), Splint (blue) (Lab Rat $2 for 1/6 uses; separate from the red Splint).
- MTablet long name not set: could be STRELETS-M Tablet or Rugged Military Tablet (both stay on the HVL watchlist).
- Removed from HVL watchlist: VialAntigens, BizID, TouristID.
- Ignored: SVD Mag (magazine), 1911 weapons.
- Images analyzed: 204 + 8 = 212.

## Steam folder batch 4 (2026-11-04 23:27, file 20261104232706)
- NEW recipe (Electronics Workshop, 1s): Superior Hacking Tool (Hacking Tool, 1.000 kg) = Oven-Controlled Crystal Oscillator x1 (owned 0/1, comes from Portable Satcom Terminal disassembly) + High-Speed Digital Processor Board x1 (DPBoard, Lab Rat $1.2K, owned 1) + Digital Synthesis Engine x1 (unpriced, owned 1).
- Queue showed Portable Satcom Terminal at 11h 5m 17s, consistent with the earlier reading that queue times count down (remaining time).
- Not costable yet: OCXO and Digital Synthesis Engine have no sell price.
- Images analyzed: 212 + 1 = 213.

## PATCH 0.5.1.0 RULE (added 2026-11-05)
- Patch 0.5.1.0 overhauled prices. Everything recorded up to 2026-11-04 23:27 (last file 20261104232706) is PRE 0.5.1.0 and shown in purple on the page with a "pre 0.5.1.0" tag.
- New price info is taken ONLY from screenshots taken after the patch (check the version in the screenshot footer, e.g. "0.5.1.0-..."). Old screenshots are never re-read for prices.
- New rows carry "ver":"0.5.1.0" in vendor_prices.json (craft items: "pv":"0.5.1.0" in ITEMS). They override older rows for the same vendor and item and are shown in the normal colour. If a vendor no longer buys an item, add a row with value null and ver 0.5.1.0.
- Recipes, disassembly times and names are not prices and stay as recorded until a new screenshot contradicts them.

## 2026-11-05 batch (first 0.5.1.0 screenshots)
- 56 new files (Steam folder 20261105110140 .. 20261105120959), footer reads 0.5.1.0-325552-H. 35 are vendor tabs at 3 locker positions plus the medical/morphine block (7 vendors each), 4 positions in all with the first block.
- Read by eye (OCR was unreliable). 234 price rows carry "ver":"0.5.1.0" and override the old rows. No vendor stopped buying anything, so there are no "nobuy" rows yet.
- Almost every price is unchanged from the pre-patch reading. Changed: High-Quality Morphine Base $3,000 -> $4,500 (Lab Rat, Vulture), Stabilized Morphine Sulfate Liquid $6,000 -> $12,000 (Lab Rat), red Splint $17 -> $4 (old reading was from the 2026-11-02 batch, condition unknown). PFRKit $180 -> $1.1K is the full 2,000/2,000 kit versus an unknown fill earlier. Bandage $6 -> $9 is 3/3 versus 2/3 earlier.
- New items: PDRing (Platinum Ring) $7.5K (Turncoat $10K, Vulture $8K), C2 LAP (C2 Military Laptop) $4.9K (Vulture $5.2K), Alien (suppressed pistol part, truncated) $4.6K at Gunny/Artisan/Turncoat/Banshee, DD FG $84, UCLog $18K (Artisan only), Ibalin blister pack (2/2) $2 (Lab Rat), SHem $39 (Lab Rat), Seal $15 (Artisan), Oven-Controlled Crystal Oscillator (OCXO) $9K (Artisan only; now linked into the SATCOM disassembly).
- Tabs not re-read: Optical Seeker disassembly shows 5h 59m 50s for Missile Seeker Head (kept 9h 31m, it may be remaining time). Lab crafting screens and the quest screen were not used for data.
- ITEMS prices re-confirmed with pv 0.5.1.0: Opium Gum, Garden Lime, Ammonium Chloride, Purified Water, Methanol, Fenethylline, HPR 3-S, Strychnine; changed: HQMB 4500, StMSL 12000, OCXO 9000 (Artisan).
- Removed from the HVL watchlist because they now have in-game prices: C2 Military Laptop, Platinum Ring.

## 2026-11-05 13:02 batch (0.5.1.0, 19 files)
- Two locker positions at all 7 vendors. 44 more 0.5.1.0 rows. Nothing repriced except confirming earlier readings; new items: SigGen (Artisan $150 only), MParts (Artisan $60 only), Paracet 1/5 (Lab Rat $0), RT97S ($675, Vulture $720), AGRKit 400/400 ($315 at Handshake and Lab Rat only), plus PBG01 $6.4K (Vulture $6.8K), GCCard $1.6K (Artisan $2.2K, Vulture $1.8K), Moxiflox 3/4 $28.
- Last 2 files (Lab Rat, Vulture, 13:04:58-13:05:00): LQMB $2K at both, unchanged; lq_base marked 0.5.1.0. The Character screen is not used.

## 2026-11-05 14:39-14:43 batch (0.5.1.0, 17 files)
- Backpacks opened in the locker (Patrol Backpack x4, Civilian Trekstars 70L, Rush 72 2.0). Inside are Lab Rat chemical stacks priced $15/$30/$36/$39/$45/$75/$90/$150, all matching the earlier readings. Item names are hidden in the opened-bag view, so only label-readable items were recorded: Ethanol $90, Chloroform $45, Sulfuric Acid $39, Purified Water $30 (Lab Rat, 0.5.1.0). The $75 brown bottle and the $15/$45 bottles could not be told apart by icon and were skipped. No new items, no price changes found.

## 2026-11-05 15:30 batch (0.5.1.0, 9 files)
- One locker position at 7 vendors, 60 more 0.5.1.0 rows; names read from the Character screens (153010, 144312).
- Electrical Parts ($60, Artisan only) now has a price, so the missing-price gap is closed for the tracking tags. Other new items: Copper $30 (Artisan), Fan $15 (Artisan), Water Purification Tablets $27 ($29 Vulture), Prism (3) $150 (Artisan), FN GOfc $90 (Artisan), 1911 C... $484 at Gunny/Artisan/Turncoat/Banshee. PFRKit 1,972/2,000 $1.1K (Gunny, Lab Rat), PGRKit 2,798/3,000 $1.2K (Handshake, Lab Rat).
- Reconfirmed unchanged: EPhone $262 (Lab Rat $350, Vulture $280), NPI2 $1.1K, MWatch, DCRing, ORI-12 $255, HpR 3-S $285, Strych $180, B12 $30, HGH $30, Anil $30, SodCit $45, Methol $30, PSU $75, PCB $45.

## 2026-11-05 19:57 to 2026-11-06 20:05 batches (0.5.1.0, 43 files)
- 19:57 (full locker bottom, 7 vendors): 147 rows. Changed: 10% Morphine Solution $4,000 -> $8,000 (Lab Rat), consistent with HQMB $4,500 and StMSL $12,000. BAC now has Banshee $2K and Vulture $2.1K (were unknown). Others unchanged. New keycards (Artisan $90 each): MS Ma..., TB UNOf, FN ORI...; DNeckl... necklace $1K (Turncoat $1.4K, Vulture $1.1K).
- 20:04: Multi-Bus Converter $4K (Artisan only), UN... Log $8K (Artisan), Ratnik Long handguard $382 (Gunny, Artisan, Turncoat, Banshee), keys RLSL G/B $60 and TB UN... $90 (Artisan), MilSoft $75 (Artisan).
- 16:00-17:20 (Lab Rat and Artisan tabs only): blue Splint 6/6 $17 (1/6 showed $2), SHem $39, FiTer $8K (Artisan only), Pipette $150 (Artisan), OTP $2.4K, SurKit 1/5 $39.
- 08:13 batch (6 Nov) mostly shows loading spinners on weapon lists, not used for prices. Character, quest and workshop screens not used (workshop 160119 shows an Electronics Workshop Unlink Field Terminal disassembly, not read).
- Multi-Bus Converter is a Basic Hacking Tool ingredient, so that recipe now has one priced input of three (CPU Card, Spoofing ASIC Module still missing).
- Workshop screenshot 160119: FiTer = UNLRA Field Terminal, disassembles in 3h 59m 55s (queue just started, so about 4h) into UNLRA Relief Manifest (UNLog, $8K at Artisan) and Multi-Bus Converter ($4K at Artisan). Added to the disassembly table. UNLog long name = UNLRA Relief Manifest.

## 2026-11-06 22:08-23:56 batch (0.5.1.0)
- Vendor tabs at 22:08 and 22:53 and 23:15 were mostly loading spinners or weapon lists, so only the 23:56 locker sheet (all 7 vendors) was read for prices.
- New item: R-438 Barrier-T (Military Equipment, 16 kg): $45K at Handshake, Gunny, Lab Rat, Artisan, Turncoat, Banshee; Vulture $48K.
- New part: Rotor 5.45x39 suppressor $285 (Gunny, Artisan, Turncoat, Banshee). Optical Seeker: Turncoat now $12K (was $10K). Re-confirmed unchanged: GCCard, MWatch, ENeckl..., RAM ($90 Artisan), MBC ($4K Artisan).
- Lab production times changed in the 0.5.1.0 lab screen: LQMB 1h, 10% Morphine Solution 1h 30m, MQMB 1h 30m, HQMB 2h, StMSL 2h. New recipe: USP Morphine Sulfate 2h 30m (HQMB, Sulfuric Acid, Sodium Citrate, Edetate Disodium).
- Workshop disassembly: SATCOM about 8h (7h 59m 57s shown), StComp 6h.

## 2026-11-07 09:59-12:15 batch (0.5.1.0)
- USP Morphine Sulfate (USPMS) sells for $17K at Lab Rat only (no other vendor buys it). Its recipe is HQMB + Sulfuric Acid + Sodium Citrate + Edetate Disodium (2h 30m); ingredient cost is about $4.5K + $39 + $45 + $75.
- New Artisan-only items: Dynamo (alternator) $150 and Burner Head (BHead) $15.
- Re-confirmed at Artisan: CivSoft $75, Copper $30, EParts $60. Everything else read in the 11:15 and 12:15 full vendor sweeps matched existing rows.
- Not bought by any vendor: SRAMM (Server RAM Module, still no price), IDLog, Newspaper - Mysterious Explosion (0.1 kg).
- The 09:59 tabs and the 22:xx weapon tabs were mostly loading spinners and were not used for prices.

## 2026-11-07 20:29-20:30 batch (0.5.1.0)
- New military items bought by all 7 vendors: LTSD-4-3 Laser Designator $60K (Vulture $64K) and MDCS-30 UAV Control Station $2K (Vulture $2.1K). They are not craft or disassembly items.
- The rest of the 7-vendor locker sweep matched existing rows. The 19:07 shot and the weapon tabs were loading spinners.

## 2026-11-09 16:32 batch (0.5.1.0)
- New Lab Rat quest "Supply and Demand III": hand in 5x USP Morphine Sulfate for USD 50,000 + 50,000 + 40,000 = $140,000, plus 300 XP and 255 rep (Medium difficulty, Hideout). Added to the Full list.
- Medium-Quality Morphine Base now sells for $3.2K at Lab Rat and Vulture (was $2.5K). Vulture now pays $14K for Gray Heroin (was $7K); Lab Rat does not buy it.
- Everything else in the 7-vendor locker sweep matched existing rows. The weapon tabs were loading spinners.

## Batch 2026-11-09 16:35 (0.5.1.0)
- Lab production recipe: Gray Heroin, 2h 0s. Ingredients (1 each): Medium-Quality Morphine Base, Acetic Anhydride, Sodium Carbonate, Chloroform. Gray Heroin 1 kg, sells $14K at Vulture (0.5.1.0).
- Vulture quest "Drug Run" (smuggling task, easy): provide 5 Gray Heroin, carry in the shipment backpack to a marked location, 1h limit. Rewards USD 50,000 + 50,000 + 20,000 = $120,000, 150 XP, rep.
- No vendor prices in this batch.
