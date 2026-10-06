## abmlite

> `/usr/bin/abmlite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cd48` | `0x1cd14` | **`-0x34`** |
| `__TEXT.__gcc_except_tab` | `0x214c` | `0x2128` | **`-0x24`** |
| `__TEXT.__auth_stubs` | `0x8f0` | `0x8d0` | **`-0x20`** |
| `__TEXT.__cstring` | `0xa73` | `0xa60` | **`-0x13`** |
| `__DATA_CONST.__auth_got` | `0x490` | `0x480` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x578` | `0x568` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 176
-  Symbols:   361
-  CStrings:  165
+  Functions: 175
+  Symbols:   359
+  CStrings:  164
Symbols:
- _TelephonyBasebandWatchdogStartWithStackshot
- _TelephonyBasebandWatchdogStop
CStrings:
- "Watchdog timed out"
```
