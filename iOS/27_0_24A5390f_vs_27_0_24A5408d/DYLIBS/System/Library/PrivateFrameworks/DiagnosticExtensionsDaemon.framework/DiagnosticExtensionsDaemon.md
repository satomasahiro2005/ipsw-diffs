## DiagnosticExtensionsDaemon

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/DiagnosticExtensionsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x759a8` | `0x75d10` | **`+0x368`** |
| `__TEXT.__objc_methlist` | `0x6fcc` | `0x700c` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x13a70` | `0x13aa0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2150` | `0x2180` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x5020` | `0x5040` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x9808` | `0x9828` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b80` | `0x3b98` | **`+0x18`** |
| `__TEXT.__cstring` | `0x56f0` | `0x5700` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1cc0` | `0x1cd0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5e4` | `0x5e8` | **`+0x4`** |

### Other Changes

```diff

-221.0.0.0.0
+222.0.0.0.0

-  Functions: 2921
-  Symbols:   4278
-  CStrings:  1787
+  Functions: 2926
+  Symbols:   4287
+  CStrings:  1789
Symbols:
+ -[DEDBugSession createdAt]
+ -[DEDBugSession persistence]
+ -[DEDBugSession setCreatedAt:]
+ -[DEDController attachmentHandler]
+ -[DEDController dedDirectory]
+ GCC_except_table122
+ GCC_except_table125
+ GCC_except_table128
+ GCC_except_table138
+ _DEDBugSessionKeyCreatedAt
+ _OBJC_IVAR_$_DEDBugSession._createdAt
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- GCC_except_table118
- GCC_except_table127
- GCC_except_table134
CStrings:
+ "createdAt"
+ "evicting stale fileless session [%{public}@]"
```
