# Paper Note: Hybrid COF Connected 3D Nanofiber PEM

## Citation

Study on the properties of hybrid COF connected three-dimensional nanofiber structures in proton exchange membranes. *International Journal of Hydrogen Energy*, 2024, 71, 334-344.

Source: https://doi.org/10.1016/j.ijhydene.2024.02.343

Evidence level: Verified-primary from local full text and DOI metadata.

## Why This Is A-Core

这篇文献直接对应第四章的“网络桥联型”结构：COF 不是简单分散填料，而是在静电纺丝 PAN/Tp 纤维表面原位合成，并通过小纤维状 COF 结构连接纤维，形成更连续的三维网络。它特别适合支撑“静电纺丝结构可以被 COF 功能化为纵向质子传导网络”这一观点。

## Material System

| Field | Value |
|---|---|
| COF/framework | TpPa-(SO3H-Py) hybrid COF |
| COF functional groups | Pa-SO3H provides sulfonic acid sites; Pa-Py introduces pyridine sites for acid-base interaction |
| Electrospun scaffold | PAN/Tp nanofiber membrane, named PTNF |
| Polymer matrix | PFSA |
| Membrane structure | PFSA@PTNF/TpPa-(SO3H:Py) sandwich composite membrane |
| Optimized ratio | Pa-SO3H:Pa-Py = 10:10 for the reported balanced performance |

## Fabrication Route

1. 1,3,5-tricarbonylresorcinol (Tp), PAN and DMF were used to prepare PAN/Tp spinning solution.
2. PAN/Tp nanofiber membrane was obtained by electrospinning.
3. Pa-SO3H and Pa-Py were introduced in different ratios for in situ COF synthesis on the PTNF surface.
4. The COF-modified fiber membrane was embedded in PFSA solution to form a sandwich composite membrane.

## Verified Metrics

| Metric | Value | Condition | Source location |
|---|---|---|---|
| Longitudinal proton conductivity | 96.67 mS/cm for PFSA@PTNF/TpPa-(SO3H:Py=10:10) | 80 C, 95% RH | Full text, results/discussion and conclusion |
| Reference longitudinal conductivity | 7.45 mS/cm for PFSA | 80 C, 95% RH | Full text, longitudinal conductivity section |
| Membrane thickness | PFSA 165 ± 5 um; PFSA@PTNF 195 ± 5 um; COF hybrid composite membranes 255 ± 5 um | Cross-section SEM/table | Full text, Table 1 |
| Tensile strength | Up to 23.3 MPa | Composite membrane mechanical test | Full text, mechanical section and conclusion |
| Oxidative stability test | Fenton reagent at 80 C for 24 h | Membrane mass loss/morphology | Full text, method and Fig. 14 caption |
| Fuel-cell peak power density | 303 mW/cm2 for PFSA@PTNF/TpPa-(SO3H:Py=10:10); 132.49 mW/cm2 for Nafion117 | H2/O2, 75 C, 100% RH, 150 sccm | Full text, fuel-cell section |

## Mechanism Chain

PAN/Tp electrospun scaffold -> in situ hybrid COF growth -> sulfonic acid sites add proton sources -> pyridine regulates acid-base interactions and network stability -> small fiber-like COF structures connect PAN fibers -> improved longitudinal proton transport through a three-dimensional network.

## What Can Be Used In Chapter 4

- 用作“网络桥联型”的核心例子。
- 用来说明静电纺丝纤维不应只是惰性增强骨架，经过 COF 原位生长后可以参与构建连续质子通道。
- 用来和 2022 PAN/TpPa-SO3H/PFSA 对比：2022 文献强调 COF 表面功能化，2024 文献进一步强调 hybrid COF 对纤维间连接和纵向传导的贡献。

## Cautions

- 横向电导率、水吸收和溶胀的具体数值主要在图中，当前未做图像读数；正式表格中不应列未核实数字。
- 与 Nafion117 的燃料电池性能比较存在膜厚和材料体系差异，正文中不能直接写“全面优于 Nafion117”。
- 该文主要体现高湿条件下的传导增强；低湿或真正高温无水 PEM 结论不能由此推出。

## Use In Our Project

适合作为第四章 4.2.3 的核心文献。若后续设计实验，可借鉴其控制组逻辑：

- PFSA pure membrane.
- PFSA@PTNF.
- PFSA@PTNF/TpPa-SO3H.
- PFSA@PTNF/TpPa-(SO3H:Py) with different Pa-SO3H:Pa-Py ratios.
