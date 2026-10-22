# Insight Toys Product and Manufacturing Dashboard

**Author:** Cameron Batts

## Validation update - October 22, 2026

The 6-page PDF parsed successfully, a sampled dashboard page was rendered and reviewed, and repository file links were checked. The original export bytes are preserved. Native SAS interactions, report calculations, filters and forecasts were not rerun. Editable SAS report definitions are absent; projects without source tables remain static case studies. This is an asset/evidence audit, not certification of a functioning native dashboard.

[Aggregate validation record](Reports/validation_results.json). 
## Problem
Organize a demonstration company’s product, quality and manufacturing indicators into an executive reporting view.

## Dashboard design and review
Review the Overview, Product Analysis and Unit Analysis pages. Compare KPI labels with the exported table totals and document the difference between an average displayed rate and an aggregate production-to-target ratio.

## Findings
The Unit Analysis export displays total production of 4,017,238, discards of 115,288 and target production of 4,328,016, alongside a labeled average Yield Rate of 90%. Dividing the displayed production total by target gives 92.82%, a different aggregate statistic. Visible unit rows include approximately 26%, 15% and 14% yield values; the report appendix defines a display rule for Yield Rate below 50%.

## Limitations
The 90% value is the export’s labeled average, not a verified weighted aggregate or a measure of causal improvement. Underlying rows, calculated-item definitions and the native SAS report are absent, so totals and aggregation grain cannot be recomputed. The visible table is a viewport and does not establish the total number of facility units. Navigation/filtering instructions in a static PDF do not establish that live interactions are available. No measured decision-speed, waste-reduction or production improvement is documented.

## Data and provenance
The export names INSIGHT_TOY_COMPANY_2017. SAS documentation identifies this as data for a fictitious toy company, rather than real client operational records. The raw table is not bundled. Report creation/update timestamps in April 2026 do not change the underlying sample-data year.

## Verification
KPI values, footer labels and the below-50% display rule were checked in the PDF text and rendered pages. The production/target ratio was recomputed from displayed totals. SAS was not accessed, and no underlying dataset was available.

## Reading the dashboard
The Overview presents customer satisfaction and product profit. Product Analysis combines product-line bars, a product-make treemap and style-level detail. Unit Analysis brings production, discards, targets and yield into one view.

## View the project
- [Analysis report](Reports/sas_insight_toys.html)
- [Portfolio analysis](https://cameron-batts.github.io/sas_insight_toys.html)
- [Original export: Toys_Report_on_Apr_25__2026.pdf](Reports/Toys_Report_on_Apr_25__2026.pdf)

## Dashboard previews
![Insight Toys](Images/Insight%20Toys.png)

## References
- [SAS documentation: Insight_Toy_Company_2017 is a fictitious-company dataset](https://support.sas.com/content/dam/SAS/support/en/books/interactive-reports-in-sas-visual-analytics/75618_excerpt.pdf)
