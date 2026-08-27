Please check out our production-ready **Kernel Library**: [**ffpa-attn**](https://github.com/xlite-dev/ffpa-attn) - Fast and Memory-Efficient Exact Attention (**BF16/FP16/FP8/FP4**) for Large Headdim, **1.5x~15x**🔥🔥 speedup over standard PyTorch SDPA. 
<div align='center'>
  <img src='https://github.com/xlite-dev/ffpa-attn/raw/main/docs/assets/perf/ffpa_speedup_cutedsl_nvidia-h20z_B1_H32_N8192_D512_T.png' width='200px'>
  <img src='https://github.com/xlite-dev/ffpa-attn/raw/main/docs/assets/perf/ffpa_speedup_cutedsl_nvidia-h20z_B1_H32_N16384_D512_T.png' width='200px'>
  <img src='https://github.com/xlite-dev/ffpa-attn/raw/main/docs/assets/perf/ffpa_speedup_cutedsl_nvidia-b200_B1_H32_N8192_D512_T.png' width='200px'>
  <img src='https://github.com/xlite-dev/ffpa-attn/raw/main/docs/assets/perf/ffpa_speedup_cutedsl_nvidia-b200_B1_H32_N16384_D512_T.png' width='200px'><br>
  <p><i><b>BF16 Attention</b> for Large Headdim: FFPA vs SDPA (FWD/BWD) across NVIDIA H200 and B200, 6x-15x↑. </i></p>
  <img src="https://github.com/user-attachments/assets/1ec7d63f-711b-479d-b352-7ac7b7bff5a8" width='815px'/><br>
  <p><i><b>FP4 Attention</b> for D=128: FFPA vs SageAttention-3 (FWD) on NVIDIA RTX PRO 6000. </i></p>
</div>
