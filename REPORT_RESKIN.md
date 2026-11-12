# Laporan Audit Reskin: Gradius-RPG (OpenRPG)

Laporan ini berisi hasil audit menyeluruh terhadap seluruh berkas proyek (`.gd`, `.tscn`, `.tres`, `project.godot`, dan berkas dialog `.dtl`/`.dch`) untuk keperluan *reskin* total dari **OpenRPG** menjadi **Gradius RPG**.

---

## 1. Judul Game dan Window Title

| Nama yang Ditemukan | Jenis | Path File & Nomor Baris |
| :--- | :--- | :--- |
| `OpenRPG` | Game Title / Window Title | `project.godot` (Baris 17) |
| `OpenRPG` | Dokumentasi / Proyek | `README.md` (Baris 5) |
| `OpenRPG` | Dokumentasi / Skrip | `src/field/ui/inventory/ui_inventory.gd` (Baris 4) |
| `OpenRPG` | Dokumentasi / Skrip | `src/field/ui/inventory/ui_inventory_item.gd` (Baris 2) |
| `OpenRPG` | Dokumentasi / Skrip | `src/common/collision_finder.gd` (Baris 4) |

---

## 2. Nama Karakter (Pemain & NPC)

| Nama yang Ditemukan | Jenis | Path File & Nomor Baris |
| :--- | :--- | :--- |
| `Gobot` | Pemain / Karakter Utama (Robot) | `overworld/characters/gobot_gfx.tscn`, `project.godot` |
| `Very Old Mechanic` | NPC (Ghost) | `overworld/maps/forest/ghost.dch` (Baris 13) |
| `Slightly Deceased Knight` | NPC / Musuh (Enemy Ghost) | `overworld/maps/town/enemy_ghost.dch` (Baris 13) |
| `Adoring Fan` | NPC | `overworld/maps/town/fan_of_four.dch` (Baris 13) |
| `Widge` | NPC (Kelas: Monk) | `overworld/maps/town/monk.dch` (Baris 13) |
| `Energetic Child` | NPC (Runner) | `overworld/maps/town/runner.dch` (Baris 13) |
| `Smith` | NPC | `overworld/maps/town/smith.dch` (Baris 13) |
| `THIEF` | NPC (Kelas: Thief) | `overworld/maps/town/thief.dch` (Baris 13) |
| `Smog` | NPC (Kelas: Warrior) | `overworld/maps/town/warrior.dch` (Baris 13) |
| `Buggs` | NPC (Kelas: Wizard) | `overworld/maps/town/wizard.dch` (Baris 13) |
| `Baloo` | Battler / Karakter Pemain (Bear) | `overworld/maps/town/battles/test_combat_arena.tscn` (Baris 38) |
| `Nutsy` | Battler / Karakter Pemain (Squirrel) | `overworld/maps/town/battles/test_combat_arena.tscn` (Baris 46) |
| `Marvellous Mathilda` | Karakter / Pemilik Toko (Disebut di Teks) | `overworld/maps/town/sign.dtl` |
| `Evillus McVillain` | Villain / Musuh (Disebut di Dialog) | `overworld/maps/town/fan_of_four.dtl` |
| `Frank the Tank` | Villain / Musuh (Disebut di Dialog) | `overworld/maps/town/fan_of_four.dtl` |
| `Steve` | Villain / Musuh (Disebut di Dialog) | `overworld/maps/town/fan_of_four.dtl` |
| `Horrible Thing at the Centre of the Universe` | Boss / Musuh (Disebut di Dialog) | `overworld/maps/town/thief.dtl` |

---

## 3. Nama Kelas / Job Karakter

| Nama yang Ditemukan | Jenis | Path File & Nomor Baris |
| :--- | :--- | :--- |
| `Monk` | Job / Klasifikasi Karakter | `project.godot`, `overworld/maps/town/monk.dch` |
| `Warrior` | Job / Klasifikasi Karakter | `project.godot`, `overworld/maps/town/warrior.dch` |
| `Wizard` | Job / Klasifikasi Karakter | `project.godot`, `overworld/maps/town/wizard.dch` |
| `Thief` | Job / Klasifikasi Karakter | `project.godot`, `overworld/maps/town/thief.dch` |
| `Knight` | Job / Klasifikasi Karakter | `overworld/characters/knight_gfx.tscn` |
| `Smith` | Job / Klasifikasi Karakter | `overworld/maps/town/smith.dch` |

---

## 4. Nama Lokasi / Peta / Area

| Nama yang Ditemukan | Jenis | Path File & Nomor Baris |
| :--- | :--- | :--- |
| `Town` | Area / Peta Utama | `src/main.tscn` (Baris 351) |
| `House` | Area / Peta Interior | `src/main.tscn` (Baris 559) |
| `Forest` / `Woods` / `Grove` | Area / Peta Hutan | `src/main.tscn` (Baris 640), `src/main.tscn` (Baris 553) |
| `Dungeon` | Nama Tema / Tileset | `overworld/maps/tilesets/dungeon_tilemap.png` |
| `Steppes` | Nama Arena Tempur | `combat/arenas/steppes.png` |
| `Marvellous Mathilda's Magnificent Munitions` | Nama Toko / Bangunan | `overworld/maps/town/sign.dtl` |

