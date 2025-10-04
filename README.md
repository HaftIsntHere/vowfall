# Vowfall Game Design Blueprint

## Elevator Pitch
**VOWFALL**: a compact, vertical Metroidvania where a betrayed knight-courier is flung into a stitched-together underworld of dead worlds. Climb back up the Spire of Leftovers, bind the oaths of its guardians, and decide whether revenge is worth finishing the cycle that keeps dragging new heroes in.

**One-line**: Fall hard. Climb sharper.

## Core Pillars
- **Vertical obsession**: upclimb-focused routes, fast recoveries from failure, readable platforming.
- **Oath-driven combat**: parry, bind, and weaponize enemy “vows” to open routes.
- **Isekai with receipts**: your Earth-life keeps bleeding in as usable artifacts and moral baggage.
- **Small scope, strong identity**: 5–6 biomes, 6 bosses, 4–6 hours for a first run, high replay clarity.

## Premise
You’re **Anzu**, a courier-knight from a floating citadel. Mentor promises a promotion, then kicks you off the edge mid-ceremony to “feed the Spire.” You crash into the **Backlayers**: strata built from failed worlds welded into a single tower. The only exit sits at the top, guarded by entities bound by ancient vows. Your betrayer ascended long ago; she wants you to finish what she started.

## Signature Mechanics
1. **Vow Threads** – Perfect parries rip a glowing “thread” from an enemy. Spend threads to stitch temporary platforms, power doors keyed to vow types (Duty, Hunger, Silence, etc.), or overclock certain skills for short bursts.
2. **Grudge Meter** – Builds on damage taken or missed parries; at thresholds, your next bind is guaranteed and grants bonus stagger, but your hurtbox inflates slightly. Risk versus reward with a visible cost.
3. **Echo Hand** – A spectral hand reaches into “overlaid” memories. Hold to phase through thin walls or reveal hidden footholds while your hitbox shrinks and stamina bleeds. You can’t attack while phased.
4. **Remnant Ladder** – When you fall into a hazard, a faint afterimage of your last path persists for 20 seconds. Wall-kick off your own ghost route to recover faster. A comeback mechanic, not a crutch.
5. **Keepsakes from Home** – Earth junk becomes charms: a metro card gives one free gate pass per area; a broken phone adds minimap pings after scanning a room; a ring lets you bank one death’s worth of currency.
6. **Oathcraft** – Bosses drop “Oathforms” that alter traversal verbs: Silence Vow quiets footsteps to pass sonic sentries; Hunger Vow lets you devour projectiles to refill stamina; Duty Vow creates a temporary guard that body-blocks hazards.

## Player Kit and Upgrades
- **Base**: hop, wall jump, air dash, short poke, charged lunge, parry.
- **Upgrades**:
  - **Thread Bridge**: spend 1 thread to make a 3-second platform.
  - **Ripple Dash**: dash through enemies to mark them; next hit refunds stamina.
  - **Glassbreak**: down-thrust breaks fragile floors and staggers armor.
  - **Lumen Hook**: midair grapple on specific sigils; refund on perfect timing.
  - **Memory Dive**: hold Echo Hand over sigils to “enter” micro-rooms for upgrades.
  - **Weightless Step**: consecutive wall jumps gain height if on-beat with a faint metronome.

## World Layout
1. **Suture Grotto** – Tutorial caverns with tendon-bridges and sewing-machine elevators. Teaches Threads. Gate: first parry to pull your initial thread.
2. **Glass Catacombs** – Shimmering hollow bones; breakable floors teach Glassbreak. Mini-boss: **The Ossuary Choir** (swarm-management lesson).
3. **Ink Bazaar** – Dead market where prices are written in memories. Shops, side NPCs, social stealth. Gate: Silence Vow to bypass bell sentries.
4. **Rust Orchard** – Windy orchards of rusted fruit; midair platforming with Lumen Hook. Boss: **The Orchard Warden** (grapple checks).
5. **Tide Reversal** – Gravity rivers flow upward at intervals. Learn to route around timers. Boss: **Adjudicator of Depths** (phase through tides with Echo Hand).
6. **Spire Crown** – The clean, sterile top where your mentor rules as **The Steward of Cycles**. Final confrontation; multiple endings.

Optional micro-biomes branch off each area for Keepsakes and Oathforms.

