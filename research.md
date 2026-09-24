# Research

My research asks where marine N₂O comes from, how it's distributed through the ocean interior, and how much the ocean releases to the atmosphere — and how those answers are changing. I approach these questions with a mix of ship-based hydrography, autonomous biogeochemical floats, and machine learning.

## Machine-learning reconstructions of ocean N₂O

Direct N₂O measurements are sparse: most come from research cruises that sample a given section once every decade or so. Meanwhile, BGC-Argo floats now measure oxygen, nitrate, and other properties continuously across the global ocean. I use machine-learning models (e.g., random forests) trained on high-quality GO-SHIP bottle data to predict N₂O from the variables floats and ships *do* measure, filling in the gaps in space and time.

A current focus is a **¼-degree, weekly reconstruction of N₂O in the eastern tropical Pacific**, one of the ocean's strongest N₂O sources thanks to its oxygen-deficient zones. I'm also exploring how satellite ocean-color observations and eddy-resolving analyses can sharpen the picture of how mesoscale eddies shape nitrogen, carbon, and oxygen cycling.

## Air-sea N₂O fluxes

The ocean is a major natural source of atmospheric N₂O, but estimates of that flux remain uncertain — especially in regions like the **Southern Ocean** and the **eastern tropical Pacific**. Building on the reconstructions above, I calculate air-sea N₂O fluxes by combining predicted surface-ocean N₂O with atmospheric N₂O records and gas-exchange parameterizations, with attention to details like skin-temperature effects that can bias flux estimates.

In the Southern Ocean, this approach showed that **low-pressure storms drive N₂O emissions** ([Kelly et al., 2026, *Nature Communications*](publications.md)). Code: [ml-argo-n2o](https://github.com/ckelly314/ml-argo-n2o).

## A global N₂O observational atlas

Machine learning is only as good as its training data. I'm assembling a **harmonized, quality-controlled compilation of ocean N₂O bottle measurements**, to be published with a DOI so the community can use a common, citable dataset. *(In preparation.)*

## Water masses and transient tracers

N₂O in the ocean interior reflects both local production and the history of the water it's carried in. Using **optimum multiparameter analysis** along GO-SHIP sections such as A16S in the South Atlantic, I attribute N₂O distributions to their source water masses. With collaborators, I'm also pairing N₂O with transient tracers like CFCs to separate preformed N₂O from what accumulates as water ages — and to trace the growing anthropogenic N₂O signal into the deep ocean.

## Isotopes of N₂O

My Ph.D. work used the stable isotopes and isotopomers of N₂O to fingerprint the microbial processes — nitrification and denitrification — that produce and consume it. Along the way I developed [pyisotopomer](https://github.com/ckelly314/pyisotopomer), a Python package for N₂O isotopocule calculations. That geochemical perspective still shapes how I interpret N₂O distributions today.

<!-- TODO: add a figure per section, e.g.
```{figure} images/etp_n2o_map.png
:width: 80%
Caption here.
```
-->

## Sea-going work

I've spent 180+ days at sea on research cruises, including GO-SHIP repeat hydrography sections. <!-- TODO: list cruises, e.g. "A16S (2026), P18 (20XX)…" -->
