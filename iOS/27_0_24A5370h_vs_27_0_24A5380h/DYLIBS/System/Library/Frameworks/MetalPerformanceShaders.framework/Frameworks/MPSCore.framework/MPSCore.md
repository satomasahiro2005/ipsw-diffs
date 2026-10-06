## MPSCore

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xa0` | `0x1e0` | **`+0x140`** |
| `__DATA_DIRTY.__objc_data` | `0xf50` | `0xe10` | **`-0x140`** |
| `__TEXT.__text` | `0x96218` | `0x96204` | **`-0x14`** |
| `__AUTH_CONST.__const` | `0x5f18` | `0x5f10` | **`-0x8`** |
| `__TEXT.__cstring` | `0xa613` | `0xa611` | **`-0x2`** |

### Other Changes

```diff

-130.0.10.2.0
+130.0.14.0.0
Functions:
~ __ZN10MPSLibrary25LoadMPSDeviceSpecificInfoERK21MPSDeviceSpecificInfo : 100 -> 88
~ sub_244b15028 -> sub_24966c01c : 532 -> 524
CStrings:
+ "130.0.14"
- "130.0.10.2"
```
