# The Industrial Base Math

> Status: working note. This is not yet a research-grade industrial-policy white paper. It states the core arithmetic and policy intuition. The literature, formal model, comparative cases, political-economy apparatus, and sectoral chapters required for a full paper are specified in [Manufacturing White Paper Research Program](./research-program.md).

This is the quantitative case for treating manufacturing as the major exception to a normally libertarian, conservative, market-first state.

The argument is not that the state should run factories. That was the License Raj error. The argument is that manufacturing depends on a physical operating environment the state already controls: land, power, logistics, and courts. A state can make that environment predictable, or it can make every producer pay a hidden tax before the first shipment leaves the factory.

## 1. Imports, Value Added, and the China Deficit

Start with the national income identity: `Y = C + I + G + X - M`. For manufacturing, the issue is not the accounting identity alone. The issue is whether Indian demand turns into Indian production capacity or foreign production capacity.

If a product is imported instead of produced domestically, the consumer still gets the product. What India does not get is the domestic value added, the wage pool, the supplier base, the process learning, and the option to produce the same good in a crisis.

India's merchandise trade with China in FY 2024-25 was approximately:

```text
Exports to China:    $14.25B
Imports from China: $113.45B
Deficit:             $99.20B
```

That gap is not only a trade statistic. It is an annual measure of industrial capacity accumulating elsewhere.

Let `D_CN` be the annual goods deficit with China, `r` the share that can be competitively localized over time, `v` the domestic value-added ratio, `m` the manufacturer profit margin, and `tau` the profit tax rate. The domestic value created by localization is `D_CN x r x v`. The corporate tax foregone under a zero-tax manufacturing policy is `D_CN x r x m x tau`.

The useful ratio is:

```text
Domestic VA created / Tax foregone
= (D_CN x r x v) / (D_CN x r x m x tau)
= v / (m x tau)
```

With `v = 40%`, `m = 10%`, and `tau = 25%`, the ratio is `0.40 / (0.10 x 0.25) = 16`. Every $1 of corporate tax foregone corresponds to $16 of domestic value added under those assumptions. If the comparison is the 15% concessional rate available to qualifying new manufacturing companies under Section 115BAB, the ratio rises to about 26.7.

The size of the localization program cancels out. What matters is value addition, margin, and tax rate.

## 2. Zero Tax Sensitivity

The earlier version used a localization table where every row repeated the same 16.0x ratio. That table was false rigor. The ratio only changes when value addition, margin, or tax rate changes.

| Domestic Value Added | Profit Margin | Tax Rate | VA / Tax Foregone |
|---------------------:|--------------:|---------:|------------------:|
| 30% | 8% | 15% | 25.0x |
| 30% | 10% | 25% | 12.0x |
| 40% | 10% | 25% | 16.0x |
| 50% | 10% | 25% | 20.0x |
| 50% | 12% | 25% | 16.7x |

This makes the policy test explicit. A zero-tax regime is strongest where domestic value addition is high and margins are not artificially inflated through transfer pricing or protected pricing. It is weakest where firms merely assemble imported kits with low value addition while claiming tax benefits.

That is why eligibility cannot be based on incorporation alone. It must require audited production, payroll, domestic value addition, and reinvestment.

## 3. PLI Versus Zero Tax

PLI is useful because it admits the core point: manufacturing needs active policy support. But its structure is selective. The state chooses sectors, firms apply, eligibility is verified, and incentives are paid against qualifying production.

Zero tax has a different mechanism. If a manufacturer earns profit on eligible production, the tax benefit is `tau x profit`, or `tau x m x sales`. At a 10% margin and 15% tax rate, the benefit is 1.5% of sales. At a 10% margin and 25% tax rate, it is 2.5% of sales.

PLI pays from the budget. Zero tax waives a claim on profit after production exists. The tradeoff is administrative: PLI allows tighter sector targeting, but it also creates discretion. Zero tax is broader, simpler, and more automatic, but only if the eligibility rules are hard enough to prevent fake manufacturing and profit shifting.

