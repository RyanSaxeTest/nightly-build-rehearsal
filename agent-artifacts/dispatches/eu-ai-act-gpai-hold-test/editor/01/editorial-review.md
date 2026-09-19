# Editorial review: dispatches/eu-ai-act-gpai-one-year-on (editor/01)

## Skeptic

Thesis: a year after the AI Act's general-purpose model duties took effect,
what a provider must do today splits into a base tier (four duties under
Article 53) and a heavier systemic-risk tier (four more under Article 55),
providers can meet Article 53 through a Commission-endorsed Code of Practice
instead of inventing their own compliance, and the Commission's own power to
fine anyone over any of it only started a year after the duties did and has
so far produced one round of information requests, nothing heavier.

Each claim the piece rests on held against the evidence record and, where the
question was precise enough to need it, against a source fetched directly:

- The four Article 53 duties and their 2 August 2025 start date: held. Every
  quoted fragment ("with a large amount of data using self-supervision at
  scale," "sufficiently detailed summary," and the rest) checked
  character-for-character against the regulation text in the evidence record.
- The systemic-risk tier, the 10^25 FLOP presumption, and the missing public
  list: held. I independently confirmed Article 3(64) defines "high-impact
  capabilities" (the "match or exceed" quote the piece cites) and Article
  3(65) defines "systemic risk," so the piece's citation is correctly paired
  with its quote.
- The Code of Practice's structure: broke. The draft described "three
  chapters: Transparency and Copyright... and Safety and Security," naming
  only two groupings for three chapters. I fetched the Commission's own Code
  of Practice page and confirmed Transparency and Copyright are two separate
  chapters alongside Safety and Security. Fixed directly, since the source
  the researcher already opened settles it.
- Meta's refusal and its timing: broke. The draft said Kaplan posted "the day
  after the Commission published its guidelines," a detail absent from the
  evidence record. I checked it against outside sources (a law-firm memo
  dating the guidelines to 18 July 2025) and found the guidelines and
  Kaplan's LinkedIn post landed the same day, per CNBC, not a day apart. Cut
  the claim rather than replace it with a fact the record itself doesn't
  carry; kept "a week after OpenAI had committed to sign it," which the
  record does support.
- The 10^25 FLOP threshold's "tens of millions of euros" cost: the evidence
  record already flags this as Epoch AI's estimate, repeated by the
  Commission, not a figure the Commission owns. The draft said "the
  Commission estimates." Reworded to attribute it as an estimate the
  Commission cites.
- The 2 August 2027 grace period: the draft's closing sentence anchored
  current models to "when the Act passed" (June 2024), a full year off the
  actual cutoff (2 August 2025) that governs the grace period. Fixed to the
  correct anchor.
- Enforcement: held throughout. Every date, figure, and quoted phrase in the
  enforcement section traces to its owning source, and the piece correctly
  declines to name any information-request recipient or Digital Omnibus
  detail the evidence record couldn't support.

None of these was a broken central claim; every fix drew on a source already
in the evidence record or already cited by name. Nothing here needed the
researcher or a rewrite from the writer.

## Cut

Three sentences failed the slop test and were removed outright:

- The orientation section's closer address a hypothetical reader directly
  ("A reader who has only seen 'the AI Act is in force' in a headline still
  cannot answer...") — a self-reference failure on its own terms, and a
  reworded lift of the commission's own framing of the reader's situation.
- The Code of Practice section's opening sentence ("A provider need not
  invent its own way to show it meets Article 53") reduced to a pattern any
  compliance story could use; deleting it lost no fact.
- The enforcement section's final paragraph opened on a pure signpost ("One
  more date sits behind all of this") ahead of the fact it was introducing.

This is the paper's first article, so no recurring formula, dek mold, or
heading shape could apply, per the brief. I ran the edge test anyway, on
every paragraph, section, and the article as a whole; the three cuts above
were the only failures. The article's actual last sentence, once its date
anchor was corrected, earns its place: it ties the abstract 2027 deadline to
the reader's own tools rather than restating the deadline.

## Reader

Read straight through, the piece gives a single dated account of which
duties bind a provider today, which exist only as a power the Commission
hasn't used, and which gaps in the record (no public systemic-risk list, no
named information-request recipient) are gaps rather than evidence the tier
is empty. Eight fragmentary Commission pages and two press accounts never
state this together; the piece is the first place that does, which matches
what the draft handoff claimed for itself, and it holds on inspection.

The prose sits closer to the voice-guide exemplars than a median AI summary,
particularly the Code of Practice section's one-duty-per-sentence pattern
with the article number closing each line, and the plain, undecorated
closer. The three cuts above were exactly the passages reading as
scaffolding rather than reporting.

Rereading the headline as the article's largest claim: "Brussels has yet to
fine anyone" is the piece's most contestable line, and the section it
anchors defends it directly, with the fining power's own start date, the
single information-request action on record, and the explicit absence of any
fine, ordered fix, or model evaluation. It holds.

## Edits

- Cut the closing sentence of the orientation section, which addressed a
  hypothetical reader in terms lifted from the commission.
- Reworded the systemic-risk compute-cost sentence to attribute the "tens of
  millions of euros" figure to an estimate the Commission cites, not one it
  made.
- Cut the Code of Practice section's opening sentence ("A provider need not
  invent its own way...").
- Corrected the Code of Practice sentence to name all three chapters
  (Transparency, Copyright, Safety and Security) instead of collapsing two
  into one label, and split it into three shorter sentences to clear the
  sentence-density check.
- Cut the unsupported, and independently verified inaccurate, "the day after
  the Commission published its guidelines" detail from the Kaplan sentence.
- Cut the empty transitional sentence opening the enforcement section's
  final paragraph ("One more date sits behind all of this").
- Corrected the closing sentence's date anchor from "when the Act passed" to
  the actual 2 August 2025 grace-period cutoff.

## Required work

None. Every finding was fixable with a source already in the evidence record
or already cited by name; nothing broke a central claim, and no gap needed
reporting from the researcher or a redraft from the writer.

## Decision

Approve. `./nb stamp` then `./nb check` report BLOCK: 0, WARN: 0, verdict
PUBLISHABLE, at 1,108 words, within the commission's 800-1200 scope and
lighter than the draft's 1,168, per this round's cut-rather-than-expand
direction.
