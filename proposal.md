# 1000 ICP-Qualified Companies Proposal

## Objective

If selected for the internship, my goal would be to build a verified list of 1000 ICP-qualified companies within one month. The list should not be a bulk dump of company names. Each company should have evidence-backed qualification based on DeepThought’s Federer ICP.

## Target ICP

The target companies would be:

* Indian manufacturing or deep-tech product companies
* Rs.50Cr to Rs.500Cr revenue where possible
* Promoter-led or founder-led
* Differentiated products or specialized technical capability
* Active growth signals
* Some evidence of operational systems or structured execution
* Sectors such as aerospace, defence electronics, specialty chemicals, industrial IoT, precision engineering, biotech, medical devices, and specialty manufacturing

## Sourcing Methods

### 1. DSIR Recognized R&D Units

DSIR-recognized companies are useful because they already show investment in in-house R&D. This is a strong signal for differentiation and technical seriousness.

Limitation: The list may include old companies, large companies, and companies outside the ICP revenue range.

### 2. Industry Expo Exhibitor Lists

I would use exhibitor lists from events such as Aero India, BioAsia, CPHI India, IMTEX, ELECRAMA, Automation Expo, and manufacturing trade fairs.

These companies are useful because exhibitors are usually growth-oriented and actively looking for customers, partners, or markets.

Limitation: Expo lists may miss smaller high-quality companies that do not spend on exhibitions.

### 3. BSE SME and NSE Emerge

Listed SME manufacturing companies are useful because annual reports make revenue, leadership, products, and growth signals easier to verify.

Limitation: This source misses private promoter-led companies.

### 4. MCA and Tofler/Zauba

MCA data can help identify companies by NIC code, directors, incorporation date, registered location, and ownership structure.

Limitation: MCA data is noisy and does not directly prove manufacturing capability or systems maturity.

### 5. LinkedIn Sales Navigator

LinkedIn can be used to find founders, MDs, CXOs, plant heads, R&D heads, and operations leaders in target sectors.

Limitation: LinkedIn data may be incomplete or self-reported.

### 6. Government and Regulatory Lists

I would use USFDA, WHO-GMP, CDSCO, AS9100, ISO, Startup India, DPIIT, and export promotion council lists.

These sources help verify whether a company has real regulatory, quality, or manufacturing depth.

Limitation: Regulatory lists are sector-specific and may overrepresent pharma, chemicals, or defence.

### 7. Industrial Area and Cluster Mapping

I would map companies from industrial clusters such as Genome Valley, Jeedimetla, Patancheru, Aerospace Park, Hardware Park, MIDC Pune, GIDC Gujarat, and Coimbatore industrial clusters.

This works because many strong MSME manufacturers are not easy to find through generic Google searches.

Limitation: Cluster data needs manual cleaning.

## 1000 Company Funnel

The process would follow this funnel:

Raw universe: 3500-4000 companies
↓
Hard filters: remove traders, distributors, pure service firms, very large companies, inactive companies
↓
Screened pool: 2000-2500 companies
↓
AI-assisted scoring: apply Federer criteria
↓
First-pass qualified: 1200-1400 companies
↓
Manual quality check: verify borderline and high-value companies
↓
Final list: 1000 ICP-qualified companies

## Automation Plan

I would automate the first-pass research using:

* Python scraping
* Playwright or BeautifulSoup for company websites
* LinkedIn and directory exports where allowed
* AI-assisted extraction of products, founders, certifications, and growth signals
* Spreadsheet scoring templates
* Manual QA for final verification

## Quality Control

To maintain quality, I would use three layers of checking:

### Layer 1: Auto-disqualification

Remove companies that are:

* Traders
* Distributors
* Pure service companies
* Generic software companies
* Too large
* PE-controlled or acquired
* Companies with no website or no visible activity

### Layer 2: AI-assisted scoring

Use AI to extract and score:

* Products
* Differentiation
* Leadership background
* Growth signals
* Systems maturity
* Revenue band if available

### Layer 3: Manual verification

Manually verify:

* Top 100 priority companies
* All borderline companies
* Any company where AI confidence is low
* Companies with unclear revenue or ownership

## Four-Week Plan

### Week 1: Build the Universe

Collect 3500-4000 companies from DSIR lists, expo directories, LinkedIn, BSE SME, MCA, regulatory lists, and industrial clusters.

Expected output: 3500-4000 raw companies.

### Week 2: Clean and Score

Remove obvious non-fits and run AI-assisted first-pass scoring.

Expected output: 2000-2500 screened companies and 1200-1400 first-pass qualified companies.

### Week 3: Manual QA

Review borderline cases and verify important evidence manually.

Expected output: 1000-1100 verified companies.

### Week 4: Final Packaging

Prepare final CSV, priority outreach list, methodology document, source breakdown, and personalization hooks.

Expected output: 1000 ICP-qualified companies and top 200 priority targets.

## Expected Yield

Based on the assignment guidance, I would expect around 30% yield. To get 1000 final companies, I would start with 3500-4000 raw companies.

## Final Deliverables

The final output would include:

* Master CSV of 1000 ICP-qualified companies
* Priority 200 outreach-ready companies
* Methodology document
* Source-wise breakdown
* Scoring notes
* Scripts or prompts used for research automation
