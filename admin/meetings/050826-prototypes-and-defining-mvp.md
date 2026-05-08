# Prototype Demo & MVP Planning Meeting Notes

**Meeting Details**
- **Type of Meeting:** Prototype Showcase & MVP Definition
- **Date:** Friday (timestamp range: 1:32 PM - 2:12 PM)
- **Platform:** Zoom

**Attendance**
- **Present:** Samuel Zubatiy, Itai Lavi, Janoj Rengaraj, Lixi Liang, Ethan M, Simar Gowda, Shubhi Srivastava, Nishant Sharma, Soohwan Jeon

---

## Agenda
1. Prototype Demos
2. MVP Direction Discussion
3. Development Workflow & Process Planning

---

## Prototype Showcases

**Sam** - Roguelite Typing Shooter (Claude, ~5 iterations)
- Character at the bottom of the screen shoots words/phrases before they fall to the ground.
- Each wave fills out a function displayed on the right side of the screen; boss battles require typing a full function.
- Random upgrades offered between waves (roguelite progression structure).

**Itai** - Plane Skydive Game (Codex)
- Player types code snippets during a plane's takeoff phase to earn tokens; longer snippets yield a higher multiplier.
- Plane eventually crashes, player is ejected and skydives while avoiding obstacles.
- Power-ups scattered throughout (e.g., slow-time, shield). Final score determined by survival time and typing multiplier.

**Lixi** - Dungeon Monster Typing Game (PC build, could not screen share)
- Horror/dungeon theme with background music. ASCII-character monsters with varying HP and damage.
- Player types words to attack monsters; HP drains if a monster's timer runs out.
- Approximately 6 different monsters. Ends with a game-over/retry screen.

**Ethan** - VS Code-Themed Typing Racer (unreported tool)
- Solo mode or race against a bot with adjustable difficulty.
- Language selection available. Post-game stats screen shows accuracy and other metrics.
- Sam noted the accuracy stat as a feature worth incorporating into the final product.

**Janoj** - Wave-Based Roguelite (buggy, built with Links)
- Similar structure to Sam's prototype: wave-based enemies with upgrades.
- Included a REM log feature. Acknowledged to be rough; concept was the focus.

**Simar** - Horror Typing Game with Glitch Effects
- Corruption bar fills as player fails to type in time; hitting zero triggers a "panic mode."
- Glitch visual effects and ambient horror music. Hard mode available.

**Shubhi** - Falling Code Snippet Game (Codex, 2 iterations)
- Code snippets fall from the top of the screen; player must type them before they hit the ground.
- Currently falls too quickly and snippets are long; noted as a tuning issue. Still early in development.

**Nishant** - CS Learning Q&A Tool (not a traditional typing game)
- Claude generates questions based on course lecture content. Player types answers; grading uses keyword matching (~35% keyword overlap threshold).
- Features a streak counter and hint tracking. Inspired by a Duolingo-style UI/UX.
- Noted by Sam as the most "practical" prototype in terms of actual learning value.

**Soohwan** - 30-Second Code Copying Game (Codex)
- A random code snippet is displayed; player copies it exactly into a text box. Score increases per successful match.
- 30-second rounds. Simple and functional, though acknowledged as a rough prototype.

---

## MVP Direction Discussion

**Agreed-Upon Direction: Haunted/Ghost Roguelite Typing Game**

After demo discussion, the group converged on the following core concept:
- A roguelite typing game (waves + random upgrades) where the player progresses through a haunted/ghost-themed environment.
- Aesthetic direction: Ghostbusters-inspired haunted house, with ghosts carrying lines of code on them. This was seen as a differentiating direction from the retro themes expected from other teams.
- Visual polish from Simar's glitch effects and horror aesthetic was called out as something worth combining with Sam's game structure.

**Educational Aspect**
- The group agreed that the game should not be purely mindless typing. Some form of learning element should be included.
- Itai proposed that certain in-game obstacles or ghosts could trigger a conceptual question (e.g., "What does this line of code do?"), answered via typing rather than clicking.
- Nishant proposed presenting multiple-choice options where the player types the correct answer rather than selecting it, keeping the typing mechanic intact.
- Language selection (as seen in Ethan and Itai's prototypes) was flagged as a good feature to let players focus on a specific language.

**Target Audience**
- Sam had written "up-and-coming computer science students" on the in-class worksheet; the group generally agreed but decided to refine the niche further once the game takes more shape.

---

## Development Process & Workflow

**AI-Assisted Development**
- The team will use a hybrid approach: AI for scaffolding and animation-heavy work, manual coding for refinements.
- No requirement to stick to one AI tool; members can use Claude, Codex, or whichever they prefer.
- Itai cautioned against building on top of an existing AI-generated prototype too much, as iterating on a large AI-generated codebase can compound bugs.

**Codebase Coordination**
- Sam raised the risk of multiple groups overwriting each other's changes, especially when AI regenerates whole files.
- Janoj advocated for using GitHub branches and resolving merge conflicts manually, noting that new features typically live in separate files and conflicts should be manageable.
- The group agreed to proceed with the branching strategy and revisit if it becomes a problem.

**User Stories & Sprint Process**
- Sam outlined the development approach: each person generates user stories defining individual features, which will then be sorted and used as sprint tasks.
- Janoj mentioned Claude's "GSD" (Get Shit Done) planning feature as a possible tool for structuring the full software plan end-to-end.
- Lixi suggested maintaining a single MD file containing all user stories and requirements to serve as consistent context for AI prompts across sessions, rather than re-explaining the project each time.
- Sam agreed the MD file approach is necessary but emphasized the game should be built iteratively across 5 weeks, not one-shot prompted.

---

## Decisions Made

- **MVP:** Roguelite wave-based typing game with a ghost/haunted horror theme and some form of educational mechanics.
- **Workflow:** GitHub branching for parallel feature development; merge conflicts resolved manually.
- **Process:** User stories to drive all feature work, discussed and compiled starting at the Monday meeting.
- **Standup Channel:** Wednesday Slack standups established as a mid-week check-in. Sam acknowledged he hadn't posted yet and committed to doing so after the meeting.

---

## Action Items

- [ ] **Sam:** Write up the MVP document based on today's discussion.
- [ ] **Everyone:** Come to Monday's meeting prepared to read out user stories for the features you want to build.
- [ ] **Sam/Itai:** Coordinate with other team leads via the group chat Ayla created to share direction and avoid duplicate project ideas.
- [ ] **Itai:** Send photos of the in-class worksheet to the group chat; each member to complete their assigned portion.
- [ ] **Everyone:** Post a Wednesday Slack standup update (Sam to post his after the meeting as well).
- [ ] **Sam:** Explore using Claude's GSD planning feature once user stories are collected, as Janoj suggested.
