# Appendix 1
## Testing Assumptions
Scenario. A pilot community-scale sawmill processes 1 million board feet (1 MMBF) per year of small-diameter thinning material. Leadership proposes scaling to a program of 3 mills. Before committing, this note stress-tests the core assumptions, adapting the framework in @scaling. As in that example, the goal is a "quick-and-dirty" order-of-magnitude check, not a perfect financial model.

Units. MBF = 1,000 board feet; MMBF = 1,000,000 board feet; tons = green (un-dried) short tons; \$ = USD. All staff figures are full-time equivalents (FTE).

## Background
This note stress-tests the decision to scale a pilot community-scale sawmill — processing 1 MMBF/yr of small-diameter thinning material — into a 3-mill program, using the assumptions-based scaling framework in @scaling. The central question is not "can one mill work?" but "what does the system actually require at 3 mills, and does the arithmetic hold?" The headline numbers: 3 MMBF/yr of lumber demands roughly 45,000 green tons/yr of small-diameter logs, which requires thinning ~2,250 acres/yr; the program employs ~54 FTE (36 at the mills, 18 in field thinning crews) at a payroll of ~\$3.15M/yr, and needs ~\$4.5M of installed mill capital. Because small-diameter thinning material is volume-hungry and labor-intensive, feedstock and staff together cost roughly 3x the value of the commodity lumber the mills produce.

Two scaling assumptions fail the stress test in ways that mirror the STAP wetland example. First, replication buys no capital economies of scale: three small mills carry the same ~\$1.50 per board foot of installed capital as one, versus ~\$0.67/BF for a single large industrial line. Second, the feedstock and staff base is far larger than intuition suggests: ~15 green tons of logs are needed per MBF of lumber (vs. ~3.8 tons/MBF for large-log industrial mills), and the payroll alone (~\$3.15M/yr) exceeds total lumber revenue (~\$1.05M/yr). The exercise therefore surfaces that the program only pencils out with value-added products (flooring/timbers), coproduct revenue (chips, residue, biochar), or a recurring subsidy on the order of ~\$3M/yr — and that treatment costs vary so widely by region (California mechanical thin at \$1,742/ac vs. \$500—800/ac western averages) that the planning numbers below should be re-run on local costs before committing [@delyser].

The purpose, as in the source framework, is a quick "order-of-magnitude" reality check rather than a precise financial model: it is meant to reveal which assumptions would sink the program, where to spend effort refining estimates, and how to budget program management, ramp-up, and failure risk at scale [@scaling].


Table 2.1 to Table A. Key Parameters for ONE Community-Scale Mill (1 MMBF/yr)

High-level planning parameters for a single "average" mill, mirroring STAP Table 2.1.

