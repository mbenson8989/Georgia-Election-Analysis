# Georgia-Election-Analysis

Georgia 2022 vs 2026 governor race, county by county: Democratic share of total ballots cast (S) and its change (ΔS). The method began with the Nebraska Cedar County audit (https://github.com/mbenson8989/Nebraska-Election-Analysis-/wiki/Cedar-Audit).

- Georgia has no party registration, so there is no Democratic registration share, no residual and no reverse-factoring constant (not computable). That step isn't needed: the base metric (Democratic votes ÷ total ballots cast) works on its own.
- 2022 = Georgia SOS OFFICIAL results. 2026 = Georgia SOS UNOFFICIAL results (state page published 11/19/2026 7:52 AM CST), retrieved 19 Nov 2026.
- Statewide S: 45.74% (2022) → 53.91%* (2026), ΔS = +8.17 points*.
- Population sort order: U.S. Census Bureau Vintage 2025 estimates.
- Verified in two independent passes: 159 counties × 13 fields = 2,067 checks, 0 mismatches; 11/11 statewide checks matched.

## Files (repo root)
| File | Contents |
|---|---|
| `ga_gov_2022_2026_by_population.csv` | 159 counties, largest to smallest: Dem/Rep/other governor votes, governor-race total, total ballots cast (2022, 2026*), S, ΔS, ballot-check and over-ballot columns, SOS county certification flag |
| `GA_Slope_S2022_to_S2026_County_Slope_Chart.png` | County slope chart |
| `GA_governor_stacked_share_by_population.png` | Stacked share bars (population order) |
| `GA_deltaS_by_county_population_order_floor_ceiling.png` | ΔS by population order |
| `GA_deltaS_vs_population_scatter.png` | ΔS vs population |
| `GA_governor_2022_Dem_share_vs_change_bar_chart.png` | Vote-share change sorted by 2022 Democratic share |
| `GA_Ceiling_and_Floor_Counties_deltaS_by_population.png` | Ceiling and floor counties |
| `GA_ballots_minus_governor_votes_rolloff_check.png` | Ballot-count check |
| `GA_over_ballot_check_dem_plus_rep_vs_ballots.png` | Texas-style over-ballot check |

See the wiki for method, sources and caveats: https://github.com/mbenson8989/Georgia-Election-Analysis/wiki
