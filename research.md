# Research

I study the marine nitrogen cycle, with a focus on **nitrous oxide (N₂O)**. N₂O is a potent greenhouse gas and the main ozone-depleting substance of the 21st century, and the ocean is one of its largest natural sources. My work looks at the nitrogen cycle at several scales: how microbes make and consume N₂O, how nitrogen and carbon cycling are linked in low-oxygen waters, and how much N₂O the ocean releases to the atmosphere.

## Machine learning for N₂O air-sea fluxes

Marine N₂O emissions are hard to pin down because they vary so much in space and time. The Southern Ocean is especially hard to measure: its storms create ideal conditions for air-sea gas exchange, but ships can rarely sample during them. To get around this, I use machine learning to predict N₂O from measurements made by Biogeochemical Argo (BGC-Argo) floats, which keep profiling through every season and every storm.

With this approach we found that **low-pressure storms amplify air-sea N₂O gradients and create hotspots of emissions**. Accounting for storm conditions, instead of assuming a standard 1 atmosphere of pressure, raises the estimated annual Southern Ocean N₂O flux by 88%. These results suggest the Southern Ocean plays a larger role in the global N₂O cycle than previously thought, and may be a weaker overall sink of greenhouse gases.

📄 Kelly et al. (2026), [Low-pressure storms drive nitrous oxide emissions in the Southern Ocean](https://www.nature.com/articles/s41467-026-68744-2), *Nature Communications* · 💻 Code: [ml-argo-n2o](https://github.com/ckelly314/ml-argo-n2o)

## Coupled nitrogen and carbon cycling in oxygen-deficient zones

Oxygen-deficient zones (ODZs) are hotspots for the loss of fixed nitrogen from the ocean and for N₂O production, but ship surveys only capture them as snapshots. We used a nearly three-year, high-resolution record from a BGC-Argo float in the Eastern Tropical North Pacific to follow a shift in the ODZ's nitrogen redox balance. A mass-balance model of the float data resolves nitrate reduction, denitrification, anammox, and nitrite oxidation, and links these nitrogen transformations to carbonate chemistry. The record shows that ODZ biogeochemistry is dynamic rather than steady-state, and that mesoscale eddies and changes in organic matter supply cause much of that variability.

📄 Bif, Kelly, et al. (2026), [BGC-Argo float reveals shifts in nitrogen-carbon cycling in an oxygen-deficient zone](https://www.nature.com/articles/s43247-026-03410-5), *Communications Earth & Environment*

## Understanding nitrogen cycle processes

Predicting how marine N₂O will respond to ocean deoxygenation requires knowing which microbial pathways produce it, and what controls them. Using ¹⁵N tracer incubations and isotopomer measurements in the Eastern Tropical North Pacific, we showed that **N₂O production from nitrate dominates** in oxygen-deficient waters. We also found that ammonia-oxidizing archaea make a significant contribution through "hybrid" N₂O production. Denitrification kept producing N₂O at oxygen concentrations much higher than expected, which matters for how N₂O emissions will respond to deoxygenation. Follow-up experiments and an ecosystem model showed that the organisms reducing nitrate to N₂O mostly don't use nitrite from the surrounding water. Their response to oxygen depends on which microbial groups are present, and it is sensitive to the type of organic matter available.

📄 Kelly et al. (2024), [Isotopomer labeling and oxygen dependence of hybrid nitrous oxide production](https://bg.copernicus.org/articles/21/3215/2024/), *Biogeosciences*
📄 Sun et al. (2025), [Mechanistic understanding of nitrate reduction as the dominant production pathway of nitrous oxide in marine oxygen minimum zones](https://www.nature.com/articles/s41467-025-63989-9), *Nature Communications*

## pyisotopomer

:::{admonition} Measure N₂O isotopocules? Try pyisotopomer.
:class: tip

The positions of ¹⁵N and ¹⁸O within the N₂O molecule (its *isotopocules*) carry a fingerprint of how that N₂O was produced. Getting accurate isotopocule values from isotope ratio mass spectrometry requires careful correction for scrambling and calibration. **pyisotopomer** is an open-source Python package that handles these calculations, from raw mass spectrometer ratios to calibrated δ¹⁵N^α, δ¹⁵N^β, δ¹⁵N^bulk, and δ¹⁸O.

- 📄 **Paper:** Kelly et al. (2023), [Pyisotopomer: A Python package for obtaining intramolecular isotope ratio differences from mass spectrometric analysis of nitrous oxide isotopocules](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/full/10.1002/rcm.9513), *Rapid Communications in Mass Spectrometry*
- 📦 **Install:** `pip install pyisotopomer` ([PyPI](https://pypi.org/project/pyisotopomer/))
- 💻 **Source:** [github.com/ckelly314/pyisotopomer](https://github.com/ckelly314/pyisotopomer)

**Interested in using pyisotopomer in your lab, or in collaborating on N₂O isotopocule work?** Please {ref}`get in touch <contact>`. I'm happy to help with setup and calibration.
:::
