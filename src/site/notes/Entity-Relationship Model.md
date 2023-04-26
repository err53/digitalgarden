---
{"dg-publish":true,"permalink":"/entity-relationship-model/"}
---

[[Data Model\|Data Model]]
[[Relational Data Model\|Relational Data Model]]

## Terminology
[[Schema\|Schema]]
[[Instance\|Instance]]

## Arrows
- Angled arrow `E ----> R`
	- One (partial)
- Round arrow `E ----) R`
	- Exactly one (on the right)
- Straight line
	- Many to many

[[Self Relationships\|Self Relationships]]


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



- 'Owned by' another entity
- Can be uniquely identified in conjunction with owning entities

- Essentially a nested element
- Eg Assignments belong to courses, courses belong to departments

Don't use weak entities if you can use simpler constructs


</div></div>


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



Not to be confused with [[Instruction Set Architecture\|Instruction Set Architecture]]

ISA relationship in databases
- Allows for hierarchical relationships
- Constraints not represented on the diagram must be documented separately
	- Overlap constraints
		- Entity belonging to *multiple* subclasses
		- Eg an entity being both Faculty and Student (a TA)
	- Covering constraints
		- Must every superclass entity *also belong* to a subclass?
		- Eg must every Person entity also be a Student, Faculty, and/or Staff?

</div></div>
