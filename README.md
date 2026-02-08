# RFIC Learning Notes (RFIC 学习笔记)

这里记录了基于 **Cadence IC618** 和 **TSMC 180nm RF** 工艺库进行射频电路设计时的仿真踩坑记录、原理分析及心得体会。

---

## 📂 目录 (Table of Contents)

### 🛠️ 仿真报错解决 (Troubleshooting)

- **[【踩坑】解决 TSMC18RF 仿真 ind_sym 电感报错 (ERROR SFE-23)](docs/01-tsmc18rf-sfe23-error.md)**
  > **内容摘要**：记录了在 Cadence 环境下，因 Model Library Setup 路径配置不当导致实际电感 `ind_sym` 报 `SFE-23` 未定义错误的成因。文中提供了重新关联 `rf018.scs` 文件及处理 Section 冲突的完整步骤。

---
