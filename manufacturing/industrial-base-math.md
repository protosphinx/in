# The Industrial Base Math

**Claim:** India's China import dependence is a larger industrial-capacity problem than the corporate tax revenue India would forgo by making qualifying new manufacturing tax-free for a fixed 10-15 year window.

The claim is mathematical, not rhetorical. If some share of imports from China can be competitively produced in India, the country gains domestic value added, wages, suppliers, process learning, and crisis capacity. The fiscal cost of a manufacturing tax holiday is only the corporate tax that would have been collected on the manufacturer's profit. Since value added is much larger than profit tax, the industrial gain can dominate the tax cost by an order of magnitude.

Under a baseline set of assumptions:

```text
Annual India-China goods deficit:      $99.20B
Domestic value-added ratio:                40%
Manufacturer profit margin:                10%
Corporate tax rate:                        25%
```

the ratio is:

```text
Domestic value added created / Corporate tax foregone
= 0.40 / (0.10 x 0.25)
= 16.0x
```

At India's 15% concessional manufacturing tax rate under Section 115BAB, the same ratio is:

```text
0.40 / (0.10 x 0.15) = 26.7x
```

That is the core of the paper. For every $1 of corporate tax waived on real qualifying manufacturing, the policy can create roughly $16 to $27 of domestic value added before counting wage taxes, GST, supplier profits, freight revenue, electricity payments, job creation, lower supply-side inflation pressure, learning effects, or strategic resilience.

The policy conclusion is narrow. India should not subsidize fake manufacturing, protected assembly, land banking, or politically connected incumbents. It should create a rule-based tax holiday for new manufacturing capacity that verifiably replaces strategic imports, raises domestic value added, puts workers on formal payroll, and reinvests into production capability.

## 1. The China Deficit Is the Scale Variable

India's merchandise trade with China in FY 2024-25 was approximately:

```text
Exports to China:    $14.25B
Imports from China: $113.45B
Deficit:             $99.20B
```

That deficit is not only a trade statistic. It is a rough annual measure of industrial demand that is being satisfied by foreign production capacity. Some of it should continue to be imported because China is cheaper, better, or more specialized. The claim does not require full import substitution. It only requires that a non-trivial share can be competitively localized over time.

Define:

```text
D = annual goods deficit with China
r = share of the deficit that can be competitively localized
Q = annual localized output = D x r
v = domestic value-added ratio
m = manufacturer profit margin
tau = corporate tax rate
T = tax-holiday duration in years
```

Domestic value added created each year is:

```text
VA = Q x v
```

Corporate tax foregone each year is:

```text
Tax foregone = Q x m x tau
```

The ratio is:

```text
VA / Tax foregone
= (Q x v) / (Q x m x tau)
= v / (m x tau)
```

The China deficit `D` and localization share `r` cancel out of the ratio. They determine the absolute scale of the program, not whether the arithmetic is favorable. The tax holiday duration `T` also cancels out if the same output, value-added ratio, margin, and tax rate apply each year:

```text
T-year VA / T-year Tax foregone
= (T x Q x v) / (T x Q x m x tau)
= v / (m x tau)
```

With discounting, the same result holds if the same discount factor is applied to both annual value added and annual tax foregone. The proof is therefore simple: the manufacturing tax holiday is arithmetically attractive whenever:

```text
v > m x tau
```

For a 10% margin and 25% tax rate, the break-even domestic value-added ratio is only:

```text
0.10 x 0.25 = 2.5%
```

Real manufacturing should clear that threshold easily. If it does not, the activity is probably not manufacturing in the relevant policy sense. It is likely pass-through trading, screwdriver assembly, or profit shifting.

## 2. The 10-15 Year Tax Holiday Example

Take a modest localization target: 10% of the annual China goods deficit.

```text
D = $99.20B
r = 10%
Q = $9.92B of annual localized output
v = 40%
m = 10%
tau = 25%
T = 10 years
```

Annual domestic value added:

