# Literature Review

> Status: working memo. This chapter maps the intellectual terrain for the full paper. It is not a substitute for close reading; it identifies what each literature contributes, what it does not prove, and what the Indian policy design must do with it.

## 0. The Standard of Proof

The manufacturing thesis has to clear a higher bar than ordinary political argument. It must show that manufacturing has externalities or coordination failures large enough to justify a policy wedge; that India has binding constraints ordinary liberalization has not solved; and that the proposed instrument is robust to Indian state-capability limits.

That means the paper cannot rest on slogans about factories, jobs, or national power. The relevant literatures impose five tests:

1. Welfare test: is the marginal social return above the marginal private return?
2. Sector test: which activities generate spillovers or network effects large enough to matter?
3. India test: what specific distortions stop Indian manufacturing firms from scaling?
4. Discipline test: how does the state withdraw benefits from non-performers?
5. Capability test: can the Indian state actually administer the instrument?

## 1. Learning Externalities: Greenwald-Stiglitz

The manufacturing exception should begin with learning, not sentiment. Greenwald and Stiglitz provide the strongest theoretical foundation: development is a process of learning, and markets underinvest in activities where the social benefits of learning exceed the private returns captured by the firm.

The implication for this paper is direct. A manufacturer may only internalize current-period profit, but production can also create process knowledge, trained workers, supplier capabilities, quality routines, and export relationships. Those spillovers are not fully priced. If the marginal social return to manufacturing exceeds the marginal private return, a policy wedge can be welfare-improving.

The zero-tax proposal must therefore be framed as a crude but administratively simple learning subsidy. The current `v / (m x tau)` arithmetic is only a static fiscal ratio. The full paper must derive a subsidy rule where the optimal wedge depends on learning elasticity, spillover intensity, time horizon, and discount rate.

Limit: Greenwald-Stiglitz establishes the case for correcting learning externalities; it does not identify which Indian sectors have the highest spillovers or whether the Indian state can administer the correction without capture. Those questions require product-space, production-network, and political-economy work.

## 2. Product Space and Economic Complexity: Hausmann-Hidalgo

The product-space literature prevents the paper from treating "manufacturing" as one abstract good. Countries diversify into products related to existing capabilities. Some products are more valuable because they sit near many other complex products and open further diversification paths.

For India, this means the 100,000-manufacturer target cannot be sector-agnostic. The paper must distinguish sectors that are close to India's current capability base from sectors that are strategically important but capability-distant. Electronics assembly, pharma APIs, apparel, auto components, specialty steel, batteries, and semiconductor ATMP do not sit at the same point in the product space.

The full paper needs India's ECI trajectory, product-space density, and comparison with Vietnam, China, and Bangladesh. The question is not simply "what should India make?" It is "which products move India into denser, more complex parts of the product space without pretending every frontier sector is immediately reachable?"

Policy implication: broad zero-tax treatment can be sector-neutral at the eligibility layer, but strategic premia should not be sector-neutral. They should go where capability adjacency, spillovers, production-network centrality, and geopolitical option value are jointly high.

## 3. Misallocation and the Missing Middle: Hsieh-Klenow

Hsieh and Klenow is the anchor for the missing-middle argument. Their QJE paper estimates large dispersion in marginal products across manufacturing plants in China and India relative to the United States. In their counterfactual, reducing misallocation to U.S.-like levels raises manufacturing TFP by roughly 30-50% in China and 40-60% in India.

This matters because India's manufacturing problem is not only low investment. It is distorted allocation. Firms stay too small, productive firms fail to scale, and capital/labor do not flow smoothly toward higher-productivity plants.

The white paper should use this literature to discipline the argument. "100,000 manufacturers" should not mean subsidizing every small firm to remain small. The goal is a thicker distribution of firms that can cross thresholds, formalize, raise productivity, and enter supplier networks.

Required upgrade: reproduce the logic with current Indian data where possible. The chapter should distinguish tax-induced informality, finance constraints, labor-threshold avoidance, land/power frictions, and sector-specific distortions rather than treating "missing middle" as one cause.

## 4. Premature Deindustrialization: Rodrik

Rodrik's premature-deindustrialization frame supplies the urgency. Late industrializers are running out of manufacturing-led development opportunities earlier and at lower income levels than early industrializers. Manufacturing peaks have shifted downward and leftward.

For India, this changes the demographic argument. It is not enough to say India has a young population. The relevant question is whether India can absorb young workers into productive tradable sectors before the industrialization window narrows further.

The full paper should chart India against Korea, Taiwan, Malaysia, China, Vietnam, and Bangladesh at comparable income levels. If India has already missed part of the classic East Asian manufacturing window, then policy must focus on sectors where India still has realistic capability adjacency and labor absorption.

Limit: the premise does not prove that any industrial policy works. It proves that delay is costly and that India must be selective about where manufacturing-led development is still feasible.

## 5. New Industrial Policy Empirics: Juhasz, Lane, Rodrik

The recent industrial-policy literature is more empirical and less ideological than the older debate. Juhasz, Lane, and Rodrik summarize a newer generation of work that uses better identification, historical shocks, production-network structure, and more detailed firm/sector data.

Lane's work on Korea's HCI drive is central because it studies an intervention with persistent capability effects after the policy period. Juhasz's Napoleonic blockade paper shows that temporary protection can lead to technology adoption and persistent industrial activity under some conditions.

The lesson is not "protect everything." The lesson is that temporary, disciplined, capability-building policy can have long-run effects when it induces learning and technology adoption. That supports sunset clauses and export discipline rather than permanent protection.

