---
name: Custom issue template
about: Describe this issue template's purpose here.
title: If running a code push workflow using the GITHUB_TOKEN repository, the new
  workflow will not run even if the repository has a workflow configured to run when
  a push event occurs.
labels: documentation, enhancement, good first issue, help wanted, question
assignees: ''

---

Issue template: 
When you use the GITHUB_TOKEN repository to perform tasks.  Events triggered by GITHUB_TOKEN except workflow_dispatch and repository_dispatch will not create a new workflow run.  This prevents you from accidentally creating recursive workflow calls. For example, if running a code push workflow using the GITHUB_TOKEN repository, the new workflow will not run even if the repository has a workflow configured to run when available.