```text
$9.92B x 40% = $3.97B
```

Annual corporate tax foregone:

```text
$9.92B x 10% x 25% = $0.25B
```

Ten-year domestic value added:

```text
$3.97B x 10 = $39.68B
```

Ten-year corporate tax foregone:

```text
$0.25B x 10 = $2.48B
```

The 10-year policy creates roughly $39.7B of domestic value added while waiving roughly $2.5B of corporate tax. The ratio is still 16.0x.

At the 15% concessional manufacturing tax rate:

```text
Annual tax foregone = $9.92B x 10% x 15% = $0.15B
Ten-year tax foregone = $1.49B
VA / Tax foregone = 26.7x
```

The same logic scales across localization shares:

| Localized Share of China Deficit | Annual Output Localized | 10-Year VA at 40% | 10-Year Tax Foregone at 25% | VA / Tax Foregone |
|---------------------------------:|------------------------:|------------------:|----------------------------:|------------------:|
| 5% | $4.96B | $19.84B | $1.24B | 16.0x |
| 10% | $9.92B | $39.68B | $2.48B | 16.0x |
| 20% | $19.84B | $79.36B | $4.96B | 16.0x |
| 30% | $29.76B | $119.04B | $7.44B | 16.0x |

The policy does not become attractive because the target is large. It is attractive because value added is much larger than profit tax. The target size only determines whether the result is small, medium, or nationally material.

A 15-year window multiplies both value added and tax foregone by 1.5 relative to the 10-year table, so the ratio remains 16.0x under the same assumptions.

The same 10% localization example also creates a flow of domestic income that does not exist under the import baseline:

```text
Annual domestic value added = $3.97B
Annual direct corporate tax foregone at 25% = $0.25B
Annual domestic income before indirect effects = $3.72B net of foregone corporate tax
```

That net figure is not fiscal revenue. It is the domestic income pool created before counting multiplier effects, supplier formation, wage taxes, consumption taxes, or lower import vulnerability.

## 3. Sensitivity: When the Claim Is Strong or Weak

The claim is strongest when domestic value addition is high, margins are normal, and the tax holiday applies only to real new production. It weakens when value addition is low, margins are artificially inflated, or firms use the regime to shift profits without building capacity.

| Domestic Value Added | Profit Margin | Tax Rate | VA / Tax Foregone |
|---------------------:|--------------:|---------:|------------------:|
| 20% | 8% | 15% | 16.7x |
| 30% | 8% | 15% | 25.0x |
| 30% | 10% | 25% | 12.0x |
| 40% | 10% | 25% | 16.0x |
| 50% | 10% | 25% | 20.0x |
| 50% | 12% | 25% | 16.7x |

The break-even condition is:

```text
v = m x tau
```

At a 25% tax rate:

| Profit Margin | Break-Even Domestic Value Added |
|--------------:|--------------------------------:|
| 5% | 1.25% |
| 10% | 2.50% |
| 15% | 3.75% |
| 20% | 5.00% |

This is why the policy should not be defended as a subsidy to corporate profit. The waived tax is a small fraction of output. The economic object being purchased is domestic value added and capability. If a project cannot produce meaningful domestic value added, it should not qualify.

## 4. The Fiscal Objection

The strongest fiscal objection is that the state gives up real revenue. That is true. The corporate tax foregone is not zero. The point is that the direct corporate tax is the wrong denominator for judging an industrial-capacity policy.

There are three fiscal channels.

First, the direct cost:

```text
Corporate tax foregone = Q x m x tau_c
```

Second, the wage-side tax base:

```text
Wage income created = Q x v x w
```

where `w` is labor's share of value added. Wage-side fiscal capture covers the corporate tax foregone when:

```text
v x w x tau_y > m x tau_c
```

With:

```text
v = 40%
w = 40%
m = 10%
tau_c = 15%
```

the required wage-side capture is:

```text
tau_y > (m x tau_c) / (v x w)
tau_y > (0.10 x 0.15) / (0.40 x 0.40)
tau_y > 9.4%
```

