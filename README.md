# Azure DevOps Work Item Classification Knowledge Base

## Question Bank

### Strategic Scope Questions
**Q-STRATEGIC-1**: "Is this work related to a strategic business goal or initiative?"
- **Purpose**: Identifies potential Epics
- **Indicators**: Business strategy, company objectives, multi-quarter goals
- **Follow-up**: If Yes → Check scope; If No → Check capability

**Q-SCOPE-1**: "Does this span multiple teams, iterations, or releases?"
- **Purpose**: Confirms Epic classification
- **Indicators**: Cross-team coordination, long timelines, complex dependencies
- **Classification**: Epic if Yes

### Capability Questions
**Q-CAPABILITY-1**: "Is this a new capability or service that delivers value to users?"
- **Purpose**: Identifies Features
- **Indicators**: New functionality, user-facing improvements, service additions
- **Follow-up**: If Yes → Likely Feature; If No → Check size

**Q-CAPABILITY-2**: "What type of value does this provide to users?"
- **Purpose**: Distinguishes between Feature and User Story
- **Options**: Major new capability / Small enhancement / Technical improvement

### Size and Scope Questions
**Q-SIZE-1**: "Is this a small, self-contained piece of work that can be delivered quickly?"
- **Purpose**: Identifies User Stories
- **Indicators**: Single sprint, independent delivery, focused scope
- **Follow-up**: If Yes → Determine Business vs Technical

**Q-SIZE-2**: "How long would this realistically take to complete?"
- **Purpose**: Helps distinguish Epic/Feature/Story
- **Options**: Multiple months / Few weeks / Days to 1 week

### Technical vs Business Questions
**Q-AUDIENCE-1**: "Is this work user-facing or technical/internal?"
- **Purpose**: Distinguishes Business from Technical User Stories
- **Indicators**: UI changes, user interaction vs. code quality, infrastructure

**Q-AUDIENCE-2**: "Who is the primary beneficiary of this work?"
- **Options**: End users / Development team / Operations team / Business stakeholders

### Problem Type Questions
**Q-PROBLEM-1**: "Is this a defect or unexpected system behavior?"
- **Purpose**: Identifies Bugs
- **Indicators**: System not working as designed, error conditions, broken functionality

**Q-PROBLEM-2**: "Is this a blocker, risk, or unplanned issue affecting delivery?"
- **Purpose**: Identifies Issues
- **Indicators**: Blocking dependencies, process problems, external factors

## Classification Patterns

### Epic Patterns
- Contains words: "strategy", "initiative", "platform", "transformation"
- Involves multiple teams or quarters
- Has business-level impact
- Example: "Launch new customer onboarding experience across all platforms"

### Feature Patterns
- Contains words: "enable", "capability", "service", "experience"
- Focused on user value delivery
- Moderate complexity and scope
- Example: "Enable self-service account creation"

### User Story Patterns
- Contains words: "as a user", "I want", "so that"
- Specific, actionable, testable
- Can be completed in one sprint
- Example: "As a user, I want to reset my password so I can access my account"

### Bug Patterns
- Contains words: "error", "broken", "not working", "fails"
- Describes current vs. expected behavior
- Needs investigation and fixing
- Example: "Password reset link returns 404 error"

### Issue Patterns
- Contains words: "blocked", "risk", "dependency", "process"
- Describes obstacles or concerns
- Needs resolution or mitigation
- Example: "Blocked by missing API documentation from third-party vendor"

## Adaptive Learning Cues

### Context Clues to Watch For
- Technical terminology → Likely Technical User Story
- Business process language → Likely Epic or Feature
- Error descriptions → Likely Bug
- User experience language → Likely Business User Story
- Dependency mentions → Likely Issue

### Question Selection Logic
- If description is vague → Ask scope questions first
- If technical details present → Ask audience questions
- If problem-focused → Ask problem type questions
- If goal-oriented → Ask strategic questions

## Classification Confidence Levels
- **High Confidence**: Clear indicators match single classification
- **Medium Confidence**: Some indicators present, may need clarification
- **Low Confidence**: Mixed indicators, require additional questions
- **Hybrid Items**: May have characteristics of multiple types - suggest primary with notes
