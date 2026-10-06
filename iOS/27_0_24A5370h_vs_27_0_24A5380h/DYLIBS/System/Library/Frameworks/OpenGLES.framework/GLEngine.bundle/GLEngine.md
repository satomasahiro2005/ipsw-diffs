## GLEngine

> `/System/Library/Frameworks/OpenGLES.framework/GLEngine.bundle/GLEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc0498` | `0xc04b4` | **`+0x1c`** |

### Other Changes

```diff

-24.0.1.0.0
+24.0.2.0.0
Functions:
~ _gleGetState : 9492 -> 9496
~ _glGetString_Exec : 1100 -> 1108
~ _glDeleteTextures_Exec : 736 -> 752
~ _glDepthRangeArrayv_Core : 556 -> 540
~ _glScissorArrayv_Core : 388 -> 376
~ _glCopyTextureLevels_Exec : 832 -> 856
~ _gleUpdateFragmentStateProgram : 4104 -> 4092
~ _gleFeedbackLinesPtr : 308 -> 316
~ _gleFramebufferTexture : 836 -> 868
~ _gleFillBitmap : 476 -> 432
~ _gleUpdateCurrentProgramState : 1688 -> 1696
~ _gleGenerateEmptyMipmaps : 1592 -> 1616
~ _gleGenerateMipmapData : 28340 -> 28388
~ _gleLLVMVecPrimLineRender : 4720 -> 4700
~ _gleLLVMVecPrimMultiRender : 8652 -> 8600
~ _gleLLVMVecPrimPolyRender : 3732 -> 3744
```
