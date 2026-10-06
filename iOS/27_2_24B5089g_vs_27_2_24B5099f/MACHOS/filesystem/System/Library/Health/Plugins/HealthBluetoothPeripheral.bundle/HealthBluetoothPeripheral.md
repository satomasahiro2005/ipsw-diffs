## HealthBluetoothPeripheral

> `/System/Library/Health/Plugins/HealthBluetoothPeripheral.bundle/HealthBluetoothPeripheral`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f0e0` | `0x3efd8` | **`-0x108`** |
| `__TEXT.__oslogstring` | `0x59fb` | `0x5952` | **`-0xa9`** |
| `__TEXT.__objc_stubs` | `0x6340` | `0x62a0` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x9d18` | `0x9cbc` | **`-0x5c`** |
| `__DATA_CONST.__got` | `0x488` | `0x460` | **`-0x28`** |
| `__DATA.__objc_const` | `0x7830` | `0x7810` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x22a8` | `0x2288` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0x22e0` | `0x22c0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x26b6` | `0x2699` | **`-0x1d`** |
| `__TEXT.__objc_methtype` | `0x2ea8` | `0x2e98` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x3edc` | `0x3ee4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x10a8` | `0x10b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5a8` | `0x5a4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  - /System/Library/PrivateFrameworks/BacklightServices.framework/BacklightServices

-  Functions: 1715
-  Symbols:   438
-  CStrings:  2675
+  Functions: 1714
+  Symbols:   433
+  CStrings:  2665
Symbols:
- _OBJC_CLASS_$_BLSAssertion
- _OBJC_CLASS_$_BLSDisableLowerGestureAttribute
- _OBJC_CLASS_$_BLSDurationAttribute
- _OBJC_CLASS_$_BLSForceActiveAttribute
- _OBJC_CLASS_$_BLSPreventBacklightIdleAttribute
CStrings:
+ "a\xb1"
+ "unitTest_seedVendedTagSessionWithOOBInfo:"
- "%{public}@: Acquired backlight assertion %{public}@"
- "%{public}@: Invalidating backlight assertion %{public}@"
- "%{public}@: Unable to acquire backlight assertion %{public}@"
- "@\"BLSAssertion\""
- "Fitness Machine BLE Scanning"
- "_dualBacklightAssertion"
- "acquireWithExplanation:observer:attributes:"
- "disableLowerGesture"
- "forceActive"
- "preventIdle"
- "q\xb1"
- "timeoutAfterInterval:"
```
