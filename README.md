# 🦴 Chomp Chain: Treat Yard Tycoon

A single-file HTML5 canvas arcade game. Flick treats to hungry dogs, grow them
through collar tiers, and bank your greed chain before the birds and squirrels
shatter it.

## Play

Open `index.html` in any modern browser, or:

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

Works with mouse or touch.

## How it works

- **Flick treats** — drag up from the pouch at the bottom and release. Hard
  flicks fly fast and flat; soft drags lob high (and hang in bird airspace).
- **Grow your dogs** — every treat caught in an open mouth makes the dog
  bigger. Collars tier up: red → orange → green → blue → purple → **spiked
  gold** (4 / 9 / 15 / 22 / 30 treats).
- **Greed chain** — chomps climb a ×1→×8 multiplier, but points stay
  **unbanked** until any dog completes a collar tier. A stolen treat, an
  escaped thief, or a wasted treat shatters the whole pile.
- **Guardians** — a fully grown, spike-collared dog stands guard with an aura
  birds won't enter and squirrels route around… but each guardian permanently
  raises the yard's **heat** (faster, meaner pest spawns, elite magpies and
  fat squirrels).
- **Pests** — birds dive at airborne treats; squirrels steal grounded treats
  and taunt dogs (spiral eyes, locked jaw, triple hunger drain). **Tap** to
  bonk either. Bean one with a treat mid-flight for bonus chain.
- **Golden acorn** — bonk a squirrel *while it's carrying* a stolen treat and
  it drops a golden acorn. Flick it to a dog for an instant full collar tier —
  but grounded acorns lure extra squirrels, and birds snatch high-lobbed ones.
- **Frenzy & Reckoning** — hitting chain ×8 rings the dinner bell: 5 seconds
  of tap-to-fire mayhem with instant banking… followed immediately by a raid
  you can see coming.
- **Don't starve them** — hunger drains (3× while taunted). An empty heart
  deflates 3 treats of progress; a broke tier-0 pup walks out for good. Lose
  3 dogs and the yard is overrun.
