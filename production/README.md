# Corrected proof production materials

Copied into this project on 28 September 2026 from the approved proofing outputs. The copied files are byte-identical to those outputs. The source archive was also checked against the current Quarto source, caption, reproducibility record and data files.

## Figure 1

- [Final PDF](../figures/Figure_1.pdf)
- [Final PNG](../figures/Figure_1.png), 600 dpi
- [Caption and alt text](figure1/Figure_1_caption_and_alt_text.txt)
- [Editable Quarto source](figure1/Figure_1.qmd)
- [Source archive](figure1/Figure_1_source.zip)
- [Reproducibility record](figure1/Figure_1_reproducibility.txt)
- Input and derived data: `figure1/figure1_data/`

This is the revised figure with enlarged lettering, the light-blue civil-photoperiod and Prussian-blue civil-night strip, grey borders around the period labels, and the continuous legend. The recommendation label correctly reads Brown et al. (2022).

The relative data paths are preserved. For an isolated reproduction, extract the source archive into a separate directory outside a Quarto project and run `quarto render Figure_1.qmd` there. Rendering within this repository also inherits its root Quarto configuration, including `output-dir: docs`. The approved production exports are in `figures/`. The existing `figures/Figure1.pdf` and root-level `figure1.qmd` have been retained.

### German version

Created on 21 October 2026. The figure labels, number formatting and alt text are translated into German. The German version has no caption. The exposure data, recommendation thresholds, solar times, colours and dimensions are preserved. R checks confirm that all four derived data files exactly match those for the English version.

- [German PDF](../figures/Figure_1_de.pdf)
- [German PNG](../figures/Figure_1_de.png), 600 dpi
- [German alt text](figure1/Figure_1_de_alt_text.txt)
- [German Quarto source](figure1/Figure_1_de.qmd)
- [German source archive](figure1/Figure_1_de_source.zip)
- [German reproducibility record](figure1/Figure_1_de_reproducibility.txt)
- [German file checksums](SHA256SUMS_de), with paths relative to the project root

For an isolated reproduction, extract the German source archive and run `quarto render Figure_1_de.qmd`. It includes the input data and original derived data used for the equality checks. The yellow and grey legend entries read “im Zielbereich” and “außerhalb Zielbereich”. The period labels read “Schlaf”, “Wach” and “3h vor Schlaf”; the lower strip reads “Nacht · Tag · Nacht”.

## Tables and supporting text

- [Editable Table 2](../tables/Table_2_editable.docx)
- [Table 2 PDF preview](../tables/Table_2_preview.pdf)
- [Corrected editable Table 1 with cited references](../tables/Table_1_corrected.docx)
- [Approved proofing suggestions and query responses](Updated_proofing_tables.md)
- [MeLiDos reference](melidos_reference.bib)

Table 2 is the previously prepared native Word table at 85 mm width. The proofing suggestions record the requested production layout and caption corrections.

## Copy verification

[SHA256SUMS](SHA256SUMS) lists the checksums of all 17 copied files, with paths relative to the project root. No analysis or figure rendering was rerun during this transfer.
