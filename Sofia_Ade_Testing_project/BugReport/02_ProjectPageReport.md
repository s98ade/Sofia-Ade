
## Summary (Summarize the bug encountered concisely)

    The text on the "Create blank project" button is incorrectly displayed as "Create black project." This typo may confuse users and does not align with the intended functionality.

## Steps to reproduce  

    1. Navigate to the GitLab URL: https://gitlab.com/projects/new#blank_project.
    2. Locate the button labeled "Create blank project."
    3. Observe the typo on the button, where "blank" is incorrectly displayed as "black."
   

## What is the current bug behavior?

    The button displays the text "Create black project" instead of the correct text.
     

## What is the expected correct behavior?

    The button should display the text "Create blank project" to align with its intended functionality.
     
## Relevant logs and/or screenshots

    Bug Screenshot: ![alt text](../Image/Bug_Project_create_blank.png)

## Possible fixes

    Correct the typo in the source code by replacing "black" with "blank" for the relevant button text in the HTML or localization file.

## Whom do you report/ Assign To/ Tags

    Report to: Frontend Development Team
    Tags: UI Bug, High Priority, Typo

## Priority

    Priority: High
    This issue directly affects user experience and can lead to confusion during project creation.   