The right design may use both: PLI for a small number of sectors with clear learning spillovers, zero tax for broad-based new manufacturing capacity that meets value-addition and payroll thresholds.

## 4. Fiscal Neutrality and the Wage-Side Caveat

The fiscal case should not pretend to know more than it knows. A previous draft used `tau_y = 10%` as average wage-side capture. That number needs a real payroll-tax and income-tax build-up before it can be asserted. The better claim is conditional.

Corporate tax foregone is `Q x m x tau_c`, where `Q` is output, `m` is margin, and `tau_c` is the corporate tax rate. Wage income created is `Q x v x w`, where `v` is domestic value addition and `w` is labor's share of value added.

For wage-side fiscal capture to cover the corporate tax foregone, the condition is:

```text
v x w x tau_y > m x tau_c
```

If `v = 40%`, `w = 40%`, `m = 10%`, and `tau_c = 15%`, the required wage-side capture is just above 9.4%. If actual wage-side capture is 10% or higher, the policy can be close to fiscally neutral before counting GST, electricity duties, port fees, railway freight, supplier profits, and higher household consumption. If wage-side capture is materially below that, the case becomes less about immediate fiscal neutrality and more about strategic capacity, employment, and future tax base creation.

That is an acceptable argument, but it should be stated honestly.

## 5. Jobs and the 100,000 Manufacturer Target

Employment math needs assumptions, not slogans. If import replacement is $20B and domestic value addition is 40%, the value added created is $8B. At $20,000 of value added per direct worker, that implies about 400,000 direct jobs. With indirect jobs in suppliers, logistics, maintenance, packaging, and services, the total employment effect can be much larger, but the multiplier should be estimated sector by sector.

The 100,000 manufacturer target is more useful because it gives a capacity ladder:

| Manufacturers | Avg. Direct Jobs | Avg. Output | Gross Output | Domestic VA at 40% |
|--------------:|-----------------:|------------:|-------------:|-------------------:|
| 10,000 | 100 | $2M | $20B | $8B |
| 100,000 | 100 | $2M | $200B | $80B |
| 100,000 | 100 | $5M | $500B | $200B |
| 100,000 | 100 | $10M | $1T | $400B |

The firms do not all need to be giants. A Dixon-style electronics assembler, a Bharat Forge-style precision exporter, and thousands of smaller component makers are all part of the same production ladder. The policy question is what raises the number of viable firms, their average output, and their domestic value addition without freezing them into low-productivity labor absorption.

## 6. Logistics, Delay, and Working Capital

Manufacturing dies in working capital before it dies in strategy.

Logistics cost is margin. If logistics costs fall from 14% to 10% of shipment value, the saving is 4% of shipment value. On $100B of goods movement, that is $4B. For a manufacturer with an 8% operating margin, a 4 percentage-point logistics disadvantage can erase half the margin before pricing, quality, or productivity are even considered.

Approval delay has the same structure. If $10M of capital is committed, the cost of capital is 12%, and approvals delay production by 180 days, the delay cost is roughly `$10M x 12% x 180/365`, or about $0.6M. That is before a single unit is produced.

Payment delay is just as brutal. A $1M invoice delayed by 90 days at 12% working-capital cost creates about $30K of financing cost. If the manufacturer's expected net profit is $50K, the delay consumes about 60% of the expected profit.

This is why factory-time matters. Land allotment, power connection, customs clearance, inspection resolution, and payment discipline all show up in the same place: the manufacturer's cash conversion cycle.

## 7. Clusters, Roads, Tariffs, and Exports

Clusters lower search costs, shared-services costs, and supplier-development costs. But the old version overstated this by treating shared infrastructure as a clean subsidy that mechanically cuts break-even output by 30%. Real clusters such as Tiruppur, Surat, Ludhiana, and Sialkot also face congestion, wage inflation, pollution costs, and local political capture. The right claim is narrower: clusters can reduce entry cost when common facilities and supplier density are real, but they need governance or the savings get eaten by externalities.

