correlation with [immune infiltration](immune_infiltration.md)

What the heatmap represents

Rows = different immune cell types (e.g., B cells, CD8+ T cells, macrophages, neutrophils, dendritic cells).

Columns = cancer types (from TCGA, e.g., BRCA, LUAD, LIHC, etc.).

Colors = correlation strength and direction between your selected gene’s expression (in this case LRP1) and the estimated abundance of each immune cell type.

Red shades = positive correlation (higher gene expression associates with higher immune infiltration).

Blue shades = negative correlation (higher gene expression associates with lower immune infiltration).

White/light = little or no correlation.

2. How to interpret correlations

Positive correlation (deep red): Suggests that tumors with higher LRP1 expression tend to recruit or accumulate more of that immune cell type. For example, if macrophages show strong red in several cancers, LRP1 expression may be linked to macrophage infiltration.

Negative correlation (deep blue): Suggests that high expression of the gene is associated with reduced presence of that immune cell type.

Cancer specificity: Correlation patterns vary between cancer types. A gene may strongly correlate with immune infiltration in one cancer (e.g., LIHC) but show no pattern in another (e.g., GBM).

3. Practical example for your file (LRP1)

If the heatmap shows red blocks for macrophages across multiple cancers, you can infer that LRP1 expression is positively associated with macrophage infiltration.

If blue appears for CD8+ T cells in some cancers, it may suggest higher LRP1 is linked with fewer cytotoxic T cells there, potentially indicating an immunosuppressive environment.

Mixed patterns (some cancers red, some blue) highlight context-dependent roles of the gene.

4. Next steps when analyzing

Look at the p-values or significance markers (TIMER sometimes uses stars on the heatmap). Only strong/significant correlations should be considered biologically meaningful.

Cross-check with clinical outcome plots (also available in TIMER) to see if the infiltration associations translate to prognosis.

Compare with mutation/sCNA modules: sometimes the gene’s copy number changes or mutations also shape immune infiltration.