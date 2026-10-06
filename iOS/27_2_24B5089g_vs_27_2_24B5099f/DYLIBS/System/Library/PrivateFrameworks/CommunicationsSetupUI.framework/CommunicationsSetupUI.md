## CommunicationsSetupUI

> `/System/Library/PrivateFrameworks/CommunicationsSetupUI.framework/CommunicationsSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97fac` | `0x98098` | **`+0xec`** |
| `__TEXT.__gcc_except_tab` | `0x4364` | `0x4380` | **`+0x1c`** |
| `__TEXT.__oslogstring` | `0x65ea` | `0x65d8` | **`-0x12`** |
| `__TEXT.__cstring` | `0xc9dc` | `0xc9cc` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x8cec` | `0x8cdc` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0xe208` | `0xe200` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5d58` | `0x5d50` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2ce0` | `0x2ce8` | **`+0x8`** |

### Other Changes

```diff

-1576.200.41.0.0
+1576.200.51.0.0

-  Functions: 3308
-  Symbols:   5406
+  Functions: 3309
+  Symbols:   5407
Symbols:
+ _CNFRegRegistrationStatusIsInProgress
Functions:
+ _CNFRegRegistrationStatusIsInProgress
~ ___50-[CNFRegSettingsController refreshAliasSpecifier:]_block_invoke : 1456 -> 1440
CStrings:
+ "Account used for settings was removed"
+ "No more useable accounts"
- "Account used for settings was removed, popping"
- "No more useable accounts, popping"
```