If actual wage-side capture is around or above that level, the policy can be close to fiscally neutral before counting other channels. If it is below that level, the case still may hold, but the honest justification becomes industrial capacity, employment, and future tax base creation rather than immediate fiscal neutrality.

Third, there are indirect fiscal channels: GST on consumption, electricity duties, port fees, railway freight, supplier profits, property taxes around clusters, and higher household spending. These should not be assumed away, but they also should not be double-counted. The clean proof should stand on domestic value added versus corporate tax foregone. Additional fiscal recovery is upside.

## 5. Why Manufacturing Is the Exception

The argument is not that the state should run factories. That was the License Raj error. The argument is that manufacturing depends on physical inputs the state already controls: land, power, logistics, customs, courts, inspections, and payment discipline.

If those inputs are slow or unreliable, the state has already imposed an implicit tax before a factory produces its first unit. A corporate tax holiday partly offsets that burden, but it is not a substitute for fixing the burden itself.

This matters because manufacturing margins are thin. A 4 percentage-point logistics disadvantage can erase half the operating margin of a firm earning 8%. A 180-day approval delay on $10M of committed capital at a 12% cost of capital costs roughly:

```text
$10M x 12% x 180 / 365 = $0.59M
```

A $1M invoice delayed 90 days at a 12% working-capital cost imposes:

```text
$1M x 12% x 90 / 365 = $29,589
```

If expected net profit on that invoice is $50,000, the payment delay consumes about 60% of profit.

The tax holiday therefore belongs inside a broader manufacturing exception: faster land allotment, reliable power, lower logistics cost, faster customs, contract enforcement, and payment discipline. Tax relief alone cannot beat China if the operating environment remains hostile.

## 6. Eligibility: How to Keep the Math Honest

The proof only works for real manufacturing. It fails if firms use the tax holiday to relabel imports, shift profits, bank land, or assemble imported kits with minimal local value addition.

Eligibility should therefore attach to production, not incorporation, geography, or political selection.

Minimum conditions:

| Condition | Reason |
|---|---|
| New or expanded production capacity | Prevents windfall gains on existing output |
| Audited domestic value addition | Ensures `v` is real |
| Formal payroll and worker count | Ensures wage base and employment are real |
| Input-output reporting | Detects pass-through imports and transfer pricing |
| Reinvestment requirement | Keeps benefits tied to capacity building |
| Sunset after 10-15 years | Prevents permanent exemption politics |
| Automatic disqualification for false reporting | Makes gaming costly |

The tax holiday should attach to eligible production revenue from qualifying manufacturing, not to all profits of a conglomerate. A firm with both trading and manufacturing businesses should not be able to shelter trading profits under a manufacturing label.

The policy should also graduate sectors. Once domestic capability is built and import vulnerability falls, the tax holiday should expire for that sector or move to a lower tier.

## 7. PLI Versus Tax-Free Manufacturing

PLI and a tax holiday are different instruments.

PLI pays from the budget against qualifying production. It is useful where the state wants tight sector targeting, especially when learning spillovers are large and early production is uneconomic.

A tax holiday waives a claim on profit after production exists. At a 10% margin and 25% tax rate, the benefit is:

```text
10% x 25% = 2.5% of sales
```

At a 10% margin and 15% tax rate, the benefit is:

```text
10% x 15% = 1.5% of sales
```

That is modest relative to many PLI-style incentives, but it is broad, automatic, and less dependent on annual budgetary disbursement. The right design can use both:

```text
PLI = targeted support for sectors with high learning spillovers
Tax holiday = broad reward for verified new manufacturing value added
```

The claim of this paper concerns the second instrument. If India is importing around $99B more from China than it exports to China, and if part of that import demand can be localized, then waiving profit tax on the new domestic production is cheap relative to the value added created.

## 8. Inflation and Consumer Prices

