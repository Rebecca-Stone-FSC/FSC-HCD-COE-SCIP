SCIP User Journey Map - Accessibility Statement
VA Financial Services Center - User Research Study
====================================================


COMPLIANCE STATUS
-----------------
The SCIP User Journey Map meets or exceeds all applicable federal accessibility
requirements. Built against the VA.gov Design System and verified through
automated structural audit and manual contrast verification.

  WCAG 2.1 Level AA        Minimum standard. Met and exceeded on all criteria.
  WCAG 2.1 Level AAA       Achieved on all text/background color pairs.
  Section 508              Compliant. Meets 36 CFR Part 1194, Subpart B.

Audit result: 0 failures, 0 warnings.


COLOR CONTRAST - VERIFIED PAIRS
--------------------------------
All pairs verified using WCAG 2.1 relative luminance formula. All achieve AAA.

  Element                            Foreground   Background   Ratio    Level
  -----------------------------------------------------------------------------
 - Page title (H1) on header         #ffffff      #162e51      13.60:1  AAA
 - Eyebrow / labels on header        #d9e8f6      #162e51      10.90:1  AAA
 - Section banner labels             #d9e8f6      #1a4480       7.71:1  AAA
 - Cell body text on white           #1b1b1b      #ffffff      17.22:1  AAA
 - Cell body text on gray-pale       #1b1b1b      #f0f0f0      15.11:1  AAA
 - Text on delight / green bg        #1b1b1b      #ecf3ec      15.25:1  AAA
 - Text on friction / gold bg        #1b1b1b      #faf3d1      15.42:1  AAA
 - Text on pain / red bg             #1b1b1b      #f4e3db      13.83:1  AAA
 - Text on critical / pink bg        #1b1b1b      #f8dfe2      13.65:1  AAA
 - Opportunity text on cyan bg       #1b1b1b      #e7f6f8      15.59:1  AAA
 - Opportunity label on dark teal    #ffffff      #244e5e       9.03:1  AAA
 - Footer copy on navy               #dfe1e2      #162e51      10.37:1  AAA
 - Focus ring on dark backgrounds    #face00      #162e51       9.00:1  AAA
 - Legend label on dark strip        #d4b86a      #10223c       8.25:1  AAA


STRUCTURAL ACCESSIBILITY
------------------------

Semantic Structure
  - lang=en attribute present on the html element
  - Descriptive title element identifying the document
  - Single h1 at the top of the page; valid heading hierarchy, no skipped levels
  - Semantic landmarks: header role=banner, main id=main-content,
    footer role=contentinfo

Keyboard Accessibility
  - Skip link at the top of the page linking to main-content
    Meets WCAG 2.4.1 (Bypass Blocks)
  - Skip link becomes visible on keyboard focus
  - Horizontal scroll region is keyboard focusable via tabindex=0 with
    role=region and a descriptive aria-label
  - No positive tabindex values; natural DOM order preserved; no keyboard traps

Focus Indicator
  - Custom focus style applied via :focus-visible on all interactive elements
  - Focus ring: 3px solid #face00 (VA focus yellow) with 3px offset
  - Focus ring contrast: 9.00:1 - exceeds WCAG 2.4.11 AAA requirement of 3:1

Screen Reader Support
  - All decorative emoji marked aria-hidden=true with adjacent sr-only text
    providing the semantic equivalent for screen readers
  - Legend color swatches marked aria-hidden=true; color meaning is also
    conveyed through visible text labels, meeting WCAG 1.4.1 (Use of Color)
  - Scrollable map region has a descriptive aria-label
  - Footer statistics use aria-label with full readable text; visual numbers
    are aria-hidden=true
  - Column headers use role=columnheader

Color Independence
  - Color is never the sole means of conveying information; all color-coded
    states (Delight, Friction, Pain, etc.) are also labeled in text
  - Signal type borders are supplemented by text labels and icon characters
  - Meets WCAG 1.4.1 (Use of Color)


TYPOGRAPHY
----------
  - All fonts from the VA.gov Design System: Source Sans 3, Bitter, Roboto Mono
  - Base font size: 16px; primary content text minimum 13px
  - Line height: 1.55 minimum throughout - meets WCAG 1.4.12 (Text Spacing)
  - No text is rendered as images


STANDARDS REFERENCED
--------------------
  - Web Content Accessibility Guidelines (WCAG) 2.1 - W3C Recommendation
  - Section 508 of the Rehabilitation Act of 1973, as amended (29 U.S.C. 794d)
  - 36 CFR Part 1194 - Information and Communication Technology Standards
  - VA.gov Design System - design.va.gov


CONTRAST METHODOLOGY
--------------------
All contrast ratios were calculated using the WCAG 2.1 relative luminance
formula as specified in Success Criterion 1.4.3. Calculations were performed
programmatically against exact hex values from VA.gov Design System color token
definitions. Every text/background pair in this document meets or exceeds the
7:1 AAA threshold.


KNOWN LIMITATIONS
-----------------
The map is optimized for desktop viewports of 1280px or wider. Horizontal
scrolling is required on narrower screens. This is a constraint of the journey
map format, not an accessibility failure. The scroll region is keyboard
accessible and properly labeled.
