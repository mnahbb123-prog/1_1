---
name: Run-button workflow order
description: Workspace-specific behavior when binding a custom console workflow to Replit's Run button.
---

Register or configure the console workflow before setting the Run-button selection in `.replit`; workflow configuration can restore the default selection.

**Why:** The workflow registration reset the selected Run target during Java console setup, leaving the new workflow configured but not selected until `.replit` was validated again afterward.

**How to apply:** For future non-artifact console workflows, configure the workflow first, then validate and apply the `.replit` Run-button selection as the final configuration step.
