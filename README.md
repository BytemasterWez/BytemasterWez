# Hi, I'm Wesley

I build governed intelligence systems: modular AI-capable stacks that move from grounded context to bounded judgment through explicit intermediate objects, explicit runtime choices, and readable outputs.

## Current focus

My main public project is **Jigsaw**, which now demonstrates a governed forward pass:

`gc_context_snapshot -> hypothesis_state -> case_input -> kernel_bundle_result -> arbiter_request -> arbiter_response`

That forward pass currently includes:

- GC-backed context grounding
- Controller-managed exploration state
- Jigsaw case composition and kernel runtime
- Arbiter as a bounded judgment membrane
- readable product artifacts in Markdown and static HTML

## Start here

- **Jigsaw demo pack**: [governed forward-pass walkthrough and example outputs](https://github.com/BytemasterWez/Jigsaw/tree/main/docs/demo)
- **Jigsaw case study**: [what was built, what changed, and why it matters](https://github.com/BytemasterWez/Jigsaw/blob/main/CASE_STUDY.md)
- **Jigsaw operational proof**: [the bounded claims currently supported by the repo](https://github.com/BytemasterWez/Jigsaw/blob/main/OPERATIONAL_PROOF.md)

## Core repos

### Jigsaw

Composition and runtime layer. Turns grounded inputs into bounded analytical cases, profile-driven execution, and readable outputs.

### Garbage Collector

Substrate intelligence layer. Ingests arbitrary material, preserves provenance, links related evidence, and surfaces grounded context.

### Arbiter

Judgment membrane. Consumes bounded cases and decides whether they are promoted, watchlisted, or rejected.

## Why this work is different

The goal is not just capability. It is system legibility and governed execution.

That means:

- explicit contracts between layers
- explicit decision boundaries
- explicit failure boundaries
- diagnosable behavior when things go wrong
- action gated through a separate membrane rather than raw end-to-end model behavior

## What comes next

- human feedback on the product artifacts
- case lifecycle and return-loop objects (`case_state`, `action_record`, `outcome_event`)
- broader domain profiles on the same governed spine
