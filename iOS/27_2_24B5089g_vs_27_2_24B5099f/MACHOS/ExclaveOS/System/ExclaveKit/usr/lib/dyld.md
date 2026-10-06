## dyld

> `/System/ExclaveKit/usr/lib/dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c894` | `0x5ca40` | **`+0x1ac`** |
| `__TEXT.__cstring` | `0xe6f7` | `0xe781` | **`+0x8a`** |
| `__TEXT.__unwind_info` | `0x1ec0` | `0x1ec8` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__const`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_DIRTY.__all_image_info`
- `__TEXT.__const`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-27102.0.0.0.0
-  Functions: 2762
-  Symbols:   2438
-  CStrings:  1475
+27104.0.0.0.0
+  Functions: 2766
+  Symbols:   2441
+  CStrings:  1478
Symbols:
+ __ZNK6mach_o6Header22parse_dylinker_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE
+ __process_panicv
+ _process_panicv.panic
+ _xrt__process_panic_exception
- xrt_process_panicv.panic
CStrings:
+ "27104"
+ "load command #%d %.*s name offset too small"
+ "load command #%d %.*s not a dylib load command"
+ "load command #%d string start offset too small"
- "27102"
```
