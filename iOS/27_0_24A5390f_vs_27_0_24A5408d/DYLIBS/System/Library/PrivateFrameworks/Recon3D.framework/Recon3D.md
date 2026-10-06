## Recon3D

> `/System/Library/PrivateFrameworks/Recon3D.framework/Recon3D`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17059b4` | `0x170b36c` | **`+0x59b8`** |
| `__TEXT.__const` | `0x112110` | `0x1127b0` | **`+0x6a0`** |
| `__TEXT.__gcc_except_tab` | `0xebcf8` | `0xec22c` | **`+0x534`** |
| `__AUTH_CONST.__const` | `0x609d0` | `0x60da8` | **`+0x3d8`** |
| `__TEXT.__unwind_info` | `0x36f90` | `0x37188` | **`+0x1f8`** |
| `__TEXT.__cstring` | `0x4d400` | `0x4d4f8` | **`+0xf8`** |
| `__DATA.__common` | `0x848` | `0x7f8` | **`-0x50`** |
| `__DATA.__data` | `0x57c0` | `0x57e0` | **`+0x20`** |

### Other Changes

```diff

-9.26.6.16.1
+9.26.7.9.0

-  Functions: 38035
+  Functions: 38104

-  CStrings:  6734
+  CStrings:  6737
CStrings:
+ "Chunk position collides with LRU sentinel key."
+ "material_histogram_.Empty() || material_histogram_.Size() == Size()"
+ "position4d != kLruInvalidKey"
+ "semantic_histogram_.Empty() || semantic_histogram_.Size() == Size()"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::cv::CVImageBuffer<img::Format::Two16u>]"
- "material_histogram_.Size() == Size()"
- "semantic_histogram_.Size() == Size()"
```
