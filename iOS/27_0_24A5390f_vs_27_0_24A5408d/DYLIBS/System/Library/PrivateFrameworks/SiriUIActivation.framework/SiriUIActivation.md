## SiriUIActivation

> `/System/Library/PrivateFrameworks/SiriUIActivation.framework/SiriUIActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f288` | `0x2f45c` | **`+0x1d4`** |
| `__TEXT.__oslogstring` | `0x4d6b` | `0x4e2b` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x4c2b` | `0x4c5b` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xbe0` | `0xc08` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x26d0` | `0x26e8` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x2928` | `0x2938` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fd8` | `0x1fe8` | **`+0x10`** |

### Other Changes

```diff

-3600.55.30.0.0
+3600.55.37.11.2

-  Functions: 1073
-  Symbols:   1658
-  CStrings:  621
+  Functions: 1077
+  Symbols:   1659
+  CStrings:  623
Symbols:
+ ___block_descriptor_48_e8_32s_e5_v8?0ls32l8
CStrings:
+ "%s #activation dismissal failed with PresentationManagerError; resetting Siri to Off (not Active) to avoid stranding in SASRequestStateActive."
+ "SiriPresentationController+SUIC.prewarmOrbView"
```