A common objection is that import substitution raises prices. That is true when the instrument is a tariff, quota, licensing restriction, or protected domestic monopoly. A tax holiday works differently. It lowers the required after-tax return on domestic production rather than raising the landed cost of imports.

The price effect depends on whether domestic production is cost-competitive after the tax holiday and operating-environment improvements.

Let:

```text
P_CN = landed price of the Chinese import
C_IN = Indian pre-tax production cost
m_req = required pre-tax profit margin
tau = corporate tax rate
```

Without a tax holiday, the domestic producer needs a price high enough to cover cost and after-tax profit:

```text
Required price = C_IN x (1 + m_req / (1 - tau))
```

With a zero corporate tax rate:

```text
Required price = C_IN x (1 + m_req)
```

At a 10% required after-tax return and a 25% tax rate:

```text
Without tax holiday: C_IN x (1 + 0.10 / 0.75) = C_IN x 1.133
With tax holiday:    C_IN x 1.10
```

The tax holiday lowers the required domestic price by roughly 3 percentage points of cost. That is useful, but it is not magic. If the India-China cost gap in a sector is 10-25%, tax relief alone will not close it. The inflation claim is narrower: a tax holiday narrows the gap without taxing consumers, and it becomes powerful only when combined with logistics reform, faster approvals, cheaper working capital, and scale. It is less inflationary than tariffs because it works by lowering domestic supply cost rather than raising import prices.

There is also a macro-inflation channel. Import dependence exposes domestic prices to foreign supply shocks, freight spikes, exchange-rate depreciation, and export controls. Domestic capacity cannot eliminate those shocks, but it gives the country an alternative source of supply. In strategic inputs, that option value matters: local production can cap price spikes during disruptions even when it is not the cheapest source in normal times.

The inflation test is therefore:

```text
Domestic price after tax holiday and friction reduction <= import price plus strategic option value
```

If the policy relies on tariffs to force consumers to buy expensive domestic goods, the inflation objection wins. If the policy lowers the cost of domestic production and creates competitive supply, the inflation effect can be neutral or disinflationary over time.

## 9. Jobs, Supplier Depth, and Capacity

The employment case follows from the value-added case, but it should be stated with assumptions rather than slogans.

If import replacement is $20B and domestic value addition is 40%, then domestic value added is:

```text
$20B x 40% = $8B
```

Using an illustrative $20,000 of value added per direct worker, roughly the order of magnitude that should be calibrated from ASI gross value added and organized-manufacturing employment, that implies:

```text
$8B / $20,000 = 400,000 direct jobs
```

Indirect jobs in suppliers, logistics, maintenance, packaging, and services can be much larger, but the multiplier should be estimated sector by sector.

This is the first non-tax benefit of the policy: manufacturing converts import demand into a domestic wage pool. Under the import baseline, Indian consumers get the product but the production wages accrue elsewhere. Under the localization case, part of the same demand becomes Indian payroll.

The second benefit is supplier depth. A finished-good factory creates demand for tooling, packaging, maintenance, testing, logistics, machine repair, components, industrial services, and quality certification. These suppliers are not a side effect. They are the industrial base. The more supplier-dense the economy becomes, the easier it is for the next manufacturer to start.

The third benefit is learning. Manufacturing capability improves through repeated production: yield improvement, defect reduction, process control, vendor qualification, inventory discipline, and export certification. These gains are not captured by the corporate tax foregone formula, but they are central to why industrial capacity compounds.

The fourth benefit is resilience. Domestic capacity gives the state and private buyers an option during war, sanctions, pandemics, shipping disruptions, or export controls. The option does not need to be used every day to have value. It is insurance against strategic supply failure.

The following 100,000-manufacturer target is illustrative, not a forecast. Its purpose is to show the scale required for the claim to matter nationally:

