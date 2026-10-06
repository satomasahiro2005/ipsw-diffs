## devicerecoveryd

> `/System/Library/PrivateFrameworks/DeviceRecovery.framework/Support/devicerecoveryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2304c` | `0x22fc8` | **`-0x84`** |
| `__TEXT.__cstring` | `0x7a90` | `0x7a4c` | **`-0x44`** |
| `__DATA_CONST.__const` | `0xcf0` | `0xcc8` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x208` | `0x210` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6f0` | `0x6e8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-144.0.0.0.0
+148.0.0.0.0

-  Functions: 811
+  Functions: 810

-  CStrings:  1637
+  CStrings:  1635
Symbols:
+ _AnalyticsSendEventSync
- _AnalyticsSendEventLazy
CStrings:
+ "05:12:05"
+ "Jun 27 2026"
- "-[DRAnalytics _queue_submitEvent:]_block_invoke"
- "09:33:51"
- "@\"NSDictionary\"8@?0"
- "Jun 13 2026"
```
