<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Nerevar Moon-and-Star</title>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600&family=Lora:ital,wght@0,400;1,400&display=swap" rel="stylesheet"/>
<style>
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

body {
  font-family: 'Lora', Georgia, serif;
  font-size: 16px;
  line-height: 1.7;
  max-width: 680px;
  margin: 0 auto;
  padding: 0 1.5rem 4rem;
}

nav {
  position: sticky;
  top: 0;
  background: inherit;
  padding: 0.75rem 0;
  margin-bottom: 1rem;
  border-bottom: 1px solid currentColor;
  display: flex;
  flex-wrap: wrap;
  gap: 0.25rem 0.75rem;
}
nav a {
  font-family: 'Cinzel', serif;
  font-size: 0.65rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  text-decoration: none;
}

.hero {
  padding: 4rem 0 2.5rem;
  border-bottom: 1px solid currentColor;
  margin-bottom: 2.5rem;
}
.hero h1 {
  font-family: 'Cinzel', serif;
  font-size: clamp(1.6rem, 5vw, 2.6rem);
  font-weight: 600;
  letter-spacing: 0.05em;
  margin-bottom: 0.3rem;
}
.hero .sub {
  font-family: 'Cinzel', serif;
  font-size: 0.62rem;
  letter-spacing: 0.25em;
  text-transform: uppercase;
  opacity: 0.5;
  margin-bottom: 1.5rem;
}
.hero p { font-style: italic; max-width: 520px; }

.badges {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-top: 1.25rem;
}
.badge {
  font-family: 'Cinzel', serif;
  font-size: 0.58rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  padding: 0.2rem 0.6rem;
  border: 1px solid currentColor;
  opacity: 0.6;
}

section {
  margin-bottom: 2.5rem;
  padding-bottom: 2.5rem;
  border-bottom: 1px solid currentColor;
}
section:last-of-type { border-bottom: none; }

h2 {
  font-family: 'Cinzel', serif;
  font-size: 0.62rem;
  font-weight: 600;
  letter-spacing: 0.25em;
  text-transform: uppercase;
  opacity: 0.5;
  margin-bottom: 1.25rem;
}

.overview p { margin-bottom: 0.75rem; }
.overview p:last-child { margin-bottom: 0; }
a { text-underline-offset: 3px; }

.group { margin-bottom: 1.5rem; }
.group:last-child { margin-bottom: 0; }

.group-label {
  font-family: 'Cinzel', serif;
  font-size: 0.58rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  opacity: 0.4;
  margin-bottom: 0.5rem;
}

.mod-list {
  list-style: none;
}
.mod-list li {
  font-family: 'Cinzel', serif;
  font-size: 0.8rem;
  letter-spacing: 0.03em;
  padding: 0.35rem 0;
  border-bottom: 1px solid;
  border-color: rgba(128,128,128,0.2);
}
.mod-list li:last-child { border-bottom: none; }

.req-grid {
  display: grid;
  grid-template-columns: auto 1fr;
  gap: 0.5rem 2rem;
  font-size: 0.9rem;
}
.req-label {
  font-family: 'Cinzel', serif;
  font-size: 0.6rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  opacity: 0.5;
  padding-top: 0.1rem;
}
.note {
  font-style: italic;
  opacity: 0.6;
  font-size: 0.85rem;
  margin-top: 1.25rem;
}

footer {
  text-align: center;
  font-size: 0.78rem;
  font-style: italic;
  opacity: 0.4;
  padding-top: 2rem;
}
</style>
</head>
<body>

<nav>
  <a href="#overview">Overview</a>
  <a href="#visuals">Visuals</a>
  <a href="#gameplay">Gameplay</a>
  <a href="#world">World</a>
  <a href="#companions">Companions</a>
  <a href="#factions">Factions</a>
  <a href="#highlights">Highlights</a>
  <a href="#requirements">Requirements</a>
</nav>

<div class="hero">
  <h1>Nerevar Moon-and-Star</h1>
  <p class="sub">OpenMW Modlist &nbsp;·&nbsp; Vanilla+</p>
  <p>A visually and mechanically enhanced Vanilla+ experience for new and returning players. PBR lighting throughout, expanded landmasses, rebalanced difficulty, and a more rewarding endgame.</p>
  <div class="badges">
    <span class="badge">OpenMW 51.0+</span>
    <span class="badge">PBR</span>
    <span class="badge">Tamriel Rebuilt</span>
    <span class="badge">Vanilla+</span>
    <span class="badge">~1000 Mods</span>
  </div>
</div>

<section id="overview" class="overview">
  <h2>Overview</h2>
  <p>Most textures are paired with PBR specular and normal maps via <strong>MVR PBR v2</strong>, giving surfaces genuine material depth under OpenMW's physically-based lighting.</p>
  <p>The main quest and Tribunal receive targeted improvements. Bloodmoon is replaced by <strong>Tomb of the Snow Prince</strong>. DLC difficulty is brought in line with the base game; main quest bosses are significantly harder. The list also includes <strong>Tamriel Rebuilt</strong>, <strong>Project Cyrodiil</strong>, and <strong>Skyrim: Home of the Nords</strong>.</p>
  <p>The game will be harder than vanilla. <a href="https://www.nexusmods.com/morrowind/mods/55542" target="_blank">HarderBetterFasterStronger</a> is included for fine-grained difficulty control.</p>
</section>

