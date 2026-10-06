## clocksyncd

> `/usr/libexec/clocksyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3af9c` | `0x3b254` | **`+0x2b8`** |
| `__TEXT.__oslogstring` | `0x57e9` | `0x5923` | **`+0x13a`** |
| `__DATA_CONST.__got` | `0x228` | `0x278` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x917d` | `0x91c9` | **`+0x4c`** |
| `__DATA.__objc_const` | `0x6a28` | `0x6a68` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1ac0` | `0x1ae8` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x59c0` | `0x59e0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xd40` | `0xd30` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x36b4` | `0x36c4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x514` | `0x51c` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1d90` | `0x1d98` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x6b8` | `0x6b0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xe80` | `0xe88` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__cstring`

### Other Changes

```diff

-1501.1.0.0.0
+1501.4.0.0.0

-  Functions: 1531
-  Symbols:   282
-  CStrings:  2451
+  Functions: 1529
+  Symbols:   281
+  CStrings:  2458
Symbols:
- _mach_get_times
CStrings:
+ "1501.4"
+ "Dropping stale trigger timing for triggerId %u: GTB %llu < threshold %llu\n"
+ "GTB/MCT offset changed (%llu -> %llu) — clearing trigger timing buffer before read\n"
+ "GTB/MCT offset changed mid-fetch (%llu -> %llu) — buffer entries are mixed; resetting\n"
+ "Nominal sync period: (%llu/%llu), nominal syncs per poll: %llu, %@\n"
+ "Reset MSG trigger timings, cachedGtbMctOffset: %llu, postResetGtbThreshold: %llu\n"
+ "Reset trigger timings: re-register failed for triggerId %u: 0x%x\n"
+ "Reset trigger timings: unregister failed for triggerId %u: 0x%x\n"
+ "Trigger timestamp overflow: whole=%llu, offset=%llu\n"
+ "_cachedGtbMctOffset"
+ "_postResetGtbThreshold"
+ "_resetTriggerTimingBuffersLocked"
- "1501.1"
- "Failed to calculate MAT offset because MCT < MAT. MCT: %llu, MAT: %llu\n"
- "Failed to calculate MAT offset from MCT. Error: %i\n"
- "MAT/MCT offset greater than INT64_MAX. MCT: %llu, MAT: %llu\n"
- "Nominal sync period: (%llu/%llu), nominal syncs per poll: %llu, %@, matOffset: %lli\n"
```
