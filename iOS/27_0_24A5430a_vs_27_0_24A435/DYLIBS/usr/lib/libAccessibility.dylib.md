## libAccessibility.dylib

> `/usr/lib/libAccessibility.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37a20` | `0x3826c` | **`+0x84c`** |
| `__TEXT.__oslogstring` | `0x182f` | `0x19b6` | **`+0x187`** |
| `__TEXT.__cstring` | `0x9836` | `0x9913` | **`+0xdd`** |
| `__AUTH_CONST.__cfstring` | `0x7000` | `0x70c0` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x3700` | `0x3740` | **`+0x40`** |
| `__TEXT.__const` | `0x210` | `0x248` | **`+0x38`** |
| `__DATA.__bss` | `0x1608` | `0x1618` | **`+0x10`** |
| `__DATA.__data` | `0x12f8` | `0x1308` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5b8` | `0x5c8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x360` | `0x368` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd68` | `0xd70` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1490
-  Symbols:   3252
-  CStrings:  1277
+  Functions: 1494
+  Symbols:   3266
+  CStrings:  1290
Symbols:
+ GCC_except_table1375
+ GCC_except_table1407
+ GCC_except_table1412
+ GCC_except_table1413
+ GCC_except_table1478
+ GCC_except_table1480
+ GCC_except_table1488
+ GCC_except_table1489
+ _MGCopyAnswer
+ _MGIsDeviceOfType
+ __AXSBrailleSensingModeExpected
+ __AXSBrailleSensingModeExpected.onceToken
+ __AXSBrailleSensingModeSetExpected
+ __AXSBrailleSensingModeSetExpected.token
+ __AXSIsViridianDevice.isViridian
+ __AXSIsViridianDevice.onceToken
+ ____AXSBrailleSensingModeExpected_block_invoke
+ ____AXSIsViridianDevice_block_invoke
+ __kAXSCacheBrailleSensingModeExpected
+ _kAXSBrailleSensingModeExpectedPreference
+ _notify_register_check
+ _notify_set_state
- GCC_except_table1371
- GCC_except_table1403
- GCC_except_table1408
- GCC_except_table1409
- GCC_except_table1474
- GCC_except_table1476
- GCC_except_table1484
- GCC_except_table1485
CStrings:
+ "BSI-DIAG: _AXSBrailleSensingModeExpected()->%{bool}d, thread=%{public}s"
+ "BSI-DIAG: _AXSBrailleSensingModeSetExpected(%{bool}d), bsiCache=%{bool}d, thread=%{public}s"
+ "BSI-DIAG: _axsHandlePrefChanged received sensing-mode notif, thread=%{public}s"
+ "BSI-DIAG: cache updated sensing-mode=%{bool}d (dispatched), thread=%{public}s"
+ "BrailleSensingModeExpected"
+ "Failed to load auxiliary bundle %@: %@"
+ "PopAccessibility.axbundle"
+ "TargetSubType"
+ "V68"
+ "com.apple.accessibility.braille.sensing.mode.expected.status"
+ "com.apple.accessibility.bsi.8.dot.mode"
+ "com.apple.accessibility.cash.braille.sensing.mode"
+ "loaded auxiliary bundle at: %@"
```
