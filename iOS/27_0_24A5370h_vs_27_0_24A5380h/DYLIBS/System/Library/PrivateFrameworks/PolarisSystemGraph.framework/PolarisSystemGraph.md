## PolarisSystemGraph

> `/System/Library/PrivateFrameworks/PolarisSystemGraph.framework/PolarisSystemGraph`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa9b8` | `0xaa04` | **`+0x4c`** |
| `__AUTH_CONST.__objc_const` | `0x2ea8` | `0x2ed8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x12d8` | `0x1300` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x950` | `0x968` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x88` | `0x90` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd8` | `0xdc` | **`+0x4`** |

### Other Changes

```diff

-256.0.2.500.1
+256.0.3.0.0

-  Functions: 312
-  Symbols:   811
+  Functions: 315
+  Symbols:   816
Symbols:
+ +[PSSGResourceOptions optionsWithDefaultStride:supportedStrides:setupSupported:baseMSGSyncID:availability:isDynamic:]
+ -[PSSGResourceOptions initWithDefaultStride:supportedStrides:setupSupported:baseMSGSyncID:availability:isDynamic:]
+ -[PSSGResourceOptions isDynamic]
+ -[PSSGResourceOptions setIsDynamic:]
+ _OBJC_IVAR_$_PSSGResourceOptions._isDynamic
+ _objc_retain_x26
- -[PSSGResourceOptions initWithDefaultStride:supportedStrides:setupSupported:baseMSGSyncID:availability:]
```
