# FSC-HCD-COE-SCIP
READ ME

SCIP User Journey Map
VA Financial Services Center - User Research Study
====================================================


OVERVIEW
--------
This repository contains the SCIP User Journey Map, a single-page HTML artifact
documenting the end-to-end experience of VISN-level capital planners across the
full annual Strategic Capital Investment Planning (SCIP) cycle.

The map was produced as part of a qualitative user research study. It covers 9
stages of the annual cycle and 6 swimlane rows of research findings per stage,
with a full opportunities row below.

The HTML file is self-contained. No server, build process, or framework is
required. Open it in any modern browser.


FILES IN THIS REPOSITORY
-------------------------
The SCIP User Journey Map
  README.txt                     This file
  ACCESSIBILITY_STATEMENT.txt    WCAG 2.1 and Section 508 compliance documentation


HOW TO OPEN
-----------
Download the HTML file and open it in a browser. No installation required.
To share it, send the file directly. The recipient opens it the same way.

Recommended minimum viewport: 1280px wide. The map is a horizontal grid and
requires horizontal scrolling on narrower screens.

The file loads fonts from Google Fonts (Source Sans 3, Bitter, Roboto Mono).
An internet connection is required to render the intended typography. If offline,
the file degrades gracefully to system fonts, and all content remains accessible.

Tested in: Chrome, Firefox, Safari, Edge (current versions).


JOURNEY STRUCTURE
-----------------
The map covers 9 stages, read left to right:

  Stage 01  Pre-Cycle Preparation
  Stage 02  Cycle Open
  Stage 03  Project Entry
  Stage 04  VISN Review
  Stage 05  Submission
  Stage 06  Budget Uncertainty
  Stage 07  Review Response
  Stage 08  Reporting
  Stage 09  Post-Cycle

Each stage has 6 swimlane rows, read top to bottom:

  What Users Are Doing   Actions and goals at that stage
  Thoughts and Needs      Mental model, unmet needs, and cognitive load
  Pain Points             Documented friction, barriers, and defects
  Workarounds             Shadow systems and compensating behaviors
  Delight Signals         What is working well and why
  Systems in Use          Tools and systems in use at each stage

Below the main grid: an Emotion Arc row summarizing the overall emotional state
at each stage, followed by an Opportunities row with prioritized design
recommendations.


READING THE COLOR SYSTEM
-------------------------
Cell background color represents the user's emotional state at that stage:

  Green background     Delight
  Gray background      Neutral
  Yellow background    Friction
  Red/pink background  Pain
  Light pink           Critical

Card left border color represents the signal type of each individual finding
within a cell:

  Red border    Pain point
  Gold border   Workaround
  Green border  Delight signal
  Blue border   Need / goal

The two layers work together. The cell background sets the emotional register
for the whole stage. The card border classifies each individual finding within
it. When they diverge -- for example a green-bordered Delight signal inside a
yellow Friction cell -- it surfaces something that is working well within an
otherwise frustrating stage.


DESIGN SYSTEM
-------------
Built using the VA.gov Design System color tokens and typography.
Color tokens sourced from design.va.gov/foundation/color-palette.
Typography: Bitter (page title), Source Sans 3 (body), Roboto Mono (labels).
All styles are embedded in the HTML file.


MODIFYING THE FILE
------------------
All content is plain HTML. Find and replace works for text edits.

CSS variables are defined in the :root block at the top of the style tag.
Color changes should be made there.

Do not change text colors without verifying contrast ratios against their
background. Refer to ACCESSIBILITY_STATEMENT.txt for all verified color pairs.

Column widths are controlled by --col-label and --col-stage CSS variables.

Adding a stage requires a new column in the grid and a corresponding entry
in every swimlane row.


RESEARCH CONTEXT
----------------
  Study type     Qualitative contextual inquiry
  Participants   VISN-level capital planners
  Saturation     Theoretical saturation reached
  Organization   VA Financial Services Center



