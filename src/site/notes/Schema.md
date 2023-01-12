---
{"dg-publish":true,"permalink":"/schema/"}
---

Describes how data is structured

Conceptual schema: in terms of the [[Data Model\|Data Model]]
Physical schema: in terms of how it's stored on disk

To create a schema, we need to do [[Requirement Analysis\|Requirement Analysis]]
- What data does the application collect?
- What data does this application need?
- What does the application do with the data?

Is a DBMS the right fit?
- Big data, ML, timescale DBs...

In relation to [[Agile Development\|Agile Development]]
- Refactoring / restructuring wrong data choices is pain (high chance of losing data)

Key design principles:
- Don't store computed variables, but raw, unchanging ones (eg birthdate instead of age)
- Names (and most string-based fields) are hard.
- 