# custom-lucky-draw-page

A flexible lucky draw display system tailored to meet various client requirements, designed to be used during live events. The system supports different winner display modes, prevents duplicate winners, and provides admin tools for result management.

## Overview

This lucky draw tool dynamically adapts based on the configured number of winners, and is used to display participant names or IDs in real time during event ceremonies.

## Key Features

- **Dual Display Modes**
  - Supports two types of displays:
    - **Single winner draw**
    - **Multiple winners draw** (e.g. 7 winners as shown in the demo)
  - Behavior and layout adapt automatically based on a parameter

- **Winner Display Customization**
  - Adjusted layout to properly format and center winner details for 1 or multiple winners
  - Clean and clear design optimized for large-screen projection

- **Duplicate Prevention**
  - System checks the database to **exclude already-drawn winners**
  - Ensures fairness by preventing repeat selections

- **Admin Tools**
  - **Download Excel** of selected winners
  - **Delete row** functionality to remove selected results if needed

## Contributions

- Customized the layout to support both single and multiple-winner scenarios
- Added logic to dynamically switch behavior based on draw parameters
- Implemented database checking to ensure unique winner selection
- Developed export and deletion tools for admin use
- Designed UI for live event screen display and visual impact

## Watch Demo
https://youtu.be/sCZiS7YWEcY
