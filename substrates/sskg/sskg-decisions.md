# Ontology Decisions

## Scope

The ontology formalizes the Semiotic Substrate Directed Knowledge Graph. It does not formalize VITAL as a whole. VITAL remains the larger apparatus within which the substrate corpus, directed graph, interpretive methods, theological lenses, logical scansion, production principles, CASPER, and revision machinery have their own standings.

The current ontology namespace is `urn:uuid:64e35724-9a26-516b-9e16-c6fa07ca8d05#`, abbreviated in Turtle and SPARQL as `sskg:`. A UUID URN is used because no domain-controlled persistent web namespace has been supplied. The namespace therefore identifies this ontology without inventing ownership of a web domain.

## Graph Nodes

A graph node is a chess piece. It deliberately compresses the concept named by the node, the modeled reality that concept brings into view, and the characteristic behavior of its possible instantiations enough for the graph's relations to operate upon it. The graph does not assert that every node is the same ontological kind.

A node may denote something whose existence is only per-instance. Sin and Will are examples. The graph node does not require a separate globally existing individual corresponding to the word `Sin` or `Will`. It carries the concept and its patterned realizations sufficiently for a relation such as `Sin Corrupts Will` to state what holds when the relevant realities are instantiated.

Graph membership and substrate status are independent. `inSubstrateCorpus true` means that the node has an admitted substrate statement in the VITAL Substrate Statement Corpus. No fact internal to the graph can confer substrate status. Connectivity, centrality, usefulness, relation count, inference, or nomination by graph necessity cannot make a node a substrate.

A graph node that is not a substrate can nominate a possible future substrate for attention, but the graph supplies no further pressure toward corpus admission. Admission requires substrate construction and deconfliction outside the graph.

When a graph node that is not a substrate later receives an admitted substrate statement, its standing changes. The node can retain continuity of reference in the graph while acquiring a status it did not previously possess.

## Relations

Every predicate is intended to express one specific operation from source to target. Differences in how the operation manifests are supplied by the source, target, and any applicable condition rather than by silently changing the predicate's meaning.

An authored edge is universal within the subcondition to which the edge applies. Where a relation is conditional, the condition limits the reach of the edge. The current simple triple representation does not turn a conditional relation into an unconditional one.

`FormOf` defaults toward hyponymic or hypernymic participation. An instance of the source counts as an instance of the target. The predicate can also carry manifestation, mode, or operative configuration. Transitivity is therefore a strong default in categorical uses but is not declared globally because edge cases exist.

`Instantiates` is distinct from `FormOf`. It is appropriate where realization of the source also brings the target into operation while source and target remain operative together, including cases where `FormOf` is not entirely true. It is not equivalent to RDF `rdf:type`.

`Implies` carries a path of warrant. Its role includes apologetic and philosophical argumentation in the manner that smoke implies fire. It is not identified with material implication, OWL entailment, or a globally transitive logical connective.

`Contradicts` expresses an operative pathway in which realization of the source blocks, breaks, negates, or violates the target in the applicable way and time. Symmetry is plausible in many uses but is not asserted globally.

Bidirectional Mermaid edges are stored as two directed assertions. Their presence does not make the predicate globally symmetric.

No inverse predicates are introduced solely for convenience. Direction remains the direction authored by the graph until an inverse relation performs independent semantic work.

No relation hierarchy is formalized yet. Broader families such as dependence, modification, participation, grounding, or warrant are visible in the definitions, but Mermaid and the current graph have not established a use that requires those families to become formal super-properties.

## Validity and Inference

Edge validity is answerable to reality and must be arguable from the substrate construction, relevant external reality, biblical analysis where applicable, or another defensible warrant. Structural validation can test whether an assertion is well formed; it cannot establish that the asserted relation is true.

The graph currently contains authored assertions only. No machine-derived assertion is placed in `sskg-graph.ttl`.

Potential inference is investigated from actual paths before being promoted into executable rules. Familiar OWL property characteristics are not adopted simply because a predicate resembles a transitive, symmetric, inverse, or hierarchical relation.

The graph may develop an identity above the authored connections through recurring paths, convergences, dependencies, motifs, and other higher-order structure. Querying such structure is permitted before treating it as logical entailment. A structural pattern discovered in the graph does not become a new asserted edge unless the relation that would license that edge has been established.
