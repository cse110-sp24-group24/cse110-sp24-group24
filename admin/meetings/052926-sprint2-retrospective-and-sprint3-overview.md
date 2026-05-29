# Sprint 2 Retrospective & Sprint 3 Kickoff Meeting Notes

**Meeting Details**
- **Type of Meeting:** Sprint Retrospective & Sprint 3 Planning
- **Date:** May 29, 2026
- **Time:** 4:34 PM - 4:48 PM
- **Platform:** Zoom

**Attendance**
- **Present:** Samuel Zubatiy, Itai Lavi, Janoj Rengaraj, Nishant Sharma, Ryan Dang, Lixi Liang

---

## Agenda
1. Sprint 2 Gameplay Progress
2. Peer Review Feedback
3. Retrospective (Sprints 1 & 2)
4. Sprint 3 Issue Assignments
5. Boss Mechanic Redesign Discussion

---

## Discussion Points & Notes

**1. Sprint 2 Gameplay Progress**

- Itai noted he could not get past the boss during testing, so he cut the falling speed in half to make it more playable. The group agreed the new speed feels appropriate.
- Itai also removed the requirement to type leading spaces before snippets, so players now start typing immediately.
- The more complex upgrades were manually tested by Itai and confirmed working. He flagged that simpler upgrades like fall speed changes are straightforward and should be fine, but asked the group to report anything they notice while playing.
- Sam noted that every branch merged has added something new and the game is coming together well overall. He acknowledged the team's good work.

**2. Peer Review Feedback**

- Nishant brought up that the team had received peer review feedback that had not yet been discussed.
- Two reviewers gave conflicting opinions on the README: one praised it, one criticized it. Sam acknowledged the README was generated quickly using the previous one as a prompt and agreed it should be revised before the final submission.
- Ryan flagged that a reviewer mentioned mobile compatibility. Janoj noted the course prompt technically requires mobile support, though the group agreed a typing game on mobile does not make much practical sense. Itai suggested it could be handled late in development by prompting an AI tool to make the layout responsive, which should be enough to satisfy the requirement without overhauling the design.
- Janoj raised a point about the changelog.md file, noting a reviewer flagged it as empty and recommended documenting major milestones. Itai then clarified that the feedback Janoj was reading was written for Group 21, not Group 24. The team's actual peer review did not prominently raise this concern.
- Sam noted that comparing the team's repo against the ones reviewed, the team is doing well relative to other groups. He added that Ayla has consistently given positive feedback in their meetings, saying she looks forward to their check-ins because there is very little to address.

**3. Retrospective (Sprints 1 & 2)**

- The team noted that a retrospective for Sprint 1 was already held last week, so this served as a combined review.
- The dedicated Sprint Slack channel was highlighted as a clear win: it kept everyone communicating and giving updates in one place. It will carry over into Sprint 3.
- One process change made coming out of the last retrospective was adding a shared time variable to the codebase, which simplified coordination across features.

**4. Sprint 3 Issue Assignments**

- Sam confirmed the Sprint 3 issues are already posted on GitHub. Itai had already made assignments, which were sent out via GitHub and the Sprint 3 Slack channel. Itai added remaining members to the channel live during the meeting.
- Sprint 3 issues are smaller and more polished in scope compared to Sprint 2, since the core game is largely implemented. The focus shifts to refinements and enhancements.
- Itai noted there is one fewer issue this sprint, so one partner group has a less clearly defined split. He encouraged those partners to coordinate directly and figure out what works best for them.
- Sam described Sprint 2 as the hardest sprint and framed Sprint 3 as a comparatively lighter lift.
- Next meeting is Monday.

**5. Boss Mechanic Redesign Discussion**

- Janoj flagged that the current boss feels repetitive because the player is essentially typing the same lines they already typed during the wave, just again in order.
- Itai proposed a two-part change: during waves, each ghost carries a random snippet from a different function rather than sequential lines from the same one; during the boss, the player types the complete function all at once rather than line by line, with a countdown timer that rewards speed and accuracy with bonus points.
- Janoj agreed and noted it aligned with what he had been thinking. Sam confirmed it was also close to how his original prototype handled the boss, and the group agreed it is a better experience.
- Sam added that he would also like the player's typing to be rendered visually on screen during the boss encounter, rather than just appearing in a plain text input box, to make the feedback feel more immersive.
- The group agreed these changes are polish items and not blockers for Sprint 3. The plan is to complete Sprint 3 issues by Wednesday, then use the Wednesday-to-Sunday window to implement these kinds of refinements. Itai summarized the priority clearly: get to a functional MVP first, then layer in the extras.

---

## Decisions Made

- **README:** To be revised and improved before final submission. The current version was a quick AI-generated draft.
- **Mobile Compatibility:** Low priority but worth a late-stage AI-assisted pass to meet the course requirement minimally.
- **Boss Mechanic:** Waves will use randomized function snippets rather than sequential lines. Boss will require typing the full function at once with a countdown for bonus points. Visual on-screen typing feedback to be added. These are post-Sprint-3 polish items.
- **Sprint Slack Channel:** Continuing into Sprint 3.
- **Sprint 3 Timeline:** Issues due by next Wednesday. Polish and enhancements planned for Wednesday through Sunday.

---

## Action Items

- [ ] **Sam:** Revise and improve the README before final submission.
- [ ] **Everyone:** Review Sprint 3 issue assignments on GitHub and in the Sprint 3 Slack channel. Reach out to Itai or Sam with any questions or conflicts.
- [ ] **Partner groups with less defined splits:** Coordinate directly to divide Sprint 3 work in a way that makes sense.
- [ ] **Everyone:** Focus on functionality and getting issues done by Wednesday. Boss mechanic redesign and polish items to follow in the Wednesday-to-Sunday window.
- [ ] **Sam/Itai:** Revisit mobile compatibility with a responsive design pass before final submission.
