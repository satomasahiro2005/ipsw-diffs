## HealthActivityCache

> `/System/Library/Health/Plugins/HealthActivityCache.bundle/HealthActivityCache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2086c` | `0x209dc` | **`+0x170`** |
| `__TEXT.__objc_methname` | `0x415b` | `0x41d4` | **`+0x79`** |
| `__TEXT.__gcc_except_tab` | `0x2f98` | `0x2f64` | **`-0x34`** |
| `__TEXT.__auth_stubs` | `0x6c0` | `0x6b0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x378` | `0x370` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x490` | `0x488` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xd30` | `0xd38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 564
-  Symbols:   334
+  Functions: 566
+  Symbols:   332
Symbols:
- _OBJC_CLASS_$_NSNotificationCenter
- _objc_opt_new
CStrings:
+ "initWithCurrentActivityCache:activeEnergyResults:appleMoveTimeResults:appleExerciseTimeResults:appleStandHourResults:"
+ "initWithStartDate:endDate:quantityValue:"
+ "notificationCenter"
- "defaultCenter"
- "setCurrentActivityCache:"
- "setQuantityValue:"
```
