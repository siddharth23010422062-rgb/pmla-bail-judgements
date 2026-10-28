# Bail in PMLA Cases in the Supreme Court of India, 2021 to 2026

**Topic:** Bail in Money-Laundering (PMLA) Cases in the Supreme Court of India: Visualising Doctrinal Evolution, 2021 to 2026
**Author:** Siddharth Shekhar
**Page:** index.html (publish with GitHub Pages)

## Research question
How has the Supreme Court of India treated bail under section 45 of the Prevention of Money Laundering Act, 2002 since the three-judge decision in *Vijay Madanlal Choudhary* (2022), and has the Court moved between strict enforcement of the twin conditions and an Article 21 approach based on custody and delay?

## Why this topic
PMLA bail is where the Act's tension is sharpest. Section 45 reverses the usual presumption in favour of bail, yet Article 21 guarantees a speedy trial. Reading the Court's judgments in order shows how it has tried to hold both ideas together, and whether the balance has shifted from one year to the next.

## Method
I built a dataset of 13 Supreme Court judgments decided between 01-09-2021 and 31-08-2026, one row per judgment, using the course Dataset template. Each row records the case name, citation, date, bench strength, type of case, who brought it, outcome, who won, main provision, a one-line issue, a one-line holding and the precedent chiefly relied on.

**Inclusion rule.** A judgment is included if bail, or the twin conditions in s 45 PMLA, was the main issue before the Court. Cases mainly about arrest, attachment or the validity of other provisions are left out. Orders without reasons are left out. The Supreme Court has decided more PMLA bail matters than this sample, so the set is selective, not complete.

**Extra coding.** For the third chart I coded each judgment as *strict* (twin conditions enforced), *liberty* (Article 21 and delay prevail) or *procedural limit* (s 45 held not to apply because of how the accused was arrested or summoned). This is my own classification and is not part of the template.

## Findings
- Judgments per year: 1 in 2022, 1 in 2023, 5 in 2024, 4 in 2025, 2 in 2026; none coded for 2021.
- The two earliest judgments enforce s 45. Four of the five 2024 judgments grant bail on custody and delay.
- From 2025 the direction is mixed. *Kanhaiya Prasad* (2025) and *Aditya Tripathi* (2026) stress the mandatory twin conditions, while *Udhaw Singh* (2025) and *Arvind Dham* (2026) grant bail on delay.
- Individuals won 9 of the 13 judgments and the State or public body won 4.

## Limitations
- The window closed on 31-08-2026, so decisions after that date (for example October 2026 rulings) are not counted.
- Thirteen judgments is too few to claim a statistical trend.
- The sample is selected, not exhaustive, and the direction coding is a judgment call.
- Some rows were first drafted from secondary reports; every row must be checked against the official judgment (see the checklist I keep with this project).

## Files
- `data.xlsx` and `data.csv`: the dataset
- `chart1_judgments_per_year.png`, `chart2_who_won_by_year.png`, `chart3_doctrinal_direction_by_year.png`
- `index.html`: the analysis page

## Use of AI
I used Claude (Anthropic) to help find candidate judgments, to draft the dataset rows, the charts and the page. I then read the judgments and checked and corrected each row myself. Any row I did not check against the official judgment is not part of the submitted dataset.
