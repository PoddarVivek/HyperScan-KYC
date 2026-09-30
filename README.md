# HyperScan KYC: a digital identity verification flow

A mobile KYC flow designed in Figma, with a PRD and a product case study. It gives users real-time feedback on their ID photo so they fix problems before submitting, instead of finding out after a rejection.

![ID capture with quality feedback](screens/Quality%20Feedback.png)

**Interactive prototype:** [Open in Figma](https://www.figma.com/proto/7KticwQEJzCErcR651ctK9/HyperScan-KYC?node-id=1-2&p=f&t=WcS7W942H7PyhpBc-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1)

## The problem

KYC fails for avoidable reasons: poor lighting, glare, a misaligned ID, a weak camera, unclear instructions. Each failure means a retry, a longer session and a higher chance the user gives up.

## The design

| Step | Screen | What it does |
|---|---|---|
| 1 | Welcome | Sets expectations before asking for anything |
| 2 | ID instructions | Lighting, glare, steadiness and framing tips |
| 3 | ID capture | Live guidance on alignment and brightness |
| 4 | Quality feedback | Plain-language prompts such as "Remove glare" or "Hold steady" |
| 5 | Auto-crop preview | Shows the processed image for confirmation |
| 6 | Selfie instructions and capture | Sets up the face match |
| 7 | Success | Confirms completion and next steps |

## Success metrics defined in the PRD

- KYC completion time: the PRD targets a fall from about 6 minutes to under 2. Both figures are planning assumptions, not measurements from a live product.
- Drop-off per screen, tracked as a funnel.
- Retry rate on ID capture.

This is a design exercise, so none of these have been measured. The [experiment approach I use for Park+](https://poddarvivek.github.io/parkplus/) shows how I would test a change like this.

## Contents

- `screens/`: all eight screens as exported from Figma
- `documents/PRD.pdf`: the product requirements document
- `documents/HyperScan KYC – Intelligent Digital Verification Flow (Product Case Study).pdf`: the case study

## Tools

Figma, Notion, funnel analysis.

## Author

Vivek Poddar, B.Tech ECE, NIT Kurukshetra. [Portfolio](https://poddarvivek.github.io/) / [LinkedIn](https://www.linkedin.com/in/vivekpoddar-work)
