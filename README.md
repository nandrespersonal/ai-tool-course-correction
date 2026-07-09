# AI Tool Course Correction

Concept-preview repository for a post-overlap AI-tool course-correction assistant.

## What this is

AI Tool Course Correction helps a team decide what to do after an existing AI tool overlaps with a broader enterprise platform or adjacent tool suite.

The assistant turns overlap into platform leverage instead of treating the earlier tool as wasted effort.

## Problem

Teams and departments can build useful AI tools before they know a larger platform is addressing the same space. When overlap appears, teams need a structured way to decide whether to retire, integrate, wrap, extend, upstream, or keep the existing tool as a bridge.

This includes the case where a tool gets **steamrolled**: a larger organization, platform release, vendor feature, or next model capability makes the original scaffold less necessary.

Sam Altman described the underlying AI-platform risk this way:

> "There are two strategies to build on AI right now. There's one strategy which is to assume the model is not going to get better and then you kind of build all these little things on top of it. There's another strategy which is build assuming that OpenAI is going to stay on the same rate of trajectory and the models are going to keep getting better at the same pace... when we just do our fundamental job because we have a mission, we're going to steamroll you."

The course-correction response should not treat steamrolling as failure by default. A displaced artifact may still have validated a workflow, exposed a gap, generated user evidence, clarified requirements, or created a bridge that helped the organization learn faster.

## Intended outcome

Given an existing tool and an overlapping platform, the assistant should produce a course-correction packet:

- original business need,
- validated workflow evidence,
- existing tool capabilities,
- overlapping platform capabilities,
- remaining gaps,
- extension opportunities,
- feature requests,
- platform-team outreach draft,
- recommended tool fate: retire, integrate, wrap, extend, contribute upstream, or bridge.

## Course-correction paths

| Path | Use when |
|---|---|
| Retire | The broader platform fully covers the need. |
| Integrate | There is a clear contribution or migration path. |
| Wrap | The platform is strong but needs a better workflow layer. |
| Extend | APIs, plugins, skills, agents, marketplace mechanisms, or config can close the gap. |
| Contribute upstream | The existing tool reveals missing platform capability or design feedback. |
| Bridge | The broader platform is directionally correct but not ready for the immediate business need. |
| Reframe | The artifact is no longer durable, but the learning, workflow evidence, or product intuition remains valuable. |

## Steamrolled artifact response

When a tool is steamrolled, the assistant should ask:

- What limitation did the original artifact compensate for?
- Did the larger model, platform, or organization actually remove that limitation?
- What validated workflow evidence should be preserved?
- Can the artifact become a wrapper, adapter, evaluation layer, memory layer, or migration bridge?
- What should be retired to avoid sunk-cost maintenance?
- What should be upstreamed as product feedback?
- What decision record should remain after the artifact is archived?

## What this is not

- Not a defense mechanism for keeping every existing tool alive.
- Not an argument against enterprise platforms.
- Not a replacement for platform-team engagement.
- Not an autonomous migration planner.
- Not an executable product yet.

## Status

Concept preview. No executable code is included yet.

Any future implementation should complete security, privacy, and governance review before release or distribution.