| # | Parameter | Planning assumption (range) | Basis / citation |
|---|-----------|----------------------------|------------------|
| 1 | Lumber capacity | 1 MMBF / yr (~ 4,200 BF per 8-hr shift x ~240 operating days) | Scenario |
| 2 | Installed mill capital cost (equipment + site, building, debarker, edger, trimmer, kiln, material handling) | ~\$1.5 M (\$1.0—2.0 M) | Small commercial sawmill equipment ~ \$100k—\$300k for a basic line; medium commercial \$500k—\$2.0 M, plus installation/site/utilities [2][3] |
| 3 | Capital intensity | ~\$1.50 per BF installed capacity | \$1.5 M / 1 MMBF |
| 4 | Lumber recovery (small-diameter logs) | 1 MBF lumber ~ 1.7 MBF log-scale (LRF ~0.6) | Small-diameter logs yield less lumber per log; Doyle/Int'l-1/4 overrun typical [6] |
| 5 | Feedstock required | ~15,000 green tons / yr (~12—15 tons per MBF of lumber; range ~10—20) | 1,700 MBF log-scale x ~9 tons/MBF for 8—14 in. logs [6] |
| 6 | Feedstock intensity (vs. industry) | ~15 tons/MBF lumber vs. ~3.8 tons/MBF at a large industrial mill | Plummer FP: 60 MMBF from 230,000 tons [5]; Gloster: 300 MMBF from ~1.0 M tons [4] |
| 7 | Mill staffing | 12 FTE (range 8—15): mgr, 2 headrig sawyers, edger/trimmer, debarker, 2 log-yard/forklift, maintenance, 2—3 kiln/sort-yard, 1—2 admin/sales | England Sawmills (small-diameter): 9 staff at up to 9 MMBF, expanding to 25 [5]; Yakama small-diameter mill: 110 staff at 30—40 MMBF [5] |
| 8 | Mill loaded wage | ~\$55,000 / FTE / yr (base ~\$39—43k at \$18—21/hr x ~1.35 benefits load) | Sawmill worker avg \$18.80/hr [9]; \$42.7k/yr / \$20.51/hr [10]; sawyer ~\$23/hr [11] |
| 9 | Mill annual payroll | ~\$660,000 / yr (12 x \$55k) | Rows 7—8 |
| 10 | Lumber price (wholesale, low-grade small-diameter product) | ~\$350 / MBF (\$250—500) | Community-mill grades (pallet/cant, #3, timbers) price well below commodity; value-added products far higher [5] |
| 11 | Feedstock delivered cost | ~\$35 / ton (planning; range \$25—60): ~ \$25/ton thinning (stump-to-truck) + ~\$10/ton hauling; stumpage ~ \$0—10 (low-value fuel-treatment byproduct) | Thinning cost ~\$21—28/ton [7][8]; hauling [7][8]. CA-specific costs run far higher: resilience mechanical thin \$1,742/ac, hand thin \$1,088/ac (~ \$54—87/ton at ~20 tons/ac), commercial-thin merchantable timber \$59.43/GT, sawlog hauling \$23—39/GT [14] |


Table 2.2 to Table B. Operating Plan for ONE 1-MMBF Mill (Annual, Planning Values)

| # | Line item | \$ / yr | Note |
|---|-----------|--------|------|
| 1 | Revenue — lumber (1,000 MBF x \$350/MBF) | +\$350,000 | Rows 1, 10 of Table A |
| 2 | Revenue — coproducts (chips, sawdust, slabs; sensitivity) | +\$50,000—135,000 | ~4,000—5,000 tons residue x \$25—30/ton; exclude from net below |
| 3 | Cost — feedstock delivered (15,000 tons x \$35/ton) | —\$525,000 | Table A row 11 |
| 4 | Cost — mill staff (12 FTE x \$55k) | —\$660,000 | Table A rows 7—9 |
| 5 | Cost — energy, blades, maintenance, insurance | —\$100,000 | Equipment-heavy ops [2][3] |
| 6 | Cost — depreciation (installed capital / 20 yr) | —\$75,000 | Non-cash |
| 7 | Total annual operating cost | —\$1,285,000 (cash); —\$1,360,000 incl. depreciation | Rows 3—6 |
| 8 | Net (before coproducts, subsidies) | ~ —\$935,000 / yr | Rows 1 — 7 |
| 9 | Unit cost | ~\$1,285—1,360 / MBF produced | Consistent with ~\$1.00—1.75/BF cost for small-scale milling [12] |

Read. A single community mill does not pencil out from lumber alone: feedstock + staff exceed gross lumber revenue by roughly 3x. Real mills close the gap with higher-value products (flooring/timbers [5]), coproducts, log-sort premiums, timber-sale revenue sharing, and/or program subsidy — exactly the kind of assumption this exercise is meant to surface.

Table 2.3 to Table C. Additional Parameters at PROGRAM Scale (3 Mills)

Program-level parameters added when going from pilot to scale, mirroring STAP Table 2.3.

| # | Parameter | Assumption (range) | Basis / citation |
|---|-----------|--------------------|------------------|
| 1 | Program size | 3 mills x 1 MMBF/yr = 3 MMBF/yr | Scenario |
| 2 | Ramp-up / sequencing | 1 new mill + ~1 thinning crew per year (mills come online t=0, t+1, t+2) | STAP: program teams can only initiate so many units per year [1] |
| 3 | Feedstock demand at full build | ~45,000 green tons / yr (3 x 15,000) | Table A row 5 |
| 4 | Thinning removal intensity | ~20 green tons/acre of merchantable small-diameter material (range 10—40) | Fuel-reduction removals of small stems [7][8] |
| 5 | Acres to treat | ~2,250 ac / yr (range ~1,100—4,500) | 45,000 tons / 20 tons/ac |
| 6 | Thinning cost (contract, stump-to-truck) | ~\$25 / ton (\$21—28); ~\$500/ac at ~20 tons/ac | Mechanized whole-tree avg \$21.34/ton, \$2,075/ha [7]; mechanical fuel treatments \$529—\$3,535/ac, median \$529 [8]. CA alternative: resilience mechanical thin \$1,742/ac, hand thin \$1,088/ac, commercial-thin merchantable timber \$59.43/GT, biomass \$16.99/BDT [14] |
| 7 | Annual thinning contract cost | ~\$1.13 M / yr (45,000 x \$25) | Rows 3, 6 |
| 8 | Field thinning crews | 3 mechanized crews, ~5 FTE each (~5—6 ac/day/crew; ~750 ac/crew/yr) | Mechanized whole-tree crew profile [7][8] |
| 9 | Field staff (direct-employ model) | 18 FTE (15 operators + 2 foremen + 1 forester/contract admin) | Row 8 |
| 10 | Field loaded wage | ~\$65,000 / FTE / yr (logging equipment operator base ~\$48k x 1.35) | BLS OES logging equipment operators ~ \$48k [13] |
| 11 | Field payroll (direct-employ alternative) | ~\$1.17 M / yr (18 x \$65k) | Rows 9—10. Alternative to contract thinning (row 7); do not double-count |
| 12 | Program management & overhead | 2 FTE + ~\$150k / yr | STAP: program-scale management adds cost not present at pilot scale [1] |
| 13 | Failure / risk events | Feedstock shortfall (fire, drought, permit delay), mill downtime, lumber price drop, crew availability | STAP: periodic minor + major failure events must be modeled [1] |

Table 2.4 to Table D. Summary Model Outputs — 1 Mill vs 3 Mills

| Metric | 1 mill (pilot) | 3 mills (program) | Ratio |
|--------|-------------------:|----------------------:|------:|
| Lumber output (MMBF/yr) | 1 | 3 | 3x |
| Installed mill capital | \$1.5 M | \$4.5 M | 3x |
| Capital per BF | ~\$1.50 | ~\$1.50 (no economies of scale — see read) | 1x |
| Feedstock required (green tons/yr) | 15,000 | 45,000 | 3x |
| Feedstock per MBF lumber (tons) | ~15 | ~15 | 1x |
| Acres treated (ac/yr) | ~750 | ~2,250 | 3x |
| Mill staff (FTE) | 12 | 36 | 3x |
| Field thinning staff (FTE) | 6 | 18 | 3x |
| Total staff (FTE) | 18 | 54 | 3x |
| Mill payroll (\$M/yr) | \$0.66 | \$1.98 | 3x |
| Field payroll, direct-employ (\$M/yr) | \$0.39 | \$1.17 | 3x |
| Total payroll (\$M/yr) | \$1.05 | \$3.15 | 3x |
| Thinning contract cost @ \$25/ton (\$M/yr) | \$0.38 | \$1.13 | 3x |
| Feedstock delivered @ \$35/ton (\$M/yr) | \$0.53 | \$1.58 | 3x |
| Lumber revenue @ \$350/MBF (\$M/yr) | \$0.35 | \$1.05 | 3x |
| Annual net, pre-subsidy/coproducts (\$M/yr) | ~ —\$0.94 | ~ —\$2.8 | 3x |

Staffing model uses direct-employ field crews (Table C rows 9—11); the contract-thinning figure is the market-rate alternative.

## Learnings

1. No capital economies of scale by replication. Building three small mills triples capital and keeps unit capital at ~\$1.50/BF — versus ~\$0.67/BF for a 300-MMBF industrial line [4]. Small-scale replication buys redundancy and community benefits, not capital efficiency. (A balancing-loop "limit to growth" in Senge's terms [1].)

2. Small-diameter feedstock is volume-hungry. ~15 tons of green material per MBF of lumber (vs. ~3.8—4 tons/MBF for large-log industrial operations [4][5]) means 3 MMBF of lumber demands ~45,000 tons/yr of thinning material and ~2,250 treated acres/yr — a large, sustained land base and a real constraint on scaling.

3. Staff dominates the cost curve. Payroll (~\$3.15M/yr at full build) exceeds total lumber revenue (~\$1.05M/yr) ~3-fold. The program cannot stand on commodity lumber; it requires coproduct revenue, value-added products, or ~\$3M/yr of subsidy/co-finance — mirroring the STAP wetland program's conclusion that scaling required a large cash subsidy [1].

4. Sensitivity levers (change any and re-run): lumber price (\$250—500/MBF), value-added product mix (flooring/timbers sell near \$1,000/MBF [5]), feedstock cost (\$25—45/ton), removal intensity per acre (10—40 tons/ac), and failure events (feedstock shortfalls, price drops) — all of which can swing the annual net by +/-\$1M/yr. Regional treatment costs are the biggest wildcard: the western-US averages used here (~\$500/ac, \$21—28/ton) sit at the low end of the observed range, while California-specific costs (mechanical thin \$1,742/ac, hand thin \$1,088/ac, commercial-thin timber \$59.43/GT [14]) would roughly double-to-triple feedstock cost and wipe out any margin — so local figures must be re-run before committing [14].

5. Time frame. Even if approved, a 1-mill/yr ramp reaches full 3-MMBF capacity only in year 3 and requires ~3 yrs of sustained thinning before feedstock stockpiles stabilize — the same "longer than announced" caution as the STAP carbon example [1].



1. GEF STAP (2021). Taking Nature-Based Solutions to Scale, 5 Guidance #4 "Check Your Scaling Assumptions" and Tables 2.1—2.4 (doc pp. 14—17). https://cdn.unenvironment.org/stapgef/public/2021-06/Taking%20Nature%20Based%20Solutions%20to%20Scale%202021-01.pdf
2. ToolboxAdvice (2025). How Much Does a Sawmill Cost? — small commercial \$100k—\$300k; medium \$500k—\$2M; installation costs. https://toolboxadvice.com/how-much-does-a-sawmill-cost/
3. EquipmentFinancingHQ (2026). How Much Does a Sawmill Cost? — hobby ~\$3k to ~\$500k industrial line. https://equipmentfinancinghq.com/cost/sawmill/
4. Forestnet (2025). A Smooth Sawmill Start-Up (Gloster, MS super-mill: \$200M capital, 300 MMBF/yr, ~1.0 M tons timber/yr, 130 direct jobs). https://forestnet.com/a-smooth-sawmill-start-up/
5. USDA Forest Service. Small-Diameter Success Stories III (England Sawmills — 9 employees, up to 9 MMBF/yr, small-diameter supply from Salmon—Challis NF; Plummer Forest Products — 60 MMBF/yr from 230,000 tons; Yakama Forest Products — small-diameter mill 30—40 MMBF/yr, 110 workers). https://www.fpl.fs.usda.gov/documnts/fpmu/sd_success_stories.pdf
6. University of Tennessee Extension SP748, Estimating Weight of Logs and Standing Timber (tons/MBF: 8-in. logs ~14 tons/MBF down to ~4.5 tons/MBF at 24 in.; Doyle scale; Timson 1972; Siegel & Row 1960). https://utia.tennessee.edu/publications/wp-content/uploads/sites/269/2023/10/SP748.pdf
7. Chang, Han et al. (2023). The Cost of Forest Thinning Operations in the Western United States, Journal of Forestry 121(2) — mechanized whole-tree avg \$21.34/ton, \$2,075/ha. https://academic.oup.com/jof/article/121/2/193/6901967
8. USDA Forest Service SRS (2009). Costs of Mechanical Fuel Reduction Treatments — fuel harvesting \$620—\$3,535/ac, median \$529/ac. https://www.srs.fs.usda.gov/pubs/ja/2019/ja_2019_mitchell_003.pdf
9. ZipRecruiter (2026). Sawmill Worker Salary — avg \$18.80/hr. https://www.ziprecruiter.com/Salaries/Sawmill-Worker-Salary
10. ERI / SalaryExpert (2026). Sawmill Worker Salary, US — \$42,658/yr (\$20.51/hr). https://www.salaryexpert.com/salary/job/sawmill-worker/united-states
11. Salary.com — Sawyer avg ~\$23/hr. https://www.salary.com/research/company/sawmill-lumber/sawyer-salary
12. Woodpreneur (2021). Economics of Small Scale Mill Operations — small-scale milling cost ~ \$1.00—1.75/BF. https://woodpreneur.com/articles/economics-of-small-scale-mill-operations-production-costs/
13. BLS OES — Logging Equipment Operators, median ~\$48,000/yr (approx.). https://www.bls.gov/oes/
14. Blue Forest / CBM (2025). Effects of Forest Management & Wood Utilization on Carbon Sequestration & Storage in California — treatment cost assumptions (Table S7: resilience mechanical thin \$1,742/ac, hand thin \$1,088/ac, commercial-thin merchantable timber \$59.43/GT, biomass \$16.99/BDT, prescribed fire \$286/ac, pile burn \$735/ac), stumpage by region (Table S8: \$99—264/MBF), haul costs (Table S9: sawlogs \$23—39/GT, biomass \$39—75/BDT). https://d3f9k0n15ckvhe.cloudfront.net/wp-content/uploads/2025/02/CBM_CA_report_FINAL.pdf

All figures are planning approximations for order-of-magnitude stress-testing (as intended by the STAP framework), not quotes or engineering estimates.
