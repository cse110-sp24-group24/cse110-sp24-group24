# Sprint 1 Kickoff Check-In Meeting Notes

**Meeting Details**
- **Type of Meeting:** Sprint 1 Check-In & Standup
- **Date:** May 18, 2026
- **Time:** 4:00 PM - 4:30 PM
- **Platform:** Zoom

**Attendance**
- **Present:** Samuel Zubatiy, Itai Lavi, Janoj Rengaraj, Nishant Sharma, Shubhi Srivastava
- **Note:** Sam indicated he would message anything important to members not present.

---

## Agenda
1. Issue Assignment Clarifications
2. Code Standards & Style Guidelines
3. Unit Testing Strategy
4. Deadline Flexibility Policy

---

## Discussion Points & Notes

**1. Issue Assignment Clarifications**

- Sam opened by noting this is a short check-in, not a long meeting, since issues were already assigned over the weekend.
- Nishant asked about issue #12, which he had received an email notification for. Sam confirmed it was assigned to him briefly by accident and then unassigned, so Nishant only needs to focus on issue #5.
- Issue #5 is shared between Nishant and Simar. Itai clarified that the work was already split in the announcement: each person handles the specific languages assigned to them. They are welcome to coordinate directly but the split is already defined.
- Sam reminded the group to use the index.html in the root directory, not any of the prototype versions, since it is already formatted with placeholders that make clear where each issue's code goes. This was a follow-up from last meeting's discussion about keeping the baseline clean.

**2. Code Standards & Style Guidelines**

- Sam raised the professor's requirement that each team develop a consistent code style, so that separate parts of the codebase are obviously written by the same team.
- Sam flagged that he hadn't fully figured this out yet and opened it up for input.
- Basic style rules proposed by Sam: consistent bracket placement on control structures (if, for, while loops), and return statements on their own line rather than inline.
- Itai suggested formalizing a set of style rules similar to what was given in CSE 11, and also proposed creating a CLAUDE.md file in the repo that documents these rules so AI coding agents can read and apply them as well.
- Janoj recommended two specific standards: camelCase naming convention for all variables and functions, and JSDoc-style comments (the multi-line format using `/**` with `@param` and `@return` tags). He noted that Claude can generate JSDoc comments automatically, so there's no need to write them by hand.
- Sam agreed these are very standard and practical, and flagged that this conversation needed to happen before the team wrote too much code.
- **Decision:** Team will adopt camelCase naming, JSDoc-style comments, and consistent bracket and return formatting. A CLAUDE.md file will be created to document these for AI context.

**3. Unit Testing Strategy**

- Janoj asked whether the team should be writing unit tests alongside their code as issues are completed.
- Sam confirmed the CI/CD pipeline via GitHub Actions is the next thing he needs to set up, and it will handle some of this. He was unsure whether per-issue unit tests were expected or if end-of-sprint testing made more sense.
- Itai suggested that writing tests alongside individual issues is useful so code can be verified before being handed off to whoever depends on it.
- Itai acknowledged that not all issues lend themselves easily to unit tests. His own issue (main screen and animations) is hard to unit test directly.
- Janoj proposed using Puppeteer end-to-end tests, the same approach used in this week's course lab. He recommended letting Claude generate the Puppeteer tests rather than writing them manually, as the documentation is dense and tedious but the task is well-suited for an LLM.
- Sam agreed and noted Puppeteer tests are mostly copy-and-paste style but require explicitly describing every interaction, which is exactly the kind of repetitive task AI handles well.
- Itai clarified that the CI/CD pipeline via GitHub Actions should stay general (syntax errors, cross-file handoff checks) while more specific Puppeteer tests can be added alongside individual issues.
- Janoj recalled the professor saying tests should not all be added at the end of the project, reinforcing that some testing should happen during development.
- **Decision:** No formal per-issue unit test requirement, but developers should test their own code locally before committing. Puppeteer end-to-end tests to be generated with AI assistance. GitHub Actions CI/CD to remain general. Sam to set it up before Sprint 1 work gets too far along.

**4. Deadline Flexibility Policy**

- Itai reminded the group that if a deadline is genuinely difficult to hit due to a midterm or a heavy week, members should communicate early rather than just missing it silently.
- Sam echoed this: assigned dates are not locked in. The team can accommodate conflicts as long as people reach out in advance so the sprint does not have to be restructured unexpectedly.
- Sam summarized both points simply: just communicate.

---

## Decisions Made

- **Code Style:** camelCase naming, JSDoc comments, consistent bracket and return formatting adopted as team standards.
- **CLAUDE.md:** Itai to create a file documenting style rules so AI agents have consistent context.
- **Testing:** Local testing before committing; Puppeteer end-to-end tests generated with AI. CI/CD pipeline via GitHub Actions to stay general.
- **Issue Completion:** When you finish an issue, message in the main Slack chat and close the issue on GitHub so dependent teammates know they can proceed.

---

## Action Items

- [ ] **Sam:** Set up the GitHub Actions CI/CD pipeline (linting and general syntax checks) before Sprint 1 work progresses further.
- [ ] **Itai:** Create a CLAUDE.md file in the repo documenting the agreed-upon code style rules.
- [ ] **Sam:** Write up and share the code style guidelines in an announcement so everyone has them before writing more code.
- [ ] **Everyone:** Write good comments throughout your code as you go. Do not wait until the end.
- [ ] **Everyone:** When you finish your issue, message in the main Slack chat and close the issue on GitHub.
- [ ] **Nishant & Simar:** Coordinate on issue #5 as needed, following the language split from Itai's original announcement.
