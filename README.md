# The-Inference-Accelerator for Physical AI　 Ver.4.3

Integration of General Purpose Training Infrastructures with the Inference Accelerator Using Open Source Compiler Toolchains
This paper proposes an open and hardware-independent architecture for connecting large-scale AI model training in the cloud with high-performance, low-latency inference on edge SoCs incorporating Rapidus GAA and Tenstorrent technologies.

The central concept is to use open-source compiler technologies and ONNX / ONNX Runtime Execution Providers (EPs) as a logical bridge between cloud-based training infrastructures and edge inference systems.
Furthermore, the architecture emphasizes portability and long‑term maintainability by ensuring that model optimization, graph partitioning, and kernel mapping remain decoupled from any specific semiconductor vendor or proprietary software stack.
## Appendix: 
ONNX and TOSA based Portability and Rapidus / Tenstorrent Inference Architecture 　
Latest　Ver.1.4-3 Revised July 30, 2026
*****************************************************************************************************************************************
The following passage is taken from the document released in September 2025, Strategic Considerations of the Gate-All-Around (GAA) Transistor for AI Semiconductors in Software-Defined Vehicles (SDVs) and Robotic Manipulation Systems: latest revised on Dec. 04, 2025.

*****************************************************************************************************************************************
The essence of technology lies in the power to break through the wall of "proprietary", and that power comes from "standardization and openness".

This strategy demonstrates that for semiconductor companies developing RMS (Robotic Manipulation System) and SDV (Software‑Defined Vehicle) solutions, providing APIs or SDKs that allow AI developers involved in RMS and SDV to freely select and integrate sensors constitutes an effective countermeasure against proprietary approaches.

Although abstraction layers such as APIs and SDKs do not lose direct compatibility with cutting‑edge manufacturing process nodes like 3nm or 2nm, existing abstraction layers must be extended and adjusted accordingly.

＊Designs and provides an API group that abstracts the physical characteristics of GAA semiconductors.

＊Designs an SDK that allows flexible combination of sensor groups and effective utilization of the API group.

Through this structure, companies aiming to advance RMSs and SDVs can:
1. effectively utilize the accurate abstraction of cutting‑edge semiconductor physical characteristics and the definition of control boundaries such as power efficiency.
2. freely select sensors optimal for RMS and SDV users.

