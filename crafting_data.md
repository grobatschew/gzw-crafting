# GZW crafting / production data (rebuilt from scratch)

Amounts are per 1 craft. Vendor prices are per single item (x1), regardless of stack size (confirmed by user). Chemicals/medical prices are from Lab Rat, electronics prices from Artisan.

## Laboratory - Production

| Product | Ingredients | Time |
|---|---|---|
| Low-Quality Morphine Base | Opium Gum 1, Garden Lime 1, Ammonium Chloride 1, Purified Water 1 | 2h 0s |
| 10% Morphine Solution | Low-Quality Morphine Base 1, Citric Acid 1, Purified Water 1 | 5h 30m (user-provided; in progress in screenshots) |
| Medium-Quality Morphine Base | Opium Gum 1, Garden Lime 1, Ammonium Chloride 1, Purified Water 1 | 2h 0s |
| High-Quality Morphine Base | Opium Gum 1, Garden Lime 1, Ammonium Chloride 1, Purified Water 1 | 2h 0s |
| Stabilized Morphine Sulfate Liquid | Medium-Quality Morphine Base 1, Sulfuric Acid 1, Methylparaben 1, Saline 1 | 5h 30m 0s |

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

## Images analyzed (96)

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
| ST1122 Storage Computer (StComp) | 12h | Incriminating Data Drive (grey drive, $9K, Vulture $9.6K), Server RAM Module (no price found; the RAM item at Artisan $90 has a green board where the dialog icon is blue, so it was not assumed to be the same) |

Valuation rule (user): disassembly material is valued raw (best vendor price for the item) and disassembled (sum of the best vendor price for each component). The page shows both in a table under the matrix. Result so far: TacRad raw $3K (Artisan) vs $10.5K disassembled; StComp raw $3K vs at least $9.6K. RSP raw price unknown.

Other findings: EKLog, IncrDD (new), EWLog $12K (Vulture price cut off in the screenshot, shown as ?), DSE $1.2K at Lab Rat, FPGA $900 at Lab Rat. The two backpack items seen at Lab Rat are now identified: the jug is PWat (Purified Water, already tracked at $30), and the 2x2 board is the Avionics Processor (AvProc, $900 at Lab Rat), a disassembly product of the Baget-53-31 Onboard Computer (not owned yet; its other components, raw price and time are unknown).

## Vendor price tracking

Full per-vendor price data is in `vendor_prices.json` (244 price rows, 7 vendors, 107 items; 29 rows come from the 2026-11-02 screenshots where only one vendor was looked at). The page's Vendor sell matrix tab embeds this data. An item with no row for a vendor shows a cross if it was checked at all vendors in the 2026-11-03 batch, otherwise a question mark. Craft-relevant findings from the 2026-11-03 batch:
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
