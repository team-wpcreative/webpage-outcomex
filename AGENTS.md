# Agents Documentation

## Project: OutcomeX Penetration Testing Website (pentest-3.html)

### Overview
This is the main penetration testing services landing page for OutcomeX, an Australian cybersecurity company. The page features a dark cyber/hacker aesthetic with neon cyan, purple, and red accents.

---

## Page Sections (in order)

### 1. Navigation (id="navbar")
- Fixed top navigation bar with glass effect
- Logo: "OUTCOMEX" with cyan "X"
- Links: Services, Process, Pricing, Contact
- CTA button: "Get Started"

### 2. Hero Section
- Main headline: "Exploit Before They Do."
- Subheadline: We go beyond surface-level vulnerability scanning to deliver real-world attacker simulation, actionable findings, and prioritised remediation guidance, helping your organisation achieve measurable risk reduction, not just another pen test report.
- CTA buttons: "View Fixed Pricing" and "How It Works"
- Trust bar with partner logos (OffSec, CREST, etc.)

### 3. Live Threat Ticker
- Fixed position scrolling threat feed
- Label: "AU Threat Feed" with pulsing red dot
- Scrolling items showing: CRITICAL, HIGH, MEDIUM, INFO threats
- Continuously animating ticker effect

### 4. ROI Calculator / Stats Section (id="stats-section")
- Section title: "Tailored. Outcome-Driven. Built for Real Security Impact." (gradient text)
- Heading: "The 2025 Imperative"
- 4 stat cards:
  - Breakout Time: 62 Mins
  - Avg. Breach Cost: $4.03M
  - Ransomware Rate: 66%
  - Exploit Window: 24 Hrs
- ROI Calculator:
  - Industry dropdown (Healthcare, Financial, Technology, Energy, Retail, Public Sector)
  - Records at Risk slider (1K to 100K+)
  - Calculated breach cost display

### 5. Why Us Section (id="why-us")
- Heading: "Why Us"
- Left column:
  - "Our penetration testing services will:" with checkmark list
  - "Outcomes. Not Just Reports." (multi-color gradient heading)
  - Framework alignment text (OWASP, ISM)
- Right column:
  - "Commitment to Excellence & Australian Standards"
  - 3 methodology cards: Structured Methodology, Australian Standards Alignment, Peer-Reviewed Deliverables

### 6. Free Attack Surface Report (id="scan")
- Left side:
  - Label: "Request Free Attack Surface Report"
  - Heading: "Is Your Perimeter Already Exposed?"
  - Description about free reconnaissance
  - Form: Domain input, Email input, Submit button
- Right side:
  - Animated scan visualization
  - Vectors Analyzed list (SSL/TLS, Ports, Credentials, DNS)
  - Deliverable Example card (sample report preview)

### 7. Our Penetration Testing Capabilities (id="services")
- Heading: "Our Penetration testing capabilities:"
- 8 service cards in 3-column grid:
  1. Web applications, APIs & Web Services
  2. External & Internal Networks
  3. Operational Technology (OT) Networks
  4. Wireless Infrastructure
  5. Mobile Applications (iOS & Android)
  6. Cloud Environments (Azure, Amazon, Google)
  7. AD / Identity Management
  8. Secure Code Review

### 8. Adversary Mindset / Elite Research (id="mindset-elite")
- Dynamic background with animated nodes
- Heading: "The Adversary Mindset" with gradient
- Elite Research Team section with stats:
  - Zero-Day Discoveries
  - CVEs Registered
  - Custom Exploit Dev
- Terminal-style output display

### 9. Process Section (id="process")
- Heading: "Our Methodology"
- 4-step process visualization:
  1. Discovery & Scoping
  2. Active Assessment
  3. Analysis & Validation
  4. Reporting & Debrief

### 10. Arsenal / Tools Section (id="arsenal")
- Heading: "Industry-Leading Tools"
- Grid of tool logos/badges

### 11. Pricing Section (id="pricing")
- 3 pricing tiers:
  1. **External Security Test** - $6999 ex GST
  2. **Web App Security Test** - $6999 ex GST (Popular badge)
  3. **Internal Security Test** - $6999 ex GST
- Special offer note: "Special Introductory Offer: Fixed-Price Penetration Testing Packages* $6999, ex GST * for new customers only"

### 12. Advanced Offerings Section
- Multi-color gradient heading: "Advanced offerings to extend your penetration testing"
- 6 offering cards:
  1. Remediation
  2. Automated Penetration Testing
  3. Red Teaming
  4. Dark Web Monitoring
  5. Managed Detection & Response (MDR)
  6. Exposure & Patch Management

### 13. Leadership Section
- "Meet the Leaders" heading
- 2 leadership cards with photos and quotes

### 14. Partners Section (id="partners")
- Heading: "Strategic Security Partners"
- Partner logos: CISCO, MICROSOFT, CROWDSTRIKE, PALO ALTO, SPLUNK, TENABLE, FORTINET, ARMIS

### 15. Elite Engineering Team (id="team")
- Heading: "Elite Engineering Team"
- Intro paragraph about certifications
- 4-column grid of certification categories:
  1. Organisational Level (CREST ANZ, ISO 27001, OffSec Partner)
  2. CREST & Offensive Security (CRT, CSPA, CEH, OSCP, OSCE)
  3. Security Leadership & Governance (CISSP, CISM, CCSP)
  4. Defensive Security & Operations (CySA+, ITIL, PMP)

### 16. Testimonials Section
- Heading: "Trusted by the Vigilant"
- 3 testimonial cards with quotes

### 17. FAQ Section
- Accordion-style frequently asked questions
- Topics: Team location, Vuln Scan vs Pen Test, Engagement speed, Business disruption, Compliance frameworks, Retesting, Credentials handling, DevOps integration, Cost factors, Engineer certifications

### 18. Contact Form (id="scan" near footer)
- Heading: "Ready to Secure Your Organisation?"
- Form fields:
  - Full Name * (required)
  - Email Address * (required)
  - Phone (optional)
  - Website (optional)
  - Position / Title (optional)
  - Message (optional textarea)

### 19. Footer
- Logo and company name
- Links: Privacy Policy, SOCI Act Compliance, Terms
- Copyright: "© 2026 OutcomeX. Australian Owned & Operated."

---

## Key Design Elements

### Color Palette
- Primary: `#00F0FF` (Cyber Cyan)
- Secondary: `#BD00FF` (Cyber Purple)
- Accent: `#FF2E2E` (Cyber Red)
- Background: `#050507` (Cyber Dark)
- Surface: `#13151A` (Cyber Gray)

### Animation Classes
- `fade-in-up` - Entrance animation
- `animate-ticker` - Scrolling ticker
- `animate-pulse` - Pulsing elements
- `scan-line` - Scanning effect

### Custom Components
- `hud-card` - Card with cyber styling
- `icon-glow-container` - Icon with glow effect
- `text-glow-cyan` - Text glow effect

---

## Scripts

### Key JavaScript Functions
- `calculateROI()` - ROI calculator functionality
- Scanner animation for threat feed
- Intersection Observer for fade-in animations
- Terminal typewriter effect
- Counter animation for stats

---

## External Dependencies
- Tailwind CSS (CDN)
- Lucide Icons (CDN)
- Google Fonts (Inter, JetBrains Mono)

---

## Notes for Agents
- This file has custom modifications including the Live Threat Ticker
- All form submissions currently use alert() for demo - will need backend integration
- Some sections reference specific team members (Madura Malwatte, Arjun De)
- Images use external URLs from GitHub