| Manufacturers | Avg. Direct Jobs | Avg. Output | Gross Output | Domestic VA at 40% |
|--------------:|-----------------:|------------:|-------------:|-------------------:|
| 10,000 | 100 | $2M | $20B | $8B |
| 100,000 | 100 | $2M | $200B | $80B |
| 100,000 | 100 | $5M | $500B | $200B |
| 100,000 | 100 | $10M | $1T | $400B |

The point is not that every firm should be small. A Dixon-style electronics assembler, a Bharat Forge-style precision exporter, and thousands of smaller component makers all belong on the production ladder. The question is what raises the number of viable firms, their average output, and their domestic value addition without freezing them into low-productivity labor absorption.

## 10. Conservative Accounting

The 16.0x figure is deliberately narrow. It compares only domestic value added to corporate tax foregone: `VA / Tax foregone = v / (m x tau)`. It ignores wage-side fiscal capture, supplier formation, indirect tax, learning-by-doing, export capability, resilience, and lower exposure to imported inflation shocks. Those effects are real but hard to measure cleanly without sector-level data. The narrow proof is meant to dominate without them. If a firm or sector does not create domestic value added, formal jobs, supplier capacity, lower import vulnerability, or eventual graduation from support, it should lose eligibility.

## 11. Geography: Where the Manufacturing Hubs Should Go

The tax-holiday proof says manufacturing can be worth much more than the corporate tax waived. It does not say where factories should be located. Geography matters because manufacturing is a logistics problem before it is a tax problem.

The eastern manufacturing arc should be built around Uttar Pradesh, Bihar, and West Bengal:

```text
UP      = large labor pool + large domestic market + freight corridor nodes
Bihar   = low-cost labor + central position on the eastern corridor
Bengal  = eastern port gateway + access to Northeast, Bangladesh, Nepal, Bhutan, and Bay of Bengal trade
```

The logic is not sentimental federalism. It is transport math. A factory has two shipment directions:

```text
Inbound cost  = cost of moving inputs to the factory
Outbound cost = cost of moving finished goods to customers or ports
```

For a candidate city `c`, define:

```text
L_c = annual labor-cost advantage
I_c = annual input-logistics cost
O_c = annual output-logistics cost
P_c = annual port-access cost for traded goods
K_c = annual delay and working-capital cost
```

The city is attractive when:

```text
L_c > I_c + O_c + P_c + K_c
```

For export-oriented or import-replacing manufacturing, `P_c` becomes decisive. A low-wage inland factory can lose its entire labor advantage if inputs and finished goods spend too much time moving to and from a port. This is why eastern manufacturing needs a corridor-and-port design, not isolated industrial parks.

### 11.1. The UP-Bihar-Bengal Corridor

UP should be a major manufacturing platform because it combines population, labor depth, demand, and nodes on the eastern freight spine. The first-order candidates are not random cities; they are places with rail, road, power, universities, existing industry, and access to large markets: Noida-Greater Noida, Ghaziabad, Meerut, Aligarh, Kanpur, Lucknow-Kanpur, Prayagraj, Varanasi, and Gorakhpur.

Bihar should be treated as the labor-and-assembly bridge of the eastern arc. Its advantage is not only cheap labor. It sits between the dense northern market and the Bengal port gateway. Patna, Bihta, Gaya, Muzaffarpur, Darbhanga, Begusarai, and Bhagalpur are plausible manufacturing nodes if power, land, skilling, and rail-road links are made reliable.

Bengal should be the eastern gateway. Kolkata-Dankuni-Durgapur-Asansol-Haldia should function as the port-linked industrial belt for the arc. Bengal already has Kolkata/Haldia port infrastructure, but the policy question is whether eastern manufacturing has enough reliable port capacity, container handling, draft, customs speed, and last-mile rail-road connectivity. If UP and Bihar become serious manufacturing hubs, Bengal must have port capacity that behaves like part of the factory system, not like a separate bottleneck.

The economic test for Bengal's port role is:

```text
Port value = inland logistics savings + export revenue enabled + import-input reliability + avoided delay cost
```

