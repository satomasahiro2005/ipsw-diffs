## ModuleBase

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/ModuleBase.framework/ModuleBase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x7bb` | `0x7c6` | **`+0xb`** |
| `__TEXT.__text` | `0x57f0` | `0x57ec` | **`-0x4`** |

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1
Symbols:
+ -[ContextPlugin credentialEncodingSeedWithOriginator:reply:]
- -[ContextPlugin credentialEncodingSeedWithReply:]
Functions:
~ -[MechanismManager _logClass:tag:level:] : 516 -> 512
CStrings:
+ "credentialEncodingSeedWithOriginator:reply:"
- "credentialEncodingSeedWithReply:"
```
