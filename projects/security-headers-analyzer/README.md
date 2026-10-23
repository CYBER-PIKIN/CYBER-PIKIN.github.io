# Security Headers Analyzer

A small, browser-based defensive security tool by Silas Yisa (Cyberpikin). It reviews **pasted HTTP response headers** against a practical baseline, assigns a simple coverage score, and offers remediation guidance.

## Features
- Checks Content-Security-Policy (CSP)
- Checks Strict-Transport-Security (HSTS)
- Checks X-Content-Type-Options
- Checks clickjacking protection via X-Frame-Options or CSP frame-ancestors
- Checks Referrer-Policy and Permissions-Policy
- Adds a simple Cache-Control check for sensitive responses
- Provides a sample input, observations, and remediation suggestions
- Runs entirely in the browser with no dependencies

## Run it
Open `index.html` in a browser, or visit the deployed GitHub Pages project at:

https://cyber-pikin.github.io/projects/security-headers-analyzer/

## Usage
1. Obtain HTTP response headers from a website or lab you are authorized to assess.
2. Paste header lines into the input box.
3. Select **Analyze headers**.
4. Review missing headers and remediation suggestions.

The tool does not send requests to websites and does not test a live target. It evaluates only the text pasted by the user.

## Limitations
This is a learning aid, not a full audit or formal compliance rating. A header may be present but weak or unsuitable for a particular application. CSP and other directives require contextual review, and production changes should be tested for compatibility.

## Skills demonstrated
HTTP security fundamentals, defensive security analysis, JavaScript, input parsing, security-header interpretation, remediation documentation, and static-site deployment.

## Author
**Silas Yisa · Cyberpikin**  
[GitHub](https://github.com/CYBER-PIKIN) · [LinkedIn](https://www.linkedin.com/in/silas-yisa) · [Portfolio](https://cyber-pikin.github.io/)
