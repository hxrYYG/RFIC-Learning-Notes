# RFIC Learning Notes (RFIC 学习笔记)

这里记录了基于 **Cadence IC618** 和 **TSMC 180nm RF** 工艺库进行射频电路设计时的仿真踩坑记录、原理分析及心得体会。

---

## 📂 目录 (Table of Contents)

### 🛠️ 仿真报错解决 (Troubleshooting)

- **[【踩坑】解决 TSMC18RF 仿真 ind_sym 电感报错 (ERROR SFE-23)](docs/01-tsmc18rf-sfe23-error.md)**
  > **内容摘要**：详细记录了在 Cadence 环境下，因 Model Library Setup 路径配置不当导致实际电感 `ind_sym` 报 `SFE-23` 未定义错误的成因。文中提供了重新关联 `rf018.scs` 文件及处理 Section 冲突的完整步骤。

---

### 📝 电路设计笔记 (Circuit Design)

- **LNA 低噪声放大器设计** (待更新...)
- **VCO 压控振荡器仿真** (待更新...)

---

## 🏷️ 工艺与工具 (Tech Stack)
- **EDA 工具**: Cadence Virtuoso IC618 / Spectre RF
- **工艺节点**: TSMC 180nm RF (tsmc18rf)

`markdown
![图片描述](../images/tsmc-sfe23/p1.png)