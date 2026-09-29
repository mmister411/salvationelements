# Inference Candidates and Boundaries

## FormOf Composition

The current graph contains:

```text
Malice --FormOf--> Sin
Idolatry --FormOf--> Sin
Treachery --FormOf--> Sin
Exploitation --FormOf--> Sin
Sin --FormOf--> Breach
```

If `FormOf` is operating categorically in the same applicable sense across both steps, the following are candidate consequences:

```text
Malice --FormOf--> Breach
Idolatry --FormOf--> Breach
Treachery --FormOf--> Breach
Exploitation --FormOf--> Breach
```

These consequences are not stored as authored edges. `FormOf` has not been declared globally transitive because its use can include manifestation, mode, or operative configuration for which unqualified transitive composition may fail.

The current graph also contains:

```text
Adultery --FormOf--> Treachery
Treachery --FormOf--> Sin
Sin --FormOf--> Breach
```

The graph separately contains the authored assertion:

```text
Adultery --FormOf--> Sin
```

`Adultery --FormOf--> Breach` is therefore a candidate consequence through categorical `FormOf` composition, but it is not materialized in the authored graph.

## FormOf and Instantiates May Coexist

The graph contains both:

```text
Adultery --FormOf--> Sin
Adultery --Instantiates--> Sin
```

The two assertions are not treated as duplicates. `FormOf` states categorical participation: an instance of Adultery counts as an instance of Sin. `Instantiates` states that when Adultery is realized, Sin is also brought into operative realization. The graph permits both relations when both claims are warranted.

## Implies Is a Warrant Path

The graph contains:

```text
Adultery --Implies--> Malice
Adultery --Implies--> Idolatry
```

These assertions state warrant-bearing pathways. They do not assert that Adultery is a form of Malice or Idolatry, and they do not authorize a general rule that every chain of `Implies` edges may be collapsed into a direct `Implies` edge.

The bidirectional Mermaid relations between Agape and God, Alignment and Logic, and Personhood and God are represented as two authored directed assertions in each case. No global symmetry rule for `Implies` follows from those local pairs.

## Contradicts

`Contradicts` is expected to be symmetric in many applications because a pathway that cannot coexist with another in the same way and at the same time commonly presents reciprocal incompatibility. The ontology does not yet declare symmetry because the relation is applied contextually and the current material does not establish that every use must reverse without loss.

## Requires

No transitive rule is currently authorized for `Requires`. From `A Requires B` and `B Requires C`, the graph must not automatically create `A Requires C` until the relevant kinds of constitutive or enabling dependence are shown to compose.

The statement that continuation of Adultery may require exploitation of trust is conditional. It is not represented as the unconditional edge:

```text
Adultery --Requires--> Exploitation
```

A future representation must preserve the condition governing continuation and the relevant exploitation of trust before that relation is admitted as a graph assertion.

## Derived and Authored Assertions

`sskg-graph.ttl` contains authored assertions. Candidate consequences in this document are not graph assertions. If executable inference is later authorized, derived assertions should remain distinguishable from authored assertions so that the path and rule that produced them remain recoverable.

No automatic inference rule is presently authorized beyond ordinary graph traversal and query operations that report paths already present in the authored graph.
