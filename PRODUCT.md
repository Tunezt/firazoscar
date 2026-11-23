# Product

<!-- impeccable:product-schema 1 -->

Written 2026-11-23 by a dispatched worker from the coordinator's brief and the resume PDF. No interview channel to the owner existed (worker terminal, coordinator relay only), so every fact below comes from the brief, `Firaz_Oscar_Resume.pdf`, or the FYP supervisor update; anything inferred is marked "inferred".

## Platform

web

## Stack

Delegated: plain static HTML + CSS + a few lines of JS, no framework, deployed on Vercel. Chosen because the page is one screen of facts that must be usable in about 1 s on phone 4G; a framework adds build steps and nothing the page needs.

## Users

- Primary: internship recruiters and engineering screeners (Malaysia / SEA, inferred from the Sunway University base) who open the link from an application form, often on a phone, and spend seconds deciding whether to read the CV.
- Secondary: engineers in a later interview round who want to verify the projects (stack, what is live, screenshots).

## Product Purpose

The personal site of Firaz Wianda Faric Oscar, final-year CS student (Sunway University x Lancaster University), replacing his GitHub link in internship applications. Success = a recruiter knows who he is, that he is available from 25 Jan 2027 (min 12 weeks), and can download the CV or contact him within the first screen; then sees shipped work with outcomes.

## Positioning

He ships live production systems for real small businesses and communities, not class demos: a café dashboard + POS live for a working café (daily use not confirmed), a paid membership business he runs (2.92x ROAS, 61 orders), paid Next.js platforms for a 4,000-member Discord community, a barbershop booking system. Outcomes first, stack second.

## Evidence (only these; never invent)

- Resume PDF (repo root) is the source of truth for education, roles, numbers and skills.
- FYP (Poernama): owner dashboard + staff POS live at a working café in Banjarmasin; WhatsApp owner assistant with 15 fixed tools, receipt photo reading, nightly anomaly alerts live on a real WhatsApp line since 23 Nov 2026 16:10 WITA (self-hosted gateway); 780 automated tests (commit a22806d, 23 Nov 2026); fixed tools answered 15/15 test questions correctly vs 2/15 for free text-to-SQL.
- Screenshots: FYP and TemanCukur use demo data, safe to show.
- Do not publish the phone number. TemanCukur live link withheld until redeploy (TODO in config).

## Accessibility

WCAG AA contrast, keyboard reachable, reduced-motion respected, readable without JS.
