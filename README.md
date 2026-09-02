# Telangana Portal - Accessibility Audit & Architecture

## Project Overview
Baseline accessibility audit for telangana.gov.in (Lighthouse Score: 84/100) + Monorepo skeleton for accessible rebuild as per RabTech Task 02.

## Architecture Boundaries
- **client/**: Frontend only - React, no direct DB access, WCAG 2.2 AA compliant components (contrast 4.5:1, keyboard focus)
- **server/**: Backend only - Node.js API, validation, security
- **docs/**: Audit reports + Lighthouse & Console screenshots as evidence
- **tests/**: Automated a11y tests using axe-core & Lighthouse CI

## Local Setup
git clone https://github.com/shivanipolasa71-coder/telangana-a11y-audits.git
cd client && npm install && npm run dev
cd ../server && npm install && npm run dev

## First Vertical Slice
Feature: Accessible Header with Skip-to-Content link, visible keyboard focus outline, high contrast toggle, screen reader support.

## Audit Evidence
- 5 Issues found: Contrast, Link Name, 404, Keyboard Focus, Alt Text
- Details in docs/audit-report.md
- Lighthouse: 84/100
