<!-- All prose for this lab lives here. Write Markdown; write chemistry as inline $\ce{...}$
     (KaTeX + mhchem). Each "## " heading becomes a section card + TOC entry (keep them short).
     Interactive blocks are mount points filled by the engine from window.LAB. -->

## An ether in one step

A **Williamson ether synthesis** is the classic way to make an ether: an **alkoxide or phenoxide** (an alkoxide's deprotonated oxygen) displaces a leaving group from an **alkyl halide** in an $S_\text{N}2$ reaction, stitching the two halves together through a new C–O–C bond. Alexander Williamson described it in 1850, and it is still the most reliable ether-forming reaction in the toolbox.

**The reaction:** **sodium hydroxide** deprotonates the phenol **guaiacol** to its **phenoxide**, a good nucleophile. That phenoxide attacks the less-hindered, chlorine-bearing carbon of **3-chloro-1,2-propanediol**, kicking out chloride and forming the aryl ether **guaifenesin**. Guaifenesin is a common **expectorant** — the active ingredient in Mucinex and Robitussin — that thins and loosens mucus in the airways.

## 1 · 3D structures

**Real geometries** from PubChem — drag to rotate, scroll to zoom. Compare the phenol **guaiacol** (whose –OH becomes the nucleophilic phenoxide) with the **product guaifenesin**, where that oxygen now bridges to the propanediol chain, and see **3-chloro-1,2-propanediol**, the alkyl halide that delivers the chain. Turn on *Highlight O* to pick out the oxygens that change.

<div data-mount="viewers"></div>

## 2 · Mechanism &amp; pathway

The ether-forming step is a **bimolecular nucleophilic substitution** ($S_\text{N}2$): the phenoxide oxygen of guaiacol attacks the primary C–Cl carbon of the chlorodiol from the back side, and chloride leaves in one concerted step.

<div data-mount="pathway"></div>

<div class="mech-grid">
<article class="mech-step"><span class="step-num">1</span>
<h3>NaOH makes the phenoxide</h3>
<p><strong>Sodium hydroxide</strong> removes the phenol O–H proton of <strong>guaiacol</strong> ($\ce{C7H8O2}$), giving a <strong>phenoxide</strong> whose negative charge is delocalized into the aromatic ring. That resonance stabilization is what lets the phenol exist as its anion — and the anion is a far better nucleophile than the neutral phenol.</p>
</article>
<article class="mech-step major-accent"><span class="step-num">2</span>
<h3>Phenoxide attacks → $S_\text{N}2$</h3>
<p>The phenoxide oxygen attacks the <strong>primary carbon</strong> that bears the chlorine in <strong>3-chloro-1,2-propanediol</strong>. The attack is a concerted <strong>backside</strong> approach, inverting that carbon as the new <strong>aryl–O–C</strong> bond forms.</p>
</article>
<article class="mech-step minor-accent"><span class="step-num">3</span>
<h3>Chloride leaves → guaifenesin</h3>
<p><strong>Chloride</strong> departs as the leaving group, completing the ether. The product is <strong>guaifenesin</strong> ($\ce{C10H14O4}$); the chloride pairs with sodium as $\ce{NaCl}$. The 1,2-diol end of the chain is a spectator and survives intact.</p>
</article>
</div>

<div class="callout info">
<h3>Why the phenoxide, not the neutral phenol?</h3>
<p>A neutral phenol –OH is a weak nucleophile and its O–H would just sit there. Deprotonating it with base unmasks the <strong>phenoxide</strong>, whose lone pair is vastly more nucleophilic — so the $S_\text{N}2$ actually proceeds. This is the heart of every Williamson synthesis: <strong>make the alkoxide/phenoxide first, then react it with the alkyl halide.</strong></p>
</div>

<div class="callout">
<h3>Which carbon reacts?</h3>
<p>The chlorodiol has three carbons, but only one carries a leaving group: the <strong>primary C–Cl</strong>. Primary carbons are the least hindered and the best $S_\text{N}2$ substrates, so substitution happens cleanly there. The two hydroxyl groups of the 1,2-diol are poor leaving groups and are <strong>untouched</strong> — they ride through to the product, which is why guaifenesin keeps its propane-1,2-diol tail.</p>
</div>

| Property | Guaiacol | 3-Chloro-1,2-propanediol | Guaifenesin |
|---|---|---|---|
| Systematic (IUPAC) name | 2-methoxyphenol | 3-chloropropane-1,2-diol | 3-(2-methoxyphenoxy)propane-1,2-diol |
| Also known as | guaiacol | &alpha;-chlorohydrin | guaifenesin |
| Formula | $\ce{C7H8O2}$ | $\ce{C3H7ClO2}$ | $\ce{C10H14O4}$ |
| Molar mass (g/mol) | 124.14 | 110.54 | 198.22 |
| Role | phenol / nucleophile precursor | alkyl halide (electrophile) | product (ether) |
| PubChem CID | [460](https://pubchem.ncbi.nlm.nih.gov/compound/460) | [7290](https://pubchem.ncbi.nlm.nih.gov/compound/7290) | [3516](https://pubchem.ncbi.nlm.nih.gov/compound/3516) |

Base: **sodium hydroxide**, $\ce{NaOH}$ (PubChem CID 14798) — forms the phenoxide and neutralizes the $\ce{HCl}$ released, so the net inorganic by-product is $\ce{NaCl}$.

## 3 · Procedure

A microscale, two-session **Williamson ether synthesis** adapted from the bundled course handout. Always use your instructor's version and your lab's safety rules — this is a study aid, not a substitute for a supervised SOP. **Guaiacol is the limiting reagent;** the chlorodiol is added in excess as a 50% solution.

<a class="dl-btn" href="docs/guaifenesin-lab-manual.pdf" target="_blank" rel="noopener">⬇ Download the full lab handout (PDF)</a>

| Reagent | Amount | Role |
|---|---|---|
| Guaiacol | 0.55 mL in 3 mL ethanol | substrate (the phenol) — **limiting** |
| 6 M $\ce{NaOH}$ | 1 mL | base (forms the phenoxide) |
| 3-Chloro-1,2-propanediol | 1.0 mL of a 50% v/v solution in ethanol | alkyl halide (excess) |
| Ethyl acetate (EtOAc) &amp; hexanes | as needed | wash / extraction &amp; TLC solvents |
| Magnesium sulfate, $\ce{MgSO4}$ | as needed | drying agent |

### Week 1 — run the reaction (in a fume hood)

1. In a **25 mL round-bottom flask**, add **0.55 mL guaiacol** dissolved in **3 mL ethanol**.
2. Add **1 mL of 6 M $\ce{NaOH}$ dropwise** — this generates the phenoxide.
3. Fit a **reflux condenser** and **reflux for 10 min** in a **sand bath**.
4. Add **1.0 mL of the 3-chloro-1,2-propanediol solution** (50% v/v in ethanol) **dropwise over 10 min**.
5. **Reflux for 1 hour.**
6. **Cool to room temperature** and remove the stir bar.
7. Transfer the mixture to a **weighed vial** with a pipette; cover it with a **Kimwipe secured by a rubber band**.
8. **Store until the next session.**

### The following week — work up &amp; analyze

1. The product should now be **dry**. Wash the solid/oil with **2 × 1 mL EtOAc**, collecting the EtOAc washes in a **separate weighed vial**.
2. Run a **TLC** of your product against **pure guaifenesin** in **50:50 hexane/EtOAc**.
3. Remove the EtOAc, then **weigh the vial** to find the mass of product.

<div class="callout">
<h3>If the product is not dry</h3>
<p>Add <strong>1 mL water</strong> to dissolve the salts, extract with <strong>2 × 3 mL EtOAc</strong>, dry the combined organic layer over <strong>$\ce{MgSO4}$</strong>, then continue with the work-up above.</p>
</div>

### Analysis

- Interpret the **NMR** spectra of the starting materials and the product: **draw guaifenesin** and connect each set of protons to its resonances with arrows.
- Calculate the **percent yield** (calculator below).
- Calculate the **$R_f$** of your product from the TLC plate.

<div class="safety"><strong>Safety:</strong> <strong>3-chloro-1,2-propanediol is highly toxic</strong> by skin absorption, ingestion, and inhalation (the central nervous system is a target organ) and is a <strong>suspected carcinogen</strong> — handle only with gloves, goggles, and a lab coat, in the fume hood. <strong>Guaiacol is toxic.</strong> <strong>$\ce{NaOH}$ is corrosive</strong> and causes severe burns. <strong>Ethanol, ethyl acetate, and hexanes are flammable</strong> — keep away from open flame. <strong>Waste:</strong> collect all organic and aqueous waste per your lab's disposal procedures.</div>

## 4 · Calculator

<div data-mount="calculator"></div>

## 5 · References

<div data-mount="references"></div>

Molecular data from [PubChem](https://pubchem.ncbi.nlm.nih.gov/compound/3516) (public domain) — guaiacol CID 460, 3-chloro-1,2-propanediol CID 7290, guaifenesin CID 3516, sodium hydroxide CID 14798. 3D rendering by [3Dmol.js](https://3dmol.csb.pitt.edu/); chemistry typeset with KaTeX + mhchem.