Roads have the same caveat. A highway has industrial value only when goods flow through it. Expressways, ports, rail links, and warehouses should be planned with production nodes rather than treated as standalone monuments.

Tariffs can create room for domestic industry, but only if they are paired with cost reduction and input-tariff alignment. Otherwise, protection can raise consumer prices while leaving producers uncompetitive. The real test is effective protection, not the headline tariff on the finished good: if inputs are also expensive, the domestic producer may receive less protection than the tariff number suggests.

Import substitution also needs export discipline. Exporting forces quality, cost control, certification, delivery reliability, and product improvement. A manufacturing policy that never asks firms to compete abroad risks producing protected domestic mediocrity.

## 8. The Zero-Tax Rule, SEZ Lessons, and Capture

Zero tax should not mean zero conditions. A rule-based zero-tax manufacturing policy should have a 10-15 year duration, five-year reviews, and eligibility tied to production, payroll, domestic value addition, and reinvestment into capacity, R&D, exports, or worker training.

The SEZ lesson matters. India has already seen how tax-preferred zones can drift into real-estate arbitrage, enclave politics, and permanent exemptions. A zero-tax manufacturing regime should therefore have a sunset from day one. Benefits should expire for firms that miss value-addition or payroll thresholds, and they should not transfer to land banking. The tax holiday should attach to production, not geography.

The strongest objection is capture. A manufacturing exception can become a new rent machine if incumbents write the rules, labor protections are bypassed, or states compete by hiding costs instead of raising productivity. That is why the policy must be published, auditable, and open to new entrants. Labor flexibility should be paired with formal payroll, safety enforcement, and portable benefits; otherwise the state will have subsidized precariousness rather than production.

## 9. Industrial Centrality: A PageRank for Supply-Chain Targeting

Sector selection is the operational hole in any zero-tax or PLI proposal. Picking by political salience reproduces the License Raj. Picking by export contribution rewards incumbents who already have lobbyists in the room. The dashboard in §10 fixes the friction problem; it does not fix the prioritization problem. What is missing is a rule-based, recomputable, publishable score that ranks sectors by their structural importance to the production network.

This section develops one. It is a directed-graph centrality measure on the input-output network, in the lineage of Acemoglu, Carvalho, Ozdaglar, and Tahbaz-Salehi (Econometrica 2012), Liu (QJE 2019), and Baqaee and Farhi (Econometrica 2019), with two policy-relevant modifications: a strategic-vulnerability weight and a capability-thickness discount. The result, Industrial Centrality (IC), is a quarterly-recomputable score that can drive zero-tax eligibility tiers, infrastructure sequencing, and the structural rows of the §10 dashboard.

### 9.1. The Production Graph

Let `G = (V, E, W)` be a directed weighted graph. `V = {1, ..., n}` indexes sectors at first, and firms at the firm-level extension. `E` is the set of input-output linkages. `W` assigns each edge `(i, j)` the technical coefficient

```text
a_{ij} = (rupees of input i used by sector j) / (rupees of total intermediate input used by j)
```

Stack the coefficients as `A in R^{n x n}`. Each column of `A` sums to at most 1; the residual is value added (wages, capital, taxes). The Leontief inverse `L = (I - A)^{-1}` has finite entries because the spectral radius of `A` is below 1 for any productive economy (Hawkins-Simon condition).

For India, `A` is computable from the CSO Supply-Use Tables (latest comprehensive vintage 2017-18, 140 sectors), and at firm level from GSTN B2B invoice flows aggregated to monthly bilateral edges. The first source is published. The second is held by GSTN and accessible through NIPFP and IIM research partnerships.

### 9.2. Forward and Backward Centrality

Standard PageRank solves the fixed point

```text
x = (1 - d) v + d P x
```

for a column-stochastic transition matrix `P`, a personalization distribution `v`, and a damping factor `d in (0, 1)`. The closed form is

```text
x = (1 - d) (I - d P)^{-1} v
```

