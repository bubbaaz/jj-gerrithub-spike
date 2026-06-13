# Thread A Workspace Note

Slice: 1 - Local workspace isolation only
Workspace directory: thread-a-note
Expected state: local-only JJ change, not uploaded

This file proves that Thread A can edit its own JJ workspace without making
the baseline workspace or Thread B workspace dirty.

User verification:
- This file should exist in `thread-a-note`.
- This file should not exist in the baseline workspace before integration.
- This file should not exist in `thread-b-readme`.
