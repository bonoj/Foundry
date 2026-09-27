# Foundry — Semantic Surface

Foundry is a bounded physical laboratory in which terrain, matter, machines, creatures, infrastructure, and larger world forms can interact in one persistent causal space.

It grows by experiment. Mechanisms begin as propositions and acquire broader semantic authority only when executable evidence earns it.

The public interaction surface is intentionally smaller than the executable capability surface. A capability does not require permanent UI exposure to remain part of Foundry, and UI exposure does not make an experiment canonical.

> **The executable governs claims of present capability. This semantic surface governs the meaning of those capabilities. Embedded archaeology records how those meanings were earned.**

This document is not a complete feature inventory, implementation specification, roadmap, or substitute for running the artifact. It exists so that Foundry can change aggressively without losing the distinctions that make its experiments meaningful.

## 1. Constitutional commitments

These are durable semantic boundaries, not commitments to the current implementation.

### Terrain is substance, not scenery

Terrain is mutable world state. Its visible geometry is a representation of that state rather than an independent decorative surface.

Terrain may be raised, removed, smoothed, excavated, cratered, or otherwise transformed when a physical grammar has authority to do so. Topological consequences such as cavities, cuts, overhangs, and exposed sections belong to the same substance.

### Apparatus is not terrain

The manufactured apparatus and the deformable material it contains are categorically different kinds of thing.

Apparatus may own immutable boundaries, support, and collision. Terrain deformation does not silently acquire authority over apparatus. A physical grammar may not act through an immutable obstruction merely because its implementation could reach world state on the other side.

**Physical grammars do not get to act through immutable apparatus.**

### Actors request; substrates realize

A machine, creature, projectile, human tool, or other actor may cause or request a physical consequence. The substrate that owns the affected state owns realization of that consequence.

An Extruder does not own terrain internals because it can excavate. A meteor does not own terrain internals because it can make a crater. Shared consequences should converge on the authority that owns the affected world state.

### World-wide invariants belong to the world

Specialized entities may own specialized behavior. Cross-cutting physical requirements should not be duplicated as payload-specific privileges.

Gravity became world-level vocabulary only after unrelated dropped bodies needed to continue obeying it independently of their machine behavior. Similar promotions should be earned by evidence rather than architectural preference.

### Physical identity should survive transformations when useful

Foundry prefers relationships among actual world entities over abstract bookkeeping when the physical identity is meaningful.

A pile can be a stockpile. A transported bearing can remain the same bearing through capture, movement, and release. A projectile can be ordinary physical matter rather than requiring a separate projectile ontology.

This is a preference for causal continuity, not a prohibition on abstraction.

### Presentation may simplify without changing truth

Simulation population and presentation population need not be identical.

Large populations may be sampled, culled, aggregated, or perceptually compressed when necessary. Presentation machinery may clarify causality without acquiring simulation authority. Temporary impact smoke can communicate an event without becoming atmospheric substance.

CPU world state and semantic state remain more authoritative than any particular rendered representation.

### Local competence does not imply omniscience

A mechanism may possess exactly the spatial competence its physical task has earned.

A drone can negotiate nearby terrain without possessing global pathfinding. A conduit can rebuild a terrain-aware route without establishing a general routing solver. A machine can discover compatible nearby ports without implying a world-wide logistics planner.

Do not promote bounded competence into global intelligence by description alone.

### Capacity is not authority

An implementation being capable of producing an effect does not establish that the world means that effect.

Likewise, source presence does not make a mechanism canonical, UI presence does not make it foundational, and implementation similarity does not prove shared ontology.

## 2. What Foundry currently knows

Current executable evidence supports two different kinds of reusable knowledge. Keep them distinct.

### World authorities

World authorities are ownership boundaries and cross-cutting physical truths that other experiments must respect. They should be promoted conservatively and remain independent of particular specimens.

### Bounded physical world

Foundry can contain a coherent local piece of world with its own terrain, apparatus, matter, entities, processes, and accumulated consequences.

The current octagonal form is useful evidence for bounded geography, not a requirement that all future Foundry locations be octagonal or share one continuous terrain substrate.

### Deformable substance

Foundry has an authoritative terrain substance capable of genuine topological change. Multiple unrelated causes can alter it while terrain retains ownership of mutation and derived physical state.

Human sculpting, excavation, impact, machine work, and destructive events may therefore share terrain consequence without sharing cause.

### Immutable manufactured support

A manufactured structure may coexist with terrain while remaining physically authoritative and non-deformable. Terrain can be removed to reveal it; matter and entities may be supported by it; projectiles may be stopped by it.

### Discrete physical matter

Foundry supports numerous individually physical pieces of matter with position, motion, gravity, support, impulse, transport, and provenance where applicable.

The existence of discrete matter does not imply an inventory system or resource economy.

### Gravity and support

Eligible physical entities can remain subject to world-owned gravity and support independently of their specialized behavior.

Authored delivery and ordinary gravity are distinct authorities. An orbital arrival may own its approach; after handoff, the delivered body belongs to ordinary world physics.

