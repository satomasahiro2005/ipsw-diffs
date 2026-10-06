## libBasebandDiagnostics.dylib

> `/usr/lib/libBasebandDiagnostics.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xccf0` | `0xcf6c` | **`+0x27c`** |
| `__TEXT.__cstring` | `0x1234` | `0x127c` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x1460` | `0x1498` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x478` | `0x488` | **`+0x10`** |

### Other Changes

```diff

-1570.0.0.0.0
+1576.0.0.0.0

-  Functions: 149
-  Symbols:   580
-  CStrings:  314
+  Functions: 151
+  Symbols:   583
+  CStrings:  323
Symbols:
+ GCC_except_table38
+ GCC_except_table44
+ __ZN5radio8asStringERKNS_12AntennaStateE
+ __ZN6config2hw9deviceNEDEv
- GCC_except_table43
Functions:
+ __ZN6config2hw9deviceNEDEv
+ __ZN5radio8asStringERKNS_12AntennaStateE
CStrings:
+ "ARM41 Int Enforce"
+ "Dynamic"
+ "Limit"
+ "Lower"
+ "Port A"
+ "Port B"
+ "Port C"
+ "Port D"
+ "Upper"
```
