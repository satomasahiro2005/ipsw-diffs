## clocksyncd

> `/usr/libexec/clocksyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b254` | `0x3b028` | **`-0x22c`** |
| `__TEXT.__oslogstring` | `0x5923` | `0x5853` | **`-0xd0`** |
| `__DATA.__objc_const` | `0x6a68` | `0x6a28` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1ae8` | `0x1aa8` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x91c9` | `0x9192` | **`-0x37`** |
| `__TEXT.__objc_methlist` | `0x36c4` | `0x36b4` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xe88` | `0xe78` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x51c` | `0x514` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`

### Other Changes

```diff

-1501.4.0.0.0
+1501.5.0.0.0

-  Functions: 1529
+  Functions: 1528

-  CStrings:  2458
+  CStrings:  2453
CStrings:
+ "%@: Dropping future trigger timing at index %ld: %llu > current MCT %llu\n"
+ "1501.5"
+ "Dropping stale trigger timing for triggerId %u: converted time %llu is in the future (now %llu) — likely a pre-hibernation entry\n"
+ "GTB/MCT offset changed mid-fetch (%llu -> %llu)\n"
+ "removeObjectAtIndex:"
- "1501.4"
- "Dropping stale trigger timing for triggerId %u: GTB %llu < threshold %llu\n"
- "GTB/MCT offset changed (%llu -> %llu) — clearing trigger timing buffer before read\n"
- "GTB/MCT offset changed mid-fetch (%llu -> %llu) — buffer entries are mixed; resetting\n"
- "Reset MSG trigger timings, cachedGtbMctOffset: %llu, postResetGtbThreshold: %llu\n"
- "Reset trigger timings: re-register failed for triggerId %u: 0x%x\n"
- "Reset trigger timings: unregister failed for triggerId %u: 0x%x\n"
- "_cachedGtbMctOffset"
- "_postResetGtbThreshold"
- "_resetTriggerTimingBuffersLocked"
```
