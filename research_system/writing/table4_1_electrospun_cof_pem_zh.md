# 表 4.1 工作版：第四章静电纺丝/纳米纤维辅助 COF 基质子交换膜文献矩阵

说明：

这是第四章核心表格的中文工作版。所有数值必须能在 `evidence_register.md` 中找到对应证据等级。`Verified-primary` 表示已从出版商页面、DOI 页面或本地全文核对；`Verified-index` 表示来自可信索引但正式写作前仍建议回看全文；`Need full text` 表示不能作为强事实使用。

## 文献矩阵

| 等级 | 证据等级 | 文献 | 材料体系 | 结合方式 | 关键性能 | 第四章用途 | 还缺什么 |
|---|---|---|---|---|---|---|---|
| A1 | Verified-primary | Gao et al., 2024, *International Journal of Hydrogen Energy*, DOI: 10.1016/j.ijhydene.2024.10.199 | TPA-TPB Schiff-base COF / electrospun PVDF nanofibers / BmimCl or BmimPF6 / PA | 先静电纺丝 PVDF，再沿 PVDF 纳米纤维原位生长 COF，随后引入离子液体并浸渍 100 wt% PA 12 h | PVDF-COF/BmimPF6/PA：0.181 ± 0.007 S/cm at 160 C；400 h 后 1.77e-2 S/cm at 80 C、1.42e-2 S/cm at 110 C；电导测试膜厚 80-105 um；178.8 mW/cm2 at 100 C，326.5 mW/cm2 at 120 C | 4.2.1 纤维复合型/高温无水路线核心案例 | MEA 湿度、气体流量、催化剂载量仍需从全文/SI补齐；文中一处 PPD 单位疑似排版为 mW/m2，按摘要和上下文暂记 mW/cm2 |
| A1 | Verified-primary | Meng et al., 2022, *Energies*, DOI: 10.3390/en15093405 | PAN/TpPa-SO3H / PFSA | 静电纺丝 PAN，PAN 表面原位生长 TpPa-SO3H，最后嵌入 PFSA 三明治膜 | 260.81 mS/cm at 80 C/100% RH；264 h 后下降 4.7%；拉伸强度 22.6 MPa；峰值功率 392.7 mW/cm2；MEA 膜厚约 150 um | 4.2.2 表面生长型核心案例 | 低 RH/高温无水表现不足；导电测试方向需在正文中谨慎表述 |
| A1 | Verified-primary | Meng et al., 2024, *International Journal of Hydrogen Energy*, DOI: 10.1016/j.ijhydene.2024.02.343 | PAN/TpPa-(SO3H-Py) / PFSA | PAN/Tp 纤维表面原位合成 hybrid COF；COF 小纤维状结构连接 PAN 纤维，形成三维网络 | 纵向电导率 96.67 mS/cm at 80 C/95% RH，约为 PFSA 13 倍；PFSA 为 7.45 mS/cm；膜厚：PFSA 165 ± 5 um，PFSA@PTNF 195 ± 5 um，hybrid COF 复合膜 255 ± 5 um；最高拉伸强度 23.3 MPa；峰值功率 303 mW/cm2 | 4.2.3 网络桥联型核心案例 | 横向导电率、水吸收、溶胀具体数值需读图或补 SI；与 Nafion117 对比存在膜厚差异，不能直接写“全面优于” |
| A2 | Verified-primary | He et al., 2024, *International Journal of Hydrogen Energy*, DOI: 10.1016/j.ijhydene.2024.05.019 | TpBd-2SO3H COF nanosheets / sulfonated bacterial cellulose nanofiber | SBCNF 通过物理缠结和氢键连接 TpBd-2SO3H 纳米片，形成层状复合膜 | 145.7-147.5 mS/cm at 80 C/100% RH；IEC 最高 3.49 mmol/g；最高拉伸强度 88.49 MPa | 支撑“纳米纤维桥联 COF 片层”的结构逻辑，但不作为静电纺丝主证据 | 膜厚、测试方向、长期耐久、MEA 缺失；145.7/147.5 mS/cm 需在最终表中统一 |
| A2 | Verified-index | Tuning sulfonated crystalline nanochannels in aramid nanofibers-reinforced CONs membranes, 2026, DOI: 10.1016/j.ces.2025.123137 | Sulfonated CONs / aramid nanofibers | ANF 增强 CON 层间连接、致密性和机械稳定性 | 最优膜 439 mS/cm at 80 C/95% RH | 4.2.3 外延机制案例；说明一维纳米纤维桥联二维 CON/COF 通道是可推广结构策略 | 需全文核实膜厚、机械数据、MEA、长期稳定；不要作为静电纺丝证据 |
| B-support | To verify | Xie et al., 2024, *Journal of Membrane Science*, DOI: 10.1016/j.memsci.2024.123052 | Free-standing COF nanofiber membrane | COF 纳米纤维构建连续离子通道 | 钒液流电池体系，不列 PEM 电导率作直接对比 | 只作“COF 纤维化/连续通道”外延讨论 | 不是 PEMFC，正文中必须明确边界 |
| B-support | To verify | Pang et al., 2025, *Advanced Energy Materials* | Hollow sulfonated COF fiber | 静电纺丝-溶剂热形成 hollow SCOF fiber | VRFB 能量效率 81.9% at 200 mA/cm2；1000 cycles，需核 | 只作结构灵感，不写成 PEM 证据 | DOI 需补；不是 PEMFC；不要混入 PEM 性能排名 |

## 中文分析

第四章不宜简单写成“COF + electrospinning 的材料总结”。更稳妥的写法是按结构关系组织：

1. **纤维复合型/高温载体型**：COF、离子液体和 PA 被放入 PVDF 纳米纤维体系中，目标是高温、低湿或无水条件下维持质子传导。
2. **表面生长型**：COF 原位生长在静电纺丝 PAN 表面，纤维负责尺寸稳定，COF 负责补充酸性位点和亲水传导路径。
3. **网络桥联型**：hybrid COF 或纳米纤维把纤维/片层连接成三维传导网络，重点不是单个填料性能，而是传导通道的连续性。

## 需要你判断

- 如果第四章标题强调“高温 PEM”，Gao et al. 2024 应该放在本章最前面，因为它直接涉及 PA、离子液体和 100-160 C。
- 如果第四章标题强调“COF 基静电纺丝 PEM”，Meng et al. 2022 和 Meng et al. 2024 应该作为主线，因为它们最贴合 PFSA/PAN/COF 静电纺丝体系。
- A2 和 B-support 文献只能用来扩展结构逻辑，不能拿来和 PEMFC 主文献直接比性能。
