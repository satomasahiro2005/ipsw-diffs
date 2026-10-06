## SwiftData

> `/System/Library/Frameworks/SwiftData.framework/SwiftData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17aeec` | `0x17cc74` | **`+0x1d88`** |
| `__DATA_DIRTY.__data` | `0x4fd8` | `0x5c80` | **`+0xca8`** |
| `__AUTH.__data` | `0xba0` | `—` | **`-0xba0`** |
| `__AUTH.__objc_data` | `0x2c8` | `—` | **`-0x2c8`** |
| `__DATA_DIRTY.__objc_data` | `0x328` | `0x5f0` | **`+0x2c8`** |
| `__DATA.__bss` | `0xa8b0` | `0xa730` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `0x4190` | `0x4310` | **`+0x180`** |
| `__DATA.__data` | `0x1f78` | `0x1e70` | **`-0x108`** |
| `__TEXT.__swift5_typeref` | `0x4378` | `0x4440` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x6ddd` | `0x6e2d` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1477` | `0x14c7` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x9354` | `0x938c` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1a00` | `0x1a18` | **`+0x18`** |
| `__DATA.__common` | `0xf8` | `0x110` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4c40` | `0x4c58` | **`+0x18`** |
| `__TEXT.__const` | `0xbce8` | `0xbcf8` | **`+0x10`** |

### Other Changes

```diff

-183.0.0.0.0
+184.0.0.0.0

-  Functions: 6940
-  Symbols:   1902
-  CStrings:  647
+  Functions: 6953
+  Symbols:   1903
+  CStrings:  650
Symbols:
+ _generic environment 9SwiftData16HistoryProvidingRzl
+ _symbolic 11HistoryType______21TransactionIdentifier_____QZ 9SwiftData16HistoryProvidingP AA0C11TransactionP
- _symbolic _____y_____y_____GG s23_ContiguousArrayStorageC 10Foundation14SortDescriptorV 9SwiftData25DefaultHistoryTransactionV
CStrings:
+ "Failed to capture initial history token for store %{public}s: %{public}@"
+ "Failed to cast future model "
+ "Illegal attempt to create a future for "
```
