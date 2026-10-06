## Rules

> `/System/Library/PrivateFrameworks/Rules.framework/Rules`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x18f00` | `0x18c00` | **`-0x300`** |
| `__DATA_DIRTY.__bss` | `0x7600` | `0x7900` | **`+0x300`** |
| `__TEXT.__text` | `0x74c24` | `0x74ebc` | **`+0x298`** |
| `__DATA.__data` | `0x1b90` | `0x1b50` | **`-0x40`** |
| `__DATA_DIRTY.__data` | `0x1028` | `0x1068` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x4c00` | `0x4c30` | **`+0x30`** |
| `__TEXT.__cstring` | `0xac1` | `0xae1` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2a10` | `0x2a08` | **`-0x8`** |

### Other Changes

```diff

-92.0.0.0.0
+94.0.0.0.0

-  Symbols:   1290
+  Symbols:   1289
Symbols:
- _swift_willThrowTypedImpl
CStrings:
+ "[nemesis.rule] Index is out of bounds for string. { stringLength="
+ "[nemesis.rule] Index range is invalid for string. { stringLength="
+ "[nemesis.rule] JSON Parsing Failed. { path="
- "[nemesis.rule] Index is out of bounds for string. { string="
- "[nemesis.rule] Index range is invalid for string. { string="
- "[nemesis.rule] JSON Parsing Failed. { json="
```
