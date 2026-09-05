
# Directed Semantic Network Graph

## The Graph

The graph is selective rather than exhaustive: not every authored substrate-level definition appears in it. Terms awaiting substrate construction, and constructed substrates for which no defensible substrate relation has yet been established, remain outside the graph until at least one such relation is identified. Some substrates are islands as far as the corpus is concerned for the sake of graph identity.

The graph constructs a relational semantic field by connecting substrates through relations supported by their substrate constructions or coherence to reality. Theology may become visible within that field through patterns disclosed by those connections, but the graph does not begin from a theological taxonomy and assign terms to it. It does not attempt to encode a complete moral, doctrinal, denominational, or other imposed system of classification. It does however presuppose some axioms at the system-level that explicit require the biblical semiotic stage.   

The graph records relations in which one substrate may require, instantiate, condition, calibrate, oppose, corrupt, or imply another. Connecting substrates may disclose dependencies, recurring patterns, and higher-order organization that isolated examination does not reveal. Relations, causes, boundaries, or operations that remain unresolved after adequate analysis may remain unresolved, but obscurity that further analysis can reduce should not be protected by calling it mystery.
### Why a Graph?

Substrates may utilize other substrates in their mechanics while remaining substrate-level definitions. A graph naturally grows from this network of relationships. It shows where one substrate requires, instantiates, calibrates, implies, or otherwise acts through another substrate. The graph surfaces how nested some substrates are and how foundational some others are. As is native to meaning and language, there are recurring structures, dependencies, tensions, and relationships whose signal is lost in the noise floor when examined alone. The graph adds a layer of communication starting from how substrates ask what persists as a signal to what emerges from the symphony of those signals.

### Graphs Have Edges

The substrate network is less about substrate contents than about implications of existence in the wild. Very little about hydrogen, oxygen or electron shells can imply wetness, resistance to compression, or explosion when contacting sodium. As is typical in chemistry or other diverse interacting components, the graph enables the display of effects, conditions, and properties that are only observable through relationships.  Some shine light on identity or participation, dependency or grounding, modification, or orientation. Others still describe logical or revelatory connection, opposition, or violation, and some describe movement across consequential states.

- Balances --- brings a substrate into proportionate relation with another by distributing, matching, offsetting, or accounting for what the latter bears or demands.

- Calibrates --- adjusts the operative degree, direction, threshold, or application of a  instance of the target.

- Contradicts --- stands in an operative incompatibility with another substrate such that full realization of the source opposes, negates, or violates some constitutive condition of the target.

- Corrupts --- a form of excessive miscalibration, the source instance acts upon an already existing target instance so that its capacities, orientation, relations, or operation persist in damaged, distorted, or disordered form.

- Counterfeits --- the source instance produces, adopts, or projects a structurally deceptive analogue of the target substrate that can function or present itself as though it were that substrate or any portion of its properties or downstream edge functions as a source while lacking or displacing something constitutive of it.

- Covers --- extends across a breach, deficit, exposure, or incompatible interval in a way that prevents that condition from determining the continuing relation or treatment.

- Displaces --- occupies, redirects, or usurps the operative place another substrate would otherwise hold.

- Echoes --- manifests a recognizable correspondence to another substrate without requiring identity, derivation, or exhaustive instantiation.

- FormOf --- the source is a differentiated manifestation, species, mode, or operative configuration of the target substrate such that participation in the source entails participation in the target.

- Fulfills --- brings into actual realization, satisfaction, discharge, or completed bearing what another substrate establishes as due, latent, forecasted, or required

- GrantedBy --- the source substrate's possession, exercise, legitimacy, or availability proceeds by conferment from the target. In `Power==GrantedBy==>God`, God is not simply a causal antecedent but the grounding giver of power.

- Implies --- the presence, coherent operation, or valid construction of the source provides sufficient structural grounds for affirming, presupposing, or deriving some participation or reality of the target, without necessarily making the target a component of the source.

- Instantiates --- realizes the target substrate in a concrete, particular, or more specifically configured operation. A new instance of the target begins with the new instance of the source. Not the same as nor a species of FormOf edge. 