Design implication: India should treat benefits as conditional and time-bounded. A firm that does not raise domestic value addition, payroll, quality, exports, or strategic output should lose access automatically.

## 6. Production Networks: Liu

Liu's production-network model is important because it gives sector targeting a formal logic. If sectors are connected through input-output linkages, distortions compound through the network. Upstream sectors can matter more than their direct output share suggests.

This is directly relevant to India's sector strategy. Supporting components, tooling, chemicals, machinery, and intermediate inputs may produce larger system effects than supporting final assembly alone. A zero-tax policy can be broad, but any strategic-capacity premium should be informed by production-network centrality rather than political salience.

The operational instrument is specified in §9 of [Industrial Base Math](./industrial-base-math.md): a damped PageRank on the Indian input-output graph, composed with a strategic-vulnerability weight (single-source import concentration) and a capability-thickness denominator (count of domestic producers above a productivity floor). The result is a quarterly-recomputable Industrial Centrality score that drives zero-tax tiering and dashboard prioritization. It is the policy-rule version of Liu's distortion centrality, with regularization and observable lobbying-resistant weights added.

Required upgrade: use Indian input-output tables and import dependence by HS code to identify where upstream constraints bind downstream manufacturing. This is where an electronics policy becomes a components, tooling, testing, and certification policy rather than a phone-assembly headline.

## 7. State Capability: Kelkar-Shah, Pritchett, Andrews, Woolcock

The strongest objection to industrial policy in India is not theoretical. It is administrative. The Indian state often struggles to execute complex discretionary programs without delay, leakage, or capture.

Kelkar and Shah's critique of Indian state capacity pushes the proposal toward low-discretion instruments. Pritchett, Andrews, and Woolcock warn that states can mimic form without function. Pritchett and Sandefur's "flailing state" frame highlights inconsistent execution across agencies and levels of government.

The implication is that India's manufacturing policy should avoid discretionary winner-picking where possible. A rule-based zero-tax regime tied to audited production, payroll, domestic value addition, and export performance requires verification capacity, but not the same level of sector-picking wisdom as classic industrial policy.

This is the central conservative/libertarian compatibility point. The state should not micromanage prices, licenses, and firm strategy. It should define narrow eligibility rules, measure factory-time, stop taxing qualifying formation, and revoke privileges when public criteria fail.

## 8. Political Settlements and Productive Rents: Khan

Khan's framework sharpens the capture problem. Rents are not automatically bad; the issue is whether they are linked to capability acquisition and whether non-performing firms can lose access.

Korea disciplined chaebols through export targets, credit control, and credible punishment. Vietnam has party-state mechanisms India cannot copy. India lacks a comparable centralized discipline mechanism, so the rent design must be more automatic and transparent.

The zero-tax proposal should therefore be treated as a constrained rent: available broadly to qualifying new manufacturing, tied to observable performance, sunsetted, and revoked when production/value-addition/payroll conditions fail.

Open problem: India has fragmented political authority and many veto points. The paper must specify who can revoke benefits, how disputes are adjudicated, and how state governments are prevented from converting manufacturing policy into land-allotment patronage.

## 9. Export Discipline: Studwell and East Asian Cases

Studwell's framework is not a formal model, but it names a mechanism the paper needs: export discipline. Protection without export discipline becomes domestic complacency. Exporting forces firms to meet external standards on cost, quality, delivery, certification, and design improvement.

This should become a load-bearing part of the proposal. Zero tax should be available for qualifying production, but deeper benefits or strategic premia should require export performance or credible import-substitution in strategic categories with measurable cost-down paths.

India-specific caveat: not every strategic category can be judged by near-term export performance. APIs, mature-node chips, grid components, and defense-linked electronics may need strategic-output tests. The discipline mechanism should differ by sector, but it must still be measurable.

## 10. Trade Theory: Effective Protection

The paper should not use nominal tariff logic. Corden's effective-rate-of-protection framework is the right tool. What matters for a producer is protection of value added, not just the tariff on the final good.

If input tariffs are high, downstream manufacturers may receive little or even negative effective protection despite high tariffs on final goods. This is a known risk in India. Any tariff-support argument must compute effective protection by sector, especially for electronics, textiles, solar components, and auto parts.

Policy implication: tariff support must be paired with input-tariff alignment and cost reduction. Otherwise "Make in India" can become higher consumer prices plus weak domestic value addition.

## 11. Direction of Technical Change and Mission Policy

Manufacturing policy is also direction-of-technical-change policy. Acemoglu's directed technical change work and Mazzucato's mission-oriented innovation frame can help clarify where the state should shape technological trajectories rather than merely subsidize current production.

For India, this matters in batteries, grid equipment, drones, mature-node semiconductors, industrial automation, and clean manufacturing. The policy should separate broad manufacturing formation from missions where technological direction and strategic capability are explicit goals.

Constraint: mission policy is more discretionary and therefore more vulnerable to state-capability failure. The paper should keep mission premia narrow, explicit, and audited separately from the broad zero-tax manufacturing regime.

## 12. What This Literature Implies for the Paper

The current thesis becomes research-grade only if it changes in four ways:

1. The zero-tax rule is derived from learning externalities and state-capacity constraints.
2. Sector priorities are chosen through product-space, production-network, and strategic-option logic.
3. Capture is addressed through political-settlement theory, not moral warning.
4. Indian feasibility is tested against state-capability limits and sector-specific institutions.

That is the work of the full white paper.
