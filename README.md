# Contribution [157]: [chore: add Español - es-ES language support]

**Contribution Number:** [157]  
**Student:** [Sherlyn Saavedra]  
**Issue:** [[GitHub issue link](https://github.com/asgardeo/javascript/issues/157)]  
**Status:** [Phase I] [Complete]

---

## Why I Chose This Issue

I selected this open PR because it aligns with one of the skills that I have which is that i am a native spanish speaker. In addition, this also benifits my skills in tech because i will be able to make a signficant contribution by using a techstack i am familiar with TypeScript, HTML, and JavaScript; it expands into a great impact as well since its part of WSO2's/asgardeo accesibility mission for users/customers. 

---

## Understanding the Issue

### Problem Description

Currently, the Asgardeo JavaScript SDK does not have support for Spanish (Español - es-ES). Users who prefer Spanish will not see UI components translated, limiting accessibility for Spanish-speaking users.

### Expected Behavior

Asgardeo JavaScript SDK will support support for Spanish (Español - es-ES), which targets Spanish-speaking users.

### Current Behavior

The Asgardeo JavaScript SDK does not have support for Spanish (Español - es-ES).

### Affected Components

No Spanish (es-ES) language support to the @asgardeo/i18n package.

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

1. Have the proper installations on system in order to properly run and contribute changes: https://github.com/SherlynS/javascript-sher
2. Fork the repo: https://github.com/asgardeo/javascript/tree/main -> https://github.com/SherlynS/javascript-sher
3. clone repo into local setup : https://github.com/SherlynS/javascript-sher
4. Work on local setup and follow along the contribution guide : [CONTRIBUTING.md](https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md)
   

### Steps to Reproduce

1. There aren't any issues to reproduce, this chore requires for me to implement something new, not to fix any bug therefore the only thing i can prove ist that they don't have any Spanish (es-ES) language support in the @asgardeo/i18n package.


### Reproduction Evidence

- **Commit showing reproduction:** [[Link to your fork]](https://github.com/SherlynS/javascript-sher), there isn't a commit showing the reproduction of any issue since there is no issue that persists. I included the forked repo which is where i plan to push my changes during implementation. 
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]: No findings, the contribution document does a good job of clarifying details for setting up the implementation phase. 

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]: following this step: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#adding-a-new-language
3. [Add function Z]: following this step: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#adding-a-new-language
5. [Update tests]: following this step: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#test-your-translation

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]
Used option 2 from the CONTRIBUTING.md file in order to test my changes against an existing application on the repository. i made some updates in the CONTRIBUTING.md  file about some specifications on what works and what doesnt work for this testing option. Some of the instructions are either too vague or out of date. 

---

## Implementation Notes

### Week [3] Progress

#### Code Changes

- **Files modified:** created a new file calles es-ES.ts where i am making all my changes in order to provide Spanish (es-ES) language support in the @asgardeo/i18n package
- **Key commits:** made 2 commits, (1) created the es-ES.ts file and made a copy of the en-US.ts file in order to have an existing format to know where i need to make edits. (2) The second commit i made changes to were three sections (i plan on doing three section changes as i go). 
- **Approach decisions:** I decided to make changes to one section everyday but made a commit that compiled changes from three days, im hoping to maybe change this up and make more commits each day as instructed in the instructions to see my progress.

#### Challanges Faced 
 - Needed to link my github account to the one i am currently working with since i originally had it linked to my school github account

#### Testing Strategy
- Was able to run a command that the CONTRIBUTING.md file walked me through in order to verify that my changes and translations were correct.
- followed this section and selected option 1: https://github.com/SherlynS/javascript-sher/blob/sherlynS-add-spa/CONTRIBUTING.md#test-your-translation

#### Branch Link

- **Link:** https://github.com/SherlynS/javascript-sher/tree/sherlynS-add-spa


### Week [Y] Progress

[Continue documenting as you work]

---

## Pull Request

**PR Link:** https://github.com/asgardeo/javascript/pull/533 - PR IS NOW OPEN FOR REVIEW AND IM WAITING ON HEARING BACK

**PR Description:** Currently, the Asgardeo JavaScript SDK does not have support for Spanish (Español - es-ES). Users who prefer Spanish will not see UI components translated, limiting accessibility for Spanish-speaking users.

This PR addresses this barrier and now customers who prefer Spanish will be able to see UI components translated and easily navigate through other UI components for each readability and use.

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [**Awaiting review** / Iterating / Approved / Merged]

**IMPORTANT UPDATE:**  I haven't been able to fully make a PR ready for review yet, since i have been doing mostly testing there is stuff that i need to add to the repositorys documentation. There is missing information which is out of date and also needed in the future for contributors who are testing thieir changes. Therefore ive been able to successfully make a draft PR but i still need to compile this before making it ready to review by the maintainer. I hope this is ok, if not please let me know as soon as possible. 

**Most Recent Up To Date Update*** i have now been able to make all the needed changes in order to make the PR open for review. i squashed my commits so the PR looks much cleaner. im hoping to get feedback from the maintainer. i believe there maybbe feedback related to testing since i did only test my changes using only 1 of the 2 testing startegies. This update is from 07/07/26. 

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
