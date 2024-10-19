# IFFuse
The code will be released soon

# Abstract
Multi-modal image fusion struggles to produce high-quality results under suboptimal illumination. The single coupling approach of current methods between low-light enhancement and image fusion tasks restricts their capacity to manage unpredictable low-light environments. To overcome these limitations, this paper proposes an infrared and visible image fusion network based on interactive illumination enhancement and fusion scene fidelity constraints, named IFFuse. First, the proposed shared illumination enhancement network (SIE-Net) focuses on deeply exploring illumination factors in low-light visible modalities. Subsequently, the scene recovery network (SR-Net) leverages the enhanced results from SIE-Net and integrates them with the advantageous features of infrared images. This one-pass imaging process improves visibility and color expression in low-light environments while ensuring efficient multimodal data integration. Benefiting from an illumination color estimator, the fusion priors feed back into the enhancement process, compelling
SIE-Net to generate enhanced results with significant contrast and vivid colors. Extensive experiments demonstrate that our IFFuse not only produces outstanding fusion results but also enhances high-level visual tasks.

# Experiments
\begin{figure}
    \centering
    \includegraphics[width=0.8\textwidth]{E:\AAAI-Data\Ar\LLVIP_1.pdf}
\end{figure}
