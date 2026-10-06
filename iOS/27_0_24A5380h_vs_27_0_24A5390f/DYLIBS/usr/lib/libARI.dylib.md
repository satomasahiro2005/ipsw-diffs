## libARI.dylib

> `/usr/lib/libARI.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2067d4` | `0x206a84` | **`+0x2b0`** |
| `__DATA_CONST.__const` | `0x46698` | `0x46718` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3e32b` | `0x3e38b` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x1ab20` | `0x1ab64` | **`+0x44`** |

### Other Changes

```diff

-1636.0.0.0.0
+1638.0.0.0.0

-  CStrings:  9458
+  CStrings:  9462
Functions:
~ __ZN6AriSdk38ARI_IBICallPsLTEAttachApnConfigReq_SDKD2Ev : 1924 -> 2004
~ __ZN6AriSdk38ARI_IBICallPsLTEAttachApnConfigReq_SDK4packEPP6AriMsg : 3136 -> 3264
~ __ZN6AriSdk38ARI_IBICallPsLTEAttachApnConfigReq_SDK6unpackEv : 12116 -> 12596
CStrings:
+ "is_always_on_home1_t135"
+ "is_always_on_home2_t136"
+ "is_always_on_roam1_t137"
+ "is_always_on_roam2_t144"
```
