Accessibility Checklist
=======================

Scout aims to meet WCAG AA compliance. For more information see [Scout's
Accessibility
Guide](https://www.notion.so/The-Guide-601ce3c8ce8c4fceaa2b109deba69c54)
and [The A11y Project
Checklist](https://www.a11yproject.com/checklist/).

Global Code
-----------

-   [ ] ["lang" attribute in the html tag indicates page
    language](https://webdesign.tutsplus.com/tutorials/use-the-lang-attribute-for-better-accessibility--cms-31961)
-   [ ] sections in a language other than the set language of the page
    have a separate "lang" attribute
-   [ ] [no meta element contains
    "user-scalable=no"](https://accessibilityinsights.io/info-examples/web/meta-viewport/)
-   [ ] [text size is in percentage, ems, or
    rems](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size)
-   [ ] [ARIA landmark elements signify content
    regions](https://fae.disability.illinois.edu/rulesets/LANDMARK_18/)

[Headings](https://www.a11yproject.com/checklist/)
--------------------------------------------------

(Scroll down to "Headings" section of page)

-   [ ] each page has only one H1 element
-   [ ] no heading levels are skipped

[Keyboard](https://accessibility.18f.gov/keyboard/)
---------------------------------------------------

-   [ ] site is keyboard navigable
-   [ ] focus order follows design specs or visual order of page, then
    returns to address bar
-   [ ] all interactive elements have focus states
-   [ ] keyboard focus moves to modal when opened
-   [ ] keyboard focus does not leave modal until it is dismissed
-   [ ] keyboard can be used to dismiss modal
-   [ ] focusing on an element with a hover state with the keyboard
    reveals the hover state

[Images](https://accessibility.psu.edu/images/imageshtml/)
----------------------------------------------------------

-   [ ] img elements have alt attribute, which matches text within image
    if applicable
-   [ ] decorative images have null (\"\") alt attribute value

[Links](https://www.w3.org/TR/WCAG20-TECHS/G201.html)
-----------------------------------------------------

-   [ ] identify links that open in a new tab or window

Accessibility Check
-------------------

-   [ ] run [pa11y](https://pa11y.org/)
