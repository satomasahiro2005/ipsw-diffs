## timed

> `/usr/libexec/timed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17734` | `0x17858` | **`+0x124`** |
| `__TEXT.__cstring` | `0x20d4` | `0x20e7` | **`+0x13`** |
| `__TEXT.__auth_stubs` | `0xbb0` | `0xba0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x5e8` | `0x5e0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x600` | `0x5f8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-340.0.11.0.0
+340.0.12.0.0

-  Functions: 618
-  Symbols:   257
+  Functions: 622
+  Symbols:   256
Symbols:
- _memcpy
CStrings:
+ "-[TMBackgroundNtpSource _fetchTime]"
+ "340.0.12"
+ "best_index > -1 && best_index < NTP_DESIRED_NUM_SERVERS"
- "-[TMBackgroundNtpSource _fetchTime]_block_invoke"
- "340.0.11"
- "machResult > kMachStart"
```
