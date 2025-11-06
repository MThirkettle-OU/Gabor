# Gabor Orientation Task

## Overview
This is a basic visual psychophysics task designed to test orientation discrimination using Gabor patches. On each trial, three Gabor patches are displayed side-by-side. One of them has a different orientation, and the participant must identify which one using the number keys **1**, **2**, or **3** (left to right).

## Instructions
1. Open the `gabor_orientation_task.html` file in a modern web browser.
2. Read the instructions at the top of the page.
3. On each trial, press **1**, **2**, or **3** to select the Gabor patch that appears differently oriented.
4. Feedback will be displayed after each response:
   - **Correct!** if the chosen patch was the odd one out.
   - **Incorrect.** otherwise.
5. The task runs for **10 trials**.
6. After completing all trials, a message will indicate the end of the task.

## Technical Notes
- The Gabor patches are generated using canvas elements and basic sine wave functions.
- The odd patch differs by **30°** from the base orientation.
- No data is stored or transmitted; this is a local-only test.

## Requirements
- A modern browser (Chrome, Firefox, Edge, Safari).
- No internet connection is required after downloading the file.
