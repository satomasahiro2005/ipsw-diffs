## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cea4` | `0x1d29c` | **`+0x3f8`** |
| `__TEXT.__oslogstring` | `0x2ad9` | `0x2cb7` | **`+0x1de`** |
| `__TEXT.__objc_methname` | `0x3f4a` | `0x3fb9` | **`+0x6f`** |
| `__DATA_CONST.__const` | `0xbc0` | `0xc20` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x3660` | `0x36c0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x17fc` | `0x181c` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1058` | `0x1070` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x988` | `0x974` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0x718` | `0x728` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Functions: 594
+  Functions: 600

-  CStrings:  1549
+  CStrings:  1557
CStrings:
+ "CRShipModeOperationScheduler: cancel disengage of ship-charge limit failed: 0x%08x (%@); lock left engaged"
+ "CRShipModeOperationScheduler: notify failed for %{public}@; releasing ship-charge limit"
+ "CRShipModeOperationScheduler: released ship-charge limit after failed notify"
+ "CRShipModeOperationScheduler: released ship-charge limit latched by cancelled discharge"
+ "CRShipModeOperationScheduler: ship-charge limit release failed (ioReturn=0x%08x, error=%{public}@); lock left engaged"
+ "_releaseShipChargeLimitForDroppedDischarge"
+ "_releaseShipLockAfterFailedNotifyFor:"
+ "_tearDownDischargeAfterCancel"
```
