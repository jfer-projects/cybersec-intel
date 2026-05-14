# Competitive Landscape Audit
**Phase 3 Prerequisite** (Can run parallel to Phase 2)  
**Timeline:** May 15 - June 15, 2026  
**Owner:** Johnathan (with analyst support starting Phase 3)  
**Purpose:** Map baseline competitive positioning before building dashboards

---

## Overview
Before building interactive competitive dashboards and positioning matrices, establish a baseline understanding of:
- Who are the top competitors per product category?
- What are their key differentiators vs. our solutions?
- How do they position to MSPs/SMBs?
- What are the key leading indicators we should monitor?

This audit will inform:
- Phase 3 Competitive Positioning Matrix dashboard
- Sales battle card content
- Roadmap differentiation decisions
- Ongoing competitive monitoring strategy

---

## Product Categories to Audit

Your portfolio spans 6 categories:

1. **Endpoint Protection (EP)**
   - Purpose-built for MSPs/SMBs
   - Competitors: Sophos, Bitdefender, Kaspersky, ESET, Malwarebytes
   
2. **Endpoint Detection & Response (EDR)**
   - Purpose-built for MSPs/SMBs
   - Competitors: Microsoft Defender for Endpoint, CrowdStrike, Falcon Insight, SentinelOne, Cybereason
   
3. **Managed Detection & Response (MDR)**
   - Managed 24/7 threat detection for MSPs/SMBs
   - Competitors: Arctic Wolf, Rapid7, Secureworks, Trustwave, Cato Networks
   
4. **DNS Protection**
   - DNS-layer threat blocking and monitoring
   - Competitors: Cisco Umbrella, CloudFlare, Quad9, OpenDNS variants
   
5. **Security Awareness Training (SAT)**
   - Phishing simulations and employee training
   - Competitors: KnowBe4, Gremlin, Proofpoint, Mimecast, Verizon DBIR
   
6. **Threat Intelligence (BrightCloud)**
   - Feeds, APIs, threat data for integrations
   - Competitors: CrowdStrike Intelligence, Recorded Future, Anomali, AlienVault

---

## Audit Methodology

### Phase 1: Competitor Identification (May 15-24)

For each product category, identify:

**Primary competitors** (direct, well-funded, actively selling to MSPs/SMBs):
- Market position: Are they growing or shrinking?
- Customer base: Any overlap with our customers?
- Momentum: Recent funding, hiring, partnerships?

**Emerging competitors** (new entrants, niche focus, or growing):
- Are they early-stage or scaling?
- Any unique positioning vs. incumbents?
- Potential threat to our market share?

**Reference:** Use LinkedIn (company growth), Crunchbase (funding), G2 (reviews), industry analyst reports

---

### Phase 2: Positioning Matrix Dimensions (May 25-31)

Create a comparison matrix for each category with these dimensions:

| Dimension | Description | Scale |
|---|---|---|
| **Pricing Model** | SaaS, perpetual, per-device, bundled, freemium | Categorical |
| **Key Strengths** | Top 1-2 differentiators (speed, ease of use, AI, integrations, etc.) | Qualitative |
| **MSP GTM Focus** | How actively are they targeting MSPs? Dedicated channel, rebrand-friendly, pricing incentives? | High / Medium / Low |
| **Bundling Strategy** | Do they bundle with other products? Standalone or part of platform? | Categorical |
| **Recent Moves** | Major product launches, pricing changes, partnerships in last 6-12 months | Qualitative |
| **Market Position** | Leader, challenger, niche player | Categorical |

**Example for EDR:**

| Competitor | Pricing | Key Strengths | MSP Focus | Bundling | Recent Moves | Position |
|---|---|---|---|---|---|---|
| CrowdStrike | Per-device SaaS | Fast detection, API richness, brand | High | Falcon platform | Strong IPO, Falcon bundles | Leader |
| SentinelOne | Per-device SaaS | Cloud-native, autonomous response, AI | High | Singularity platform | Q1 funding, EDR+XSIAM bundle | Challenger |
| Arctic Wolf | Managed service | 24/7 managed detection, ease of use, SMB focus | Very High | All-in-one | Q1 partnership (Microsoft), expanding platform | Challenger |
| Microsoft Defender | Bundled or per-device | Integration with Windows/M365, pricing | Medium | Enterprise platform | Continual feature updates | Leader (Enterprise), Growing (SMB) |

---

### Phase 3: Threat Landscape Baseline (June 1-10)

Document what's currently exploited and how it affects your market:

**By threat type:**
- **Ransomware:** Top variants (LockBit, BlackCat, etc.), target industries, attack vectors
- **Vulnerability exploitation:** Most commonly exploited CVEs in SMB environments
- **APT / Nation-state:** Which groups target SMBs? Which industries?
- **Supply chain attacks:** Recent incidents affecting managed service providers?
- **Insider threat:** Increasing concern among SMBs/MSPs? Regulatory pressure?
- **Zero-days:** Frequency, impact on your customer base

**By geography:**
- North America: Threat distribution
- Europe: GDPR/NIS compliance drivers
- Asia-Pacific: Growing threat landscape

**By customer segment:**
- SMBs (10-100 users)
- Managed service providers (serving multiple SMBs)
- Regulated industries (healthcare, finance, education)

**Output:** `THREAT_LANDSCAPE_BASELINE.md` (2-3 pages, includes charts)

---

### Phase 4: Leading Indicators to Monitor (June 10-15)

For each competitor, identify signals we should track:

**Funding & Growth:**
- Series A/B/C rounds (indicates momentum)
- Secondary market trades (valuations)
- Revenue growth announcements