Production networks admit two natural specializations.

**Forward Industrial Centrality (FIC)** measures the extent to which a sector's output propagates downstream. Take `P = A` after column-normalization with uniform redistribution over dangling sectors, and let `v_F` be a personalization vector concentrated on final-demand sinks (households, exports, strategic categories). Solve `x_F = (1 - d) (I - d A)^{-1} v_F`. A sector with high `x_F` is one whose value-add is widely consumed downstream. Pharma APIs, basic chemicals, and electronics components score high.

**Backward Industrial Centrality (BIC)** measures the extent to which a sector is fed by upstream supply that the rest of the economy depends on. Take `P = A^T` and a uniform `v_B`. A sector with high `x_B` is one whose failure propagates broadly because many downstream sectors depend on it. This is the policy-relevant direction for strategic-capacity questions: what loses the most output if input `i` becomes unavailable.

The damping factor `d` plays two roles. Mathematically it makes the iteration a contraction with modulus `d`, so power iteration converges geometrically irrespective of the spectral structure of `P`. Operationally it weights short over long supply chains: `d = 0.85` (the Brin-Page choice) emphasizes effects within roughly six supply-chain steps, which matches the empirical depth of most Indian manufacturing chains. The limit `d -> 1` recovers the classical Leontief multiplier.

### 9.3. Connection to the Production-Network Literature

Three results from the recent macro-network literature anchor the construction.

Acemoglu, Carvalho, Ozdaglar, and Tahbaz-Salehi (2012) showed that idiosyncratic sectoral shocks do not wash out in aggregation when the production network is asymmetric. The standard deviation of GDP fluctuations decays slower than `1/sqrt(n)`, and the rate of decay is governed by the degree distribution of `A`. Their "influence vector" `alpha = (1/n) (I - (1 - alpha) A)^{-1} 1` is structurally a uniform-personalization PageRank up to scaling.

Baqaee and Farhi (2019) generalized Hulten's theorem beyond the first order. Once non-linearities are admitted, shocks at network-central nodes have outsize macroeconomic consequences with magnitude proportional to Domar-weighted higher derivatives of the aggregate production function evaluated at central nodes. The policy reading: distortions and supports concentrated at high-centrality sectors have first-order welfare effects.

Liu (2019) is the most directly relevant. He defines distortion centrality `delta = (I - A')^{-1} epsilon` where `epsilon` is the sectoral wedge vector, and proves that under a wide class of inefficiencies, the optimal industrial subsidy is positive and largest at sectors with high `delta`. India's policy-relevant `epsilon` includes labor-regulation wedges, credit-allocation wedges, and inverted input-tariff structures. Liu's distortion centrality is a Leontief-weighted distortion vector. BIC is the damped, regularized variant.

The contribution here is operational rather than theoretical: composing centrality with two observable, lobbying-resistant weights to produce a decision rule that can survive contact with administrative practice.

### 9.4. Two Policy-Relevant Weights

For each sector `i`, define two scalars.

**Strategic vulnerability** `m_i in [0, 1]` is the share of sector `i`'s domestic absorption supplied by a single concentrated foreign source, computed from DGCI&S commodity-country flows. For each four-digit HS code mapped into the I-O classification, take the maximum import share from any single country (or politically-linked country bloc), weighted by domestic absorption. Active pharma ingredients, mature-node semiconductor wafers, lithium-cell precursors, and rare-earth permanent magnets place sectors at `m_i > 0.6`. Diversified or domestically-dominant sectors have `m_i` near zero.

**Capability thickness** `h_i > 0` is a normalized count of domestic firms producing in sector `i` with revenue above a productivity floor (for example, ASI Schedule plants above Rs 5 crore turnover), drawn from the ASI plant frame and MCA company data. Sectors with thousands of domestic producers (textiles, food processing, basic auto components) have high `h_i`. Sectors with under a hundred (mature semis, large turbines, advanced API molecules) have low `h_i`. The denominator penalizes adding state weight to sectors that are already supplier-thick.