- Offends --- produces or constitutes an impactful disparity relative to the target such that the target's integrity, order, standing, intention, or relation is violated or placed under adverse judgment.

- PoweredBy --- depends for effective operation, realization, continuation, or efficacy upon the target substrate as an enabling element, such that at least one existing instance or the instantiation of a new instance must proceed.

- Recalibrates --- changes a calibration already present in another substrate, shifting its operative orientation, weighting, range, or allowed possibilities. It therefore differs from Calibrates by presupposing an antecedent calibration that is being altered.

- RedeemsFor --- retrieves, releases, restores, or reclaims a referent from the condition established by the target and directs that recovered reality toward another viable status or relation. Similar to Fulfills and Covers.

- Requires --- the source cannot validly arise, operate, or retain the relevant substrate identity without the target being present, calibrated, available, or presupposed in some constitutive or enabling capacity. Requirement does not entail that the target is sufficient for the source, as a given substrate may have several requirements or other internal conditions.

- RootedIn --- the source derives a constitutive grounding, orientation, or reason for its identity from the target, while remaining distinct from it.

- Translates --- converts, carries, or renders the operative significance of one substrate into the terms or consequences of another. In `Atonement--Translates-->Cost`, an incompatibility and its remedy become accountably expressed through decrement, liability, foreclosure, or restoration. The relation does not say atonement is cost; it says atonement carries the relevant incompatibility through a cost-bearing structure.

## Mermaid

---
config:
  layout: elk
  theme: neo-dark
---
flowchart RL

Adultery--Contradicts-->Commitment
Adultery--Instantiates-->Sin
Agape--FormOf-->Affinity
Agape--Covers-->Breach
Agape--RootedIn-->Personhood
Agape<==Implies==>God
Agreement--Instantiates-->Assent
Agreement--FormOf-->Alignment
Alignment<--Implies-->Logic
Atonement--Translates-->Cost
Atonement--Requires-->Logic
Assent--Requires-->Will
Assent--Requires-->Logic
Assent--Implies-->Alignment
Breach--Offends-->God
Breach--Instantiates-->Cost
Commitment--Requires-->Assent
Covenant--Requires-->Commitment
Covenant--FormOf-->Agreement
Cost--Implies-->Logic
Faith--Instantiates-->Logic
Faith--Requires-->Commitment
Faith--Requires-->Will
Forgiveness--Requires-->Assent
Forgiveness--FormOf-->Deliverance
Forgiveness--PoweredBy-->Agape
Grace--Echoes-->God
Grace--Implies-->Agape
Grace--Implies-->Will
Grace--FormOf-->Power
Holiness--Echoes-->God
Judgment--Requires-->Assent
Judgment--Instantiates-->Wrath
Judgment--Instantiates-->Deliverance
Justice--Instantiates-->Judgment
Justice--Balances-->Cost
Mercy--Calibrates-->Judgment
Logic--Implies-->God
Mercy--FormOf-->Grace
Personhood<==Implies==>God
Power==GrantedBy==>God
Repentance--Recalibrates-->Assent
Righteousness--FormOf-->Alignment
Righteousness--Calibrates-->Faith
Salvation--Instantiates-->Forgiveness
Salvation--Requires-->God
Salvation--Implies-->Commitment
Salvation--PoweredBy-->Grace
Salvation--RedeemsFor-->Sin
Salvation--FormOf-->Deliverance
Salvation--Instantiates-->Atonement
Sanctification--Implies-->Grace
Sanctification--Instantiates-->Holiness
Sanctification--Requires-->Commitment
Sin--Contradicts-->Holiness
Sin--Corrupts-->Will
Sin--Displaces-->Agape
Sin--Counterfeits-->Personhood
Sin--Counterfeits-->Logic
Sin--Instantiates-->Assent
Sin--Recalibrates-->Affinity
Sin--FormOf-->Breach
Will--Calibrates-->Affinity
Will--Implies-->Personhood
Will--FormOf-->Power
Malice--FormOf-->Sin
Idolatry--FormOf-->Sin
Treachery--FormOf-->Sin
Exploitation--FormOf-->Sin
Wrath--FormOf-->Power
Wrath--Fulfills-->Cost

"""
