---
name: reset-session
description: Summarizes progress to the project context file and clears the session to conserve tokens.
---

# Reset Session Skill

## Instructions

When the user triggers this skill, execute the following steps precisely:

1. **Summarize Progress:** Automatically run a prompt equivalent to `/compact` that synthesizes the current architecture decisions, state of code, and immediate next steps.
2. **Determine and Write Context File:** 
   - Check the current workspace and session history to identify the existing context file name and path based on the user's standard practices (e.g., `GEMINI.md`).
   - If the file name and path are confidently known, explicitly state them to the user for confirmation (e.g., "Saving progress to `./GEMINI.md`...").
   - If the file name or path cannot be confidently determined, ask the user to provide the target file path before proceeding.
   - Once confirmed or provided, write the condensed summary to that file, overwriting it with the fresh state.
3. **Wipe Session:** Inform the user that the state has been successfully preserved in the file, and then immediately execute the `/clear` command to reset the conversational context window to zero.