Both weights are observable, recomputable quarterly, and resistant to firm-level lobbying because they aggregate over thousands of underlying flows.

### 9.5. The Industrial Centrality Score

Combine:

```text
IC_i = (BIC_i x m_i) / h_i
```

A sector with high `IC` is structurally critical, strategically vulnerable, and thinly supplied domestically. These are the sectors where state coordination produces the largest expected reduction in strategic exposure per unit of effort.

Two operational variants are useful.

**IC-export** uses FIC instead of BIC, with `v_F` concentrated on exports, identifying sectors whose downstream output reaches foreign buyers most thickly. This is the variant for export-discipline targeting (§7).

**IC-employment** weights the numerator by sectoral labor intensity from ASI, identifying sectors where centrality coincides with employment generation. This is the variant for the §5 100,000-manufacturer target.

The general form admits a tunable upstream-downstream balance:

```text
IC_i^{(k)} = (w_k x BIC_i + (1 - w_k) x FIC_i) x m_i / h_i
```

with `w_k in [0, 1]` indexing the policy use case (capacity, exports, employment, strategic).

### 9.6. The Algorithm

```text
Input:
  A     : n x n technical-coefficient matrix
  m     : n-vector of strategic-vulnerability weights, m_i in [0, 1]
  h     : n-vector of capability-thickness counts, h_i > 0
  v     : n-vector personalization, sum(v) = 1
  d     : damping factor, default 0.85
  w     : upstream weight, w in [0, 1]
  tol   : convergence tolerance, default 1e-9
  k_max : iteration cap, default 200

Procedure:
  1. Build P_B from A^T, row-stochastic, dangling rows redistributed uniformly over V.
  2. Build P_F from A,   row-stochastic, dangling rows redistributed uniformly over V.
  3. For each P in {P_B, P_F}:
       x_0 := v
       for k in 1 .. k_max:
         x_k := (1 - d) v + d P x_{k-1}
         if ||x_k - x_{k-1}||_1 < tol break
       record x_k as BIC or FIC.
  4. For each i:
       IC_i := (w x BIC_i + (1 - w) x FIC_i) x m_i / h_i
  5. Rank sectors by IC, descending.

Output:
  IC vector, BIC vector, FIC vector, ranked sector list.
```

**Convergence.** The map `x -> (1 - d) v + d P x` is a contraction in the L1 norm with modulus `d` whenever `P` is row-stochastic, so `||x_k - x*||_1 <= d^k x ||x_0 - x*||_1`. With `d = 0.85` and `tol = 1e-9`, convergence is reached in roughly `ceil(log(tol) / log(d)) ~ 128` iterations, independent of `n`. Existence and uniqueness of the fixed point follow from Banach.

**Complexity.** Each iteration costs `O(nnz(A))`, where `nnz` counts non-zeros. For the 140-sector I-O table, `nnz` is on the order of 5,000 and a full IC computation runs in milliseconds. For the firm-level GSTN graph at roughly 1.4M registered manufacturers and approximately 5 x 10^7 monthly bilateral edges, each iteration costs about 50 ms with sparse linear algebra (scipy.sparse, PETSc), and the full IC computation finishes in under 10 seconds on a single workstation. Quarterly recomputation is trivially affordable.

**Numerical stability.** The damping factor regularizes the spectral problem. Even when `A` has near-unit spectral radius, the damped iteration has spectral radius `d` and converges. This is the operational reason for preferring damped PageRank over the raw Leontief inverse for policy targeting.

### 9.7. Worked Qualitative Illustration

This paper is the specification, not the empirical execution. The qualitative structure of `IC` for India in 2026 is expected to resemble:

