## AudioCodecs

> `/System/Library/Frameworks/AudioToolbox.framework/AudioCodecs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6910a8` | `0x68ec40` | **`-0x2468`** |
| `__TEXT.__unwind_info` | `0x9ad0` | `0x9b78` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x1b6ab` | `0x1b6ff` | **`+0x54`** |
| `__DATA_DIRTY.__bss` | `0xd0` | `0xf0` | **`+0x20`** |
| `__DATA.__bss` | `0x658` | `0x648` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x11e4c` | `0x11e44` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-811.0.0.0.0
+812.0.0.0.0

-  Functions: 9743
+  Functions: 9741

-  CStrings:  3562
+  CStrings:  3563
CStrings:
+ "%25s:%-5d  Error: STIC render layout channel count does not match configured output"
+ "22:15:03"
+ "Apple LLVM 21.0.0 (clang-2100.3.25.1) [+internal-os]"
+ "Jun 26 2026"
- "00:08:28"
- "Apple LLVM 21.0.0 (clang-2100.3.23.3) [+internal-os]"
- "Jun 12 2026"
```
