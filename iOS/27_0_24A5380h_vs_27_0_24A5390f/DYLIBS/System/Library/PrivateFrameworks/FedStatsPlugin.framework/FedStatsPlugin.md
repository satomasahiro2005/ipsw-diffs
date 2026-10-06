## FedStatsPlugin

> `/System/Library/PrivateFrameworks/FedStatsPlugin.framework/FedStatsPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3199c` | `0x3280c` | **`+0xe70`** |
| `__DATA_DIRTY.__data` | `—` | `0x208` | **`+0x208`** |
| `__AUTH.__data` | `0xd68` | `0xb90` | **`-0x1d8`** |
| `__DATA.__bss` | `0x800` | `0x700` | **`-0x100`** |
| `__DATA_DIRTY.__bss` | `—` | `0x100` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x17ec` | `0x18cc` | **`+0xe0`** |
| `__DATA.__common` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__const` | `0xf68` | `0xf88` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x328` | `0x340` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x7d8` | `0x7c0` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x660` | `0x674` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xb98` | `0xb88` | **`-0x10`** |
| `__DATA.__data` | `0x5a0` | `0x598` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x130` | `0x138` | **`+0x8`** |

### Other Changes

```diff

-35.0.0.0.0
+38.0.0.0.0

-  Functions: 524
-  Symbols:   444
-  CStrings:  194
+  Functions: 533
+  Symbols:   449
+  CStrings:  197
Symbols:
+ _OBJC_CLASS_$_NSNumber
+ _kDPMetadataDPConfigOverallClippingBound
+ _kDPMetadataDediscoTaskConfigDPConfig
+ _symbolic _____ySdG s23_ContiguousArrayStorageC
+ _symbolic _____ySfG s23_ContiguousArrayStorageC
CStrings:
+ "[%s] Ignoring invalid OverallClippingBound=%f; expected a finite positive value"
+ "[%s] Scaled histogram by 1/%f for PINE submission"
+ "[%s] Scaled histogram has non-finite values; skipping submission for %s"
```
