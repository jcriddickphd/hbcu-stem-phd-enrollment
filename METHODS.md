# Methods

## Enrollment (GSS)

- **Measure.** First-time, full-time doctoral entrants. GSS reports first-time enrollment for full-time students only.
- **Domestic.** U.S. citizens and permanent residents, as reported by GSS.
- **Universe.** GSS covers science, engineering and health. Education, humanities, business and law are outside it.
- **Years.** Fall 2019 through fall 2025 public use files.

## STEM definition

UNESCO ISCED-F 2013 broad fields 05 (natural sciences, mathematics and statistics), 06 (information and communication technologies), 07 (engineering) and 08 (agriculture, forestry, fisheries and veterinary). GSS field codes are mapped to broad fields with NSF Table A-6. Social sciences and psychology (03) and health (09) are excluded.

This is broader than the grouping in Riddick and Oliss (CSET, April 2025), which omitted agriculture and computer science.

## Institutions

- **HBCU R1/R2:** the fourteen HBCUs holding a 2025 Carnegie R1 or R2 designation. South Carolina State's research doctorates are in education, outside the GSS universe, so it contributes no entrants.
- **The 27 NYT universities:** the research universities in the *New York Times* analysis of doctoral enrollment (Nov. 9, 2026).
- Institutions are matched by exact GSS name. Where GSS changed a name between years (University of Illinois Urbana-Champaign in 2025; Southern University and A&M College in 2023 and 2025), the names were linked and checked against the IPEDS unit ID.

## Conferrals (IPEDS)

Research doctorates conferred (award level 17) by two-digit CIP, mapped to the same ISCED-F STEM fields. Professional doctorates such as the DVM (award level 18) are excluded, consistent with Carnegie. IPEDS has not released 2024-25, so conferral figures end in 2023-24. Values are in `data/derived/table2_stem_share_conferred.csv`.

## Carnegie thresholds

R1: $50 million in total research spending and 70 research doctorates. R2: $5 million and 20. The 2025 designations use the higher of a three-year average or the most recent year; future releases use the three-year average only.

## Graphics

- **Index chart and cover.** Each line is indexed to 2019 = 100. The cover's gray lines are 131 non-HBCU universities with at least 25 domestic STEM entrants in 2019, at least one in every year, and an index between 45 and 255. Lines are smoothed between yearly values; only the yearly points are data.
- **STEM share graphic.** Each column is the 33% STEM share floor recommended in the CSET brief; the solid portion is the actual share of research doctorates conferred in STEM, 2017-18 through 2023-24.

## Institution lists

**HBCU R1/R2 (14):** Howard University (R1); Clark Atlanta, Delaware State, Florida A&M, Hampton, Jackson State, Morgan State, North Carolina A&T, Prairie View A&M, South Carolina State, Southern University and A&M College, Tennessee State, Texas Southern, Virginia State (R2).

**The 27 NYT universities:** Columbia; Duke; Emory; Georgia Tech; Johns Hopkins; Michigan State; Northwestern; Ohio State; Stanford; Stony Brook; Texas A&M; UC Irvine; UC Riverside; UC San Diego; Chicago; Colorado Boulder; Florida; Georgia; Illinois Urbana-Champaign; Kansas; Michigan; Missouri-Columbia; Southern California; Wisconsin-Madison; Virginia Tech; Washington University in St. Louis; Yale.