If a Bengal port upgrade cuts the weighted average port-access cost for UP-Bihar-Bengal manufacturers by even 1% of shipment value, then on $100B of annual goods movement the saving is:

```text
$100B x 1% = $1B per year
```

That is before counting faster inventory turns, lower working capital, lower rejection risk from delayed delivery, and export growth. The port is therefore not a Bengal-only project. It is the eastern arc's shared manufacturing infrastructure.

### 11.2. The City Score

City selection should not be left to politics. It can be scored with a recomputable freight-network centrality measure plus normalized feasibility variables.

Build a directed weighted graph:

```text
G = (V, E, W)
```

where:

```text
V = cities, ports, industrial clusters, logistics nodes
E = freight, supplier, labor, and market links between nodes
W_ij = strength of the link from node i to node j
```

The edge weight should be defined in one unit, or normalized before composition. A practical version is:

```text
W_ij = annual freight value from i to j
```

If supplier-buyer transactions, travel-time reliability, labor catchments, and market access are added, each should first be converted to a percentile score in `[0, 1]`, then combined by a stated weighted sum. Do not multiply variables with different units.

Normalize `W` into a row-stochastic transition matrix `P`. Then compute PageRank:

```text
x = (1 - d) v + d P x
```

where:

```text
x = city freight-network centrality score, normalized to [0, 1]
d = damping factor, default 0.85
v = personalization vector
```

The personalization vector changes by policy goal:

```text
Import substitution: weight ports, customs nodes, and China-heavy input sectors
Jobs:                weight labor-abundant districts
Exports:             weight ports, airports, testing labs, and high-reliability freight nodes
Supplier depth:      weight existing industrial clusters and MSME density
```

Then define normalized city variables, all in `[0, 1]` where higher is better:

```text
C_c = freight-network centrality
L_c = industrial land readiness
P_c = power reliability
S_c = skill availability
A_c = port or market access
D_c = delay-cost score, defined as 1 - normalized delay cost
G_c = governance reliability score
```

The composite score is a weighted sum:

```text
GeoScore_c =
  w_C C_c + w_L L_c + w_P P_c + w_S S_c + w_A A_c + w_D D_c + w_G G_c
```

with:

```text
w_C + w_L + w_P + w_S + w_A + w_D + w_G = 1
```

For export-oriented manufacturing, increase `w_A` and `w_C`. For labor-intensive assembly, increase `w_S` and `w_L`. For power-intensive manufacturing, increase `w_P`. This is less elegant than multiplying everything together, but it is dimensionally honest and inspectable.

Cities with high `GeoScore` are not merely large. They are places where production, labor, suppliers, markets, and ports connect with low friction.

An illustrative eastern ranking would likely put the following nodes high, subject to real data:

| Role | Likely Nodes | Why They Matter |
|---|---|---|
| National capital manufacturing interface | Noida-Greater Noida, Ghaziabad | Demand, electronics, suppliers, Delhi NCR access |
| Western UP corridor | Meerut, Aligarh | Labor, existing industry, freight access |
| Central UP production belt | Kanpur, Lucknow-Kanpur, Prayagraj | Labor, universities, market access |
| Eastern UP bridge | Varanasi, Gorakhpur | Links UP to Bihar and eastern markets |
| Bihar assembly and labor bridge | Patna-Bihta, Gaya, Muzaffarpur, Begusarai | Labor, corridor position, emerging industrial land |
| Bengal port-industrial belt | Dankuni, Kolkata, Haldia, Durgapur, Asansol | Port access, rail convergence, heavy industry |

The algorithm should be recomputed annually. If a city improves power reliability, land availability, port access, or customs speed, its score should rise. If congestion, delay, or governance risk worsens, its score should fall.

## 12. Sector Targeting: Where the Tax Holiday Should Be Strongest

The math proves that real domestic value addition can dominate tax foregone. It does not prove that every sector deserves the same treatment. The highest priority sectors are those where three conditions coincide:

```text
High domestic value-added potential
High strategic import vulnerability
Thin domestic supplier base
```

