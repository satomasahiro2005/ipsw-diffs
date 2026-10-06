## NANDInfo

> `/System/Library/PrivateFrameworks/NANDInfo.framework/NANDInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d2a8` | `0x1d4e4` | **`+0x23c`** |
| `__AUTH_CONST.__objc_intobj` | `0x11b50` | `0x11bc8` | **`+0x78`** |
| `__TEXT.__cstring` | `0xc74c` | `0xc7a9` | **`+0x5d`** |
| `__TEXT.__oslogstring` | `0x1171` | `0x11b7` | **`+0x46`** |
| `__TEXT.__unwind_info` | `0x288` | `0x2a0` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xd660` | `0xd668` | **`+0x8`** |

### Other Changes

```diff

-849.0.11.0.0
+849.40.12.0.1

-  Functions: 272
-  Symbols:   470
-  CStrings:  2383
+  Functions: 279
+  Symbols:   472
+  CStrings:  2386
Symbols:
+ _ApplyFTLPrivacyTransforms
+ _CalculateAveragePECycles
CStrings:
+ "%{public}s: %{public}@ should be of type NSNumber, but was %{public}@"
+ "Unable to gather other manipulated nand stats"
+ "Unable to gather other system related stats"
+ "applyVccSessionTimePrivacyTransforms"
- "Unable to gather new delta fields"
```
