# Learn AR with SPECS — Project Context

> This is the durable, public-safe source of truth for the project. Keep it current when a verified rule, decision, product goal, acceptance criterion, or submission requirement changes. Never add credentials, tokens, account/session data, private infrastructure, personal data, unpublished legal/financial information, or temporary debugging state.

## Status

- **Phase:** Ideation
- **Concept:** Not selected
- **Participation model:** Solo
- **Target:** SPECS 27 augmented-reality Lens
- **Primary objective:** Win First Place ($1,250 USD)
- **Submission deadline:** November 9, 2026 at 5:00 PM EST (22:00 UTC)
- **Current process:** The participant will present ideas first; the assistant will then present an independent idea set; all candidates will be challenged and scored using the same rubric before selecting or combining them.

## Official sources

- [Competition overview](https://learn-specs.devpost.com/)
- [Official rules](https://learn-specs.devpost.com/rules)
- [Schedule](https://learn-specs.devpost.com/details/dates)
- [Resources and FAQ](https://learn-specs.devpost.com/resources)
- [Official Learn AR skill pack](https://github.com/challengepost/learn-specs)
- [CLAD documentation](https://developers.specs.com/docs/clad)
- [CLAD agents and skills](https://developers.specs.com/docs/clad/overview-section/agents-and-skills)
- [Snap design best practices](https://developers.snap.com/spectacles/best-practices/design-for-spectacles/design-best-practices)
- [LEAF testing guide](https://developers.specs.com/docs/clad/tools/test-your-lens-with-leaf)
- [Official concept video](https://www.youtube.com/watch?v=S6w4aRVGQxs)
- [Devpost live judging review](https://www.youtube.com/watch?v=Xh8Ie_VuA_0)

Last verified: **October 28, 2026**. Rules, judges, dates, tools, and platform documentation can change; re-check official sources before implementation lock and submission.

## Schedule

- Submission period: October 15, 2026 at 10:00 AM EDT through November 9, 2026 at 5:00 PM EST.
- Live build session: October 29 at 12:00 PM ET.
- Live project review: November 5 at 12:00 PM ET.
- Judging: November 10 at 10:00 AM EST through November 17 at 5:00 PM EST.
- Winners announced: on or around November 19 at 2:00 PM EST.

## Stage One — eligibility gate

Stage One is pass/fail. A high-quality idea receives no score if it misses the contract.

The entry must:

1. Be a new SPECS Lens created during the submission period.
2. Be planned with the official Devpost Learn `plan-lens` skill.
3. Be built by an AI coding agent through CLAD, Lens Studio, and Lens Studio MCP.
4. Run consistently in Lens Studio Preview and behave as described.
5. Use only authorized/licensed third-party code, assets, APIs, SDKs, and data.
6. Provide an English description explaining the Lens and its functionality.
7. Provide a public GitHub, GitLab, or Bitbucket repository containing the Lens Studio project.
8. Provide a public YouTube demo under three minutes showing the working Lens, preferably in Lens Studio Preview.
9. Remain freely accessible for judging through the end of the judging period.

Include the generated `devpost/` planning documents even though the formal rules call them optional: the overview asks for them and they demonstrate the required process.

## Stage Two — equal scoring

| Criterion | Weight | Plain meaning | Concrete proof |
|---|---:|---|---|
| **Design** | 25% | A complete, coherent product rather than a technical proof of concept | One understandable end-to-end journey; intentional placement, timing, controls, feedback, onboarding, recovery, comfort, and visual identity |
| **Technical Implementation** | 25% | Build quality and effective use of CLAD, Lens Studio, and MCP | Reliable Preview behavior, appropriate SIK/UIKit, clean compilation/runtime logs, meaningful CLAD/MCP use, and repeatable LEAF evidence where applicable |
| **Innovation / Idea** | 25% | A creative, memorable concept differentiated from existing work | A specific user and moment, a distinctive execution or combination, and a reason the experience belongs on glasses |
| **Presentation** | 25% | A clear video proving the project end-to-end | Show the working Lens immediately; state the problem, user, and importance; make interactions legible; briefly show the planning/build/iteration process |

### Tie-breaking order

1. Design
2. Technical Implementation
3. Innovation / Idea
4. Presentation

Design is equally weighted during scoring but receives the first tie-breaking advantage.

## Publicly listed judges

### Joe Holmes — AI Learning Hackathon Architect, Devpost

Verified background and signals:

- AI/ML curriculum designer with experience creating practical learning programs.
- Official repository history attributes the current `plan-lens` skill and its refinements to him.
- In Devpost's live project review, he explicitly favored:
  - intentional detail over generic one-prompt output;
  - a personal fingerprint;
  - a small job done well;
  - purpose and audience understood within seconds;
  - low-friction, trustworthy access;
  - realistic demo content and platform-appropriate interaction;
  - validation and security hygiene;
  - simplicity when authentication/cloud complexity adds no value;
  - showing the working product immediately.
- He explained that innovation need not be unprecedented: a familiar capability can be innovative through distinctive execution, combination, audience, interaction, or visual treatment.

### Darlyze Calixte — Developer Marketing Manager, Devpost

Verified background and signals:

- Software developer and CreateHER Fest co-founder/Technical Director.
- Works across developer education, AI, AR/VR, community building, inclusion, and responsible technology.
- Public work emphasizes privacy, permissions, independent verification, and security from the start.
- In the joint live project review, she evaluated products as a first-time user and emphasized:
  - immediate clarity about purpose and audience;
  - intuitive onboarding and progressive disclosure;
  - low cognitive load;
  - plain, internationally understandable language;
  - accessibility;
  - realistic examples;
  - interaction appropriate to the device;
  - complete validation;
  - planning documents that match the delivered product.

### Panel uncertainty

The rules permit unlisted or replacement judges, multiple panels or rounds, peer review, and automated AI-assisted analysis. Joe and Darlyze are strong public signals, not guaranteed sole scorers. The official rubric is authoritative.

## Product doctrine

### Three genuine strengths of glasses

A candidate should use at least one convincingly; the strongest concepts combine two or more:

1. **Shares the user's view:** responds to what and where the user is looking.
2. **Draws in the world:** places content at the relevant physical location and scale.
3. **Leaves the body free:** keeps hands available and eyes on the real task.

### Design rules

- Do not build a website floating in front of the face.
- Place information on or beside what it concerns.
- Show information when useful, then let it recede.
- Prefer a few large, forgiving SIK/UIKit targets with visible targeting feedback.
- Keep essential content where the user is already looking.
- Keep main content around 0.6–1.6 metres away and slightly below eye level unless the use case requires otherwise.
- Avoid sustained raised-arm interaction and steep neck angles.
- Use readable light content; black is transparent on the additive display.
- Make the first action and current state obvious.
- Include a reset or recovery path.
- Do not record, identify, or follow people without consent.

## Capability map

SPECS 27 is a standalone see-through AR computer with a 51° display, 16 million colors, open-ear stereo audio, microphones, dual processors, Wi-Fi (and an optional cellular case), world-facing cameras, hand tracking, voice input, and 6DoF world tracking. A Lens can use TypeScript/JavaScript logic, 3D rendering, animation, particles, physics, sound, standard UI, local/on-device ML, HTTPS/WebSockets, remote media, cloud AI services, location/heading, world surfaces, persistent spatial anchors, and synchronized multi-user sessions.

Device capability is broader than hackathon-demo capability:

| Capability | Available on device | Hackathon position |
|---|---|---|
| World-scale 3D, text, panels, animation, particles, simple physics and spatial sound | Yes | Strong, directly demonstrable |
| Head/world tracking and content fixed in space | Yes | Strong, directly demonstrable |
| Standard hand input: ray, pinch, poke, press, grab, drag, throw, sliders and toggles | Yes | Strong with SIK/UIKit and mouse-driven Preview |
| Full hand joints, custom poses, two-hand motion and speed interpretation | Yes | Do not make core: Preview cannot prove natural behavior |
| Real surfaces, depth and lightweight world hit testing | Yes | Use a virtual surface or deterministic placement in Preview |
| Camera frames, still capture and on-device SnapML classification/detection/segmentation | Yes, permission-controlled | Do not make core: real camera vision is unavailable in Preview |
| Marker, face and some body/object tracking | Supported with limits and permissions | High demo/privacy risk; never identify or follow people without consent |
| Speech-to-text in 40+ languages, microphones and voice commands | Yes | Pair every action with a button; voice may not work in Preview |
| GPS, heading and location-aware content | Yes, with account/network/permission requirements | Simulate the route/place with sample data and virtual markers |
| HTTPS, WebSockets, external APIs and downloaded media | Yes | Use sample data and deterministic offline fallback |
| Remote AI: OpenAI, Gemini, DeepSeek, image/TTS/realtime services and Snap text-to-3D | Yes, token/permission-controlled | Optional enhancement only; never make the judged flow depend on a live response |
| Persistent world anchors across sessions | Yes | Keep out of done criteria because persistence cannot be demonstrated reliably |
| Synchronous colocated multi-user Connected Lenses | Yes | Keep out of core: requires multiple physical devices and people |

Privacy permissions constrain combinations. Camera, microphone, precise location and similar sensitive data require consent; combining them with external connectivity may require transparent or extended permissions, and some experimental combinations cannot be publicly released. Prefer processed local signals and the least permission needed.

For ideation, separate the **trigger** from the **value**. If recognition, voice, location, AI or live data triggers the experience, Preview may substitute an explicit button or fixed sample. The useful spatial response after that trigger must still be complete and real.

## Preview contract

Every done criterion must be demonstrable in Lens Studio Preview.

### Reliable

- World-scale 3D models and text
- Spatial placement and walking around the scene
- SIK/UIKit pinch, press, grab, drag, throw, sliders, and toggles
- Animation, simple physics, and spatial sound
- LEAF automation of standard SIK interactions

### Requires a visible deterministic stand-in

- Recognition of real objects, signs, food, text, or places
- Real routes and location data
- Voice commands
- AI responses
- External live data

The stand-in must be disclosed. Build the valuable behavior after sensing for real; never pretend a mocked input is live recognition.

### Keep out of core done criteria

- Live camera understanding
- Custom/two-hand gesture dependence
- Hand-speed or raw-pose interpretation
- Cross-session spatial persistence
- Two-device shared experiences
- Any network, voice, or AI dependency without a deterministic fallback

One spatial moment done exceptionally well is a complete project.

## Known competitive pressure

Existing official SPECS experiences and prior CLAD work already cover navigation, measurement, timers, calling, drawing instruction, astronomy/education, sports training, karaoke, productivity, creative tools, and shared games. A current public forum post also names a spatial maintenance trainer.

Do not reject a category merely because it exists. Reject a generic execution. Differentiation must come from the user, problem, spatial moment, interaction, visual metaphor, or combination.

## Idea evaluation protocol

Each candidate receives the same evaluation:

```text
Stage-one viability:       pass / fail
Design:                    /25
Technical implementation: /25
Innovation / idea:         /25
Presentation potential:    /25
Total:                     /100
Glasses necessity:
Preview proof:
Fatal dependency or risk:
Strongest differentiator:
Smallest complete version:
```

### Questions every idea must answer

1. Who exactly has the problem?
2. What precise real-world moment are they in?
3. Where are their eyes and hands?
4. Why is using a phone or laptop materially worse?
5. What information or object belongs in their space, and where?
6. What is the single principal interaction?
7. What can be completed end-to-end in Preview?
8. What makes this execution memorable rather than generic?
9. What can be proven in the first 30 seconds of the demo?
10. What is deliberately out of scope?

### Ideation process

1. Collect the participant's ideas without prematurely narrowing them.
2. Produce an independent assistant idea set.
3. Score all ideas against the same gates and criteria.
4. Combine compatible strengths rather than defend idea ownership.
5. Short-list the strongest candidates.
6. Identify the single riskiest indispensable capability of each finalist.
7. Run the cheapest decisive capability spike before locking the concept.
8. Lock the concept, name, one spatial moment, done criteria, and exclusions.
9. Run the official `plan-lens` interview and approve `devpost/design-brief.md` before building.

## Tooling state

- Official `plan-lens` skill: project-local installation required.
- Official `ls-clad` plugin: project configuration required; the runtime machine must install the plugin and run it from the Lens Studio project directory.
- Lens Studio runtime and MCP connection: pending environment qualification.
- Concept implementation: not started.

## Public repository safety

This repository is intended to be public. Never commit:

- Credentials, tokens, cookies, browser/account sessions, or private keys.
- `.mcp.json` or any MCP configuration containing bearer credentials.
- Personal addresses, identity documents, banking/tax information, or private account status.
- Private LAN addresses, machine inventory, remote-access configuration, or internal infrastructure.
- Private diary or Mnemon content.
- Raw recordings, temporary captures, crash dumps, or local caches.
- Unlicensed assets or third-party material with unclear rights.
- Submission secrets or anything that should not remain permanently public.

## Current next steps

1. Receive the participant's idea set.
2. Produce the assistant's independent idea set.
3. Evaluate and combine candidates using the rubric above.
4. Select finalists and run bounded capability checks.
5. Lock the concept and complete the official `plan-lens` interview.
6. Build, verify, iterate, obtain live-review feedback, and prepare the submission.
