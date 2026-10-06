## CommunicationsSetupUI

> `/System/Library/PrivateFrameworks/CommunicationsSetupUI.framework/CommunicationsSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x904a0` | `0x8eafc` | **`-0x19a4`** |
| `__TEXT.__gcc_except_tab` | `0x444c` | `0x42cc` | **`-0x180`** |
| `__TEXT.__oslogstring` | `0x6665` | `0x64ed` | **`-0x178`** |
| `__DATA_CONST.__const` | `0x14e0` | `0x1490` | **`-0x50`** |
| `__TEXT.__cstring` | `0xc697` | `0xc647` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0xbb00` | `0xbac0` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0xd89` | `0xdc9` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5bb0` | `0x5ba0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x8a7c` | `0x8a74` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x29b0` | `0x29a8` | **`-0x8`** |

### Other Changes

```diff

-1567.100.1.0.0
+1568.100.1.0.0

-  Functions: 3063
-  Symbols:   5192
-  CStrings:  1798
+  Functions: 3061
+  Symbols:   5186
+  CStrings:  1789
Symbols:
+ -[CNFRegController _deduplicatePhoneAliases:]
+ GCC_except_table118
+ GCC_except_table120
+ GCC_except_table66
+ GCC_except_table69
+ GCC_except_table81
+ GCC_except_table87
+ GCC_except_table92
+ ___45-[CNFRegController _deduplicatePhoneAliases:]_block_invoke
- -[CNFRegController _deduplicatePhoneAliases:context:]
- -[CNFRegController _synthesizedVettedDevicePhoneAliasesForAccount:fromAppleIDAccounts:notAlreadyIn:]
- GCC_except_table108
- GCC_except_table119
- GCC_except_table122
- GCC_except_table128
- GCC_except_table198
- GCC_except_table64
- GCC_except_table68
- GCC_except_table70
- GCC_except_table89
- _OUTLINED_FUNCTION_2
- ___53-[CNFRegController _deduplicatePhoneAliases:context:]_block_invoke
- ___block_descriptor_40_e8_32s_e15_B32?08Q16^B24ls32l8
- ___block_descriptor_40_e8_32s_e21_q16?0"CNFRegAlias"8ls32l8
CStrings:
- "CNFRegController"
- "Claiming vetted alias %@ on AppleID account %@ before setting display name"
- "Deduplicating %lu phone number alias(es) from %@"
- "Eagerly claiming vetted alias %@ on AppleID account %@"
- "Redirecting caller ID alias %@ from non-operational PhoneNumber account to registered AppleID account %@"
- "Synthesizing vetted alias %@ — missing from PhoneNumber account, found on AppleID account"
- "allAvailableAliases"
- "q16@?0@\"CNFRegAlias\"8"
- "useableAliases"
```
