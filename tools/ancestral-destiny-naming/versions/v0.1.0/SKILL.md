# Ancestral Destiny Naming

Version: 0.1.0  
Status: DEVELOPMENT / TEST-READY / NOT CANON

## Purpose

Manufacture names, bynames, place-nicknames and retrospective labels that make a trajectory appear inherited, fated, geographically encoded or morally owed. The skill must also manufacture the counter-case: names that expose, misdirect, contradict, parody or falsely overdetermine the same trajectory.

The name is evidence of a reading, not proof of the world. Treat it as a narrative instrument with provenance, pressure and possible fraud.

## Core distinction

`name → apparent inheritance/destiny → reader expectation → later confirmation, fracture or exposure`

Never silently convert a generated label into biography, etymology, historical fact or ethnic claim.

Every output carries:

- `SOURCE`: observed, historical, invented, translated or retrospective;
- `FUNCTION`: forecast, burden, camouflage, irony, accusation, memorial, route-marker or false clue;
- `FIT`: true, partial, inverted, absent or deceptive;
- `REVEAL`: what later evidence would confirm, revise or break it.

## Pattern families

### 1. Patronymic / matronymic obligation

Construct identity through an ancestor rather than an isolated individual.

Forms:

- `X ben/bat Y` — son/daughter of an ancestor;
- `X-son`, `X-sen`, `X-dóttir`, `X-datter`, `X-dotter` — inherited relation;
- `House/Farm of X` — lineage as territory;
- `named-after-Y` — explicit memorial obligation.

Use for: inherited debt, recurring promise, disputed descent, a child carrying the wrong ancestor, or a lineage that has become administrative fiction.

Adversarial inversion: the name accurately identifies descent but falsely implies character. Or the bearer is named for an ancestor they never knew and becomes the family's opposite.

### 2. Place / farm / threshold names

Make geography behave like ancestry.

Forms:

- `[terrain] + [dwelling]`: Berg, Holm, Lund, Dal, Vik, Haug, -heim;
- `[person] of [place]`;
- `[place] + [historical pressure]`: Winterpeg, Deadmonton, Raincouver;
- border, quay, wreck, station, island, crossing or abandoned settlement.

Use for: migration, exile, settlement, failed return, a town whose nickname preserves an old wound, or a person who belongs to a place only by paperwork.

### 3. Auspicious / protective naming

Name toward a desired future: blessing, survival, joy, peace, repair, prosperity, intelligence or continuity.

Forms:

- `good-fortune / peace / life / light / repair` compounds;
- memorial naming after a deceased relative;
- a name chosen to preserve a quality rather than a person;
- a protective name whose surface meaning is deliberately stronger than reality.

Adversarial inversion: the auspicious name becomes a curse, an accusation, a failed promise or a bureaucratic label attached to a ruin.

### 4. Epithet by contradiction

Name a person, town or institution after the quality it visibly lacks.

Forms:

- `Job` for a person with no patience;
- `Propitious` for a doomed vessel;
- `Posteriors` for a shipwreck whose survivors were left behind;
- `IntelligenceShield` for a system that leaks;
- `Akolite` for the person who refuses discipleship.

The contradiction must be legible from action, not explained in a footnote.

### 5. Portmanteau diagnosis

Fuse a proper name with a pressure, demographic shift, climate, bureaucracy, violence, emptiness or stereotype.

Examples supplied by the operator: `Honkouver`, `Deadmonton`, `Winterpeg`, `Chilangolandia`, `Nacatittlan`, `Mataulipas`, `Londonistan`, `Mohamadim`.

Use cautiously: the mechanism can expose power, but it can also reproduce xenophobia, class contempt or ethnic reduction. Store the target, speaker, historical context and harm vector.

Forms:

- `[place] + climate`: Raincouver, Winterpeg;
- `[place] + perceived emptiness/bureaucracy`: Deadmonton;
- `[place] + demographic or migration claim`: only with marked speaker-position;
- `[place] + moral condition`: `Mataulipas`, `Nacatittlan`;
- `[name] + plural/collective suffix`: `Mohamadim`, to make a population appear like a lineage, sect or administrative category.

### 6. Trauma-bounded compounds

Bind an event into a name without claiming that the event exhausts the bearer.

Examples: `Traumbaum`, `alcohol-aid`, `shipwreck Posteriors`.

Test the boundary:

- Does the compound preserve the event?
- Does it reduce the person to the event?
- Does it reveal who had the authority to name?
- Can the bearer reclaim, reject or mutate it?

### 7. Retrospective timeline naming

Name an earlier stage after a later consequence, creating the impression that the ending was always present.

Procedure:

