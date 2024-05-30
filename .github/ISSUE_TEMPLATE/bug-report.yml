name: Bug Report
description: Create a report to help us improve HighLife
labels: ["bug", "triage"]
assignees:
  - 

body:
  - type: markdown
    attributes:
      value: |
        Thank you for taking the time to fill out this bug report.
        Only bug related issues are accepted, so please refrain from submitting any other requests (including support requests).
        
        \* Issue reports that fail to deliver the proper information may be closed without any feedback.
  
  - type: input
    id: steam-name
    attributes:
      label: Steam Username
      description: |
        This is required to be able to find your player account if needed
      placeholder: 
    validations:
      required: true
      
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: |
        Please be clear and concise
      placeholder: 
    validations:
      required: true
  
  - type: input
    id: expectation
    attributes:
      label: Expected result
      description: |
        What should've happened instead?
    validations:
      required: true
  
  - type: textarea
    id: repro
    attributes:
      label: Reproduction steps
      description: |
        This is important to us. Fill in the exact steps you took, test and remove any steps that aren't relevant.
      placeholder: |
        1. 
        2. 
        3. 
        4. 
    validations:
      required: true
  
  - type: dropdown
    id: importancy
    attributes:
      label: Importancy
      description: |
        To your knowledge how would you describe the importancy of this bug?
      options:
        - Unknown
        - Slight inconvenience
        - There's a workaround
        - Low
        - Medium
        - High
        - Critical
        - Crash
    validations:
      required: true
  
  - type: textarea
    id: misc
    attributes:
      label: Additional information
      description: |
        Anything else you'd like to add?
