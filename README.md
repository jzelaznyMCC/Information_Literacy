# Information_Literacy
MCC Information Literacy Assets
# Overview
This repository contains assets used for library instruction by MCC Librarians.
# Guidelines
When using LLMs to assist with coding and content creation we use this prompt:
- Build it as ONE self-contained HTML file: all HTML, CSS, and JavaScript inline. No external libraries, fonts, images, or scripts.
- Privacy: no login, no data collection, and no network requests of any kind (no fetch, no XMLHttpRequest, no submitting forms, no analytics). Never ask for a name, student ID, or email.
- Accessibility (WCAG 2.1 AA): fully keyboard operable with a visible focus outline, semantic HTML with real labels, feedback announced to screen readers with aria-live, contrast of at least 4.5:1, never color alone to carry meaning, alt text on images, and respect reduced-motion settings.
- Responsive: works on a phone and on a laptop, and stays usable at 200% zoom.
- Include a footer with my name, the license, and a line telling students how to report a problem.
- Plain, uncluttered design, with instructions a student can follow without me there.
- LMS compatibility: use ES5 JavaScript only (var and function declarations; no arrow functions, let, const, classes, template literals, async or await), flat global functions with no wrapper functions around the whole script, synchronous DOM updates, and CSS-only animation rather than chained timers.
