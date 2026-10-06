## ClockKit

> `/System/Library/Frameworks/ClockKit.framework/ClockKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x29e0` | `—` | **`-0x29e0`** |
| `__DATA_DIRTY.__objc_data` | `0xf50` | `0x3930` | **`+0x29e0`** |
| `__TEXT.__text` | `0x6be38` | `0x6c0e8` | **`+0x2b0`** |
| `__DATA_DIRTY.__bss` | `0x338` | `0x560` | **`+0x228`** |
| `__DATA.__bss` | `0x9f0` | `0x7f0` | **`-0x200`** |
| `__TEXT.__oslogstring` | `0x2cba` | `0x2cfe` | **`+0x44`** |
| `__AUTH_CONST.__cfstring` | `0x54a0` | `0x54c0` | **`+0x20`** |
| `__TEXT.__const` | `0xa58` | `0xa78` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x97b4` | `0x97d4` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3688` | `0x36a0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2488` | `0x2498` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x7a0` | `0x7a8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2483.493.1.0.0
+2483.503.0.0.0

-  Functions: 3852
-  Symbols:   6839
-  CStrings:  977
+  Functions: 3857
+  Symbols:   6845
+  CStrings:  979
Symbols:
+ +[CLKDevice _pdrDeviceVersionForPDRDevice:]
+ -[CLKDevice _currentPDRDevice]
+ -[CLKDevice handleDeviceDidUnpairNotification:]
+ GCC_except_table125
+ GCC_except_table181
+ GCC_except_table45
+ GCC_except_table47
+ GCC_except_table49
+ GCC_except_table59
+ GCC_except_table68
+ _PDRDidUnpairNotification
+ __CLKIsDayPeriodPattern
+ ___47-[CLKDevice handleDeviceDidUnpairNotification:]_block_invoke
- GCC_except_table124
- GCC_except_table177
- GCC_except_table43
- GCC_except_table46
- GCC_except_table48
- GCC_except_table56
- GCC_except_table67
CStrings:
+ "Received device unpaired notification for our pairingID: %{public}@"
+ "b"
```
