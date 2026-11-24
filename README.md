# Core Web Vitals and Page Speed Performance Auditor

[![Core Web Vitals Auditor](https://img.shields.io/badge/TAVARDT-Core%20Web%20Vitals-5b3cf5.svg)](https://tools.tavardt.com/nz/core-web-vitals-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audits latency TTFB, edge delivery, render-blocking scripts, and Cumulative Layout Shift stability in New Zealand.

Developed and maintained by the digital systems performance division of **TAVARDT**.

***

## Core Web Vitals Audit Capabilities

* **Server Response and TTFB Analysis**: Precise measurement of initial Time to First Byte latency and New Zealand network edge routing.
* **Render-Blocking Resource Inspection**: Detection of synchronous CSS stylesheets and JavaScript assets delaying initial rendering.
* **Visual Stability Audit (CLS)**: Verification of explicit image dimensions and lazy loading implementations to eliminate layout shifts.
* **HTTP Compression Verification**: Audits Brotli and Gzip payload compression configuration.
* **W3C Performance Health Score**: Quantitative 0 to 100 performance score with prioritized remediation guidance.

***

## Installation and Execution

Requires Python 3.8 or higher.

```bash
git clone https://github.com/TAVARDT-New-Zealand/core-web-vitals-tester-nz.git
cd core-web-vitals-tester-nz
python cwv_tester.py https://company.co.nz
```

To output results in structured JSON format:

```bash
python cwv_tester.py https://company.co.nz -json
```

***

## Comprehensive Web Diagnostic

For full web performance audits and real-world loading simulations:

* **Official Core Web Vitals Checker Tool**
* **TAVARDT Enterprise Portal**

***

## Web Performance and Speed Optimization Advisory

For New Zealand digital assets aligning with W3C Standards and NZ Digital Performance Architecture, contact the specialists at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/nz/
* **Diagnostic Suite:** https://tools.tavardt.com/nz/
* **Technical Contact:** https://ag.tavardt.com/nz/contact/

***

© 2026 TAVARDT. All rights reserved.
