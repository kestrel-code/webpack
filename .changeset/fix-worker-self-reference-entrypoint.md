---
"webpack": patch
---

Fix Worker self-reference by properly registering async entrypoints when module is not the root block, ensuring correct chunk graph connections for self-referencing Workers.
