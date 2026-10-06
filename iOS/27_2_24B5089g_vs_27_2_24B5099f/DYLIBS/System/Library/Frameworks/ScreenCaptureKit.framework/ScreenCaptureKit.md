## ScreenCaptureKit

> `/System/Library/Frameworks/ScreenCaptureKit.framework/ScreenCaptureKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3706c` | `0x370dc` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x2600` | `0x2620` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5cd8` | `0x5cf8` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x8b50` | `0x8b60` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x386c` | `0x387c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2308` | `0x2310` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd10` | `0xd18` | **`+0x8`** |

### Other Changes

```diff

-765.11.1.0.0
+765.14.1.0.0

-  Functions: 1453
-  Symbols:   2573
-  CStrings:  870
+  Functions: 1454
+  Symbols:   2574
+  CStrings:  871
Symbols:
+ -[RPFeatureFlagUtility edgeLightDevOverrideActive]
+ ___block_descriptor_40_e8_32w_e232_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12lw32l8
- ___block_descriptor_40_e8_32w_e229_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12lw32l8
CStrings:
+ "RPEnableEdgeLightDev"
+ "v20@?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12"
- "v20@?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12"
```
