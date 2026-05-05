# Manufacturing White Paper Backlog

This document is the backlog for the research project. The canonical reader-facing draft is [Manufacturing Policy for India](./white-paper.md). The current [Industrial Base Math](./industrial-base-math.md) file is a working note; [Literature Review](./literature-review.md) and [Annotated Bibliography](./bibliography.md) are appendices.

The target is a paper with enough structure that economists, industrial-policy practitioners, and state officials can argue with the assumptions instead of dismissing the piece as rhetoric.

## 1. Core Thesis to Prove

The paper proves a narrower claim than "manufacturing matters":

India needs a low-discretion, rule-based manufacturing-capacity policy built around zero tax for qualifying new manufacturing profits, factory-time metrics, export discipline, and state-level competition, because manufacturing generates learning spillovers and strategic-capacity externalities that private firms cannot fully capture.

The burden of proof:

- show that manufacturing has positive learning and capability externalities
- show that India has specific manufacturing misallocation and premature-deindustrialization constraints
- show that a rule-based instrument is better matched to Indian state capacity than discretionary winner-picking
- show that the proposal differs from failed SEZ-style rent extraction
- show which sectors deserve broad zero-tax treatment and which deserve additional strategic-capacity premia

## 2. Paper Architecture

### A. Executive Doctrine

Move the five-line doctrine to the front, not the end:

- small state for daily life
- strong state for industrial capacity
- free markets on national infrastructure
- zero tax for qualifying new manufacturing capacity
- factory-time as the ease-of-doing-business metric

This section stays short. The rest of the paper derives it.

### B. Welfare-Theoretic Foundation

Engage Greenwald-Stiglitz. The manufacturing exception must be framed as a learning-externality argument, not a preference for factories.

Required move:

```text
Private return = current-period profit
Social return = current-period profit + learning spillovers + supplier capability accumulation + strategic option value
```

The optimal policy wedge derives from learning-curve elasticity, spillover coefficient, time horizon, and social discount rate. The current `v / (m x tau)` ratio belongs only as a static corner case of a dynamic optimum.

### C. Dynamic Capability Model

Build a two-stock model:

```text
K_t = physical capital stock
H_t = capability stock
```

Capability evolves with production volume, process learning, supplier density, and labor formation:

```text
H_{t+1} = H_t + phi(Q_t, supplier_density_t, export_discipline_t) - depreciation
```

The model simulates 10-year and 20-year cumulative value added under three regimes:

- baseline PLI-only
- zero-tax broad manufacturing
- zero-tax plus strategic-capacity premia

Outputs:

- cumulative domestic value added
- employment
- fiscal cost
- export share
- capability stock

### D. India in the Product Space

Use the economic-complexity / product-space literature to answer what India should plausibly make next.

Required comparisons:

- India versus Vietnam, China, and Bangladesh on ECI trajectory
- density to unoccupied products
- sectors within reach versus aspirational sectors
- risk of a one-product trap

This grounds the 100,000-manufacturer target in product-space geometry rather than generic industrial ambition.

### E. Misallocation and the Missing Middle

Use Hsieh-Klenow as the anchor. Treat the missing middle as a misallocation problem, not a descriptive complaint.

Required empirical work:

- reproduce the size-distribution distortion argument using ASI where possible
- show productivity dispersion within comparable manufacturing categories
- connect size-dependent distortions to labor law thresholds, finance access, and compliance burdens
- estimate the manufacturing TFP gain from reducing distortions

### F. Premature Deindustrialization

Use Rodrik's frame. Compare India's manufacturing employment and value-added shares against Korea, Taiwan, Malaysia, China, Vietnam, and Bangladesh at comparable income levels.

The point:

India's urgency is demographic and industrial. Manufacturing-led development peaks earlier and lower for late industrializers, which makes the window narrower than the old East Asian path suggests.

### G. Comparative Case Studies

Required cases:

