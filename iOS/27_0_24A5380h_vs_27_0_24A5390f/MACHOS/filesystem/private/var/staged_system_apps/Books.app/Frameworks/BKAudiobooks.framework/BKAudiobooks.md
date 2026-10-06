## BKAudiobooks

> `/private/var/staged_system_apps/Books.app/Frameworks/BKAudiobooks.framework/BKAudiobooks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20d0c` | `0x20dd8` | **`+0xcc`** |
| `__TEXT.__objc_methname` | `0x79f5` | `0x7a35` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x25c3` | `0x25f2` | **`+0x2f`** |
| `__TEXT.__objc_stubs` | `0x5b20` | `0x5b40` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x300c` | `0x3024` | **`+0x18`** |
| `__DATA.__objc_const` | `0x4af8` | `0x4b08` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1e00` | `0x1e08` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x938` | `0x930` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-6643.0.0.0.0
+6647.0.0.0.0

-  CStrings:  1911
+  CStrings:  1913
CStrings:
+ "_sendPlayerAudioSessionActivationFailedWithError:"
+ "observer: audio session activation failed = %@"
+ "player:audioSessionActivationFailedWithError:"
- "preflightForPlayWithCompletion:"
```
