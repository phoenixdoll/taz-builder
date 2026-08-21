# Terror AustraliZ Season 0 Build Planner

A single-page character build planner for Project Zomboid, covering vanilla
Build 42, [Jack of Some Trades](https://github.com/phoenixdoll/Jack-Of-Some-Trades),
and Somewhat Traits together. Pick a profession and traits the same way you
would at character creation, and see the resulting trade-skill caps and
starting levels JOST would actually give you.

No build step, no dependencies beyond a Google Fonts stylesheet — it's a
single `index.html` file. Open it directly or serve it as-is.

## Data sources

Trait/profession costs and skill bonuses are read from the installed game's
vanilla scripts. JOST's cap/starting-level formulas match the mod's built-in
defaults — if a server retunes JOST's sandbox options, results will drift
from what players actually see in-game. Somewhat Traits' point costs are
accurate; its gameplay effects (moodle/speed changes) are described but not
modeled numerically.

## Local preview

Just open `index.html` in a browser — no server required.
