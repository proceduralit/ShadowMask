# ShadowMask

Calculating shadow area based on the MVP matrices in Shader and Niagara

![Alt text](./doc_res/ParagonSample.jpg "")

## Shadow Parameters
Sun location parameters are in the BP_ShadowCaster > Sun category.

![Alt text](./doc_res/SunLocation.jpg "")

Shadow parameters for the shaders are accessible in Mats > MPC_ShadowParameters

![Alt text](./doc_res/ShadowParameters.jpg "")

## Niagara Particles

![Alt text](./doc_res/Niagara.jpg "")

Niagara particles are spawned in the screenspace and then projected on the surfaces with CustomDepth Stencil Value 1.0

![Alt text](./doc_res/CustomStencil.jpg "")

### Textures that I've used in this project

![Alt text](./doc_res/dls.jpg "")

[Ghost Face](https://www.cleanpng.com/png-ghostface-paper-sticker-wall-decal-skull-cartoon-f-270164/)

[Clover Patches On Grass](https://quixel.com/megascans/home?search=clover&search=patches&search=on&search=grass&assetId=sgmkajak)

## Videos
[![Test](https://img.youtube.com/vi/QE0BcVpHjO8/hqdefault.jpg)](https://www.youtube.com/embed/QE0BcVpHjO8)
[![Final](https://img.youtube.com/vi/XbfmlwDumGg/hqdefault.jpg)](https://www.youtube.com/embed/XbfmlwDumGg)
