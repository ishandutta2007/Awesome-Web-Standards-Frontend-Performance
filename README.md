# Awesome-Web-Standards-Frontend-Performance

# Top Web Standards & Frontend Performance Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Core Web Vitals, Synthetic Speed Testing, Real User Monitoring (RUM), Bundle Optimization & Browser Standards Guidance*  
**Last updated: November 2026**

This repository (`Awesome-Web-Standards-Frontend-Performance`) tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Web Standards & Frontend Performance** — Top Web Standards Frontend Performance (Opensource) 🌟 Star if you like it! 🌟. These tools audit Core Web Vitals (LCP, INP, CLS), automate Lighthouse CI performance budgets, execute synthetic browser benchmarks, monitor real user telemetry, optimize JavaScript/CSS/image payloads, and guide modern web standards adoption.

**Examples** include Lighthouse CI, WebPageTest, Google PageSpeed Insights, SpeedCurve, Calibre, GTmetrix, DebugBear, Treo, Pingdom Tools, Uptrends, and `GoogleChrome/modern-web-guidance` (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted synthetic performance testing, CI/CD performance gates, Core Web Vitals RUM libraries, bundle analyzers, and web standards toolkits — ideal for frontend architects, performance engineers, DevOps teams, and web standards advocates.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Google PageSpeed Insights & CrUX](https://web.dev)**  
  Official Google web performance diagnostic portal combining lab Lighthouse audits with real-world Chrome User Experience Report (CrUX) Core Web Vitals field data.

- **[SpeedCurve](https://speedcurve.com)**  
  Continuous synthetic monitoring and Real User Monitoring (RUM) platform tracking Core Web Vitals, JavaScript CPU flamegraphs, and competitive performance benchmarks.

- **[Calibre](https://calibreapp.com)**  
  Automated web performance monitoring platform offering pull-request performance budgets, Core Web Vitals tracking, and third-party script impact analysis.

- **[DebugBear](https://debugbear.com)**  
  Synthetic website speed testing and Real User Monitoring platform featuring detailed request waterfalls, LCP/INP debugging, and CrUX trend dashboards.

- **[GTmetrix](https://gtmetrix.com)**  
  Cloud website speed testing and performance reporting service powered by Lighthouse metrics, multi-region test servers, and historical waterfall comparisons.

- **[Treo](https://treo.sh)**  
  Cloud Lighthouse CI and Core Web Vitals analytics platform tracking Chrome UX Report trends across millions of domains and pull-request builds.

- **[Pingdom Website Speed Test (SolarWinds)](https://pingdom.com)**  
  Hosted synthetic uptime and page speed testing utility analyzing load times, HTTP response codes, and asset size breakdowns from global locations.

- **[Uptrends Website Speed Test](https://uptrends.com)**  
  Cloud synthetic monitoring and multi-browser speed testing suite measuring Core Web Vitals, waterfall timings, and mobile performance.

- **[Sentry Performance & Web Vitals](https://sentry.io)**  
  Application performance monitoring platform providing Real User Monitoring for LCP, INP, CLS, slow resource spans, and frontend error correlation.

- **[Datadog Real User Monitoring (RUM)](https://datadoghq.com)**  
  Enterprise cloud observability platform tracking frontend Core Web Vitals, synthetic browser tests, and end-to-end API latency.

- **[Vercel Speed Insights](https://vercel.com)**  
  Managed Real User Monitoring service measuring Core Web Vitals across real visitor devices, routes, and network conditions.

## Open-Source GitHub Projects

- **[Modern Web Guidance (GoogleChrome/modern-web-guidance)](https://github.com)**  
  Official Google Chrome open-source guidance and diagnostic framework helping developers adopt modern web standards, Baseline browser APIs, and frontend performance best practices.

- **[Google Lighthouse (GoogleChrome/lighthouse)](https://github.com)**  
  Industry-standard open-source automated auditing tool for improving web page performance, accessibility, progressive web apps, SEO, and modern web standards compliance.

- **[Lighthouse CI (GoogleChrome/lighthouse-ci)](https://github.com-ci)**  
  Open-source suite of CLI tools and self-hosted server for running Lighthouse on every commit, asserting performance budgets, and preventing Core Web Vitals regressions in CI/CD.

- **[Sitespeed.io (sitespeedio/sitespeed.io)](https://github.com)**  
  Complete open-source web performance monitoring suite combining Browsertime, Lighthouse, WebPageTest, and Grafana dashboards for continuous synthetic testing.

- **[Browsertime (sitespeedio/browsertime)](https://github.com)**  
  Open-source Node.js and Docker tool driving real Chrome, Firefox, Edge, and Safari browsers to collect Navigation Timing, Core Web Vitals, and video speed index metrics.

- **[WebPageTest (Catchpoint/WebPageTest)](https://github.com)**  
  Open-source codebase of the premier synthetic web performance testing engine offering multi-step scripting, filmstrip captures, and network throttling.

- **[web-vitals (GoogleChrome/web-vitals)](https://github.com)**  
  Tiny (~2 KB), modular open-source JavaScript library from Google for accurately measuring all Core Web Vitals (LCP, INP, CLS, FCP, TTFB) on real users' browsers.

- **[Unlighthouse (harlan-zw/unlighthouse)](https://github.com)**  
  Fast open-source CLI and web UI that crawls and scans entire websites with Google Lighthouse concurrently in minutes instead of testing single URLs one by one.

- **[Garie (boyney123/garie)](https://github.com)**  
  Open-source Docker-based web performance monitoring system combining Lighthouse, Browsertime, Cron jobs, InfluxDB, and Grafana out of the box.

- **[PerfCascade (micmro/PerfCascade)](https://github.com)**  
  Open-source SVG HAR (HTTP Archive) waterfall viewer and performance analysis component for visualizing network request timings.

- **[Capo.js (rviscomi/capo.js)](https://github.com)**  
  Open-source diagnostic library and browser extension auditing HTML `<head>` element ordering to eliminate render-blocking bottlenecks and accelerate LCP.

- **[Speculation Rules & Quicklink (GoogleChromeLabs/quicklink)](https://github.com)**  
  Lightweight open-source library accelerating subsequent page navigations by prefetching and prerendering in-viewport links during browser idle time.

- **[Partytown (BuilderIO/partytown)](https://github.com)**  
  Open-source lazy-loaded library relocating resource-intensive third-party analytics and marketing scripts off the main thread into a Web Worker to improve INP.

- **[Baseline / web-features (web-platform-dx/web-features)](https://github.com)**  
  W3C WebDX Community Group open-source dataset and tooling defining Baseline browser interoperability across Chrome, Edge, Firefox, and Safari.

- **[MDN Browser Compat Data (mdn/browser-compat-data)](https://github.com)**  
  Official Mozilla open-source machine-readable repository tracking web standards support across every desktop and mobile browser engine.

- **[Webhint (webhintio/hint)](https://github.com)**  
  OpenJS Foundation customizable open-source linting tool auditing websites for accessibility, speed, cross-browser compatibility, PWA standards, and security.

- **[bundlesize & size-limit (ai/size-limit)](https://github.com)**  
  Open-source performance budget tool for JavaScript libraries and web apps that calculates real execution and download time on simulated low-end devices in CI.

- **[Rollup / Webpack Bundle Analyzer (webpack-contrib/webpack-bundle-analyzer)](https://github.com)**  
  Open-source interactive treemap visualizer helping frontend engineers inspect bundle composition and eliminate dead code.

- **[Squoosh & Sharp (lovell/sharp)](https://github.com)**  
  High-performance open-source Node.js image processing library for converting assets into modern AVIF and WebP formats at build or edge runtime.

- **[Critters / Beasties (danielroe/beasties)](https://github.com)**  
  Open-source Webpack/Vite plugin that automatically inlines critical above-the-fold CSS and lazy-loads remaining stylesheets to eliminate render-blocking CSS.

- **[Axe-core (dequelabs/axe-core)](https://github.com)**  
  Industry-standard open-source accessibility testing engine powering Lighthouse's accessibility audits and WCAG web standards compliance checks.

- **[Playwright (microsoft/playwright)](https://github.com)**  
  Open-source cross-browser automation framework widely used to script multi-step user journeys, capture Chrome DevTools traces, and measure INP under CPU throttling.

### Additional Strong Open-Source Options

- **[Yellow Lab Tools (YellowLabTools/YellowLabTools)](https://github.com)** open-source frontend quality and weight analyzer auditing DOM complexity, CSS rules, and web font overhead.
- **[Phantomas (macbre/phantomas)](https://github.com)** open-source headless browser performance metrics collector and monitoring CLI.
