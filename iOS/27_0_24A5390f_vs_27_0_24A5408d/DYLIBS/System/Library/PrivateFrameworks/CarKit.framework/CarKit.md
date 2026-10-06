## CarKit

> `/System/Library/PrivateFrameworks/CarKit.framework/CarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61a40` | `0x61d18` | **`+0x2d8`** |
| `__TEXT.__objc_methlist` | `0x632c` | `0x6354` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x5c40` | `0x5c60` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x102d8` | `0x102b8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1bd0` | `0x1be0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x36f8` | `0x36f0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x730` | `0x72c` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-797.0.0.0.0
+799.2.0.0.0

-  Functions: 3041
-  Symbols:   4737
-  CStrings:  1418
+  Functions: 3044
+  Symbols:   4739
+  CStrings:  1419
Symbols:
+ -[CRSubtitleStyle debugDescription]
+ -[CRSubtitleStyle description]
+ -[CRSubtitleStyle hash]
+ -[CRSubtitleStyle isEqual:]
+ -[CRVehicle(FeatureSupport) supportsAmbientLightSync]
- -[CRSubtitleStyle cornerRadius]
- -[CRSubtitleStyle setCornerRadius:]
- _OBJC_IVAR_$_CRSubtitleStyle._cornerRadius
CStrings:
+ "%@ %@"
```
