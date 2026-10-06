## mobile_obliterator

> `/usr/libexec/mobile_obliterator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b338` | `0x1b77c` | **`+0x444`** |
| `__TEXT.__cstring` | `0xaa47` | `0xacf5` | **`+0x2ae`** |
| `__TEXT.__objc_stubs` | `0x880` | `0x920` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x7c6` | `0x809` | **`+0x43`** |
| `__DATA_CONST.__cfstring` | `0x20a0` | `0x20e0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x2e0` | `0x308` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x1520` | `0x1540` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x198` | `0x1b0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xaa8` | `0xab8` | **`+0x10`** |
| `__TEXT.__const` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x400` | `0x408` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-397.0.0.0.0
+400.0.0.0.0

-  Functions: 273
-  Symbols:   398
-  CStrings:  1384
+  Functions: 276
+  Symbols:   402
+  CStrings:  1404
Symbols:
+ _IOMobileFramebufferSetBrightnessControlCallback
+ _IOServiceWaitQuiet
+ _OBJC_CLASS_$_NSCondition
+ _OBJC_CLASS_$_NSDate
CStrings:
+ "%s: %s: IOMobileFramebufferCreateDisplayList failed"
+ "%s: %s: IOMobileFramebufferOpenByName failed: 0x%x"
+ "%s: %s: IOMobileFramebufferSetBrightnessControlCallback failed: 0x%x"
+ "%s: %s: IOMobileFramebufferSwapBegin failed: 0x%x"
+ "%s: %s: IOMobileFramebufferSwapEnd failed: 0x%x"
+ "%s: %s: IOMobileFramebufferSwapSetBrightness failed: 0x%x"
+ "%s: %s: IOMobileFramebufferSwapWaitWithTimeout failed: 0x%x"
+ "%s: %s: NVMe sanitize failed on %s"
+ "%s: %s: NVMe sanitize stalled on %s"
+ "%s: %s: Timed out waiting for container to quiesce after Data volume deletion"
+ "%s: %s: no embedded panel found"
+ "%s: %s: timed out waiting for brightness control callback"
+ "Sanitize Status"
+ "broadcast"
+ "dateWithTimeIntervalSinceNow:"
+ "lock"
+ "nvme_sanitize_poll"
+ "turn_on_backlight_iomfb"
+ "unlock"
+ "waitUntilDate:"
```
