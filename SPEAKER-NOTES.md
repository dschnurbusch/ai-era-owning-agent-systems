# Owning Your Agent Systems — first-draft speaker notes

Proposed pacing: 27 minutes of content plus 3 minutes of buffer. Rehearse before treating these as measured times. The 30-minute breakout is separate.

This is a suggested talk track, not attributed quotations or claims about Dan's measured firm results. Add a genuine personal example in rehearsal. No live client systems are needed.

## 1. Owning your agent systems — 1:30

Open with the operating problem, not the software. “The question is not which AI is smartest. It is whether a useful job gets done, whether I can inspect it, and who owns the failure.”

State the promise: people will leave able to distinguish the system's parts and describe a first job worth delegating. “Digital employee” is a design metaphor. Software has no professional license or independent accountability.

## 2. Start with a job — 1:00

Read the bounded assignment. Draw attention to “for my review.” The useful deliverable is an unsent draft with evidence, not autonomous communication.

Ask the audience to hold one recurring job in mind throughout the talk. Don't open a discussion yet.

## 3. The continuum — 2:30

Explain buy, configure, operate. Advance once to trace the line, then again to reveal the tradeoff.

“The farther toward operating the system we go, the more control we can exercise. We also inherit more work.” The horizontal positions are teaching categories, not scores. They overlap.

Filevine LOIS and Clio Work / Vincent are examples of legal-platform agents. Claude and ChatGPT offer commercial general-purpose agent surfaces; specify the actual product and plan when evaluating them. Hermes and OpenClaw are examples of open harnesses. Do not say commercial products cannot use custom connectors or skills.

## 4. Choose the responsibility — 2:00

Walk each column by the job it fits, not by a feature inventory. “Buying is not failure. Maintaining software you didn't need is not sophistication.”

Explain a concrete procurement question: can this system do the exact job, within the right permissions, and export the result? Test that instead of relying on the marketing label.

## 5. Separate the layers — 1:30

Make the key distinctions: open/proprietary harness, local/hosted inference, and where the harness runs. These are separate decisions.

“Running Hermes on your laptop doesn't mean client information never leaves the laptop.” Draw the data boundary around the model provider and each connected service. Avoid treating either self-hosting or vendor hosting as an automatic security conclusion.

## 6. The architecture — 2:30

Define the layers in plain language. The model reasons. The harness coordinates the loop. Tools give access. Skills give procedure. Memory helps continuity; source records establish facts.

Build the stack with three advances. End on permissions and verification as the boundary, not another optional feature. “The chat window is an entry point. It is not an authority grant.”

## 7. Tools and skills — 1:30

Explain MCP as a connection standard. Show how three bounded tools let the agent read, find correspondence, and prepare an unsent draft.

Read the skill example, especially its stop condition. Procedures can travel across systems more readily than bespoke runtime code, but actual compatibility and permission enforcement still need testing.

## 8. The work loop — 2:00

Follow the line across retrieval and checking, down through drafting and approval, then back to verification. Advance twice to reveal the consequential steps.

“Approval is for a specific action. Verification checks the actual destination.” A successful tool response isn't proof that the intended result exists. If a write's outcome is uncertain, inspect before retrying.

## 9. A reviewable result — 3:00

Spend time here. Explain the fictional record asks for two items. The recent message contains one. The actual attachment must be reviewed, not merely inferred from its filename.

Show the narrower draft and the sources. Ask: “What should the agent not do?” Briefly answer: send the message, mark everything complete, or pretend the missing statement arrived.

This is a static walkthrough, deliberately reliable on stage. If adding a demonstration later, use a short sanitized recording and keep these still scenes as backup. Do not present this fictional example as a live production result.

## 10. Failure and control — 2:00

Two failures are enough: stale evidence and false completion. Show the control next to each.

Trust is not confidence in the model's tone. It is a review path, a stop rule, and evidence that the action happened. Preserve unknown facts instead of filling gaps with plausible values.

## 11. Team deployment — 2:30

Separate shared procedure from shared identity. Each person needs the right role and matter access. “Read, draft, and send are three permissions, not one.”

Explain the table as illustrative. A reviewer authorizes an exact action; the service checks authority. Staff don't acquire Dan's credentials because a prompt says they are acting for him.

Name an operating owner. Someone must handle credentials, upgrades, incidents, and cost. Sensitive logs should not become a second client-data warehouse.

## 12. Cost — 3:00

Use the before/after workflow shape instead of made-up savings numbers. Retrieve a narrow set of facts. Load the relevant skill. Use code for deterministic work; use reasoning where judgment warrants it.

The equation is an accounting framework: include the model, infrastructure, review, and maintenance for a consistent period, divided by accepted results. A cheaper model that doubles review time may be the more expensive workflow.

Don't imply every extraction can safely skip human checking. Distinguish mechanical filtering from legal interpretation.

## 13. First job — 1:00

Point to the six elements on the slide and the fuller worksheet in the guide. Give people permission to start small.

The breakout can use one nonconfidential job to identify sources, a relevant connector, a procedure, and a review boundary. No need to install infrastructure in the main talk.

## 14. Close — 1:00

“Own the procedure. Choose what else to own.” Restate: know what you control, what you rent, and who is responsible.

Point to the downloadable guide and worksheet. Use the remaining three-minute buffer for pacing or a brief question if the session host permits it.

## Stage checklist

- Download and extract the offline package. Open `index.html?mode=present#s1`, or open `index.html` and click Present, then Home.
- Test the actual clicker. Right/Space/PageDown reveal or advance; Left/PageUp reverse; G toggles guide; F fullscreen.
- Use laptop power and disable notification banners before stage time. Do not depend on venue Wi-Fi.
- Confirm the venue accepts a browser presentation from your laptop and test the projector's resolution.
- Attendees use the guide link; keep the PDF as a durable takeaway. The site itself adds no analytics.
- The draft has no live demo or embedded video. Those can be added after narrative review, with explicit sanitization.
