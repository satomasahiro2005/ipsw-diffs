## EmailCore

> `/System/Library/PrivateFrameworks/EmailCore.framework/EmailCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a0ac` | `0x5aa34` | **`+0x988`** |
| `__TEXT.__oslogstring` | `0xc47` | `0xc7f` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x483` | `0x4b3` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x9c8` | `0x9e8` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x5360` | `0x5340` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x330` | `0x348` | **`+0x18`** |
| `__TEXT.__const` | `0x11c0` | `0x11d0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x82fe` | `0x82ee` | **`-0x10`** |
| `__AUTH_CONST.__const` | `0x2280` | `0x2288` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a38` | `0x2a40` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x71a0` | `0x7198` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2a40` | `0x2a38` | **`-0x8`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0

-  Functions: 2024
+  Functions: 2030
Symbols:
+ +[_ECHeaderAuthenticationResultsParser _scanToCFWSOrPeriodOrSemicolonOrEqualWithScanner:intoString:]
+ +[_ECHeaderAuthenticationResultsParser _statementsWithScanner:expectLeadingSemicolon:intoArray:]
+ ___100+[_ECHeaderAuthenticationResultsParser _scanToCFWSOrPeriodOrSemicolonOrEqualWithScanner:intoString:]_block_invoke
+ ___swift_memcpy42_8
+ __scanToCFWSOrPeriodOrSemicolonOrEqualWithScanner:intoString:.onceToken
+ __scanToCFWSOrPeriodOrSemicolonOrEqualWithScanner:intoString:.whitespacePeriodSemicolon
- +[_ECHeaderAuthenticationResultsParser _scanToCFWSOrPeriodOrSemicolonWithScanner:intoString:]
- +[_ECHeaderAuthenticationResultsParser _statementsWithScanner:intoArray:]
- ___93+[_ECHeaderAuthenticationResultsParser _scanToCFWSOrPeriodOrSemicolonWithScanner:intoString:]_block_invoke
- ___swift_memcpy25_8
- __scanToCFWSOrPeriodOrSemicolonWithScanner:intoString:.onceToken
- __scanToCFWSOrPeriodOrSemicolonWithScanner:intoString:.whitespacePeriodSemicolon
CStrings:
+ "(.;="
+ "Authentication-results header found with no authserv-id"
- "(.;"
- "x-"
```
