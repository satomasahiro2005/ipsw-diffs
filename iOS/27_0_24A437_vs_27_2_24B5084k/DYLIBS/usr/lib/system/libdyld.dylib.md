## libdyld.dylib

> `/usr/lib/system/libdyld.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ce24` | `0x1cf28` | **`+0x104`** |
| `__TEXT.__unwind_info` | `0xd98` | `0xda0` | **`+0x8`** |

### Other Changes

```diff

-27062.0.0.0.0
+27102.0.0.0.0

-  Functions: 852
-  Symbols:   1078
+  Functions: 853
+  Symbols:   1079
Symbols:
+ __ZZZ19dyldFrameworkVtablevEUb_EN3$_08__invokeEPvPFvS0_PKvmE
Functions:
~ ____Z19dyldFrameworkVtablev_block_invoke : 144 -> 176
+ __ZZZ19dyldFrameworkVtablevEUb_EN3$_08__invokeEPvPFvS0_PKvmE
~ __ZN6mach_o8Platform6byNameENSt3__117basic_string_viewIcNS1_11char_traitsIcEEEE : 704 -> 880
```
