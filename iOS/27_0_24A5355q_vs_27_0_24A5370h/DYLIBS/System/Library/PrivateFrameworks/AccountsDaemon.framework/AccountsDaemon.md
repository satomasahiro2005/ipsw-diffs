## AccountsDaemon

> `/System/Library/PrivateFrameworks/AccountsDaemon.framework/AccountsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x831d4` | `0x83554` | **`+0x380`** |
| `__TEXT.__oslogstring` | `0x8fca` | `0x904a` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x16e0` | `0x1750` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x4b68` | `0x4b98` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1eb0` | `0x1ee0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x3c64` | `0x3c8c` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x24b4` | `0x24d8` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x1060` | `0x1080` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3d83` | `0x3da3` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x29b8` | `0x29d0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xd78` | `0xd80` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2c0` | `0x2c4` | **`+0x4`** |

### Other Changes

```diff

-1116.0.0.0.0
+1118.0.0.0.0

-  Functions: 2411
-  Symbols:   3196
-  CStrings:  1182
+  Functions: 2423
+  Symbols:   3213
+  CStrings:  1185
Symbols:
+ -[ACDAccountStore allCredentialItems]
+ -[ACDAccountStore credentialItemForAccount:serviceName:]
+ -[ACDAccountStore setCredentialItemCleanupVolatilityDuration:withCompletion:]
+ -[ACDAccountStore triggerCredentialItemCleanupWithCompletion:]
+ -[ACDAccountStoreFilter setCredentialItemCleanupVolatilityDuration:withCompletion:]
+ -[ACDAccountStoreFilter triggerCredentialItemCleanupWithCompletion:]
+ -[ACDKeychainCleanupActivity accountStore]
+ -[ACDKeychainCleanupActivity removeExpiredCredentials]
+ -[ACDKeychainCleanupActivity setAccountStore:]
+ -[ACDKeychainCleanupActivity setVolatilityDuration:]
+ -[ACDKeychainCleanupActivity volatilityDuration]
+ GCC_except_table101
+ GCC_except_table103
+ GCC_except_table108
+ GCC_except_table113
+ GCC_except_table120
+ GCC_except_table138
+ GCC_except_table140
+ GCC_except_table143
+ GCC_except_table148
+ GCC_except_table154
+ GCC_except_table156
+ GCC_except_table162
+ GCC_except_table191
+ GCC_except_table205
+ GCC_except_table210
+ GCC_except_table232
+ GCC_except_table234
+ _OBJC_IVAR_$_ACDKeychainCleanupActivity._volatilityDuration
+ __OBJC_$_PROP_LIST_ACDKeychainCleanupActivity
+ ___37-[ACDAccountStore allCredentialItems]_block_invoke
+ ___54-[ACDKeychainCleanupActivity removeExpiredCredentials]_block_invoke
+ ___56-[ACDAccountStore credentialItemForAccount:serviceName:]_block_invoke
+ ___block_descriptor_32_e27_v24?0"NSURL"8"NSError"16l
+ ___block_descriptor_32_e38_v24?0"ACCredentialItem"8"NSError"16l
+ ___block_descriptor_40_e8_32r_e29_v24?0"NSArray"8"NSError"16lr32l8
+ ___block_descriptor_40_e8_32r_e38_v24?0"ACCredentialItem"8"NSError"16lr32l8
+ _kACDAccountsTestingEntitlement
- -[ACDAccountStoreFilter credentialItemForAccount:serviceName:completion:]
- -[ACDAccountStoreFilter credentialItemsWithCompletion:]
- -[ACDAccountStoreFilter insertCredentialItem:completion:]
- -[ACDAccountStoreFilter removeCredentialItem:completion:]
- -[ACDAccountStoreFilter saveCredentialItem:completion:]
- GCC_except_table104
- GCC_except_table109
- GCC_except_table112
- GCC_except_table114
- GCC_except_table124
- GCC_except_table139
- GCC_except_table144
- GCC_except_table150
- GCC_except_table152
- GCC_except_table158
- GCC_except_table179
- GCC_except_table199
- GCC_except_table204
- GCC_except_table226
- GCC_except_table228
- ___block_descriptor_32_e20_v20?0B8"NSError"12l
CStrings:
+ "\"Client is not entitled to set cleanup volatility duration.\""
+ "\"Client is not entitled to trigger credential item cleanup.\""
+ "v24@?0@\"ACCredentialItem\"8@\"NSError\"16"
```
