# Commission: dispatches/eu-ai-act-gpai-one-year-on

## The request

The owner asked: "Write me an article on what the EU AI Act's rules for
general-purpose AI models actually require of model providers now that they
have been in force for a year, and what has changed in practice."

No link or document came with the request. The request is the commission.

## Home

Series `dispatches` (open, manual), template `article`, no tags. First article
in a new paper: no published coverage, no neighboring articles this run, no
recent openers, deks, or outline shapes to avoid.

## Contribution

The article establishes, from the governing texts and what the Commission and
providers have done since 2 August 2025, what a provider of a general-purpose
AI model placed on the EU market is now obliged to do, and what has changed in
the year since those obligations applied. It answers the question a reader who
has heard "the AI Act is in force" cannot answer from the headlines: which
duties bind which providers today, and which have teeth yet.

## What the piece must establish, not mention

- The obligations on every general-purpose model provider under Article 53
  (technical documentation, downstream information, a copyright policy, the
  public training-content summary) and the date they applied.
- The systemic-risk tier under Article 51 and Article 55: the compute
  presumption, the extra duties (evaluation, adversarial testing, incident
  reporting, cybersecurity), and who has been designated or presumed in.
- The Code of Practice: what signing it buys a provider, who signed, and who
  refused, named.
- Enforcement: when the Commission's powers to fine general-purpose providers
  apply (August 2026), what the AI Office has done with them, and any
  enforcement or compliance action on the record in the first year.
- The grace period for models placed on the market before 2 August 2025 and
  what it means for the models readers use.

## Reader

The press has no editorial profile yet. Write for the natural audience of the
house standard: a technically literate reader who follows AI and policy and
has not read the regulation. Define each term of art on first use. Assume the
reader knows what a language model is and does not know what a "general-purpose
AI model" means in the Act.

## Sources

Primary sources own the claims: the Regulation (EU) 2024/1689 text on EUR-Lex,
the Commission's guidelines on general-purpose AI model obligations (July
2025), the General-Purpose AI Code of Practice and the Commission's signatory
list, the AI Office's own announcements on enforcement, and providers' own
published compliance documents where they exist. Secondary reporting only for
context or for events the primary record does not describe. The series floor
is five sources; the argument will need more.

Source policy as resolved by `nb source-policy --series dispatches` and the
production policy as resolved by `nb production-policy --series dispatches`
are appended below.

## Production

Harness: Claude Code, this checkout, as the local agent. The owner switched the
press to the economy profile during production. Coach and researcher were
already running on the harness model, Claude Fable 5.1, at default effort;
writer and editor run on Claude Sonnet 5 at the profile's effort. Nothing is
required, so nothing is traded down against a directive.

Scope, set by the owner during production: this is a light rehearsal piece.
Aim near the 800-word floor and never past 1200. Five to seven sources, the
primary documents first; one enforcement fact on the record is enough, not a
survey. Each role spends the least it can to meet the standard, and none
chases completeness. No charts. No hold: the article publishes when the check
passes.

## Records
--- source policy
{"series": {}, "templates": {"article": {"min_sources": 5}}}
--- production policy
{"profile": "economy", "stages": {"editor": {"effort": "high", "model": "capable", "required": false}, "researcher": {"effort": "medium", "model": "capable", "required": false}, "writer": {"effort": "medium", "model": "capable", "required": false}, "writing-coach": {"effort": "low", "model": "efficient", "required": false}}}