A rule-based targeting score can be built from the production network, but the variables need definitions.

Let:

```text
BIC_i = normalized backward industrial centrality of sector i, in [0, 1]
m_i   = import-vulnerability score, in [0, 1]
s_i   = domestic supplier-scarcity score, in [0, 1]
```

`BIC_i` is computed from the input-output network: sectors are nodes, input flows are directed edges, and backward centrality measures how widely a sector's failure would propagate downstream. `m_i` can be measured as the import share of domestic absorption from a concentrated foreign source or bloc. `s_i` is high when domestic supplier thickness is low; for example, it can be defined from the count of domestic producers above a productivity floor, converted into a percentile scarcity score.

Then a simple normalized score is:

```text
IndustrialCentrality_i = BIC_i x m_i x s_i
```

Because each term is dimensionless and bounded in `[0, 1]`, the score is interpretable: a high score means the sector is structurally important, strategically exposed, and thinly supplied domestically. If any one term is near zero, the sector is not a top strategic target under this instrument. A weighted-sum version can be used for robustness checks, but the multiplicative version is useful as a strict screen.

Qualitatively, the top tier for India is likely to include active pharma ingredients, mature-node semiconductor inputs, lithium-cell precursors, rare-earth permanent magnets, and selected chemical intermediates. Textiles and food processing may be employment-intensive, but they are already domestically thick; they need a different policy mix.

The sector list should be recomputed and published. Graduation should be automatic. If import vulnerability falls or domestic supplier thickness rises, the sector exits the top tier. The concession ends when capability is built, not when lobbying fails.

The sector score and geography score should be combined only after both are normalized. A conservative rule is a two-stage screen:

```text
1. Keep sectors with IndustrialCentrality above threshold.
2. Within those sectors, rank cities by GeoScore for that sector's logistics and labor needs.
```

That is how policy avoids two mistakes: giving incentives to the right sector in the wrong location, or building industrial parks in good locations for sectors that do not matter strategically.

## 13. The Dashboard

Every state should publish a manufacturing dashboard that measures the variables that determine whether the tax holiday can actually create capacity:

| Metric | Why It Matters |
|--------|----------------|
| Days from intent to first production | Master friction metric |
| Industrial land allotment time | Entry speed |
| Power connection time and uptime | Setup and operating reliability |
| Logistics cost by corridor | Competitiveness |
| Port dwell and customs clearance time | Input and export speed |
| MSME payment delay | Working capital health |
| Contract enforcement time | Trust |
| Domestic value addition by sector | Tests the core claim |
| Export share by sector | Competitiveness discipline |
| Jobs per crore of investment | Employment intensity |
| Output per worker | Productivity |
| Defect or rejection rates | Quality |
| Top sectors by Industrial Centrality | Sector targeting |
| Top cities by GeoScore | Geography targeting |
| Port-access cost by manufacturing belt | Export and input competitiveness |
| Average time from factory gate to port gate | Working-capital and reliability |
| Sectors graduating from support | Anti-capture test |

The tax holiday is not a substitute for state capacity. It is a forcing function. If a state wants manufacturing, it should be able to show how quickly a firm can acquire land, receive power, clear inputs, hire formally, ship goods, collect payment, and reinvest.

## 14. What Would Disprove the Claim

The claim is falsifiable. It fails if any of the following are true:

1. The localized share of China imports is not competitively producible in India.
2. Domestic value addition is too low to clear the break-even condition `v > m x tau`.
3. Firms inflate margins through transfer pricing to maximize tax benefits.
4. The tax holiday mostly rewards existing production rather than new capacity.
5. The regime becomes a land or incorporation arbitrage instead of a production incentive.
6. The operating environment remains so costly that the tax benefit cannot offset logistics, delay, power, and working-capital disadvantages.
7. Domestic supply is created only behind consumer-price inflation, rather than through lower production cost and competitive output.
8. Factories are placed in politically convenient locations where labor savings are erased by port distance, logistics delay, power unreliability, or supplier thinness.

