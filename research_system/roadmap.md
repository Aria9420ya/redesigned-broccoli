# Research Roadmap

## Stage 0: System Setup

Goal: make the research process reproducible.

- Maintain a literature matrix.
- Maintain a mechanism knowledge map.
- Maintain experiment templates and sample records.
- Track next actions through GitHub issues.

Exit criteria:

- GitHub repository exists.
- `research_system` files are versioned.
- First 10-20 core papers are extracted into the matrix.

## Stage 1: Literature Map

Goal: understand the frontier of COF/electrospun PEM research.

Key outputs:

- Benchmark table of conductivity, RH, temperature, swelling, IEC, mechanical strength, and MEA performance.
- COF chemistry taxonomy.
- Electrospinning route taxonomy.
- Gap list with experimentally testable questions.

Priority paper groups:

- COF/PFSA or COF/Nafion composite PEMs.
- COF grown on electrospun PAN/PVDF/PFSA-compatible nanofibers.
- Sulfonated, phosphonated, zwitterionic, imidazole/triazole, ionic-liquid, and heteropoly-acid COF systems.
- Low-RH and high-temperature PEMs.

## Stage 2: Hypothesis And Route Selection

Goal: select one route with a clear mechanism and controls.

Candidate route:

PFSA or Nafion matrix + electrospun PAN/PVDF scaffold + sulfonated or acid-bearing COF.

Decision criteria:

- Conductivity improves under matched RH/T.
- Swelling does not erase the conductivity benefit.
- Acid/proton carrier remains fixed after soaking.
- Fiber scaffold contributes more than mechanical reinforcement.
- MEA performance is plausible, not only ex situ conductivity.

## Stage 3: Experiment Matrix

Goal: produce a minimal but decisive sample series.

Core sample series:

- Benchmark commercial membrane.
- Polymer-only membrane.
- Polymer + electrospun scaffold.
- Polymer + COF.
- Polymer + scaffold + COF.
- COF loading series.
- Post-treatment or acidification series if needed.

## Stage 4: Characterization And Mechanism

Goal: link structure and performance.

Minimum evidence chain:

- COF formation and functionalization.
- Fiber morphology and COF distribution.
- Water uptake, swelling, IEC, and mechanical properties.
- EIS conductivity versus RH/T.
- Stability after soaking, humidity cycling, or Fenton test.
- MEA performance when available.

## Stage 5: Writing And Figures

Goal: turn the project into a manuscript-level argument.

Figure plan:

- Figure 1: research problem and design logic.
- Figure 2: synthesis and membrane architecture.
- Figure 3: structural/morphology validation.
- Figure 4: proton transport and stability metrics.
- Figure 5: fuel-cell performance and mechanism model.

## Current Next Actions

1. Extract 10 core papers into `literature_matrix.md`.
2. Decide whether the first route should be PAN/PFSA/COF or PVDF/COF/ionic-liquid.
3. Build the first sample naming system.
4. Create GitHub issues for literature, experiment design, and data templates.
