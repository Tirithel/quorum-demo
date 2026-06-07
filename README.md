# Quorum Demo Sandbox

A repository **managed by Quorum's autonomous agents** — this is one of the projects Quorum
orchestrates, used as a real remote git tree (not local/scratch mode).

Agents clone this repo, work on a `quorum/<TICKET>` branch, push their commits, and the engine
merges approved branches into `main`. Builder → QA → Reviewer all share this same remote branch.
