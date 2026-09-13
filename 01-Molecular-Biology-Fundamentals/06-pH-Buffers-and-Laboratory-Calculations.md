# pH, Buffers and Laboratory Calculations

## Introduction

A large part of molecular biology depends on preparing solutions correctly. Even when the biological principle behind an experiment is correct, an inaccurate buffer concentration, incorrect pH, or dilution error can affect the outcome.

During molecular biology experiments, solutions are used for almost everything: DNA extraction, PCR, restriction digestion, electrophoresis, protein extraction, staining, washing, and protein quantification. Therefore, understanding the basic chemistry and calculations behind laboratory solutions is an important practical skill.

This section covers the concepts of **pH, acids and bases, buffers, molarity, percentage solutions, stock solutions, dilutions, and serial dilutions**, along with calculations commonly encountered in molecular biology laboratories.

---

## 1. Understanding pH

pH is a measure of the hydrogen ion concentration of a solution.

The basic equation is:

$$
pH=-\log_{10}[H^+]
$$

where:

* \([H^+]\) = hydrogen ion concentration in mol/L
* pH = negative logarithm of hydrogen ion concentration

For example, if:

$$
[H^+]=1\times10^{-3}M
$$

then:

$$
pH=-\log(10^{-3})=3
$$

Therefore, the solution has a pH of 3.

### General interpretation

|  pH | General nature |
| --: | -------------- |
| < 7 | Acidic         |
|   7 | Neutral        |
| > 7 | Basic/alkaline |

At 25°C:

$$
pH+pOH=14
$$

Therefore:

$$
pOH=14-pH
$$

---

## 2. Acids and Bases

An **acid** increases the concentration of hydrogen ions in solution, while a **base** reduces the effective hydrogen ion concentration or increases hydroxide ion concentration.

Examples relevant to laboratory work include:

* Hydrochloric acid (HCl)
* Acetic acid
* Sodium hydroxide (NaOH)
* Tris-based buffers
* Phosphate buffers

The important point in molecular biology is not simply whether a reagent is acidic or basic. The **pH of the final solution** can strongly affect enzyme activity, nucleic-acid stability, protein structure, and binding interactions.

---

# 3. Why pH Matters in Molecular Biology

Biological molecules contain chemical groups whose charge can change with pH.

For proteins, changes in pH can alter:

* ionic interactions
* hydrogen bonding
* protein folding
* enzyme activity
* solubility

DNA is also affected by extreme pH. Strongly acidic or alkaline conditions can disrupt nucleic-acid structure and may contribute to degradation or denaturation depending on the conditions.

Enzymes are particularly sensitive to pH because their catalytic activity depends on the chemical state of amino-acid residues within or around the active site.

This is why molecular biology reactions are normally performed in carefully selected buffers.

---

# 4. Buffers

A **buffer** is a solution that resists large changes in pH when relatively small amounts of acid or base are added.

A typical buffer contains:

* a weak acid and its conjugate base

or

* a weak base and its conjugate acid.

A common example is an acetate buffer containing acetic acid and acetate.

Another important laboratory buffer system is **Tris**, which is widely used in molecular biology and biochemistry.

---

## 5. Henderson-Hasselbalch Equation

The relationship between buffer composition and pH can be described using the Henderson-Hasselbalch equation:

$$
pH=pK_a+\log_{10}\left(\frac{[A^-]}{[HA]}\right)
$$

where:

* \(pK_a\) = acid dissociation constant expressed logarithmically
* \([A^-]\) = concentration of conjugate base
* \([HA]\) = concentration of weak acid

This equation is useful for understanding how changing the ratio of the two buffer components changes the pH.

### Example

Suppose a buffer has:

$$
pK_a=4.76
$$

and the required pH is:

$$
pH=5.06
$$

Then:

$$
5.06=4.76+\log\left(\frac{[A^-]}{[HA]}\right)
$$

Therefore:

$$
0.30=\log\left(\frac{[A^-]}{[HA]}\right)
$$

Taking the antilog:

