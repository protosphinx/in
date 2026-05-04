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

## 9. Dashboard and Clock

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
