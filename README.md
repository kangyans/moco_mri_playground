## MoCoMRI playground
**Notice:** No new information in this repo except the codes from [ismrm_moco_workshop](https://github.com/lab-midas/ismrm-moco-workshop). The main purpose of this repo is self-learning.

### Notes

- In [ismrm_moco_workshop](): ```bart nufft -a traj kspace_rad imgreco``` should be ```bart nufft -i traj kspace_rad imgreco```
- [sigpy](https://github.com/mikgroup/sigpy-mri-tutorial) was used in this repo instead of [gpuNUFFT](https://github.com/andyschwarzl/gpuNUFFT) (Personally, *sigpy* is more user-friendly 😄)
- Rewrite the **simulate_motion_radial** function with *sigpy* module