| Sector cluster | BIC | m | h | IC rank |
|---|---|---|---|---|
| Active pharma ingredients (key molecules) | High | High (China 0.6-0.8) | Low | Top decile |
| Mature-node semiconductors | Moderate | High (Taiwan, China) | Very low | Top decile |
| Lithium-cell precursors | Moderate-high | Very high (China) | Near zero | Top decile |
| Rare-earth permanent magnets | Moderate | Very high (China) | Near zero | Top decile |
| Advanced auto components | High | Moderate | Moderate | Mid-upper |
| Industrial chemicals (commodity) | High | Moderate | Moderate | Mid |
| Apparel and textiles | Moderate | Low | Very high | Lower |
| Food processing | Low-moderate | Low | Very high | Bottom |

Two structural points emerge. First, the IC ranking does not coincide with employment intensity. Textiles and food rank low because they are domestically thick. They are addressed by a different instrument: the IC-employment variant, or direct labor-policy reform. Second, the top-decile IC sectors substantially overlap the announced PLI list, with two important divergences. PLI covers solar modules where IC is moderate (China-heavy but `h` is rising fast post-2022); PLI does not cover several IC top-decile chemical intermediates where domestic capability remains thin and import dependence is severe.

The reading: a recomputed quarterly IC ranking would give the next iteration of PLI, or its successor instrument, a rule-based target list with explicit graduation when `m_i` falls below threshold or `h_i` rises above threshold. The concession ends when the capability is built, not when the lobbying ends.

### 9.8. Connection to the Rest of the Paper

The IC algorithm operationalizes three earlier sections.

**Zero-tax eligibility (§3, §8).** Sectors are tiered. Tier 1 is the top-decile IC: full zero-tax for the maximum 15-year window with strict eligibility. Tier 2 is the top-quartile IC: a 10-year window. Tier 3 is all qualifying manufacturing under §8's general conditions: a 7-year window. Graduation is automatic when IC drops below threshold for four consecutive quarters.

**The 100,000-manufacturer target (§5).** Composition matters. Roughly 10,000 in IC top-decile sectors where individual scale and capability matter most; roughly 30,000 in IC mid-quartile sectors where supplier-base depth matters; the remaining 60,000 in employment-intensive sectors selected by IC-employment. Aggregate counts hide the structural problem.

**The dashboard (§10).** Add three structural rows: top-10 sectors by IC; sectors that exited the top decile this quarter (capability built); sectors that entered the top decile this quarter (new strategic exposure). The dashboard becomes a state-capability instrument, not just a friction monitor.

### 9.9. Limitations

The algorithm has four well-defined failure modes.

**Sector aggregation.** The 140-sector I-O classification masks within-sector heterogeneity. "Pharmaceuticals" hides the molecule-level dependence on six Chinese intermediates. Operationalization at firm level via GSTN data resolves this but raises data-privacy and access questions. The plan: publish at 140-sector for transparency, refine to four-digit HS for actual policy ranking.

**Structural change.** `A` evolves. Treating it as fixed assumes the production technology is stationary over the policy horizon. For a country undergoing rapid industrialization that assumption is wrong: building cell-precursor capacity changes `A` for batteries, autos, and the grid simultaneously. Mitigation: recompute quarterly; treat IC as a rolling instrument, not a one-time master plan.

**Endogeneity of `h`.** The capability-thickness denominator is itself a target variable. Once policy raises `h_i`, IC drops for that sector. This is a feature (graduation), but it implies the IC ranking is not a static optimum. It is the gradient of where to push next, recomputed continuously.

**Strategic gaming.** A foreign supplier could try to game `m_i` downward by routing through a third country. Mitigation: compute `m_i` on country-of-origin (rules-of-origin certificates) rather than country-of-shipment, and aggregate over politically-linked country blocs (China and Hong Kong) rather than nominal national borders.

These are real limits, not deal-breakers, and each has a mitigation path. The IC algorithm is a substantial improvement over discretionary sector lists drawn up by committee, while remaining honest about the parameters it depends on.

### 9.10. What This Adds to the Doctrine