$$
\frac{[A^-]}{[HA]}=10^{0.30}\approx2.0
$$

So the conjugate-base-to-acid ratio should be approximately:

$$
[A^-]:[HA]\approx2:1
$$

This is a theoretical calculation; actual buffer preparation may also involve practical pH adjustment using a calibrated pH meter.

---

# 6. Molarity

Molarity describes the number of moles of solute present per litre of solution.

$$
M=\frac{\text{moles of solute}}{\text{volume of solution in litres}}
$$

Therefore:

$$
\text{moles}=M\times V
$$

where \(V\) must be expressed in litres.

If the required mass is needed:

$$
\text{Mass}=M\times V\times MW
$$

where:

* \(M\) = required molarity
* \(V\) = final volume in litres
* \(MW\) = molecular weight in g/mol

---

## 7. Molarity Calculation Example

Suppose 250 mL of 0.5 M NaCl is required.

Molecular weight of NaCl:

$$
MW=58.44\,g/mol
$$

Convert volume:

$$
250\,mL=0.250\,L
$$

Calculate the required mass:

$$
Mass=0.5\times0.250\times58.44
$$

$$
Mass=7.305\,g
$$

Therefore, approximately:

$$
\boxed{7.31\,g}
$$

of NaCl is required to prepare 250 mL of a 0.5 M solution, followed by dissolving and making the final volume up to 250 mL.

### Important point

The final volume should be made up **after dissolving the solute**, rather than simply adding the calculated amount of solvent to the solute.

---

# 8. Percentage Solutions

Percentage concentrations are commonly used for laboratory solutions and gels.

## 8.1 Weight/Volume Percentage (% w/v)

A 1% w/v solution means:

$$
1\,g/100\,mL
$$

For example:

$$
0.8\%\,w/v=0.8\,g/100\,mL
$$

### Example: Agarose

Suppose 50 mL of 0.8% agarose is required.

$$
Mass=\frac{0.8\,g}{100\,mL}\times50\,mL
$$

$$
Mass=0.4\,g
$$

Therefore:

$$
\boxed{0.4\,g}
$$

of agarose is required for 50 mL of a 0.8% w/v gel solution.

---

## 8.2 Volume/Volume Percentage (% v/v)

A 10% v/v solution means:

$$
10\,mL/100\,mL
$$

For example, to prepare 100 mL of a 10% v/v solution:

$$
10\,mL
$$

of the liquid component is used and the final volume is adjusted to 100 mL.

---

## 8.3 Weight/Weight Percentage (% w/w)

A 10% w/w solution or mixture means:

$$
10\,g
$$

of solute per:

$$
100\,g
$$

of final mixture.

The distinction between w/v, v/v, and w/w is important because they describe different quantities.

---

# 9. Stock Solutions

A **stock solution** is a concentrated solution prepared so that smaller working solutions can be produced from it.

For example:

* 10X buffer = concentrated stock
* 1X buffer = working concentration

Using stocks reduces repeated preparation and helps maintain consistency between experiments.

However, the concentration of the stock must be known accurately.

---

# 10. Dilution Equation

The most commonly used dilution equation is:

$$
C_1V_1=C_2V_2
$$

where:

* \(C_1\) = initial concentration
* \(V_1\) = volume of stock required
* \(C_2\) = final concentration
* \(V_2\) = final volume

Therefore:

$$
V_1=\frac{C_2V_2}{C_1}
$$

---

## 11. Dilution Example

Suppose 100 mL of 1X buffer is required from a 10X stock.

$$
C_1=10X
$$

$$
C_2=1X
$$

$$
V_2=100\,mL
$$

Therefore:

$$
V_1=\frac{1\times100}{10}
$$

$$
V_1=10\,mL
$$

So:

* 10 mL of 10X stock
* Add solvent to a final volume of 100 mL

Thus:

$$
\boxed{10\,mL\ stock+90\,mL\ solvent}
$$

gives 100 mL of 1X solution.

---

# 12. Another Dilution Example

Suppose a DNA sample has a concentration of 200 ng/µL and a working concentration of 50 ng/µL is required, with a final volume of 100 µL.

