# One record, one pulse

Visible anchors: GSE-1 [pages 5–6](../specimens/GSE-1-redacted.pdf#page=5); GSE-2 [pages 8–9](../specimens/GSE-2-redacted.pdf#page=8).

GSE-2 names `GSE2_RECORD_TRANSPORT_V1`. The visible transport clause calls for actual host selection/assembly, a full `Current_Record`, and `History_Append` for the current pulse. The host retains unchanged program/footer and joins prior history. The visible pulse clause increments once; initialization already sets pulse 1.

GSE-1 describes a corresponding explicit transport mode. Its assembly guarantee distinguishes serialization from synthesizing missing semantic fields.

Loose questions:

- Which invariant checks can be implemented without another semantic inference?
- What should identify a retried proposal so the same pulse is not appended twice?
- Which missing clauses change whether a successor is complete?

This is a reading pointer, not an implementation or a completed reconstruction.
