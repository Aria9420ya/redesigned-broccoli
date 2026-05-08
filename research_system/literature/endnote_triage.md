# EndNote Triage

Last updated: 2026-05-08

## Source

EndNote 2025 local library: `我的 EndNote 个人图书馆.enl`

Visible groups:

- `近五年合在一起`: 390 references.
- `近五年COFs and electrospinning`: 49 references.
- `近五年COFs and fuel cell`: 296 references.
- `近五年COFs and proton exchange membrane`: 145 references.
- `综述`: 58 references.
- `COF静电关键词1`: 67 references visible in current EndNote window.

## Important Limitation

This file is a triage layer, not verified evidence. Entries from EndNote visibility alone must be treated as `EndNote-visible` until checked against DOI/publisher/full text and registered in `evidence_register.md`.

## Immediate A-Candidates For Review/Paper

| Priority | Title | Year | Journal | Why it matters | Evidence status | Next action |
|---|---|---:|---|---|---|---|
| A1 | Synergistic rigid-flexible COF-based composite membranes for enhanced proton conductivity and mechanical strength | 2026 | Journal of Membrane Science | Direct PEM article with TpPa-SO3H/SPVA rigid-flexible design; strong conductivity/mechanics/fuel-cell relevance | Verified-primary from ScienceDirect search; DOI 10.1016/j.memsci.2026.125213 | Add to literature matrix, evidence register, and paper note |
| A1 | Water-Retentive Covalent Organic Framework Membranes for Efficient Proton Conduction in PEMFCs | 2025 | Advanced Functional Materials | Direct PEMFC/COF membrane paper; low-RH water retention is central to review logic | Verified-index from Nature Index/Colab; DOI 10.1002/adfm.202520568 | Verify publisher page/full text, then add |
| A1 | Triazine-rich covalent organic framework composited proton exchange membranes for flexible operating temperature and enhanced long-term stability fuel cells | 2025 | Journal of Power Sources | Direct HT-PEMFC COF composite paper; OPBI/PA/high-temperature route | Verified-primary from ScienceDirect; DOI 10.1016/j.jpowsour.2025.236351 | Add to high-temperature route section |
| A1 | Highly flexible SCOF proton exchange membrane reinforced with PTFE to enhance fuel cell power density | 2025 | Journal of Membrane Science | Already in knowledge base; frontier supported SCOF PEM benchmark | Verified-primary | Keep as performance ceiling |
| A1 | In Situ Growth of COF on PAN Nanofibers to Improve Proton Conductivity and Dimensional Stability in Proton Exchange Membranes | 2022 | Energies | Already in knowledge base; closest COF + electrospinning + PFSA route | Verified-primary | Keep as first-route template |
| A2 | Study on the properties of hybrid COF connected three-dimensional nanofiber structures in proton exchange membranes | 2024 | International Journal of Hydrogen Energy | Very relevant to nanofiber/PEM route; likely close to thesis topic | EndNote-visible | Verify DOI/publisher and extract |
| A2 | Covalent organic frameworks with flexible side chains in hybrid PEMs enable highly efficient proton conductivity | 2024 | Materials Horizons | Direct hybrid PEM mechanism; flexible side-chain strategy | EndNote-visible | Verify DOI/publisher and extract |
| A2 | Solution-processable ionic covalent organic framework nanosheets for robust mixed matrix membranes with enhanced proton conductivity | 2025 | Journal of Power Sources | Direct mixed-matrix PEM route; solution-processable iCOF nanosheets | EndNote-visible | Verify DOI/publisher and extract |
| A2 | Synthesis of a Nitrile- and Ether-Rich Covalent Organic Framework as a Filler and Its Application for Proton Exchange Membranes | 2025 | ACS Applied Materials & Interfaces | Direct COF filler/PEM paper; functional-group design | EndNote-visible | Verify DOI/publisher and extract |
| A2 | Free-Standing Polymer Covalent Organic Framework Membrane with High Proton Conductivity and Structure Stability | 2023 | ACS Applied Polymer Materials | Free-standing polymer-COF membrane; useful for self-supporting route comparison | EndNote-visible | Verify DOI/publisher and extract |
| A2 | COF hybrid membrane with high phosphoric acid retention capacity for electrochemical hydrogen compression | 2025 | Journal of Membrane Science | Adjacent to PEM/EHC and acid-retention strategy | EndNote-visible | Verify and decide review placement |

## Review Articles To Prioritize

| Priority | Title | Year | Journal | Use |
|---|---|---:|---|---|
| R1 | Unlocking the proton highway: Covalent organic framework composite membranes for fuel cells | 2026 | Fuel | Already in knowledge base; taxonomy/gap framework |
| R1 | Recent Advances in the Application of Covalent Organic Framework-Based Ionic Conductors in Proton Exchange Membrane Fuel Cells | 2025 | Chemistry - A European Journal | Likely strong review backbone for PEMFC-specific COF ionic conductors |
| R1 | Next-generation fuel cell technologies empowered by covalent organic frameworks-based materials: A review on emerging potential of COFs for functional membranes and catalytic advancements | 2026 | Coordination Chemistry Reviews | Broad fuel-cell COF review; useful for introduction and scope |
| R2 | Covalent Organic Frameworks for Proton Exchange Membranes | 2024 | Progress in Chemistry | Chinese/field review; useful for terminology and Chinese writing |
| R2 | Emerging Covalent Organic Frameworks for Efficient Proton Conductors | 2023 | Industrial & Engineering Chemistry Research | Proton-conduction review; useful for mechanism section |
| R2 | Recent advancements of covalent organic frameworks (COFs) as proton conductors under anhydrous conditions for fuel cell applications | 2023 | RSC Advances | High-temperature/anhydrous background |
| R2 | Regulation of proton conduction pathways in covalent organic frameworks | 2026 | Coordination Chemistry Reviews | Mechanism-oriented review lead |

## Likely Exclude Or Background Only

These may be useful for membrane science background but are not central to COF/PEMFC review unless the thesis scope includes ion transport broadly:

- COF membranes for desalination, nanofiltration, oil-water separation, osmotic power, blue energy, salinity-gradient energy.
- COF membranes for Li-metal electrodes, vanadium redox flow batteries, rare-earth ion separation.
- MOF-only PEM or nanofiber papers unless used as contrast/background.

## Best Next Step

Export the EndNote group as RIS/BibTeX/XML and let Codex parse all 390 records. Recommended export:

1. Select group `近五年合在一起` or the more focused group.
2. EndNote: `File` -> `Export...`.
3. Format: `RefMan (RIS)` or `BibTeX`; include abstracts if available.
4. Save into this repository, e.g. `research_system/literature/endnote_exports/endnote_390.ris`.
5. Ask: `按 PROMPTS.md 的 Find Literature/Compare Papers 模式，筛选这个 EndNote 导出文件，生成 A/B/C 等级和综述候选表。`