Using:

$$
C_1V_1=C_2V_2
$$

$$
200V_1=50\times100
$$

$$
V_1=\frac{5000}{200}
$$

$$
V_1=25\,\mu L
$$

Therefore:

* 25 µL DNA sample
* 75 µL appropriate diluent

Final volume:

$$
100\,\mu L
$$

Final concentration:

$$
50\,ng/\mu L
$$

---

# 13. Serial Dilution

A serial dilution involves making a series of successive dilutions.

For example, a 1:10 dilution performed three times produces:

$$
\frac{1}{10}\times\frac{1}{10}\times\frac{1}{10}
$$

$$
=\frac{1}{1000}
$$

Therefore, the final dilution is:

$$
\boxed{1:1000}
$$

This approach is useful when the required concentration is much lower than the original concentration.

Serial dilution is commonly encountered in:

* microbial experiments
* protein assays
* nucleic-acid measurements
* enzyme assays
* cell-based experiments

---

# 14. Dilution Factor

The dilution factor can be expressed as:

$$
DF=\frac{V_{final}}{V_{sample}}
$$

For example, if 100 µL of sample is brought to a final volume of 1 mL:

$$
DF=\frac{1000}{100}=10
$$

This represents a 10-fold dilution.

The concentration after dilution is:

$$
C_{final}=\frac{C_{initial}}{DF}
$$

---

# 15. Unit Conversions

Many laboratory calculation mistakes are caused by incorrect units rather than incorrect formulas.

Some useful conversions are:

$$
1\,L=1000\,mL
$$

$$
1\,mL=1000\,\mu L
$$

$$
1\,g=1000\,mg
$$

$$
1\,mg=1000\,\mu g
$$

$$
1\,ng=1000\,pg
$$

Therefore:

$$
1\,g=10^6\,\mu g
$$

and:

$$
1\,mg=10^6\,ng
$$

When using molarity equations, volume must normally be converted into **litres**.

When using micropipettes, volumes are generally handled in **microlitres**.

---

# 16. Concentration and Volume in PCR

PCR requires small quantities of multiple components, so dilution calculations are essential.

For example, if a primer stock is:

$$
100\,\mu M
$$

and the desired concentration in a 25 µL reaction is:

$$
0.4\,\mu M
$$

the required volume of primer stock would be:

$$
V_1=\frac{C_2V_2}{C_1}
$$

$$
V_1=\frac{0.4\times25}{100}
$$

$$
V_1=0.10\,\mu L
$$

Although this is mathematically correct, 0.10 µL is usually too small and inaccurate to pipette reliably.

A practical solution is to prepare an appropriately diluted intermediate primer working stock and use a larger pipetting volume.

This illustrates an important laboratory principle:

> A mathematically correct volume is not always a practically useful pipetting volume.

---

# 17. Master Mix Calculations

When the same reaction is performed for multiple samples, a **master mix** can be prepared containing the common reagents.

For example, suppose 10 reactions require 20 µL of common master mix each.

The theoretical volume is:

$$
10\times20=200\,\mu L
$$

In practice, additional volume is often prepared to compensate for pipetting losses and dead volume.

For example, if 10% excess is intentionally included:

$$
200\times1.10=220\,\mu L
$$

Therefore, 220 µL of master mix would be prepared.

The exact excess should be chosen according to the laboratory protocol and number of reactions.

---

# 18. Why Accurate Calculations Matter

An error in one component can affect an entire experiment.

For example:

### Incorrect buffer concentration

May alter:

* enzyme activity
* DNA binding
* electrophoretic migration
* protein stability

### Incorrect DNA concentration

May result in:

* insufficient template
* excessive template
* inconsistent PCR amplification

### Incorrect primer concentration

May contribute to:

* weak amplification
* nonspecific products
* primer-dimer formation

### Incorrect gel concentration

Can affect the separation of nucleic acids or proteins.

Therefore, laboratory calculations are not just mathematical exercises. They directly influence experimental reliability.

---

