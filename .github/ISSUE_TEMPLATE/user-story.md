---
name: User Story
about: User Story templete
title: ''
labels: user-story
assignees: ''

---

name: User Story
description: Describe a feature from the user's perspective
labels: ["user story"]
 
body:
  - type: markdown
    attributes:
      value: |
        ## User Story
        Fill in the fields below. **Role**, **Action**, **Value**, **Acceptance Criteria**, **Use Case**, and **Priority** are required.
 
  - type: input
    id: role
    attributes:
      label: Role
      description: Who is this story for?
      placeholder: e.g. Administrator, Teacher, Student
    validations:
      required: true
 
  - type: input
    id: action
    attributes:
      label: Action
      description: What do they want to do?
      placeholder: e.g. create a lesson by selecting a group, teacher, room, and time slot
    validations:
      required: true
 
  - type: input
    id: value
    attributes:
      label: Value
      description: Why do they want to do it? What is the benefit?
      placeholder: e.g. it appears in the schedule and is visible to all users
    validations:
      required: true
 
  - type: textarea
    id: acceptance-criteria
    attributes:
      label: Acceptance Criteria
      description: List at least 3 criteria. Each line is one criterion.
      placeholder: |
        - [ ] ...
        - [ ] ...
        - [ ] ...
    validations:
      required: true
 
  - type: input
    id: use-case
    attributes:
      label: Use Case
      description: Which Use Case does this story belong to?
      placeholder: e.g. UC-02
    validations:
      required: true
 
  - type: dropdown
    id: priority
    attributes:
      label: Priority
      description: Select the priority and then add the corresponding label (Priority:HIGH / Priority:MEDIUM / Priority:LOW) manually on the right side panel.
      options:
        - "High"
        - "Medium"
        - "Low"
    validations:
      required: true
 
  - type: textarea
    id: notes
    attributes:
      label: Notes
      description: Any additional context, edge cases, or design decisions (optional)
      placeholder: e.g. Consider mobile layout for this feature
    validations:
      required: false
 
  - type: textarea
    id: mockups
    attributes:
      label: Screenshots / Mockups
      description: Attach any wireframes or screenshots if available (optional)
      placeholder: Drag and drop images here
    validations:
      required: false
