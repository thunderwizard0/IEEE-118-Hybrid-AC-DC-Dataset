Improved IEEE 118-bus hybrid AC/DC power system data
改进的 IEEE 118 节点交直流混合配电网数据集
# Improved IEEE 118-Bus Hybrid AC/DC Distribution Network Dataset

本数据集为配电网弹性评估与两阶段主动防御（Two-Stage Active Defense）研究提供底层网络参数。
基于标准 IEEE 118 节点系统进行了交直流混合架构扩展。

## 数据文件说明 (`IEEE_118_hybrid_AC_DC_data.json`)
本 JSON 文件包含了完整的研究拓扑与设备参数，主要字段包括：
- `ac_buses` / `ac_branches`: 交流侧节点与支路参数（含线路阻抗、容量极限）
- `dc_buses` / `dc_branches`: 直流侧扩展节点与直流真线参数
- `vsc`: 柔性多状态开关 (VSC) 参数及容量
- `sop`: 智能软开关 (SOP) 互联参数
- `dg` / `ess`: 分布式电源 (DG) 及储能系统 (ESS) 的接入位置、容量与充放电约束
- `load_priority`: 负荷分级优先度 (VIP, Essential, Normal) 及对应的失负荷价值 (VOLL)

## 引用 (Citation)
如果您在研究中使用了本数据集，请引用相关论文（见后文）。