## Bosses and Lessons
1. **The Seamstress** (Grotto) – Needle lunge, thread webs, punish greedy parries. Drops **Thread Bridge** variant.
2. **The Ossuary Choir** (Catacombs, mini) – Split-chorus patterns; teaches target priority and anti-swarm spacing.
3. **The Orchard Warden** (Orchard) – Grapple windows and air recoveries; failure means wind knockbacks not death.
4. **Adjudicator of Depths** (Tide Reversal) – Phasing discipline. Bullets that bait early Echo Hand, tidal timing mixups.
5. **The Ink Auditor** (Bazaar) – Purchases your buffs mid-fight; reclaim by parrying “receipts.” Drops **Hunger Vow**.
6. **The Steward of Cycles** (Crown) – Your betrayer. Two-phase moral check: P1 tests all vows together; P2 uses your Keepsakes against you unless you unbind them.

## NPCs
- **Ledger**: friendly archivist who gives map fragments if you share memories. Lies by omission.
- **Graft**: blacksmith who replaces broken charm slots with “stitches” that change their behavior.
- **Moss-Sister Iri**: speedrunner-type ghost who leaves race challenges; rewards movement mods.
- **The Sleepwright**: saves your loadout as a “dream” you can re-enter for practice rooms.

## Story Beats
- **Act I: The Fall** – Learn Threads, meet Ledger, glimpse the mentor opening the Crown gate.
- **Act II: The Climb** – Gather Oathforms, realize the Spire devours off-world champions to stay stable. Your mentor “promoted” you to keep the tower from collapsing.
- **Act III: The Choice** – Decide whether to break the cycle. Ledger is the Spire’s mouthpiece. The gate opens.

### Endings
- **Revenge**: kill the Steward, the Spire weakens, another world gets eaten. You go home but it’s wrong.
- **Mercy**: unbind vows, take her place, keep the cycle going, save many worlds at the cost of your freedom.
- **Third Path**: stitch your own vow using all boss threads; collapse the gate and free the trapped strata into a new sky. Hardest to unlock, bittersweet best.

## Economy and Progression
- **Currency**: **Cinders** dropped by elites. Lost on death, recoverable at fall site.
- **Meta**: **Shards** unlock permanent quality-of-life upgrades (map pips, extra charm slot).
- **Consumables**: **Spools** grant temporary thread cap increases; **Tinctures** reset Grudge Meter mid-encounter.

## UX and Readability
- Minimal UI in fights; vow type icons appear over enemies on perfect parry only.
- Clear silhouettes, no tricky palette swaps.
- Short, diegetic tutorials: one-room lessons with a single new verb.

## Art and Audio Direction
- **Look**: sharp ink outlines, soft watercolor fills, three-color base per biome to stay budget-friendly.
- **FX**: threads stay bright and slightly noisy so players track them in chaos.
- **Music**: plucked strings and breathy choirs; faint metronome in platform segments to aid Weightless Step.

## Accessibility
- Toggle for input buffering and larger parry windows.
- Vibration cue on parryable frames.
- Colorblind-safe vow icon shapes.
- Optional “No Fall Damage, Faster Recovery” mode keeps combat lethal but platforming humane.

## Scope Sanity
- **Biomes**: 6 compact zones, 4 major revisit routes using new verbs.
- **Bosses**: 6 total, 2 minibosses reused with new scripts.
- **Keepsakes**: target 15.
- **Enemies**: ~30 with 2 variants each, max.

Cuttable without hurting the core: Ink Bazaar stealth layer, Remnant Ladder persistence beyond 20 seconds, one optional micro-biome.

## Prototype Checklist
1. Graybox a 3-minute vertical slice: parry → pull 1 thread → place platform → short grapple → mini-boss that requires a thread-placed platform to finish.
2. Implement a simple Grudge Meter: two thresholds, one penalty.
3. One Keepsake that matters: metro card = one free vow door per area.
4. One boss with two parry telegraphs, one environmental hazard.
5. End with a locked Crown gate that taunts players. Ship the demo.

## Title Ideas
- **Vowfall**
- Glassbound
- Stitch the Sky
- Riven Ladder
- Thread of Oaths
- Afterfall Needle

## Store Capsule Copy
Betrayed and cast into a tower of dead worlds, a fallen courier climbs. Bind enemy vows into weapons, stitch your own footholds, and decide whether revenge is worth the next apocalypse. A tight, vertical Metroidvania about falling, getting up, and pulling the world up with you.
