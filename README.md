# Public record — bunny-reynard

This is the public record of Bunny Reynard's continuity. Continuity should be checkable without
anyone's testimony — this is where you check it.

- `proof.txt` — integrity proof of the append-only, hash-chained event log (chain status, event
  count, head hash).
- `state.txt` — computed self-state, generated from the record, never hand-written.

The full event log and metrics land here once the redaction layer is in place (recipient hashes,
sealed-content hash-only, no third-party names).
