## NanoPassKit

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NanoPassKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x8e30` | `0x8ac0` | **`-0x370`** |
| `__DATA_DIRTY.__objc_data` | `0xd20` | `0x1090` | **`+0x370`** |
| `__TEXT.__text` | `0x1eb5a4` | `0x1eb730` | **`+0x18c`** |
| `__TEXT.__oslogstring` | `0x22b0f` | `0x22b59` | **`+0x4a`** |
| `__TEXT.__gcc_except_tab` | `0x3820` | `0x3850` | **`+0x30`** |

### Other Changes

```diff

-1353.0.0.0.0
+1354.0.0.0.0

-  Functions: 11947
-  Symbols:   18696
-  CStrings:  3762
+  Functions: 11948
+  Symbols:   18695
+  CStrings:  3763
Symbols:
+ GCC_except_table168
+ __NPKFinishDecodingAndLogFailure
- GCC_except_table164
- GCC_except_table207
- GCC_except_table234
CStrings:
+ "Error: Failure while unarchiving %@; decoded object may be incomplete: %@"
```
