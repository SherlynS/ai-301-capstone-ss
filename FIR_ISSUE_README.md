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

Going in depth on environment set up:
1. Followed the  [CONTRIBUTING.md](https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md) file specifically this section :
  https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md
i wasn't sure how to download some of these tools - so i used AI to help me understand how to download these tools an what the specific purposes are.
<img width="558" height="622" alt="Screenshot 2026-08-08 at 6 49 11 PM" src="https://github.com/user-attachments/assets/0bf76724-2607-4132-9792-4be0fbecef01" />

   
Then from there i asked more about what these tools are for - so i could get an understanding behind why these are needed as i start my implementation process.

<img width="583" height="471" alt="Screenshot 2026-08-08 at 6 53 20 PM" src="https://github.com/user-attachments/assets/a124c024-4648-47ed-a2d3-e186f0fb0ff1" />

I encountered a challenge which i was able to solve and iterate on which fulfills the second requirement on the spreadsheet. 
**Environment Setup section documents real challenges encountered + how they were resolved**

### Steps to Reproduce

1. There aren't any issues to reproduce, this chore requires for me to implement something new, not to fix any bug therefore the only thing i can prove ist that they don't have any Spanish (es-ES) language support in the @asgardeo/i18n package.

As i mentioned before there isn't an existing bug/issue that needs to be reproduced this specific task is a feature which needs to be implemented. Once i set up my environment i than begin exploring the setup of the files which give different language capabilities. This was the specific section i was following since these were the instructions of the maintainer: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#contributing

maintainer instructions: https://github.com/asgardeo/javascript/issues/157#issuecomment-4672524578
The PR contains the only files which i touched in addition to the sample application (which isn't in the PR): 
1. .changeset/spanish-translation-bundle.md - added a description of what the changes made were for and introducing spanish translation - https://github.com/asgardeo/javascript/pull/533/changes#diff-fea5f6559db89947005bdb88a88fa3c288d7fe0834859ad38d163d0699efe367
2. packages/i18n/src/constants/TranslationBundleConstants.ts - included default translations of package to be english and spanish -https://github.com/asgardeo/javascript/pull/533/changes#diff-0c4c4192a8c64cf24f3f30c9e9fb52813b4d246cfe48d468ea7a857f0bec4d3a
3. packages/i18n/src/translations/es-ES.ts - specific spanish translation of various application components - https://github.com/asgardeo/javascript/pull/533/changes#diff-03ec6917cb3bb70bfa4eca3357014edd29b79861fdd91d883ba5333e4a589a3d
4. packages/i18n/src/translations/index.ts - updated this to include the path for spanish translation file - https://github.com/asgardeo/javascript/pull/533/changes#diff-c008274c53cb32bd3fba1f2856457ebca7912c364f20b08a0f1d4cdce17f58fc
5. CONTRIBUTING.md - used this file to explore the different steps towards making the feature happen -  https://github.com/asgardeo/javascript/pull/533/changes#diff-eca12c0a30e25b4b46522ebf89465a03ba72a03f540796c979137931d8f92055
6. /Users/ssaavedra27/open-source-proj/javascript-sher/samples/teamspace-react/src/main.tsx - sample application path used for testing 

if we want to go into details then here are the steps: 
1. cloned repo
2. had the package pre reqs installed
3. Decided to explore first the existing files and how the languages were being used across the different application components 
4. created a new language file : https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#create-a-new-language-file
5. copied the existing structure of the english file: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#create-a-new-language-file
6. Update the translation components to be now in spanish: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#create-a-new-language-file
7. Exported the new language bundle: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#create-a-new-language-file
8. Tested my translation using an exising sample application : https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#create-a-new-language-file - which was option 2: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#option-2-integrate-into-an-existing-sample
9. Updated the AsgardeoProvider: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#testing-with-asgardeoprovider
10. Made a changeset- since we are adding a new feature this is a required step: https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#releases - https://github.com/asgardeo/javascript/blob/main/CONTRIBUTING.md#creating-a-changeset
11. Opened a PR and waiting on maintainer approval 

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


### Week [7] Progress 
Was able to get some feedback from maintainer on one minor edit (see here: https://github.com/asgardeo/javascript/pull/533#discussion_r3601500068). Was able to make this change and update the PR. Already request for a new review -hopefully this will allow all the checks to pass. --> WORKING ON NEW ISSUE NOW: https://github.com/SherlynS/ai-301-capstone-ss/blob/main/SEC_ISSUE_README.md

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

**Most Recent Up To Date Update*** i have now been able to make all the needed changes in order to make the PR open for review. i squashed my commits so the PR looks much cleaner. Im hoping to get feedback from the maintainer. i believe there may be feedback related to testing since i did only test my changes using only 1 of the 2 testing startegies. This update is from 07/07/26. 

**Most Recent Up To Date Update*** I have gotten beedback from an automated bot which the maintainers include in order to suggest any channges before they actually go into review. Im hoping to get some feedback from the actual maintainers this week. I already made a comment letting the maintainers know that i am ready for feedback from them, hopefully this will get their attention. Until then i'll move on to working on fidning a new PR to work on this week. Feedback recently from - 07/12/26. 

- Alert message to maintainer: https://github.com/asgardeo/javascript/issues/157#issuecomment-4953890441
- Most recent commit with suggested changes from CodeRabbit Bot - https://github.com/asgardeo/javascript/pull/533

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
