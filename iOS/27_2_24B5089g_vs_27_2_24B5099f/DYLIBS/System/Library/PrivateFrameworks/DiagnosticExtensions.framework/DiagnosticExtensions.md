## DiagnosticExtensions

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/DiagnosticExtensions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x2a0` | `—` | **`-0x2a0`** |
| `__DATA_DIRTY.__data` | `—` | `0x2a0` | **`+0x2a0`** |
| `__TEXT.__text` | `0x17dfc` | `0x17ec8` | **`+0xcc`** |
| `__TEXT.__oslogstring` | `0x3348` | `0x3393` | **`+0x4b`** |
| `__TEXT.__objc_methlist` | `0x121c` | `0x1224` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6b8` | `0x6c0` | **`+0x8`** |

### Other Changes

```diff

-150.0.0.0.0
+151.0.0.0.0

-  Functions: 594
-  Symbols:   1000
-  CStrings:  439
+  Functions: 596
+  Symbols:   1002
+  CStrings:  440
Symbols:
+ -[DEExtension init]
+ GCC_except_table12
+ GCC_except_table17
+ GCC_except_table20
+ GCC_except_table41
+ GCC_except_table48
+ GCC_except_table50
+ GCC_except_table59
+ GCC_except_table61
+ GCC_except_table8
- GCC_except_table14
- GCC_except_table19
- GCC_except_table40
- GCC_except_table47
- GCC_except_table49
- GCC_except_table58
- GCC_except_table60
- GCC_except_table9
CStrings:
+ "No plug-in URL for extension [%{public}@]; cannot read logging preferences"
```