# 19. pH Measurement in the Laboratory

A pH meter is commonly used when accurate pH measurement is required.

General principles include:

1. Calibrate the instrument using appropriate standard buffers.
2. Rinse the electrode appropriately between measurements.
3. Avoid contaminating the buffer solutions.
4. Allow the reading to stabilize.
5. Record the final pH.
6. Store the electrode according to the manufacturer's instructions.

For experiments involving sensitive enzymes, even moderate pH deviations can influence activity.

---

# 20. Common Calculation Errors

### 20.1 Forgetting unit conversion

For example:

$$
250\,mL\neq250\,L
$$

Before using a molarity equation, convert:

$$
250\,mL=0.250\,L
$$

### 20.2 Confusing stock and final concentration

In:

$$
C_1V_1=C_2V_2
$$

\(C_1\) is the **starting/stock concentration**, while \(C_2\) is the **desired final concentration**.

### 20.3 Confusing final volume with solvent volume

If the final volume should be 100 mL, the components should be adjusted so that the **total final volume** is 100 mL.

### 20.4 Ignoring pipetting limits

A calculated volume such as 0.05 µL may be mathematically valid but experimentally impractical.

### 20.5 Mixing up concentration units

For example:

$$
1\,mg/mL
$$

is equivalent to:

$$
1\,\mu g/\mu L
$$

but this relationship should be checked rather than assumed.

---

# 21. Connection to Molecular Biology Techniques

The concepts in this section appear repeatedly throughout molecular biology.

| Technique                         | Relevant calculation/concept          |
| --------------------------------- | ------------------------------------- |
| DNA isolation                     | Buffer composition, pH                |
| DNA quantification                | Concentration and dilution            |
| Agarose gel electrophoresis       | % w/v gel preparation                 |
| PCR                               | Primer and reagent concentrations     |
| Restriction digestion             | Enzyme and buffer concentrations      |
| DNA ligation                      | DNA concentration and molar ratios    |
| Protein extraction                | Buffer preparation and pH             |
| Protein quantification            | Dilution and standard curves          |
| SDS-PAGE                          | Gel percentage and sample preparation |
| Microbial work                    | Serial dilution                       |
| Bioinformatics sample preparation | Concentration normalization           |

This is why solution preparation and calculation skills form a foundation for many seemingly different molecular biology experiments.

---

# 22. Practical Calculation Checklist

Before preparing a solution, I would check:

* What is the required final concentration?
* What is the required final volume?
* What is the concentration of the available stock?
* Which equation applies?
* Are all units compatible?
* Is the calculated volume practical to pipette?
* Does the protocol require a final volume adjustment?
* Is the solution sensitive to pH?
* Does the solution require sterilization or filtration?
* Does the prepared solution need a label with concentration and date?

A short calculation check before starting is usually much easier than troubleshooting an experiment afterward.

---

# Key Takeaways

* pH is related logarithmically to hydrogen ion concentration.
* Buffers resist changes in pH and are essential for maintaining suitable experimental conditions.
* The Henderson-Hasselbalch equation relates buffer pH to the ratio of conjugate base and weak acid.
* Molarity expresses moles of solute per litre of solution.
* Percentage solutions may be expressed as w/v, v/v, or w/w.
* Stock solutions allow convenient preparation of working concentrations.
* The fundamental dilution relationship is:

$$
\boxed{C_1V_1=C_2V_2}
$$

* Serial dilution allows large dilution factors to be achieved systematically.
* Correct unit conversion is essential for reliable calculations.
* A calculated volume must also be practical to pipette accurately.
* Good solution preparation is part of experimental quality control, not merely routine laboratory work.

---

## Learning Note

One thing that became clearer to me from these calculations is that molecular biology has a strong quantitative side. Reagents are not simply added because a protocol says so; their concentrations, volumes, pH, and ratios can determine whether a reaction behaves as expected.

The dilution equation in particular is simple, but it appears repeatedly in practical work. Understanding the calculation rather than memorizing individual volumes makes it much easier to adapt a protocol when the sample number or final reaction volume changes.