### World-owned terrain deformation

Unrelated actors can cause terrain changes through a shared terrain-owned mutation boundary.

The existence of shared deformation does not require all causes to produce the same shape. A surface bite, meteor crater, and human sculpt operation may express different physical intent while respecting the same ownership boundary.

### Persistent entities with local behavior

Foundry can host persistent physical entities that own specialized state and behavior while remaining subject to shared world systems.

Motion does not become a universal component merely because several entities move. Shared architecture should emerge only where a shared requirement becomes materially useful.

### Earned capabilities

Earned capabilities are things Foundry has demonstrated it can meaningfully express. They are reusable possibilities, not necessarily constitutional world primitives.

### Spatial ports and provisional relationships

Entities may expose spatial input and output interfaces. Relationships can be discovered and bound through those interfaces without callers needing to know concrete machine classes.

Current evidence supports local, exclusive, provisional relationships. It does not establish branching, balancing, priority, typed-resource, or generalized network semantics.

### Physical transport

Foundry can claim an existing physical object, constrain its motion through a transport mechanism, and release that same object back into ordinary world physics.

Transport may negotiate changed terrain and may fail or spill contents when its physical mechanism disappears.

This is stronger than representational flow, but it is not yet a generalized logistics ontology.

### Autonomous material handling

Autonomous actors can perceive claimable physical matter, reserve it, travel to it with bounded terrain awareness, carry the same physical object, and deposit it.

This establishes local material-handling competence. It does not establish global pathfinding, task planning, warehouse logic, or an autonomous economy.

### Directional entity semantics

An entity may own an explicit semantic direction so geometry, targeting, effects, and behavior agree about what its orientation means.

Directional semantics belong to the entity, not to incidental mesh orientation.

### Bounded machine–creature interaction

Machines and mobile creature-like entities can perceive and physically affect one another through bounded relationships.

Current turret behavior demonstrates local search, acquisition, tracking, firing, ballistic matter, finite hit state, and destructive consequence. This does not establish a generalized combat, health, faction, or biology framework.

### Orbital delivery

Foundry has an authored grammar for introducing persistent physical entities from above at a chosen horizontal locus.

Delivery owns arrival. It does not permanently own the delivered entity's physics or behavior.

### Persistent consequences and transient causal presentation

World-changing events may leave persistent consequences while temporary effects clarify the causal interval and then disappear.

A crater is world state. Its impact cloud is presentation.

## 3. Semantic authority and experimental status

Not everything implemented in Foundry has equal semantic authority. Use these distinctions when extending or interpreting the artifact.

### World authority

A durable ownership boundary or cross-cutting physical truth that other experiments must respect.

Promotion into world authority should be rare and evidence-driven.

### Earned capability

A capability or relationship supported strongly enough by executable evidence that other experiments may safely rely on Foundry being able to express it.

An earned capability need not become a world authority.

### Active specimen

An implemented proposition available for ordinary experimentation. It may be useful and persistent without yet justifying a generalized abstraction.

Individual machines and creatures commonly begin here.

### Probe

A deliberately disposable experimental specimen introduced to ask a bounded question of the existing world.

**Probes are not payloads by default.**

A probe may fail, disappear, or remain local. Several probes using similar implementation machinery do not by themselves establish a framework.

### Archaeology

Retained evidence from earlier experiments. Archaeology can explain why current semantics exist and can contain mechanisms worth revisiting, but it carries no automatic present-tense authority.

Dormant does not mean deleted. Deleted from active vocabulary does not mean the experiment taught nothing.

### Presentation is an orthogonal axis

Perceptual machinery may make state, scale, causality, or transition legible at any experimental status.

Presentation can be mature and important without representing simulated substance or granting gameplay authority. Experimental status and representational status are independent.

These statuses are semantic roles, not necessarily runtime tags.

## 4. How Foundry learns

Foundry should remain cheap to surprise.

Start with the smallest physical or representational proposition capable of answering the question.

Let failures remain visible long enough to become evidence.

Prefer existing physical vocabulary before inventing domain-specific abstractions.

Promote shared machinery only when unrelated specimens expose a genuinely shared requirement.

Do not infer a framework merely because several implementations resemble one another.

Do not infer simulation truth merely because presentation is convincing.

Do not infer general intelligence from bounded local competence.

A mechanism succeeding in one causal role does not earn authority in another. Temporary impact particulate working as meteor occlusion did not make it good persistent weather. Several moving mechanical probes did not automatically earn an actuator framework. One transport mechanism does not create a logistics ontology.

Failed active machinery may be removed. Preserve the useful lesson as archaeology rather than keeping every experiment alive in the current interface.

When an experiment exposes a genuinely cross-cutting invariant, promote the smallest useful concept. Gravity earned a world system because every eligible dropped body needed it. Terrain deformation earned a world-owned boundary because unrelated causes needed to alter the same authoritative substance.

**Promotion follows evidence.**

## 5. Current toolkit

This is a sparse working inventory of useful mechanisms presently available in the executable. It exists to prevent rediscovery and expose combinatorial possibilities.

