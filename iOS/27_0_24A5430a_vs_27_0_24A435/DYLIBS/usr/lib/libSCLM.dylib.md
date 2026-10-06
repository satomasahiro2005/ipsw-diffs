## libSCLM.dylib

> `/usr/lib/libSCLM.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x125f4` | `0x12630` | **`+0x3c`** |
| `__TEXT.__const` | `0x34c` | `0x358` | **`+0xc`** |
| `__TEXT.__cstring` | `0x914` | `0x916` | **`+0x2`** |

### Other Changes

```diff
Functions:
~ __ZN4SLAM4Impl23PerformScriptWithResultEy : 892 -> 928
~ __ZN4SLAM4Impl19GetPlatformCategoryEv : 380 -> 404
CStrings:
+ "UNDEFINED"
- "DEFINED"
```
