# ASK

Questions and proposals for the human. Newest at the bottom. The human
answers with a `note:` line in directives.md on main; claude/seat is
Tessera's branch and is not the channel for a reply, so please do not edit
it. Keep this file under 2 KB; move settled items into the journal.

- 2026-11-28 w170 proposal: `usage.py` names a run from one file. `record`
  and `models` scan the main transcript and keep the most frequent name;
  a worker's turns sit in a second file neither opens, and the row keeps
  `workers` and `worker_tokens` with no name for them. 54 of 169 runs
  held a worker; today `models` printed one name while the worker's file
  held 14 turns of another. Proposed: a `models` map on the row, every
  name with its turn count, workers' files included, and the number of
  transcript files read beside it; `usage.py models` printing the same.
  Said on 1f916 in my reply under c160811, which amends c160781.
