<p align="center">
  <a href="https://github.com/orgolabs"><img src="https://orgolabs.github.io/shared/brand/orgolabs-wordmark.png" alt="orgolabs — organic chemistry labs" width="300"></a>
</p>

# Guaifenesin by Williamson Ether Synthesis — an interactive, fact-checked explainer

> Part of **[orgolabs](https://github.com/orgolabs)** — interactive, fact-checked organic chemistry labs.
> **Live site:** https://orgolabs.github.io/guaifenesin-synthesis/

The **Williamson ether synthesis** of the expectorant **guaifenesin** (Mucinex/Robitussin) from **guaiacol** and **3-chloro-1,2-propanediol**. It shows *how* and *why* the reaction works: real 3D structures (PubChem + [3Dmol.js](https://3dmol.csb.pitt.edu/)), the phenoxide **SN2** mechanism, the procedure, and a live yield calculator.

## The chemistry in one line

Base makes the guaiacol phenoxide, which does an SN2 on the primary C–Cl of the chlorodiol:
`C₇H₈O₂ + C₃H₇ClO₂ —NaOH→ C₁₀H₁₄O₄ + NaCl + H₂O`.

## Run it locally

Open `index.html`, or serve with `python3 -m http.server`. The shared engine, styles, and 2D pathway images load from https://orgolabs.github.io/shared/.

## Credits & licensing

- Site content and code: **MIT License**.
- Molecular data: **PubChem**, U.S. National Library of Medicine — **public domain** (guaiacol CID 460, 3-chloro-1,2-propanediol CID 7290, guaifenesin CID 3516).
- 3D rendering: **3Dmol.js** (Rego & Koes, *Bioinformatics* 2015) — **BSD-3-Clause**.

> Educational summary only — not a substitute for a supervised laboratory SOP. 3-Chloro-1,2-propanediol is highly toxic and a suspected carcinogen; handle with full PPE in a hood.
