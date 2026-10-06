## SwiftMedia

> `/System/Library/PrivateFrameworks/SwiftMedia.framework/SwiftMedia`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x482b0` | `0x47aa4` | **`-0x80c`** |
| `__DATA_DIRTY.__data` | `0x6d0` | `0xb98` | **`+0x4c8`** |
| `__AUTH.__data` | `0x5e8` | `0x2a0` | **`-0x348`** |
| `__DATA.__data` | `0x9c8` | `0x840` | **`-0x188`** |
| `__AUTH.__objc_data` | `0x140` | `—` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0x190` | **`+0x140`** |
| `__DATA.__bss` | `0x16c0` | `0x15c0` | **`-0x100`** |
| `__DATA_DIRTY.__bss` | `0x300` | `0x400` | **`+0x100`** |
| `__TEXT.__const` | `0x27b0` | `0x2730` | **`-0x80`** |
| `__TEXT.__eh_frame` | `0x2e7c` | `0x2e1c` | **`-0x60`** |
| `__TEXT.__swift5_reflstr` | `0xd0f` | `0xcdf` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x1228` | `0x1200` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0xb30` | `0xb10` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x228` | `0x208` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x9c4` | `0x9ac` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x1202` | `0x1212` | **`+0x10`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x548` | `0x540` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-60.59.2.0.0
+60.63.1.0.0

-  Functions: 1498
+  Functions: 1478
Symbols:
+ ___swift_closure_destructor.266Tm
+ _keypath_get.109Tm
+ _keypath_set.110Tm
- ___swift_closure_destructor.271Tm
- _keypath_get.116Tm
- _keypath_set.117Tm
CStrings:
+ "Calling FigPlaybackItemSetBooleanProperty with restrictsAutomaticMediaSelectionToAvailableOfflineOptions: "
- "Calling FigPlaybackItemSetCMTimeProperty with restrictsAutomaticMediaSelectionToAvailableOfflineOptions: "
```
