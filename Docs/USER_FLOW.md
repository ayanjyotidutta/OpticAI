# 🗺️ User Flow: OpticAI

This document outlines the logic paths a user takes from landing to completion.

### 1. Entry Point (Landing Page)
- **User Action:** Clicks "START GAME".
- **Logic:** Initialize `round` to 1, `history` to empty array, and generate first `targetColor`.

### 2. State: MEMORIZE (The Stare)
- **User Action:** Observes color.
- **Constraint:** 5000ms (5s) countdown.
- **Logic:** Once `msTimer === 0`, transition to `GUESS` state.

### 3. State: GUESS (The Match)
- **User Action:** Adjusts 3 HSL Sliders.
- **Constraint:** 30s countdown.
- **Termination:** User clicks "LOCK IT IN" or timer hits 0s.
- **Logic:** Execute `calculateScore()` and push result to `history` array.

### 4. State: RESULT (The Feedback)
- **User Action:** Clicks "NEXT ROUND".
- **Logic:** - IF `round < 5`: Increment `round` and return to **MEMORIZE**.
    - IF `round === 5`: Transition to **FINAL SUMMARY**.

### 5. State: FINAL SUMMARY (The Analysis)
- **User Action:** Reviews scores or Clicks "RETRY".
- **Logic:** - Sum total scores.
    - Map `totalScore` to `getTieredInfo` (Tier name + Humor quote).
    - Reset app state on "RETRY".
