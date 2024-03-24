# poetrycorpus
A corpus of public domain (mostly Victorian romantics) poetry for training (about 6k poems, 300k lines of poetry, ~2M words) 

Jsonl is pretty straightforward--poem, author, title.

A (hopefully small) fraction of longer poems may be truncated or incorrectly split into smaller poems.

The shuffled text is suitable for training a LoRa on oobabooga (as plain text file with hardcuts).  Note format of expected prompt.
