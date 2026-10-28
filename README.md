# Clarity Sprint: Sample Diagnostic

A Clarity Sprint is a fixed-scope diagnostic engagement from Lēdor Labs. Over a short, bounded run, the Sprint maps where a team's project time actually goes, tests that map against evidence, and scores the candidate changes so the client can decide what to fix first. It ends in a diagnostic document: findings tied to evidence, a scored opportunity map, and recommendations sequenced over the next 90 days.

This folder holds a complete sample of that deliverable, so a prospective client can see the shape, the evidence standard, and the reasoning before engaging.

## The client is fictional

Alder & Quill Studio does not exist. The studio, its people, and every figure in the sample were invented to show the format. The sample says so on its face, in its header and its closing note, because a sample that could be mistaken for a real engagement would be a small fraud. Nothing in it is a finding about a real organization, a testimonial, or a result.

## The method in brief

**Evidence first.** The Sprint runs stakeholder interviews and workflow interviews, and inventories the documents the team actually works from. Every finding points to a named interview excerpt, a client document, or a second source that agrees. The grading rule for the real deliverable: no evidence, no claim. Contradictions between sources are logged and carried into the findings, not averaged away.

**Findings report work, never people.** The Sprint maps tasks and workflows. No individual is scored, ranked, or recommended on.

**Risk is split in two.** Each candidate change is scored on two separate risk factors, each 0 to 3:

- **Impact:** what is harmed if this work goes wrong.
- **Catch:** whether a named checkpoint stops the harm before it lands.

**Effective Risk = Impact - Catch, never below zero.** The two are scored separately because a single risk number hides which one is doing the work. A high-impact task with a strong checkpoint in front of it is a different problem from a medium-impact task with nothing watching it, and the fix differs too: one needs care, the other needs a checkpoint.

**The full score.** Each candidate is also scored 0 to 3 on Repetition, Information readiness, and Worth, and 0 to 3 on Exception load. The priority index is:

Priority index = Repetition + Information readiness + Worth - Effective Risk - Exception load

The index sorts candidates into classes: Automate, Assist first, Fix information first, Keep human, and Do not automate. Three overrides outrank the arithmetic:

- **Impact 3 means Keep human at any index.** Work whose failure harms client trust or the client's money stays under human judgment, however repetitive it is.
- Impact 2 or higher with Catch 1 or lower cannot be classed Automate or Assist first until a real checkpoint exists.
- Low information readiness moves a candidate to Fix information first at any index. Automating on top of broken inputs produces faster broken outputs.

Every score carries its reason in writing. A score without a reason does not ship. And the scores sort the leads; they do not make the decision. A person does.

## How to read the sample

`sample-diagnostic.md` follows the live deliverable section by section:

1. **Intake summary:** the decision the Sprint informs, and the scope agreed with the sponsor, including what was deliberately left out.
2. **Evidence base:** the interviews, documents, and contradictions the findings rest on.
3. **Findings:** what the evidence showed, each with its evidence named.
4. **Scored opportunity map:** every candidate task scored, classed, and reasoned.
5. **Sequenced recommendations:** what to do in days 1 to 30, 31 to 60, and 61 to 90, each with an owner, plus an explicit list of what the Sprint does not recommend.

In a live engagement, an appendix ships with the full evidence log and the complete scoring rubric. The sample omits the appendix and labels its figures as sample data throughout; the format is the point of the document.

## Who runs this

A Clarity Sprint is run by Lēdor Labs. Rodel Oiga is its Principal. Contact and more on how Lēdor Labs works: rodeloiga.com.
