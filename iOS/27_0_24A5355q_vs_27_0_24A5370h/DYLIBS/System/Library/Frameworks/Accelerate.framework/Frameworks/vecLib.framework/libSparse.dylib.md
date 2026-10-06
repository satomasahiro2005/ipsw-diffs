## libSparse.dylib

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparse.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16b7d0` | `0x1671d8` | **`-0x45f8`** |
| `__TEXT.__eh_frame` | `0x350` | `0x2a8` | **`-0xa8`** |
| `__TEXT.__cstring` | `0x4dcb` | `0x4e08` | **`+0x3d`** |
| `__TEXT.__oslogstring` | `0x1ccc` | `0x1d06` | **`+0x3a`** |
| `__TEXT.__gcc_except_tab` | `0xa2c` | `0xa4c` | **`+0x20`** |
| `__TEXT.__const` | `0x6f0` | `0x700` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x16b0` | `0x16a0` | **`-0x10`** |

### Other Changes

```diff

-192.0.0.0.1
+194.0.0.0.0

-  Functions: 1964
+  Functions: 1967

-  CStrings:  601
+  CStrings:  602
CStrings:
+ "Unexpected matrix storage scheme.\n"
+ "Workspace size calculation overflowed in partialLURefactor.\n"
- "Unexpected matrix storage scheme %d.\n"
```
