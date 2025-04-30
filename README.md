# custom-lucky-draw-page (Client-Specific Modifications)

This lucky draw page was modified to align with specific client requirements for a live event. The changes focused on enhancing flexibility in how winners are displayed and improving the admin tools for managing results.

## Overview

The system displays lucky draw winners either individually or in groups, depending on a configurable parameter. Additional logic was added to prevent duplicate winners and support admin operations.

## Key Features

- **Configurable Display Modes**
  - Modified the layout to support:
    - **Single-winner display**
    - **Multiple-winner display** (e.g., 7 winners at once)
  - Behavior dynamically adjusts based on draw parameter

- **Winner Display Enhancements**
  - Refined visual layout to ensure clean and balanced presentation, whether showing 1 or multiple winners

- **Duplicate Winner Prevention**
  - Integrated logic to check the database and **exclude participants who have already won**

- **Admin Controls**
  - Added functionality to **download results as Excel**
  - Implemented a **delete row** feature for managing winner data in real time

## Contributions

- Modified the lucky draw page to match event-specific requirements
- Customized layout and logic for dynamic winner display
- Integrated database checks to prevent duplicate winners
- Implemented export and deletion features for admin convenience

## Watch Demo
https://youtu.be/sCZiS7YWEcY
