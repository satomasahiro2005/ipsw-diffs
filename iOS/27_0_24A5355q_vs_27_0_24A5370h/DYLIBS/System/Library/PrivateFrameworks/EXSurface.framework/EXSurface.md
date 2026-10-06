## EXSurface

> `/System/Library/PrivateFrameworks/EXSurface.framework/EXSurface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42c4` | `0x42fc` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x2d8` | `0x2d0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x1e8` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   516
+  Symbols:   515
Symbols:
- _objc_release_x9
Functions:
~ -[EXSurfacePlaneArray initWithEXSurfacePriv:] : 204 -> 200
~ -[EXSurfacePlaneArray dealloc] : 100 -> 112
~ -[EXSurfacePlaneDescriptorArray init] : 116 -> 128
~ -[EXSurfacePlaneDescriptorArray dealloc] : 100 -> 112
~ -[EXSurfacePrivImageDescArray initWithDescriptor:] : 248 -> 244
~ -[EXSurfacePrivImageDescArray initWithPlaneCount:] : 140 -> 152
~ _EXSurfaceRangeAllocatorGetFreeSize : 64 -> 68
~ _EXSurfaceRangeAllocatorGetMaxFreeSize : 104 -> 116
```