---

## 5. Nama Item, Senjata, & Perlengkapan

| Nama yang Ditemukan | Jenis | Path File & Nomor Baris |
| :--- | :--- | :--- |
| `Key` | Item / Kunci | `src/common/inventory.gd`, `assets/items/key.atlastex` |
| `Coin` | Item / Mata Uang | `src/common/inventory.gd`, `assets/items/coin.atlastex` |
| `Bomb` | Item / Peledak | `src/common/inventory.gd`, `assets/items/bomb.atlastex` |
| `Red Wand` | Item / Tongkat Sihir | `src/common/inventory.gd`, `assets/items/wand_red.atlastex` |
| `Blue Wand` | Item / Tongkat Sihir | `src/common/inventory.gd`, `assets/items/wand_blue.atlastex` |
| `Green Wand` | Item / Tongkat Sihir | `src/common/inventory.gd`, `assets/items/wand_green.atlastex` |
| `Trinket` | Item / Aksesoris | `overworld/maps/town/thief.dtl` |
| `Stupid Badge` | Item / Penghargaan | `overworld/maps/town/thief.dtl` |
| `Unfathomably large sword` | Senjata (Warrior) | `overworld/maps/town/warrior.dtl` |

---

## 6. Nama Skill / Action Tempur

| Nama yang Ditemukan | Jenis | Path File & Nomor Baris |
| :--- | :--- | :--- |
| `Punch` | Skill Tempur (Melee) | `combat/battlers/bear/player_melee_action.tres` (Baris 11) |
| `Focus` | Skill Tempur (Buff) | `combat/battlers/bear/focus_attack.tres` (Baris 9) |
| `Arrow Storm` | Skill Tempur (Area) | `combat/battlers/squirrel/area_attack.tres` (Baris 11) |
| `Heal` | Skill Tempur (Recovery) | `combat/battlers/squirrel/heal_friendly.tres` (Baris 9) |
| `Quick Attack` | Skill Tempur (Fast) | `combat/battlers/bugcat/quick_attack.tres` |
| `Area Attack` | Skill Tempur (Area) | `combat/battlers/wolf/area_attack.tres` (Baris 9) |
| `FUS RO DOH!` | Skill / Kutipan Mantra (Wizard) | `overworld/maps/town/wizard.dtl` |

---

## 7. Teks Naratif dan Dialog Penting

| Kutipan / Teks Naratif | Jenis | Path File |
| :--- | :--- | :--- |
| "Help me... Please help me... How many years have I been waiting? You were programmed for ONE JOB, meet me in the woods! Did your batteries run out? Why are they working now? I'm so hungry. Should have packed a lunch. Please help me..." | Teks Narasi Pembuka | `overworld/maps/opening_cutscene.dtl` |
| "Your father was a hamster and your mother reeked of elderberry!" | Dialog Tempur (Enemy Ghost) | `overworld/maps/town/encounter_before_combat.dtl` |
| "En garde!" | Dialog Tempur | `overworld/maps/town/encounter_before_combat.dtl` |
| "Me and the fam just got back from slaying another ancient being. Punch 'im? What kind of monster do I look like? We got 'im with the power of friendship!" | Dialog NPC (Monk / Widge) | `overworld/maps/town/monk.dtl` |
| "Does your mom tell you to stop and look carefully at things? *My* mom always tells me I never notice anything unless I look twice!" | Dialog NPC (Runner) | `overworld/maps/town/runner.dtl` |
| "You wouldn't walk into someone's house unannounced, would you?" | Dialog NPC (Smith) | `overworld/maps/town/smith.dtl` |
| "We defeated the Horrible Thing at the Centre of the Universe and all I got was a stupid badge." | Dialog NPC (Thief) | `overworld/maps/town/thief.dtl` |
| "You may ask, why am I so popular with the ladies? Is it because I'm super edgy? My angelic appearance? My poor social skills? Why, it's my unfathomably large sword, of course!" | Dialog NPC (Warrior / Smog) | `overworld/maps/town/warrior.dtl` |
| "THEY'RE HERE! The Gang of Four, THEY'RE THE BEST!!! They're so cool! They can TIME TRAVEL at whim! They've saved the known universe 6 TIMES! They defeated Evillus McVillain, Frank the Tank, and Steve LAST FRIDAY!" | Dialog NPC (Adoring Fan) | `overworld/maps/town/fan_of_four.dtl` |
| "Marvellous Mathilda's Magnificent Munitions (Closed for pest control) PS: Darn kids stay off my lawn or I'll turn you all into newts!!!" | Teks Papan / Tanda | `overworld/maps/town/sign.dtl` |
