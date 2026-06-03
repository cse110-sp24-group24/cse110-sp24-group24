# Sprint 3 Standup & Pre-Midterm Check-In Meeting Notes

**Meeting Details**
- **Type of Meeting:** Sprint 3 Standup & Check-In
- **Date:** June 3, 2026
- **Time:** 4:04 PM - 4:12 PM
- **Platform:** Zoom

**Attendance**
- **Present:** Samuel Zubatiy, Itai Lavi, Janoj Rengaraj, Ryan Dang, Ethan, Soohwan Jeon
- **Note:** Soohwan had audio issues throughout the meeting and was advised to follow up via Slack or DM.

---

## Agenda
1. Sprint 3 Issue Status Check
2. Post-Sprint-3 Polish Plan
3. Final Presentation Format
4. CI/CD Pipeline Overview (Midterm Prep)

---

## Discussion Points & Notes

**1. Sprint 3 Issue Status Check**

- Sam opened by asking who had looked at their issues and whether everything seemed reasonable and doable.
- Sam reiterated the overall Sprint 3 scope: adding remaining features like the stats screen and making buttons like "play again" fully functional.
- Ethan confirmed that he and Janoj worked until 11pm the previous night and got most of their issue working. A few test case problems still need to be resolved before it is fully closed.
- Soohwan indicated he was running into some issues with his audio-related task but had audio problems during the call and could not fully explain. Sam and Itai advised him via the meeting that as long as he does not delete any existing code, he is free to add to the audio manager file as needed to make his issue work. They directed him to follow up in chat or DMs if he needs further help.

**2. Post-Sprint-3 Polish Plan**

- Ryan asked whether the team would meet after Wednesday to handle finishing touches.
- Sam and Itai confirmed yes. The plan is to compile a short shared doc listing any remaining bugs, missing small features, and nice-to-haves that did not make it into the sprint.
- Itai framed it as low-pressure: since everything at that point is a nice-to-have, no one who is busy will be forced to contribute. It will be based on available bandwidth.
- Sam noted the difficulty and tab behavior have already been addressed, so the list of remaining items should be short.
- The post-sprint meeting will likely be Thursday, though Sam suggested Wednesday could also work since people will be finishing up until the very end of the sprint.

**3. Final Presentation Format**

- Ryan asked about the plan for the final presentation.
- Sam confirmed that details have not been fully released by the professor yet, but more information is expected at Wednesday's class session.
- Based on what is known: the final block is 3 hours, shared across roughly 25 groups, which works out to approximately 5 to 7 minutes per group. Itai noted that timeline lines up with how these things typically go given the number of teams.
- Sam said he will share whatever is communicated Wednesday with the full team.

**4. CI/CD Pipeline Overview (Midterm Prep)**

- Itai flagged that the professor indicated the CI/CD pipeline would be on the midterm exam, and that everyone should be able to explain their own team's setup.
- Sam gave a brief explanation for the group:
  - **CI (Continuous Integration):** Any time code is committed, it automatically runs through the team's lint tests and checks compliance with the established style guidelines.
  - **CD (Continuous Deployment):** If the CI checks pass, the game is automatically deployed to GitHub Pages. If CI fails, deployment does not happen.
  - The full term stands for Continuous Integration / Continuous Deployment.
- Sam noted he built the pipeline himself, so his description reflects exactly how it works. He shared a Quizlet he made covering relevant terminology for the midterm as well.

---

## Decisions Made

- **Post-Sprint Polish:** A shared doc will be created to track remaining bugs and nice-to-haves. A follow-up meeting planned for Thursday (tentatively) after the Wednesday sprint deadline.
- **Final Presentation:** No structural decisions yet; waiting on Wednesday's class for details.
- **CI/CD for Midterm:** Everyone should be able to describe the team's pipeline as: lint checks on every commit (CI) and auto-deploy to GitHub Pages on passing (CD).

---

## Action Items

- [ ] **Ethan & Janoj:** Resolve remaining test case issues and close their Sprint 3 issue.
- [ ] **Soohwan:** Follow up with Sam or Itai via Slack on audio manager issue. Add to the file as needed without removing existing code.
- [ ] **Sam:** Create a shared doc for post-sprint polish items.
- [ ] **Sam/Itai:** Share final presentation details with the team after Wednesday's class.
- [ ] **Everyone:** Sprint 3 issues due by Wednesday. Good luck on the midterm tomorrow.
