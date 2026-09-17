# Primordial Soup

A browser-based evolution simulation. Nothing is seeded — every organism starts from scratch, and every trait, behavior, and role is discovered through mutation and survival rather than handed to it. The world expands through biome stages (Petri Dish → Bowl → Tank → Pond → Lake → Sea) as biological milestones are reached, and the player shapes the world through terraform tools earned by playing.

## Play it

Open `index.html` in a browser, or play the hosted version once GitHub Pages is enabled for this repo.

## What's actually happening under the hood

- Organisms carry a 13-trait genome (speed, size, sense, efficiency, reproduction, and more) and grow phenotypically from food rather than spawning at full size.
- Reproduction is food-triggered, not a timer — well-fed organisms divide, with population pressure emerging naturally from food scarcity.
- Roles like predator, parasite, filter-feeder, and sessile anchor-dweller are all discovered through behavior over generations, not pre-assigned.
- A full trophic cascade runs in the ocean biome: dissolved nutrients feed colony organisms, which feed urchins, which feed crabs, which feed fish.
- The player can terraform the world (rocks, islands, vents, shallows, currents) once specific milestones are hit, gradually shaping the ecosystem rather than controlling it directly.

## Status

Actively in development. Current focus areas include tuning the trophic cascade balance and colony growth rates.

## License

Source-available, not open-source. See [LICENSE.md](./LICENSE.md).
