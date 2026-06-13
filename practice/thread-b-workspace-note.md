# Thread B Workspace Note

Slice: 1 - Local workspace isolation only
Workspace directory: thread-b-readme
Expected state: local-only JJ change, not uploaded

This file proves that Thread B can edit its own JJ workspace without making
the baseline workspace or Thread A workspace dirty.

User verification:
- This file should exist in `thread-b-readme`.
- This file should not exist in the baseline workspace before integration.
- This file should not exist in `thread-a-note`.
