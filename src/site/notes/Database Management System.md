---
{"dg-publish":true,"permalink":"/database-management-system/"}
---

See: [[Database\|Database]]

- Software designed to assist in maintaining and utilizing databases
- Files and FSs by themselves can be unpredictable ([[Concurrent System\|Concurrent System]], sudden power loss), and don't provide any strong guarantees about data consistency
- DBMSes are easier to use and come with these guarantees out of the box

## Benefits
- Data Independence
	- Data usage separated from data storage
- High-level query language
	- Specify *what* you want, now *how* to retrieve it
- Provide:
	- Strong guarantees about data integrity and recovery
	- [[Concurrent System\|Concurrent]] data access
	- Efficiency even with large volumes of data