**Hiring:**
- Job postings (indicate product development focus: AI/ML, managed services, etc.)
- Leadership changes (new Chief Product Officer = product direction shift)
- Expansion to new geographies

**Product Development:**
- Feature announcements (new products, integrations, AI capabilities)
- Patent filings (indicate R&D direction)
- Customer advisory board announcements (gauges customer influence on roadmap)

**Partnerships:**
- Cloud integrations (AWS, Azure, Google Cloud)
- Ecosystem partnerships (security vendors, SIEM)
- OEM/reseller agreements

**Marketing & Positioning:**
- Analyst relations (Gartner, Forrester reviews)
- Conference presence (keynotes, sponsored tracks)
- Customer wins announced

**Example tracking spreadsheet:**

| Competitor | Signal Type | What to Monitor | Frequency | Purpose |
|---|---|---|---|---|
| CrowdStrike | Hiring | Job openings on LinkedIn; focus on AI/ML engineers | Weekly | Indicates product direction |
| SentinelOne | Funding | Crunchbase, SEC filings, press releases | Monthly | Competitive threat assessment |
| Arctic Wolf | Partnerships | Press releases, analyst reports | Bi-weekly | Market consolidation risk |
| Bitdefender | Product | G2 reviews, feature announcements | Monthly | Gap analysis vs. our EP |

---

## Deliverables

### 1. Competitive Positioning Matrix (Interactive)
**Format:** HTML or Spreadsheet (embedded in hub)  
**Content:** Rows = Product categories, Columns = Competitors, Cells = Comparison dimensions  
**Update frequency:** Quarterly

**Output file:** `COMPETITIVE_POSITIONING_MATRIX.html` or `.xlsx`

### 2. Threat Landscape Baseline Report
**Format:** Markdown + visual charts  
**Content:** Threat types, affected customer segments, historical trends, industry impact  
**Update frequency:** Quarterly

**Output file:** `THREAT_LANDSCAPE_BASELINE.md`

### 3. Competitive Intelligence Monitoring Strategy
**Format:** Markdown  
**Content:** List of leading indicators per competitor, monitoring sources, update frequency, escalation criteria  
**Update frequency:** As-needed (when new competitors emerge or monitoring sources change)

**Output file:** `COMPETITIVE_MONITORING_STRATEGY.md`

---

## Audit Timeline (Detailed)

| Week | Task | Owner | Deliverable |
|---|---|---|---|
| May 15-24 | Competitor identification & profile creation | Johnathan | Competitor profiles (1-2 pages each) |
| May 25-31 | Build positioning matrix | Johnathan | `COMPETITIVE_POSITIONING_MATRIX.html` |
| Jun 1-10 | Threat landscape baseline research | Johnathan + Analyst | `THREAT_LANDSCAPE_BASELINE.md` |
| Jun 10-15 | Define monitoring strategy & leading indicators | Johnathan + Analyst | `COMPETITIVE_MONITORING_STRATEGY.md` |
| Jun 15 | Review with executive sponsor | Johnathan | Feedback incorporated, audit complete |

---

## Research Sources

### Primary Sources
- **Competitor websites:** Product pages, pricing, case studies, customer testimonials
- **LinkedIn:** Company info, employee headcount, recent hires, job postings
- **G2/Capterra:** Customer reviews, feature comparisons, recent moves
- **SEC filings:** For public competitors (if any)
- **Press releases & announcements:** Via company websites, TechCrunch, SecurityWeek

### Secondary Sources
- **Analyst reports:** Gartner Magic Quadrant (if available), Forrester Wave, IDC
- **Industry publications:** Dark Reading, BleepingComputer, SecurityWeek, CyberSecurityToday
- **GitHub & Product updates:** Feature releases, public roadmaps
- **Customer interviews:** Ask sales/support: "What features do customers wish we had? How do competitors compare?"

### Specialized Sources
- **Patent databases:** Google Patents, USPTO (indicates R&D direction)
- **Crunchbase:** Funding rounds, company metrics, employee count growth
- **Threat intelligence:** CrowdStrike reports, Malwarebytes labs, vendor advisories

---

## Success Criteria

- ✅ Competitive positioning matrix complete for all 6 product categories
- ✅ 5-7 competitors identified per category (with brief profiles)
- ✅ Threat landscape baseline documented with top 10 threats by impact
- ✅ Leading indicator tracking strategy defined (sources, frequency, escalation)
- ✅ Executive sponsor reviews and approves baseline
- ✅ Monitoring strategy is feasible with current team capacity

---

## Risks & Mitigations

| Risk | Impact | Mitigation |
|---|---|---|
| **Incomplete competitor data** | Dashboards lack context | Use multiple sources; note data confidence levels ("Well-documented" vs. "Emerging"); flag gaps |
| **Rapid market changes** | Baseline becomes stale | Establish quarterly review process; flag as living document, not snapshot |
| **Too many competitors to track** | Analysis paralysis; unfocused monitoring | Prioritize by market impact (only track top 5-7 per category); revisit annually |
| **Threat landscape too broad** | Cannot rank by importance | Focus on threats impacting SMB/MSP customers; align with portfolio capabilities |

---

## Handoff to Phase 3

Once complete (June 15):
- **Positioning matrix** becomes the visual basis for Phase 3 dashboard
- **Threat baseline** becomes the starting point for threat trend analysis
- **Monitoring strategy** becomes the ongoing intel collection plan

Phase 3 will automate the update process (weekly/bi-weekly refreshes) and add trend visualization.

---

**Next Step:** Kick off competitor identification (May 15), run in parallel with stakeholder interviews.