- Korea HCI, 1973-1979: learning persistence after policy ended
- Taiwan ITRI / TSMC: public research to industrial flagship
- Vietnam, 2000-2020: FDI-led labor-cost arbitrage and export discipline
- Bangladesh garments: labor-intensive success, quota history, and one-product trap
- China Made in China 2025 / dual circulation: adversary-scale state-firm bargain

These cases identify mechanisms India can copy and mechanisms India cannot copy.

### H. Sectoral Institutional Chapters

Manufacturing is many policy problems grouped under one word. The paper needs sector chapters with different policy logics.

Required sectors:

- Semiconductors: design, fab, ATMP, mature nodes, Dholera/Tata-PSMC, Vedanta-Foxconn failure
- Pharma APIs: China dependence, molecule-level PLI, bulk-drug parks, quality/regulatory issues
- Electronics assembly: Foxconn Sriperumbudur, Tata Electronics, SMT lines, component ecosystem gap
- Textiles and apparel: Tiruppur, Bangladesh competition, MMF transition, size-cap lock-in
- Steel and auto: Bharat Forge, Tata/JLR, Maruti, CBAM, EV transition

Each chapter needs named institutions, binding constraints, policy instruments, and measurable targets, but the structure follows the sector rather than a common template.

### I. Political Economy and State Capability

The capture objection needs a real apparatus. Use Mushtaq Khan's productive-rent framework, Pritchett/Andrews/Woolcock on capability traps, Pritchett-Sandefur on India's flailing state, and Kelkar-Shah on Indian state capacity.

The question:

What institutional design turns manufacturing rents into capability accumulation instead of rent dissipation?

Required design answers:

- low-discretion eligibility
- automatic sunset
- export discipline
- audited domestic value addition
- payroll/formality condition
- public dashboard
- independent audit
- clear exit for non-performance

### J. Federal Architecture

Manufacturing execution is heavily state-mediated. The paper needs a federalism chapter.

Required comparisons:

- Tamil Nadu
- Gujarat
- Maharashtra
- Karnataka
- Telangana
- Uttar Pradesh

Policy design:

- race-to-the-top manufacturing dashboard
- avoid race-to-the-bottom fiscal concessions
- Manufacturing Council modeled partly on GST Council logic
- coordination on land, power tariffs, labor-code rollout, logistics corridors

### K. Strategic-Capacity Real Options

Strategic capacity is modeled as a real option under geopolitical volatility.

Candidate sectors:

- pharma APIs
- rare earths
- mature-node semiconductors
- drones
- telecom/RAN
- grid and battery components

Output:

Layered policy design:

- broad zero-tax treatment for qualifying manufacturing
- additional strategic-capacity premium for narrow categories where option value is high

### L. Five Institutional Bottlenecks

Separate chapters replace abstract mentions of "logistics" and "delay":

- Energy: industrial power cross-subsidy, DISCOM fiscal stress, open access
- Logistics: National Logistics Policy, Gati Shakti, DFCs, port dwell time
- Land: LARR 2013, industrial land banks, title, zoning, FSI/FAR
- Labor: labor codes, state rules, threshold effects, formal payroll
- Capital: MSME credit gap, TReDS, supply-chain finance, working capital

Each chapter maps reforms to named statutes, schemes, or institutions.

### M. Objections Chapter

A serious paper steelmans the strongest objections.

Required objections:

- Bhagwati/Panagariya: broad liberalization beats industrial policy
- Krueger/public choice: rents dominate learning
- Kelkar/Shah: the Indian state lacks execution bandwidth
- Pritchett: basics-first before industrial ambition

The zero-tax proposal is defended as a low-discretion instrument that needs audit and registration capacity, not winner-picking capacity.

## 3. Bibliography to Work Through

### Theory and Formal Models

