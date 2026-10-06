## Recon3D

> `/System/Library/PrivateFrameworks/Recon3D.framework/Recon3D`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172b0c4` | `0x171ef90` | **`-0xc134`** |
| `__TEXT.__eh_frame` | `0x125c` | `0xb34` | **`-0x728`** |
| `__TEXT.__gcc_except_tab` | `0xed800` | `0xed98c` | **`+0x18c`** |
| `__TEXT.__unwind_info` | `0x37320` | `0x37220` | **`-0x100`** |
| `__TEXT.__cstring` | `0x4d3ff` | `0x4d48f` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x60a98` | `0x60aa8` | **`+0x10`** |
| `__TEXT.__const` | `0x1135e0` | `0x1135f0` | **`+0x10`** |

### Other Changes

```diff

-9.26.5.12.6
+9.26.6.1.0

-  Functions: 38095
-  Symbols:   1890
-  CStrings:  6729
+  Functions: 38096
+  Symbols:   1892
+  CStrings:  6733
Symbols:
+ _CV3DReconPrivacyHandlerVisibleMeshUUIDs
+ _CV3DReconPrivacyHandlerVisiblePlaneUUIDs
CStrings:
+ "No registered client for the given Client ID"
+ "config.metal_device should not be null."
+ "created device should not be null."
+ "device.internal() != nullptr"
```
