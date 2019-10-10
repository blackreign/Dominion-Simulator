# Dominion-Simulator
(Open) Dominion Simulator to be updated for beta round 15 with preliminary changes<br><br>
See https://opendominion.net/<br>
Happy simming!
<h1>Game Change Log</h1><br>
<b>Round 15 (preliminary)</b><br>
<ul>
<li>Prestige gain: change divisor from 12 to 10.</li>
<li>Prestige loss: reintroduce prestige loss for hits under 60% (old wiki). Ensure prestige loss for hits 60%—75% if they are subsequent hits that qualify for prestige loss.</li>
<li>Spy losses: cut in half for info ops, and implement spy loss equivalents for Halfling/Lizardfolk.</li>
<li>Land generation: switch to 85:65.</li>
<li>Defensive casualties: new base 3.375/0.75*0.85 = 3.825%.</li>
<li>Defensive casualties reduction: reduced by land ratio. 75% hit would generate 3.825% * 75% = 2.86875% casualties. Nerfs SPUD.</li>
<li>Nox: Lich +1 OP to 6 OP and +100p to 1,050p.</li>
<li>WE: Mystic +50p to 1,125p; LBM +25p to 350p, 10r; and Druid -50p to 1,050p.</li>
<li>SPUD: change pop bonus back to +12.50% and revert elite conversion range.</li>
<li>Gnome: Juggernaut to a fixed 7 OP.</li>
<li>Explore formula: changed as per Yami's proposal 2 in this sheet: https://docs.google.com/spreadsheets/d/1VK-but66RWfKVStXznzB6EKE6PuyPh13sKyU_x7FC-w/edit#gid=417348194</li>
<li>Orc: no change.</li>
<li>Shrines: change to 5x.</li>
<li>Global TC: to be implemented.</li>
</ul>
<b>Round 14</b><br>
<ul>
<li>Dwarven Cleric -40p</li>
<li>Gnome gets Racial spell from Dwarf. Miner's Sight (+20% Ore production, replaces Mining Strength.)</li>
<li>Gnome Juggernaut op to 7.5 (max vs 90% target)</li>
<li>Nox Nightshade based on swamp instead of built swamp. +100p </li>
<li>Nox Lich -100p</li>
<li>Icekin removed 5% platinum bonus, Archmage cost reduced to 825p</li>
<li>Spirit/Undead +2.5% pop bonus to 15%. Conversion changed to be similar to Dominion Classic.</li>
<li>Lycanthrope Werewolf -25p, 4/4</li>
<li>Explore cost increase of 10% removed for both platinum and draftees. 300 acres now have 5 draftees explore cost again.</li>
</ul>
<b>Simulator Changes</b>
<ul>
 <li>Added names to a lot of formulas involving constants for readability purposes.</li>
</ul>
<h1>Simulator Bug fixes</h1><br>
<b>Round 15</b>
<ul>
 <li>Redesigned Military page so it uses correct base elite1 and elite2 unit dp and op for e.g. forest based units</li>
 <li>Fixed issue with lumber cost with factories taking DB</li>
</ul>
<b>Round 14</b>
<ul><li>fixed a population bug with WG</li>
  <li>added useless race spell to accommodate mana expenses for other races</li>
  <li>fixed the starting time</li>
  <li>fixed clear sim button</li>
  <li>fixed renaming The Nox to Nox on overview page</li>
  <li>fixed a bug with Nox dp on overview page</li>
  <li>fixed a bug with construction cost involving factories and taking land bonus</li>
 <li>fixed bug with log files where destroying buildings used wrong columns</li>
 <li>fixed an issue with servertime being wrong in logs</li>
</ul>