**Toolkit membership conveys availability, not semantic authority.** These mechanisms are examples of what Foundry can currently do, not requirements on future implementations and not automatically members of world authority or earned capability.

**Read downward to understand what is available. Read upward to understand what it is allowed to mean.**

Keep this section terse. Add something when knowing it exists materially changes what a successor might attempt. Remove or revise it when executable capability changes.

- **Terrain tools** — raise, carve, and smooth deformable terrain.
- **Meteor** — orbital strike with transient arrival/impact presentation, apparatus obstruction, and persistent terrain consequence.
- **Extruder** — removes a bounded terrain bite and emits ordinary physical bearings from that event.
- **Thumper** — repeatedly imparts mechanical impulse to nearby granular matter.
- **Link Node** — discovers and binds compatible nearby spatial ports; makes relationships perceptible.
- **Pipe Ends** — pair into a terrain-aware conduit that transports the same claimed bearings between endpoints.
- **Drone Factory** — produces autonomous drones that claim, retrieve, and physically deposit nearby bearings using local terrain-aware flight.
- **Turret** — bounded creature acquisition and tracking; fires ordinary bearing matter ballistically under world gravity.
- **Crawler / Jumper / Floater** — mobile creature specimens with distinct morphology, behavior, and durability.
- **Mechanical probes** — articulated experimental specimens including IK Walker and Walking Snake; probe status, not generalized locomotion vocabulary.
- **Water** — bounded visual/geographic water volume; no hydrodynamic authority.
- **Wonder Field** — 25 monumental visual-ontology specimens; presentation and shape exploration without gameplay authority.
- **Six Cities field** — six miniature city-machine morphology specimens testing semantic scale and civic/industrial verbs.
- **Biome provenance** — terrain/material identity can survive terrain-to-ordinary-matter transformation.

## 6. Open pressures

This section is intentionally volatile. Rewrite it as experiments change.

Current experiments have left unresolved pressure around several boundaries. These are evidence of open questions, not priorities for subsequent work:

- articulated locomotion and terrain negotiation;
- relationships among machines, creatures, matter, and infrastructure;
- increasingly physical logistics without premature inventory/economy abstraction;
- construction and persistent infrastructure;
- semantic scale, including machinery, settlement, city, and creature interpretations;
- composition of bounded physical worlds and whatever forms of traversal might eventually connect them;
- the boundary between autonomous local competence and larger coordination;
- richer environmental processes whose simulation authority must be earned rather than inferred from appearance.

These are questions, not roadmap commitments.

The next useful experiment may come from somewhere else entirely.

## 7. Known non-claims

Current Foundry should not be interpreted as claiming that:

- water is hydrodynamic;
- biome provenance is a resource or crafting system;
- ports constitute a generalized network architecture;
- Item Pipes constitute a generalized logistics framework;
- Drone Factory behavior constitutes pathfinding or task planning;
- creature specimens constitute generalized biology, AI, factions, or combat;
- turret interactions constitute a generalized health or weapons framework;
- mechanical probes constitute a general actuator or locomotion framework;
- the Wonder Field constitutes an architectural canon or construction grammar;
- the city-machine field constitutes a civilization simulation or city generator;
- semantic scale implies a single canonical physical scale;
- transient effects are simulated substances merely because they are visually convincing;
- an implemented or dormant mechanism is canonical merely because it remains in source;
- every executable capability belongs on the quiet public interaction surface;
- absence from the quiet UI means a capability is dormant, deprecated, or unimportant;
- visibility in the quiet UI grants greater semantic authority.

These non-claims are not prohibitions. They identify territory that remains open.

## 8. Reading the archaeology

Foundry contains extensive chronological semantic notes embedded directly in the executable.

Those notes are laboratory evidence, not a timeless specification. Earlier statements may intentionally contradict later ones because the artifact changed its mind after executable evidence.

Do not silently reconcile those contradictions.

**Contradiction in archaeology can be evidence of learning, not documentation debt.**

When interpreting Foundry:

1. Run and inspect the current executable to establish what presently happens.
2. Use this semantic surface to interpret what current capabilities are allowed to mean.
3. Use embedded archaeology to understand how those meanings were earned, including failures and abandoned directions.
4. Treat implementation details as replaceable unless current semantics genuinely depend on them.

History may explain an authority without retaining the implementation that first produced it.

## 9. Extension rule

A new experiment does not need permission from a feature taxonomy.

Add the smallest useful specimen. Let it interact with the existing world. Observe what survives contact.

If it uses existing vocabulary, reuse that vocabulary.

If it discovers something local, keep the discovery local.

If it fails, remove the machinery without erasing the lesson.

If unrelated experiments repeatedly require the same new physical or semantic capability, consider promoting the smallest shared concept into Foundry's earned capabilities or, where a genuine cross-cutting authority has emerged, its world authorities.

If evidence eventually contradicts this document, revise the document.

The purpose of the semantic surface is not to prevent Foundry from becoming something unexpected.

It is to let Foundry become something unexpected **without forgetting what it already knows**.