These are not minor caveats. They are the design constraints. A tax-free manufacturing regime should be conditional, audited, temporary, and tied to domestic value addition. Without those safeguards, the policy becomes a rent machine. With them, the arithmetic is strong.

## Conclusion

The claim is `16.0x` at a 25% tax rate and `26.7x` at the 15% concessional manufacturing rate: `VA / Tax foregone = v / (m x tau)`. The ratio scales over a 10-15 year tax holiday because time scales both sides. The policy is only defensible for verified new manufacturing that clears the falsifiers in §14 and is placed where labor, suppliers, freight, power, and port access survive the full cost equation.

> Working note: this is not yet a research-grade industrial-policy white paper. It states the core arithmetic and policy intuition. The literature, formal model, comparative cases, political-economy apparatus, and sectoral chapters required for a full paper are specified in [Manufacturing White Paper Research Program](./research-program.md).

## Source Anchors

- Department of Commerce / DGCI&S data reports India's FY 2024-25 goods trade with China at approximately $14.25B exports and $113.45B imports.
- Press Information Bureau trade releases report FY 2024-25 merchandise exports of about $437B and imports of about $720B, with a merchandise deficit of about $283B.
- MoSPI's Annual Survey of Industries 2022-23 release reports growth in industrial output, gross value added, and manufacturing employment, with total persons engaged around 18.5M in organized manufacturing.
- The Production Linked Incentive program has an official outlay around Rs 1.9-1.97 lakh crore across 14 sectors, with reported disbursements, sales, exports, and employment generation.
- The National Logistics Policy material notes private estimates of India's logistics cost at 13-14% of GDP and a target reduction toward 9-10%.
- Income-tax Act section 115BAB provides a concessional 15% tax rate for qualifying new domestic manufacturing companies, showing that India already recognizes manufacturing-specific tax treatment.
- DFCCIL / Eastern Dedicated Freight Corridor material describes the eastern freight spine running to Dankuni in West Bengal through major north Indian and eastern states, making it the natural rail backbone for a UP-Bihar-Bengal manufacturing arc.
- Syama Prasad Mookerjee Port, Kolkata material identifies Kolkata/Haldia as West Bengal's major port system and the natural eastern gateway for the hinterland; the policy question is port capacity, reliability, draft, container handling, customs speed, and last-mile connectivity.
- Acemoglu, D., Carvalho, V. M., Ozdaglar, A., and Tahbaz-Salehi, A. (2012). "The Network Origins of Aggregate Fluctuations." Econometrica 80(5): 1977-2016. The foundational result that sectoral shocks do not wash out in aggregation when the input-output network is asymmetric.
- Liu, E. (2019). "Industrial Policies in Production Networks." Quarterly Journal of Economics 134(4): 1883-1948. Defines distortion centrality and proves that optimal industrial subsidies are largest at network-central, distorted sectors.
- Baqaee, D. R., and Farhi, E. (2019). "The Macroeconomic Impact of Microeconomic Shocks: Beyond Hulten's Theorem." Econometrica 87(4): 1155-1203. Generalizes Hulten's theorem to non-linear production networks; shocks at central nodes have outsize aggregate effects.
- Carvalho, V. M., and Tahbaz-Salehi, A. (2019). "Production Networks: A Primer." Annual Review of Economics 11: 635-663. Survey of the input-output network literature relevant to industrial policy.
- Page, L., Brin, S., Motwani, R., and Winograd, T. (1999). "The PageRank Citation Ranking: Bringing Order to the Web." Stanford Technical Report. The original damped-iteration algorithm whose specialization to production networks underlies the Industrial Centrality score.
- CSO Supply-Use Tables (latest comprehensive vintage 2017-18, 140 sectors) supply the technical-coefficient matrix used in the Industrial Centrality algorithm. Firm-level extension uses GSTN B2B invoice flows accessible through NIPFP / IIM research partnerships.