<section id="visuals">
  <h2>Visuals</h2>

  <div class="group">
    <div class="group-label">Textures</div>
    <ul class="mod-list">
      <li>Morrowind Enhanced Textures 6.1</li>
      <li>MVR PBR v2</li>
      <li>Glow in the Dahrk</li>
      <li>Beautiful Cities of Morrowind</li>
      <li>Morrowind Interiors Project</li>
    </ul>
  </div>

  <div class="group">
    <div class="group-label">Shaders &amp; Lighting</div>
    <ul class="mod-list">
      <li>Epoch's Post Process Shaders</li>
      <li>Screenspace Lighting and Shadowing</li>
      <li>OpenMW Dynamic Ambient Visual Effects</li>
    </ul>
  </div>

  <div class="group">
    <div class="group-label">Nature &amp; Sky</div>
    <ul class="mod-list">
      <li>Vurt's Animated Tree Suite</li>
      <li>Skies .IV &amp; Better Night Sky</li>
    </ul>
  </div>
</section>

<section id="gameplay">
  <h2>Gameplay &amp; Mechanics</h2>

  <div class="group">
    <div class="group-label">Combat</div>
    <ul class="mod-list">
      <li>N'Garde — Active Block and Parry</li>
      <li>Bullseye</li>
      <li>Timed Directional Attacks</li>
      <li>Backstabs</li>
      <li>Weapon Sheathing 1.6</li>
      <li>ReAnimation v2 Rogue</li>
    </ul>
  </div>

  <div class="group">
    <div class="group-label">Difficulty &amp; Balance</div>
    <ul class="mod-list">
      <li>Beware the Sixth House</li>
      <li>Boss Overhaul — Dagoth Ur</li>
      <li>Tribunal &amp; Bloodmoon Rebalance</li>
      <li>MDMD — More Deadly Morrowind Denizens</li>
      <li>Improved Vanilla Leveling</li>
    </ul>
  </div>

  <div class="group">
    <div class="group-label">Immersion &amp; Character</div>
    <ul class="mod-list">
      <li>Sun's Dusk</li>
      <li>Graphic Herbalism</li>
      <li>Blight Storms Restored</li>
      <li>Character Traits Framework</li>
      <li>Tamriel Unlimited</li>
    </ul>
  </div>
</section>

<section id="world">
  <h2>World Expansion</h2>

  <div class="group">
    <div class="group-label">Landmasses</div>
    <ul class="mod-list">
      <li>Tamriel Rebuilt — Grasping Fortune</li>
      <li>Solstheim: Tomb of the Snow Prince</li>
      <li>Project Cyrodiil</li>
      <li>Skyrim: Home of the Nords</li>
      <li>Lyithdonea — The Azurian Isles</li>
    </ul>
  </div>

  <div class="group">
    <div class="group-label">Location Overhauls</div>
    <ul class="mod-list">
      <li>Kogoruhn — Extinct City of Ash and Sulfur</li>
      <li>The Corprusarium Experience</li>
      <li>New Ilunibi</li>
    </ul>
  </div>
</section>

<section id="companions">
  <h2>Companions</h2>
  <ul class="mod-list">
    <li>Arvesa</li>
    <li>Ahnassi Shares a Song</li>
    <li>Prisoner Jiub</li>
  </ul>
</section>

<section id="factions">
  <h2>Factions &amp; Story</h2>

  <div class="group">
    <div class="group-label">Faction Additions</div>
    <ul class="mod-list">
      <li>South Wall — A Thieves Guild Hideout</li>
      <li>Web of Mephala</li>
      <li>Magically Thievish Thieves Guild</li>
      <li>Free the Slaves</li>
      <li>The Law of House Telvanni</li>
    </ul>
  </div>

  <div class="group">
    <div class="group-label">Narrative</div>
    <ul class="mod-list">
      <li>The Dream is the Door</li>
      <li>Gare's Last Gasp</li>
      <li>Honorable Dagoth</li>
    </ul>
  </div>
</section>

<section id="highlights">
  <h2>Further Highlights</h2>

  <div class="group">
    <div class="group-label">Foundations</div>
    <ul class="mod-list">
      <li>Patch for Purists</li>
      <li>Morrowind Optimization Patch</li>
      <li>Cutting Room Floor — Modular</li>
      <li>OAAB Data</li>
    </ul>
  </div>

  <div class="group">
    <div class="group-label">Quality of Life</div>
    <ul class="mod-list">
      <li>Smart Ammo for OpenMW</li>
      <li>Perfect Placement</li>
    </ul>
  </div>
</section>

<section id="requirements">
  <h2>Requirements</h2>
  <div class="req-grid">
    <div class="req-label">Engine</div>
    <div>OpenMW 51.0 or later</div>
    <div class="req-label">DLCs</div>
    <div>Tribunal and Bloodmoon (both required)</div>
    <div class="req-label">Downloads</div>
    <div>~42–43 GB</div>
    <div class="req-label">Installed</div>
    <div>~63–64 GB</div>
    <div class="req-label">Total</div>
    <div>~105–107 GB — archives can be deleted after installation</div>
  </div>
  <p class="note">Difficulty is higher than vanilla. Adjust the in-game slider or HarderBetterFasterStronger settings at any time.</p>
</section>

<footer>Nerevar Moon-and-Star &nbsp;·&nbsp; All mods remain the property of their respective authors.</footer>

</body>
</html>
