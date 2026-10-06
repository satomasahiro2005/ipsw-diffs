## SiriMessageTypes

> `/System/Library/PrivateFrameworks/SiriMessageTypes.framework/SiriMessageTypes`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x99c0` | `0x9a80` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x2800` | `0x2848` | **`+0x48`** |
| `__TEXT.__text` | `0x12ffec` | `0x130018` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0xe80` | `0xea0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x519a` | `0x51af` | **`+0x15`** |
| `__DATA.__objc_ivar` | `0x32c` | `0x33c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xa20` | `0xa30` | **`+0x10`** |
| `__TEXT.__const` | `0x1e170` | `0x1e160` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x528` | `0x530` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8aa0` | `0x8a98` | **`-0x8`** |

### Other Changes

```diff

-3600.26.1.0.0
+3600.26.2.0.0

-  Functions: 14446
-  Symbols:   4641
+  Functions: 14447
+  Symbols:   4652
Symbols:
+ -[SMTRequestContextData invocationContext]
+ -[SMTRequestContextDataMutating invocationContext]
+ -[SMTRequestContextDataMutating setInvocationContext:]
+ -[SMTRequestDispatcherSessionConfiguration invocationContext]
+ -[SMTRequestDispatcherSessionConfigurationMutating invocationContext]
+ -[SMTRequestDispatcherSessionConfigurationMutating setInvocationContext:]
+ _OBJC_CLASS_$_AFInvocationContext
+ _OBJC_IVAR_$_SMTRequestContextData._invocationContext
+ _OBJC_IVAR_$_SMTRequestContextDataMutating._invocationContext
+ _OBJC_IVAR_$_SMTRequestDispatcherSessionConfiguration._invocationContext
+ _OBJC_IVAR_$_SMTRequestDispatcherSessionConfigurationMutating._invocationContext
+ ___block_descriptor_109_e8_32s40s48s56s64s_e58_v16?0"SMTRequestDispatcherSessionConfigurationMutating"8ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_101_e8_32s40s48s56s_e58_v16?0"SMTRequestDispatcherSessionConfigurationMutating"8ls32l8s40l8s48l8s56l8
CStrings:
+ "invocationContext"
- "(\""
```