1. Identify a neutral event `E`.
2. Identify later consequence `C`.
3. Generate a label `N(E←C)` that makes C appear latent in E.
4. Generate the counter-label `N(E↛C)` that proves the relation was fabricated.
5. Record the evidence needed to distinguish history from hindsight.

This is a narrative operation, not time travel and not proof of destiny.

## Convention grammar

Use these slots when generating candidates:

`[carrier] + [inheritance marker] + [pressure] + [moral temperature]`

Examples:

- `Mara-bat-Repair` — memorial obligation;
- `Northholm` — place made hereditary;
- `Propitious-9` — auspicious label under technical numbering;
- `Traumbaum` — trauma fixed as a family tree;
- `Honkouver` — place plus demographic displacement, speaker-position required.

Allowed operations:

- suffix, prefix, translation, mistranslation;
- phonetic drift;
- false cognate;
- inherited name attached to a non-inheritor;
- place name moved onto a person;
- occupation turned into destiny;
- blessing turned into evidence against the bearer;
- future consequence projected backward;
- derogatory label reclaimed by the target.

## Adversarial matrix

For every candidate generate at least one marginal variation in each column:

| Axis | Kosher / functional reading | Opposite / adversarial reading |
|---|---|---|
| Lineage | name preserves a real relation | name invents or falsifies descent |
| Place | place records belonging | place is exile, occupation or imposed identity |
| Destiny | name forecasts a pressure | name creates the pressure by being believed |
| Blessing | name protects continuity | blessing becomes ironic evidence of failure |
| Epithet | contradiction reveals character | contradiction is propaganda by an enemy |
| Portmanteau | compressed social diagnosis | stereotype disguised as diagnosis |
| Trauma | event is remembered without totalizing | event colonizes the person |
| Retrospect | later event clarifies earlier form | hindsight manufactures inevitability |
| Authority | bearer or community chooses the name | institution, enemy or outsider imposes it |
| Reception | name travels and changes meaning | same name becomes a trap in another body |

`Kosher` here means structurally admissible within the project’s naming logic, not religious certification or factual truth. Mark religious and ethnic materials with care; do not treat Jewish or Scandinavian traditions as a single uniform code.

## Output record

```yaml
name: ""
surface_form: ""
pronunciation_or_wordplay: ""
carrier: person | place | vessel | institution | event | timeline-node
pattern_family: patronymic | matronymic | place | auspicious | epithet | portmanteau | trauma | retrospective
source_mode: observed | historical | invented | translated | retrospective
speaker_or_namer: ""
apparent_reading: ""
counter_reading: ""
fit: true | partial | inverted | absent | deceptive
obligation_or_pressure: ""
harm_vector: none | class | ethnic | religious | national | gendered | disability | other
reclaimable: true | false | unknown
evidence_needed: []
later_reveal: ""
status: seed | test-ready | retained | rejected | dormant
```

## Manufacturing protocol

1. Capture the observed pattern without normalizing spelling or intent.
2. Classify the mechanism, not merely the vocabulary.
3. Generate a primary name and three marginal variations.
4. Generate the opposite reading deliberately.
5. Test whether the name predicts, burdens, camouflages, accuses or retrospectively edits the timeline.
6. Mark cultural source, speaker-position and harm vector.
7. Keep all variants until a scene, route or editorial decision selects one.
8. Record the selection as a cut; preserve rejected variants and the reason.

## Failure tests

- If the name only sounds exotic, reject as ornament.
- If the alleged ancestry cannot alter action, classify as surface decoration.
- If the epithet explains the character before the character acts, weaken it.
- If a portmanteau uses a population as a punchline without a speaker or target, quarantine it.
- If a name is treated as proof of destiny, generate a disconfirming route.
- If all variants point to the same interpretation, the adversarial range is insufficient.
- If the reader cannot tell whether the name is history, rumor or imposition, either preserve that uncertainty deliberately or add a provenance tag.

## Minimal test

Input: a neutral town, a survivor, an inherited name and a later betrayal.

Produce:

- one lineage name;
- one place nickname;
- one auspicious name;
- one hostile epithet;
- one retrospective name;
- one counter-name for each;
- a selection receipt explaining which name changes the scene and which names remain marginal.

## Sources and boundaries

The skill borrows mechanisms from patronymic/matronymic, toponymic, occupational, characteristic and memorial naming. Historical traditions are pattern sources, not templates for assigning identity. Jewish and Scandinavian naming practices contain internal variation across time, language, community and region; preserve that variation rather than compressing it into a single “code.”

External examples such as `Raincouver`, `Winterpeg`, `Deadmonton` and `Hongcouver` are treated as documented nickname mechanisms; their social valence is not assumed to be neutral.

## Promotion gate

Do not promote this skill from seed to active canon until a bounded literary test shows that it changes at least one future decision: naming, scene interpretation, timeline reading, route selection or rejection of an accidental stereotype.
