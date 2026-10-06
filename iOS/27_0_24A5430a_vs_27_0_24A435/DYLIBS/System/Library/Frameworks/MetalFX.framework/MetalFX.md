## MetalFX

> `/System/Library/Frameworks/MetalFX.framework/MetalFX`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f614` | `0x7f5f4` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc16c` | `0xc170` | **`+0x4`** |

### Other Changes

```text
Functions:
~ __Z30sBBRNet_MLP_GenerateDescriptorPU19objcproto9MTLDevice11objc_objectP6NSDatatttt : 1228 -> 1248
~ __ZN12FrameGenImplI10MFXDevice3EC2ERS0_PU21objcproto10MTLLibrary11objc_objectyyyy14MTLPixelFormatS5_bbb : 3776 -> 3724
~ __ZN12FrameGenImplI10MFXDevice3E8encodeToERS0_PU27objcproto16MTLCommandBuffer11objc_objectRK14FrameGenParams : 5120 -> 5128
~ -[tBBRNet setupModelWithLibrary:] : 5532 -> 5548
~ -[Conv1x1FusedBilinear createBuffers] : 704 -> 720
~ __ZN3mfx7weights12toBlockMajorIDhEEP6NSDataS3_tttt : 372 -> 376
~ __ZN3mfx7weights12toBlockMajorIhEEP6NSDataS3_tttt : 376 -> 380
~ __ZN12FrameGenImplI10MFXDevice4E8encodeToERS0_PU28objcproto17MTL4CommandBuffer11objc_objectRK14FrameGenParams : 5196 -> 5200
~ __ZN12FrameGenImplI10MFXDevice4EC2ERS0_PU21objcproto10MTLLibrary11objc_objectyyyy14MTLPixelFormatS5_bbb : 3844 -> 3792
```
