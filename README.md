<p align="center"><img src="logo.svg" width="96" alt="Roto"></p>

# Roto

Aerial data for quarries. We measure stockpile volumes from drone imagery, so a quarry gets weekly inventory numbers instead of a once-a-month surveyor walk-around.

## The problem

A quarry learns its real stockpile volumes once a month, when a mine surveyor spends half a day walking the site with a total station. Everything between those visits is a blind spot. Short-loading and plain theft pile up, and nobody sees it until the next survey. Kazakhstan's construction sector grew 15.9% in 2025, and the quarries feeding that demand still run their yards on monthly numbers.

## How it works

A 249 g drone flies an automated route over the stockyard. Twenty minutes per site. The imagery goes through a photogrammetry pipeline built on open-source WebODM, which produces a 3D model and computes each pile's volume. The client gets a report with deltas against the previous scan, sold as a subscription of 2 scans a month.

We don't replace the licensed mine surveyor. We cover the blind weeks between his official surveys with operational numbers.

The legal part is done up front. The aircraft is under Kazakhstan's 250 g registration threshold and quarries sit outside populated areas, so flights fall into the open category and don't need permits.

## Status

Pre-MVP. Applying to Almaty Hub Incubation (September 14 to December 6, 2026). The plan for the 12 weeks. Validate measurement error on a reference pile against manual survey, run 5 free demo flights across the 28 quarries in the Almaty region catalog, convert 2 of them into paid subscriptions by Demo Day. The failure threshold is set in advance, fewer than 2 paying organizations by November 15 kills the hypothesis and we'll publish the data either way.

Next vertical on the same stack. Construction progress monitoring for Almaty developers, planned for 2027.

## Team

- **Amangeldi Bekaidar**, Founder and CEO. Sales and negotiations, drone pilot on site visits. Full-time.
- **Myrzabay Beknurtas**, Co-founder and CTO. Photogrammetry pipeline and measurement accuracy. Built LocalQuakeAlert (ESP32 seismic detector) solo. Full-time.
- **Bakhtiyar Merey**. Communications, design, customer interviews. Part-time.

Same team behind EcoStep. 1st place at TURAQTY JOL 7.0, LOI from Almaty Metro, invited to TechCrunch Disrupt 2026.

## Contact

Almaty, Kazakhstan - asgalaxytabs2@gmail.com
