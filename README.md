# J. Willard Gibbs, *The Scientific Papers*, Volume I — printed pages 1–134

The first 134 pages of Volume I (*Thermodynamics*) of *The Scientific Papers of J. Willard Gibbs* (London: Longmans,
Green, 1906), typeset in LaTeX from the printed text.

| Paper | Printed pages | PDF | LaTeX |
| --- | --- | --- | --- |
| I. Graphical Methods in the Thermodynamics of Fluids (1873) | 1–32 | [PDF](pdf/Gibbs_Scientific_Papers_Vol1_I_Graphical_Methods.pdf) | [LaTeX](tex/Gibbs_Scientific_Papers_Vol1_I_Graphical_Methods.tex) |
| II. A Method of Geometrical Representation of the Thermodynamic Properties of Substances by Means of Surfaces (1873) | 33–54 | [PDF](pdf/Gibbs_Scientific_Papers_Vol1_II_Geometrical_Representation.pdf) | [LaTeX](tex/Gibbs_Scientific_Papers_Vol1_II_Geometrical_Representation.tex) |
| III. On the Equilibrium of Heterogeneous Substances (1875–78), first part | 55–134 | [PDF](pdf/Gibbs_Scientific_Papers_Vol1_III_Equilibrium_of_Heterogeneous_Substances_pp055-134.pdf) | [LaTeX](tex/Gibbs_Scientific_Papers_Vol1_III_Equilibrium_of_Heterogeneous_Substances_pp055-134.tex) |

## Completeness

This is a partial edition of Volume I.

- Papers I and II are complete.
- Paper III runs from page 55 to page 353 of the volume. The edition has pages 55–134, up to the section
  *On the Values of the Potentials when the Quantity of one of the Components is very small*, which begins on page 135.
- Not yet transcribed: pages 135–353 of Paper III, Papers IV–IX of Volume I, the biographical sketch, and Volume II.
- The figures are redrawn in LaTeX (TikZ) from the printed figures.
- The readers do not mark the page breaks of the 1906 volume; their page numbers are not those of the print. Page
  references in Gibbs's text refer to the 1906 volume.

## How it was made

The text was transcribed from the scan of the 1906 volume by AI (OpenAI's ChatGPT), in installments of about ten
pages. Each installment was checked against the scan by AI, with OCR used only to locate text.

## Checks

On 27 October 2026 Claude Opus 5.5 (Anthropic) compared printed pages 20, 45 and 130 with the scan. Pages 20 and 130
agree with the print. On page 45 a prime was missing ("L′ and V" for "L′ and V′") and two terms that the print sets
in italics were roman; these are corrected. The other pages have not had a second check. Expect occasional
differences in symbols, primes and italics.

## Source

The transcription follows the Internet Archive scan of the Gerstein Library (University of Toronto) copy,
[scientificpapers01gibbuoft](https://archive.org/details/scientificpapers01gibbuoft).

## Building

Run `pdflatex` twice on each file in `tex/`.

## Rights

Gibbs's text is in the public domain. The transcription and typesetting are dedicated to the public domain under
[CC0 1.0](LICENSE).

## Earlier versions

Earlier versions were published on Zenodo, [doi:10.5281/zenodo.20649835](https://doi.org/10.5281/zenodo.20649835).
Zenodo has blocked access to our account, so please use this repository from now on.

---

[Sponsor this work](https://github.com/sponsors/KokunoYumeto)
