# OpenUSD Hydra Contributions

Autodesk is extending the Hydra framework inside OpenUSD to add new capabilities. Hydra (prefix "Hd") is the OpenUSD framework that "enables the communication between multiple scene graphs and multiple renderers." [This presentation from SIGGRAPH 2019](https://openusd.org/files/Siggraph2019_Hydra.pdf) explains more about Hydra.

This repository has links to the proposals, branches, and pull requests for Autodesk's Hydra contributions. As these are contributions to OpenUSD, the code is intended for the OpenUSD repository and is not stored here. While work is in progress, the code for these and other OpenUSD contributions from Autodesk can be found in [the Autodesk fork of OpenUSD](https://git.autodesk.com/autodesk-forks/USD).

Also listed below are other Autodesk projects related to Hydra, but that are separate from OpenUSD itself.

All work is shared under [the same license](https://github.com/PixarAnimationStudios/OpenUSD/blob/release/LICENSE.txt) as OpenUSD.

## OpenUSD Projects

### Hgi Vulkan Backend Stabilization

[Proposal](https://github.com/PixarAnimationStudios/OpenUSD-proposals/pull/15) and [Branch](https://github.com/PixarAnimationStudios/OpenUSD/tree/feature-hgi-vulkan) and [Pull Request](https://github.com/PixarAnimationStudios/OpenUSD/pull/2553) (original)

### Hgi Vulkan Backend on Android

[Proposal](https://github.com/PixarAnimationStudios/OpenUSD-proposals/pull/17)

### Hgi WebGPU Backend

[Proposal](https://github.com/PixarAnimationStudios/OpenUSD-proposals/pull/14) and [Branch](https://github.com/autodesk-forks/USD/tree/adsk/feature/webgpu)

### Hgi DirectX 12 Backend

[Proposal](https://github.com/PixarAnimationStudios/OpenUSD-proposals/pull/12) and [Branch](https://github.com/autodesk-forks/USD/tree/adsk/feature/DirectX12Hgi) and [Pull Request](https://github.com/PixarAnimationStudios/OpenUSD/pull/2508)

### Hgi Ray Tracing with Vulkan Implementation

[Proposal](https://github.com/PixarAnimationStudios/OpenUSD-proposals/pull/21) and [Branch](https://github.com/autodesk-forks/USD/tree/adsk/feature/hgiraytracing)

### Text

[Proposal](https://github.com/PixarAnimationStudios/OpenUSD-proposals/tree/main/proposals/text) (plus [latest proposed update](https://github.com/PixarAnimationStudios/OpenUSD-proposals/pull/62)) and [Branch](https://github.com/autodesk-forks/USD/tree/adsk/feature/text) and [Pull Request](https://github.com/PixarAnimationStudios/OpenUSD/pull/3002)

### Line Style

[Proposal](https://github.com/PixarAnimationStudios/OpenUSD-proposals/tree/main/proposals/LineStyle) (plus [latest proposed update](https://github.com/PixarAnimationStudios/OpenUSD-proposals/pull/60)) and [Branch](https://github.com/autodesk-forks/USD/tree/adsk/feature/LineStyle) and [Pull Request](https://github.com/PixarAnimationStudios/OpenUSD/pull/3151)

### Billboards

[Proposal](https://github.com/PixarAnimationStudios/OpenUSD-proposals/pull/39)

## Related Projects

### [Arnold USD](https://github.com/Autodesk/arnold-usd)

A set of components and tools to use the Arnold renderer with OpenUSD, including a Hydra render delegate.

### [Aurora](https://github.com/Autodesk/Aurora)

A real-time GPU path-tracing renderer with a Hydra render delegate, intended for viewport display.

### [Hydra for Maya](https://github.com/Autodesk/maya-hydra)

A Maya plug-in that replaces the main Maya viewport with a Hydra viewer.