- Greenwald and Stiglitz, "Helping Infant Economies Grow," AER Papers and Proceedings, 2006.
- Greenwald and Stiglitz, *Creating a Learning Society*, 2014.
- Aghion, Cai, Dewatripont, Du, Harrison, and Legros, "Industrial Policy and Competition," AEJ: Macroeconomics, 2015.
- Liu, "Industrial Policies in Production Networks," QJE, 2019.
- Itskhoki and Moll, "Optimal Development Policies with Financial Frictions," Econometrica, 2019.
- Acemoglu on directed technical change.
- Mazzucato on mission-oriented innovation.

### Recent Industrial-Policy Empirics

- Lane, "Manufacturing Revolutions: Industrial Policy and Industrialization in South Korea," QJE, 2022.
- Juhasz, "Temporary Protection and Technology Adoption: Evidence from the Napoleonic Blockade," AER, 2018.
- Juhasz, Lane, and Rodrik, "The New Economics of Industrial Policy," Annual Review, 2023.
- Manelici and Pantea, "Industrial Policy at Work," 2023.

### India-Specific Work

- Hsieh and Klenow, "Misallocation and Manufacturing TFP in China and India," QJE, 2009.
- Besley and Burgess, "Can Labor Regulation Hinder Economic Performance? Evidence from India," QJE, 2004.
- Kelkar and Shah, *In Service of the Republic*, 2019.
- Aiyar, Mody, and Subramanian on India's demographic clock.
- RBI U.K. Sinha Committee Report on MSMEs, 2019.

### Comparative and Historical Frameworks

- Studwell, *How Asia Works*, 2013.
- Wade, *Governing the Market*, 1990.
- Amsden, *Asia's Next Giant*, 1989.
- Chang, *Kicking Away the Ladder*, 2002.
- Rodrik, "Premature Deindustrialization," Journal of Economic Growth, 2016.
- Hausmann and Hidalgo et al., *The Atlas of Economic Complexity*, 2014.

### Political Economy and State Capability

- Khan, "Political Settlements and the Governance of Growth-Enhancing Institutions," 2010.
- Pritchett, Woolcock, and Andrews on capability traps.
- Pritchett and Sandefur on India's flailing state.
- North, Wallis, and Weingast, *Violence and Social Orders*, 2009.
- Acemoglu and Robinson, *Why Nations Fail*, 2012.

### Trade Theory

- Corden, "The Structure of a Tariff System and the Effective Protective Rate," JPE, 1966.

## 4. Data Work Required

The current note uses high-level official numbers. A white paper needs reproducible tables.

Minimum datasets:

- DGCI&S bilateral trade by HS code
- ASI plant-level or industry-level data
- PLI scheme sectoral approvals, disbursements, sales, exports, and employment
- state-level industrial land allotment and power-connection data
- port dwell-time and customs-clearance data
- EPFO/ESI payroll data for wage-side fiscal capture
- tariff schedules for effective-rate-of-protection calculations
- sector-level domestic value-addition estimates

## 5. Deliverable Sequence

1. Literature memo: 15-20 pages, with annotated bibliography.
2. Model memo: Greenwald-Stiglitz static rule plus dynamic capability model.
3. India data memo: ECI/product-space, ASI missing middle, trade dependence.
4. Case-study memo: Korea, Taiwan, Vietnam, Bangladesh, China.
5. Sector memo: semis, APIs, electronics, textiles, steel/auto.
6. Political-economy memo: capture, state capacity, federal architecture.
7. Full white paper: 80-120 pages.

The current essay will not be stretched into that paper. It remains the seed thesis.

## 6. Next Full-Prose Chapters

To break template pressure, the next writing pass produces three uneven, evidence-led chapters before expanding the rest of the outline:

1. Hsieh-Klenow and the Indian missing middle, using ASI where possible.
2. Korea HCI, using Lane as the anchor and focusing on persistence after policy withdrawal.
3. State capability and capture, using Kelkar-Shah, Pritchett/Andrews/Woolcock, and Khan.

These three chapters set the style standard: prose first, numbers early, equations only where they do work, and no common chapter mold.
