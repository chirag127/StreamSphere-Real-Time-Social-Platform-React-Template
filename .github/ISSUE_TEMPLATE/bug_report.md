---
name: Bug Report
about: Create a report to help us improve
title: "[Bug] "
labels: bug
assignees: "chirag127"

body:
  - type: markdown
    attributes:
      value: |+
        ## Bug Report
        Thank you for reporting a bug! Please provide as much detail as possible to help us quickly diagnose and fix the issue.

        **Project Name:** StreamSphere-Real-Time-Social-Platform-React-Web-App
        **Repository:** [https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App](https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Web-App)

        --- 
  - type: textarea
    id: what-happened
    attributes:
      label: What did you expect to happen?
      description: |+
        Clearly describe what you expected the application to do.
      placeholder: |+
        For example: "I expected the real-time feed to update instantly when a new message is posted."
    validations:
      required: true
  - type: textarea
    id: current-behavior
    attributes:
      label: What actually happened?
      description: |+
        Describe the actual behavior you observed. Be as specific as possible.
      placeholder: |+
        For example: "The feed did not update until the page was manually refreshed, or it updated with a significant delay."
    validations:
      required: true
  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: Steps to reproduce
      description: |+
        Provide a step-by-step guide to reproduce the problem. This is crucial for us to fix it.
      placeholder: |+
        1. Go to the main feed page.
        2. Post a new message.
        3. Observe the feed...
    validations:
      required: true
  - type: textarea
    id: environment
    attributes:
      label: Environment (System, Browser, Versions)
      description: |+
        Please provide information about your environment:
        *   Operating System: (e.g., Windows 11, macOS Sonoma 14.2, Ubuntu 22.04)
        *   Browser and Version: (e.g., Chrome 120.0.6099.129, Firefox 115.0.2)
        *   Project Dependencies: (If known, e.g., specific versions of React, Node.js)
      placeholder: |+
        *   OS: Windows 11
        *   Browser: Chrome 120
        *   Node.js version: 20.10.0
        *   npm/yarn version: npm 10.2.3
    validations:
      required: true
  - type: textarea
    id: additional-context
    attributes:
      label: Additional context
      description: |+
        Any other context about the problem. Screenshots, logs, or links to relevant discussions are helpful.
      placeholder: |+
        Add any screenshots, console logs, or relevant information here.
