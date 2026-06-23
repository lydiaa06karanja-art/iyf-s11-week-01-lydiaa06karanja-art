# Accessibility Audit Report - IYF Website

**Website:** https://vigilant-space-waffle-r74w666qqpwfp7gx.github.dev/
**Audit Date:** June 22, 2026
**Tool Used:** WAVE Web Accessibility Evaluation Tool
**Auditor:** Regina Gathoni

## Executive Summary
This report documents accessibility issues found on the IYF website using WAVE. The scan identified 1 error and 1 alert that need improvement to meet WCAG 2.1 AA standards.

## Issues Found
| Issue Type | Severity | Count | Description |
| --- | --- | --- | --- |
| Errors | High | 1 | Missing form label on input field |
| Contrast Errors | Medium | 0 | All text meets 4.5:1 contrast ratio |
| Alerts | Low | 1 | Skipped heading level - H1 to H3 jump |

## Screenshot Evidence
![WAVE Scan Results](./wave-screenshot.png)
*WAVE scan showing 1 error, 0 contrast errors, and 1 alert. AIM Score: 9.7/10*

## Recommendations
1. **Add form label** - Connect the input field to a `<label>` tag so screen readers can identify it
2. **Fix heading structure** - Change H3 to H2 to maintain proper heading hierarchy H1 → H2 → H3
3. **Keep good contrast** - Current colors pass WCAG 2.1 AA standards, maintain this

## Conclusion
The website has minor accessibility barriers. The missing form label is the critical fix for screen reader users. The heading structure is easy to correct. Overall AIM Score of 9.7/10 shows the site is mostly accessible.

---
*Report generated for IYF S11 Week 1 - Task 2.3*
