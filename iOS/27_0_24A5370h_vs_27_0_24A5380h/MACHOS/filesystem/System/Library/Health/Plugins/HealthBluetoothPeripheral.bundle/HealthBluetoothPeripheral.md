## HealthBluetoothPeripheral

> `/System/Library/Health/Plugins/HealthBluetoothPeripheral.bundle/HealthBluetoothPeripheral`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e8c8` | `0x3ece0` | **`+0x418`** |
| `__TEXT.__objc_methname` | `0x9c06` | `0x9c81` | **`+0x7b`** |
| `__DATA_CONST.__const` | `0x1298` | `0x12e8` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x430` | `0x478` | **`+0x48`** |
| `__TEXT.__cstring` | `0x262c` | `0x266e` | **`+0x42`** |
| `__TEXT.__objc_stubs` | `0x62a0` | `0x62e0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x58a7` | `0x58e6` | **`+0x3f`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x10a8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2270` | `0x2280` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 1704
-  Symbols:   433
-  CStrings:  2659
+  Functions: 1707
+  Symbols:   435
+  CStrings:  2664
Symbols:
+ _HKQuantityTypeIdentifierDistanceWalkingRunning
+ _OBJC_CLASS_$_HDWorkoutUtilities
CStrings:
+ "%{public}@: Failed to associate GymKit DWR samples: %{public}@"
+ "B24@?0@\"HDDatabaseTransaction\"8^@16"
+ "enumerateQuantitiesOfType:from:to:transaction:profile:error:handler:"
+ "performReadTransactionWithHealthDatabase:error:block:"
+ "v16@?0@\"<HDWorkoutQuantity>\"8"
```
