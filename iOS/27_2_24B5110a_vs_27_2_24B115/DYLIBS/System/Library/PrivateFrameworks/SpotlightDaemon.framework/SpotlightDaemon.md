## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/SpotlightDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xca118` | `0xcae84` | **`+0xd6c`** |
| `__TEXT.__oslogstring` | `0xd686` | `0xd788` | **`+0x102`** |
| `__AUTH_CONST.__cfstring` | `0x8240` | `0x8320` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x9e7f` | `0x9f53` | **`+0xd4`** |
| `__AUTH_CONST.__const` | `0x13e8` | `0x1428` | **`+0x40`** |
| `__DATA.__bss` | `0x178` | `0x198` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ee0` | `0x3f00` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2a68` | `0x2a78` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1138` | `0x1140` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 3469
-  Symbols:   5209
-  CStrings:  2762
+  Functions: 3477
+  Symbols:   5216
+  CStrings:  2773
Symbols:
+ GCC_except_table47
+ GCC_except_table54
+ GCC_except_table57
+ GCC_except_table61
+ GCC_except_table64
+ GCC_except_table65
+ ___MDQueryCreateStringByAddingBackslashEscapes
+ ___isWellFormedBundleID_block_invoke
+ _bundleIDsPassingGrammar
+ _isWellFormedBundleID
+ _isWellFormedBundleID.allowed
+ _isWellFormedBundleID.once
+ _stringQueryTemplatesOnly
- GCC_except_table45
- GCC_except_table49
- GCC_except_table52
- GCC_except_table56
- GCC_except_table59
- GCC_except_table63
CStrings:
+ "%@ == \"%@\""
+ "((%@) && (%@ == \"%@\") && (%@))"
+ "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-."
+ "Client %@ passed a non-string %@ entry; dropping it"
+ "Client %@ passed malformed %@ entry (%@); dropping it"
+ "Client %@ trying to search additional bundle (%@) without having entitlement %@"
+ "Client %@ trying to use instant answers without being an allowed client"
+ "additionalBundleIDs"
+ "additionalQueries"
+ "disableBundles"
+ "instantAnswersBundleIDs"
+ "instantAnswersQueries"
+ "prefsDisabledBundles"
- "(%@ == %@)"
- "23F"
```
