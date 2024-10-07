# fpsPrediction
these two notebooks are made from the dataset on kaggle "FPS Benchmark" by Ulrik Thyge Pedersen

I had performed linear regression on this dataset and after plotting the predicted value and actual values on a graph I had realised the data had a polynomial relationship and after performing polynomial regression the R^2 had increased

R^2 with Linear Regression: 0.94
R^2 with Polynomial Regression: 0.99

Dataset: https://www.kaggle.com/datasets/ulrikthygepedersen/fps-benchmark

A brief description of each feature:

1. **CpuName**: Name or model identifier of the CPU.
2. **CpuNumberOfCores**: Total number of physical cores in the CPU.
3. **CpuNumberOfThreads**: Total number of threads supported by the CPU.
4. **CpuBaseClock**: Base clock speed of the CPU in GHz.
5. **CpuCacheL1**: Size of the Level 1 (L1) cache in kilobytes.
6. **CpuCacheL2**: Size of the Level 2 (L2) cache in kilobytes.
7. **CpuCacheL3**: Size of the Level 3 (L3) cache in megabytes.
8. **CpuDieSize**: Physical size of the CPU die in mm².
9. **CpuFrequency**: Operational frequency of the CPU in GHz.
10. **CpuMultiplier**: CPU's clock multiplier factor.
11. **CpuMultiplierUnlocked**: Indicates if the CPU multiplier is unlocked (1 = unlocked, 0 = locked).
12. **CpuProcessSize**: Size of the transistors in nanometers.
13. **CpuTDP**: Thermal Design Power of the CPU in watts.
14. **CpuNumberOfTransistors**: Total number of transistors on the CPU.
15. **CpuTurboClock**: Maximum turbo clock speed of the CPU in GHz.
16. **GpuName**: Name or model identifier of the GPU.
17. **GpuArchitecture**: GPU architecture type (e.g., Turing, Pascal).
18. **GpuBandwidth**: Memory bandwidth of the GPU in GB/s.
19. **GpuBaseClock**: Base clock speed of the GPU in MHz.
20. **GpuBoostClock**: Boost clock speed of the GPU in MHz.
21. **GpuBus.interface**: GPU's bus interface type (e.g., PCIe).
22. **GpuNumberOfComputeUnits**: Number of compute units in the GPU.
23. **GpuDieSize**: Physical size of the GPU die in mm².
24. **GpuDirectX**: Version of DirectX supported by the GPU.
25. **GpuNumberOfExecutionUnits**: Total number of execution units in the GPU.
26. **GpuFP32Performance**: FP32 floating-point performance of the GPU in TFLOPS.
27. **GpuMemoryBus**: Width of the GPU memory bus in bits.
28. **GpuMemorySize**: Total amount of GPU memory in GB.
29. **GpuMemoryType**: Type of memory used in the GPU (e.g., GDDR6).
30. **GpuOpenCL**: Version of OpenCL supported by the GPU.
31. **GpuOpenGL**: Version of OpenGL supported by the GPU.
32. **GpuPixelRate**: Pixel fill rate of the GPU in GP/s.
33. **GpuProcessSize**: Size of the GPU transistors in nanometers.
34. **GpuNumberOfROPs**: Number of Render Output Units (ROPs) in the GPU.
35. **GpuShaderModel**: Version of Shader Model supported by the GPU.
36. **GpuNumberOfShadingUnits**: Total number of shading units in the GPU.
37. **GpuNumberOfTMUs**: Number of Texture Mapping Units (TMUs) in the GPU.
38. **GpuTextureRate**: Texture fill rate of the GPU in GT/s.
39. **GpuNumberOfTransistors**: Total number of transistors on the GPU.
40. **GpuVulkan**: Version of Vulkan supported by the GPU.
41. **GameName**: Name of the game being benchmarked.
42. **GameResolution**: Resolution at which the game is tested.
43. **GameSetting**: Game graphical setting (e.g., low, medium, high).
44. **FPS**: Frames per second achieved during gameplay.
