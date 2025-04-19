---
aliases: [] # << Add alternative names, acronyms (e.g., [DAG, Directed Acyclic Graph])
tags: [concept] # << Add type tags like #definition, #theorem, #method OR status tags like #stub, #developing, #review
created: {{date:YYYY-MM-DD HH:mm}}
updated: {{date:YYYY-MM-DD HH:mm}}
---
---
# {{title}} <!-- Note title should be the precise name of the concept -->

## Summary/Definition

<!-- One or two sentences defining the core idea. -->

## Explanation

<!-- Elaborate on the definition. Provide details, nuances, context. -->
<!-- Use [[Wikilinks]] liberally here to connect to other Atomic Notes! -->
<!-- Example: This concept is crucial for understanding [[Confounding]]. -->

## Examples

<!-- Concrete examples illustrating the concept. -->

*   Example 1:

## References

<!-- Link to specific [[Resource Notes]] if applicable -->
*   Derived from:
*   Discussed in:

---
#### Linked Concepts (Auto-Generated)
```dataviewjs
// Requires Dataview plugin. Lists outgoing links from this note's body
// that likely point to other Atomic Notes (by checking the path).
const outlinks = dv.current().file.outlinks;
// Filter for links pointing to the '10 Atomic Notes' folder (adjust path if needed)
const conceptLinks = outlinks.filter(link => link.path.startsWith("10 Atomic Notes/"));
if (conceptLinks.length > 0) {
    dv.list(conceptLinks);
} else {
    dv.paragraph("No links to other Atomic Notes detected in the body.");
}
```