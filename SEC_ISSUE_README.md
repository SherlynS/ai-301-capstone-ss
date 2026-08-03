# Contribution [#18]: [Add a new Newsletter Fetcher]

**Contribution Number:** [2]  
**Student:** [Sherlyn Saavedra]  
**Issue:** [https://github.com/Infrasity-Labs/awesome-tech-newsletter/issues/18]  
**Status:** [Phase I] [In Progress]

---

## Why I Chose This Issue

[1-2 paragraphs explaining why this issue interests you, how it matches your skills/learning goals, what you hope to learn]
This issue seems not only fairly straightforward for a first time contributer but also supports a community of developers who use this newsletter in the day to day journeys. Seems like something that is impactful to contibute to and worth taking time to work on. 

---

## Understanding the Issue

### Problem Description

Expanding the sources this project pulls newsletter data from. Fetchers live in fetchers/ and feed into aggregate.py, which merges, dedupes, and scores results before they land in the final list.

Pick one unsupported newsletter source or aggregator for example, a specific newsletter's own signup/archive page, a directory like TLDR's competitors, Substack's discovery/search API, or an RSS-based newsletter archive, and add support for it. You don't need to cover every possible source, just one.

### Expected Behavior

Should find a new source from which this newsletter org/service can provide to their customers - investigate what already exists and find a new option.

### Current Behavior

Existing fetcher in fetchers include the current resources which this newsletter to provides. The expected output shape (title, host, description, link, category, etc.)

### Affected Components

fetchers/ secction where the current resources live for which the newsletter to provides to customer and also documentation to provide for other contributors -as well as showing customers what is available to them. 

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]
1. Forked Repo: https://github.com/SherlynS/awesome-tech-newsletter
2. Explore suggested files from PR description: `fetchers/` and `aggregate.py` to see what newsletters are already being used to collect info from.
3. Explore `CONTRIBUTING.MD file` - download required pacakges to be able to run code + run tests

### Steps to Reproduce

1. Fork Repo 
2. Explore `CONTRIBUTING.MD file
3. Download required pacakges to be able to run code + run tests

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork] https://github.com/SherlynS/awesome-tech-newsletter
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction] - Was able to explore what existing newsletters they are getting information from: https://github.com/Infrasity-Labs/awesome-tech-newsletter/tree/main/fetchers

### Side Note 
- Worked on exploring some newsletters in order to provide options to the maintainer on which newsletter they would prefer to provide to their customers to share with
- Here is a response i curated to request to become an assignee of the Open PR and provided newsletter options which i like and know contain valuable information: https://github.com/Infrasity-Labs/awesome-tech-newsletter/issues/18#issuecomment-5086294279 

### Update 07/27-08/02
Haven't heard back from maintainer from first issue - sent a quick reminder: https://github.com/asgardeo/javascript/issues/157#issuecomment-5172899376. Same thing for second PR- seems like maintainer isn't active so i sent a quick update: https://github.com/Infrasity-Labs/awesome-tech-newsletter/issues/18#issuecomment-5172869695

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
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

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

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

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