Sector targeting becomes auditable: the eligibility list is published quarterly and any analyst can rerun the computation from open data. The policy is self-graduating: sectors exit when capability is built, with no political-will requirement at the exit gate. Capture is structurally harder, because a firm seeking inclusion must alter `m` (the country-trade structure) or `h` (the domestic supplier base), both observable in third-party data. And the framework is portable: the same algorithm with different `m` and `h` vectors is the right operational instrument for Vietnam, Indonesia, and any other Asian industrializer making the same calculation. The algorithm is country-agnostic; the parameters are country-specific.

## 10. Dashboard and Clock

Every state should publish a manufacturing dashboard:

| Metric | Why It Matters |
|--------|----------------|
| Days from intent to first production | Master friction metric |
| Industrial land allotment time | Entry speed |
| Power connection time and uptime | Setup and operating reliability |
| Logistics cost by corridor | Competitiveness |
| Port dwell and customs clearance time | Input and export speed |
| MSME payment delay | Working capital health |
| Contract enforcement time | Trust |
| Domestic value addition by sector | Depth |
| Export share by sector | Competitiveness |
| Jobs per crore of investment | Employment intensity |
| Output per worker | Productivity |
| Defect or rejection rates | Quality |

The clock is concrete. India has roughly a decade-plus before the demographic dividend window tightens, and PLI in its current reported form has produced about Rs 20.41 lakh crore in sales, Rs 8.3 lakh crore in exports, and 14.39 lakh jobs against Rs 28,748 crore disbursed. The next test is whether policy can move from scheme-wise success to system-wide capacity: shorter factory setup times, higher domestic value addition, faster payments, and a measurable path toward 100,000 manufacturers.

## Source Anchors

- Department of Commerce / DGCI&S data reports India's FY 2024-25 goods trade with China at approximately $14.25B exports and $113.45B imports.
- Press Information Bureau trade releases report FY 2024-25 merchandise exports of about $437B and imports of about $720B, with a merchandise deficit of about $283B.
- MoSPI's Annual Survey of Industries 2022-23 release reports growth in industrial output, gross value added, and manufacturing employment, with total persons engaged around 18.5M in organized manufacturing.
- The Production Linked Incentive program has an official outlay around Rs 1.9-1.97 lakh crore across 14 sectors, with reported disbursements, sales, exports, and employment generation.
- The National Logistics Policy material notes private estimates of India's logistics cost at 13-14% of GDP and a target reduction toward 9-10%.
- Income-tax Act section 115BAB provides a concessional 15% tax rate for qualifying new domestic manufacturing companies, showing that India already recognizes manufacturing-specific tax treatment.
- Acemoglu, D., Carvalho, V. M., Ozdaglar, A., and Tahbaz-Salehi, A. (2012). "The Network Origins of Aggregate Fluctuations." Econometrica 80(5): 1977-2016. The foundational result that sectoral shocks do not wash out in aggregation when the input-output network is asymmetric.
- Liu, E. (2019). "Industrial Policies in Production Networks." Quarterly Journal of Economics 134(4): 1883-1948. Defines distortion centrality and proves that optimal industrial subsidies are largest at network-central, distorted sectors.
- Baqaee, D. R., and Farhi, E. (2019). "The Macroeconomic Impact of Microeconomic Shocks: Beyond Hulten's Theorem." Econometrica 87(4): 1155-1203. Generalizes Hulten's theorem to non-linear production networks; shocks at central nodes have outsize aggregate effects.
- Carvalho, V. M., and Tahbaz-Salehi, A. (2019). "Production Networks: A Primer." Annual Review of Economics 11: 635-663. Survey of the input-output network literature relevant to industrial policy.
- Page, L., Brin, S., Motwani, R., and Winograd, T. (1999). "The PageRank Citation Ranking: Bringing Order to the Web." Stanford Technical Report. The original damped-iteration algorithm whose specialization to production networks underlies §9.
- CSO Supply-Use Tables (latest comprehensive vintage 2017-18, 140 sectors) supply the technical-coefficient matrix `A` used in the §9 algorithm. Firm-level extension uses GSTN B2B invoice flows accessible through NIPFP / IIM research partnerships.
