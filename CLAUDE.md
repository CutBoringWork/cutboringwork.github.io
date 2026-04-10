# CutBoringWork Marketing Site

Static marketing site for Clara, hosted on GitHub Pages at cutboringwork.com.

## Architecture
- Jekyll-based static site (GitHub Pages builds automatically on push)
- Layout: _layouts/default.html
- Includes: _includes/header.html, _includes/footer.html
- Styles: assets/css/base.css
- Fonts: DM Sans (body) + Fraunces (headings) via Google Fonts

## Pages
- index.html — Homepage (hero, product features, values)
- about.html — Nilesh's personal story ("Why We Built Clara")
- methodology.html — How Clara rates facilities (pin colors, data source, process)
- privacy.html — Privacy policy
- terms.html — Terms of service
- 404.html — Custom 404 page

## Deployment
- Push to master → GitHub Pages auto-deploys
- Git remote: github.com:CutBoringWork/cutboringwork.github.io.git
- CNAME: cutboringwork.com
- Clara app lives at clara.cutboringwork.com (separate repo/server)

## Brand
- Primary color: #1b4d4a (dark teal)
- Background: #fdfcf8 (cream), #f5efe0 (warm)
- Entity: EE LLC / Cut Boring Work
- Contact: howto@cutboringwork.com

## Legal
- AI disclaimer footer on every page (added 2026-03-23)
- Privacy and Terms updated 2026-03-23 to cover voice calls, SMS, AI processing, Stripe, facility portal
- All Clara Chat pages link to these legal pages as canonical source
