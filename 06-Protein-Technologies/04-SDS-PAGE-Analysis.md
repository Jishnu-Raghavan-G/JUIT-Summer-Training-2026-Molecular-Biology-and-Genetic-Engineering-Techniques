# SDS-PAGE Analysis

## Introduction

After electrophoresis and staining, the SDS-PAGE gel is analyzed to understand the protein pattern in each sample.

The position, number and intensity of protein bands provide useful information about **molecular size, sample complexity and relative protein abundance**.

## Reading an SDS-PAGE Gel

A typical gel contains:

- **Protein ladder** — reference for molecular mass
- **Sample lanes** — contain experimental proteins
- **Protein bands** — represent separated proteins

```text
        Ladder     Sample 1     Sample 2
          │           │            │
Top       │    █      │     █      │
          │    █      │     █      │
          │    █      │          █ │
          │    █      │       █    │
Bottom    │    █      │    █       │

Proteins that migrate farther generally have lower molecular mass under standard SDS-PAGE conditions.

Protein Molecular-Weight Estimation

The molecular mass of an unknown protein can be estimated by comparing its migration with the protein ladder.

A more quantitative approach uses the relationship between migration distance and the logarithm of molecular mass.

Conceptually:

Greater migration distance → lower molecular mass

A calibration plot can be prepared using ladder proteins to estimate the molecular mass of an unknown band.

Band Intensity

Band intensity can provide a rough indication of the relative amount of a protein.

A darker or more intense band generally indicates a greater amount of that protein within the detectable range of the stain.

However, band intensity should not automatically be treated as an exact measurement of protein concentration.

Common Band Patterns
Single Prominent Band

A dominant band may indicate that one protein is present at a relatively high level.

This can be useful when evaluating a purified or recombinant protein sample.

Multiple Bands

Multiple bands indicate that the sample contains proteins with different molecular masses.

This is common in:

Crude cell extracts
Tissue extracts
Microbial lysates
Partially purified samples
Smearing

A smear rather than distinct bands may result from:

Protein overloading
Protein degradation
Incomplete sample preparation
Problems during electrophoresis
Very heterogeneous samples
Comparing Samples

SDS-PAGE can be used to compare protein profiles between different samples.

For example:

Observation	Possible interpretation
Same major band in two samples	Similar protein may be present
Additional band in one sample	Additional protein or expression product
Stronger band	Higher relative abundance
Missing band	Protein may be absent or below detection
Shifted band	Possible difference in molecular mass or processing

These interpretations should be supported by appropriate controls and experimental information.

Estimating Protein Purity

A purified protein preparation may show one dominant band, while a crude extract generally contains many bands.

Therefore, SDS-PAGE can provide a qualitative indication of purification.

Crude sample
████ ███ ██ █ ████
      ↓
Purification
      ↓
████████████
Dominant target band

A single visible band does not necessarily prove absolute purity because proteins with similar molecular masses may migrate together.

Comparing Expected and Observed Molecular Mass

If a protein is expected to have a particular molecular mass, its observed position can be compared with the molecular-weight ladder.

A difference between expected and observed mass may result from:

Protein processing
Post-translational modifications
Unusual migration behavior
Fusion tags
Experimental error

Therefore, SDS-PAGE provides an estimate rather than a definitive molecular identity.

Sample Comparison

When comparing samples, loading approximately similar amounts of protein is important.

Unequal loading can make one sample appear to have stronger protein expression simply because more total protein was loaded.

Protein quantification before SDS-PAGE therefore improves interpretation.

Common Problems During Analysis
Observation	Possible reason
Faint bands	Low protein amount or weak staining
Very dark bands	Excessive protein loading
Smearing	Overloading or protein degradation
Curved bands	Uneven electrophoresis conditions
Diffuse bands	Poor sample preparation or electrophoresis
Unexpected band size	Protein modification, processing or experimental issue
Role of Controls

Controls make gel interpretation more reliable.

Useful controls may include:

Protein molecular-weight ladder
Known protein sample
Untreated or reference sample
Appropriate experimental controls

The exact controls depend on the purpose of the experiment.

Applications

SDS-PAGE analysis is useful for:

Estimating protein molecular mass
Comparing protein profiles
Assessing sample complexity
Monitoring protein purification
Evaluating recombinant protein expression
Checking protein extraction
Selecting samples for further analysis
Practical Analysis Workflow
Run SDS-PAGE
      ↓
Stain gel
      ↓
Visualize protein bands
      ↓
Compare with protein ladder
      ↓
Estimate molecular mass
      ↓
Compare band patterns and intensity
      ↓
Interpret results with controls
Key Takeaways
SDS-PAGE separates proteins mainly according to molecular mass.
The protein ladder provides a reference for estimating band size.
Band intensity can provide information about relative protein abundance.
Multiple bands usually indicate a complex protein mixture.
Smearing may indicate overloading, degradation or technical problems.
Similar protein loading is important when comparing samples.
SDS-PAGE is useful for assessing protein profiles and monitoring purification.
Learning Note

I learned that running the gel is only half of the experiment. The real information comes from interpreting the band pattern carefully. Comparing the ladder, band positions, intensity and controls gives a much clearer picture of what is present in the protein sample.
