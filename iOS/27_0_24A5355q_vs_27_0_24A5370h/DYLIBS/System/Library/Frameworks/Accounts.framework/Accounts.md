## Accounts

> `/System/Library/Frameworks/Accounts.framework/Accounts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c334` | `0x59198` | **`-0x319c`** |
| `__TEXT.__oslogstring` | `0x531f` | `0x4f74` | **`-0x3ab`** |
| `__AUTH_CONST.__objc_const` | `0x5ec0` | `0x5c38` | **`-0x288`** |
| `__TEXT.__objc_methlist` | `0x4364` | `0x417c` | **`-0x1e8`** |
| `__TEXT.__gcc_except_tab` | `0x3820` | `0x3660` | **`-0x1c0`** |
| `__TEXT.__unwind_info` | `0x1b18` | `0x1a80` | **`-0x98`** |
| `__AUTH.__objc_data` | `0x960` | `0x910` | **`-0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2308` | `0x22b8` | **`-0x50`** |
| `__TEXT.__cstring` | `0x3e5b` | `0x3e29` | **`-0x32`** |
| `__AUTH_CONST.__cfstring` | `0x4a00` | `0x49e0` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x3ec` | `0x3d0` | **`-0x1c`** |
| `__DATA_CONST.__const` | `0x2638` | `0x2620` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x350` | `0x348` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1a8` | `0x1a0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x140` | `0x138` | **`-0x8`** |

### Other Changes

```diff

-1116.0.0.0.0
+1118.0.0.0.0

-  Functions: 2002
-  Symbols:   3451
-  CStrings:  1148
+  Functions: 1948
+  Symbols:   3388
+  CStrings:  1122
Symbols:
+ -[ACAccountStore setCredentialItemCleanupVolatilityDuration:withCompletion:]
+ -[ACAccountStore triggerCredentialItemCleanupWithCompletion:]
+ -[ACAccountStoreCache _lock_clearCachedAccountsForType:]
+ -[ACAccountStoreCache clearCachedAccountType:]
+ GCC_except_table240
+ GCC_except_table252
+ GCC_except_table257
+ GCC_except_table261
+ GCC_except_table264
+ GCC_except_table267
+ GCC_except_table270
+ GCC_except_table273
+ GCC_except_table276
+ GCC_except_table283
+ GCC_except_table288
+ GCC_except_table297
+ GCC_except_table300
+ GCC_except_table312
+ GCC_except_table316
+ GCC_except_table322
+ GCC_except_table327
+ GCC_except_table334
+ GCC_except_table340
+ GCC_except_table344
+ GCC_except_table351
+ GCC_except_table358
+ GCC_except_table370
+ GCC_except_table380
+ GCC_except_table403
+ GCC_except_table409
+ _ACTrustedDeviceIDTokenKey
+ ___46-[ACAccountStoreCache clearCachedAccountType:]_block_invoke
+ ___61-[ACAccountStore triggerCredentialItemCleanupWithCompletion:]_block_invoke
+ ___61-[ACAccountStore triggerCredentialItemCleanupWithCompletion:]_block_invoke_2
+ ___61-[ACAccountStore triggerCredentialItemCleanupWithCompletion:]_block_invoke_3
+ ___76-[ACAccountStore setCredentialItemCleanupVolatilityDuration:withCompletion:]_block_invoke
+ ___76-[ACAccountStore setCredentialItemCleanupVolatilityDuration:withCompletion:]_block_invoke_2
+ ___76-[ACAccountStore setCredentialItemCleanupVolatilityDuration:withCompletion:]_block_invoke_3
+ ___block_descriptor_48_e8_32bs_e40_v16?0"<ACRemoteAccountStoreProtocol>"8ls32l8
+ ___block_descriptor_72_e8_32s40s48bs_e20_v20?0B8"NSError"12ls32l8s40l8s48l8
+ _kACDAccountsTestingEntitlement
- +[ACProtobufCredentialItem dirtyPropertiesType]
- -[ACAccountStore allCredentialItems]
- -[ACAccountStore credentialItemForAccount:serviceName:]
- -[ACAccountStore insertCredentialItem:withCompletionHandler:]
- -[ACAccountStore removeCredentialItem:withCompletionHandler:]
- -[ACAccountStore saveCredentialItem:withCompletionHandler:]
- -[ACCredentialItem _encodeProtobufData]
- -[ACCredentialItem _encodeProtobuf]
- -[ACCredentialItem _initWithProtobuf:]
- -[ACCredentialItem _initWithProtobufData:]
- -[ACProtobufCredentialItem .cxx_destruct]
- -[ACProtobufCredentialItem accountIdentifier]
- -[ACProtobufCredentialItem addDirtyProperties:]
- -[ACProtobufCredentialItem clearDirtyProperties]
- -[ACProtobufCredentialItem copyTo:]
- -[ACProtobufCredentialItem copyWithZone:]
- -[ACProtobufCredentialItem description]
- -[ACProtobufCredentialItem dictionaryRepresentation]
- -[ACProtobufCredentialItem dirtyPropertiesAtIndex:]
- -[ACProtobufCredentialItem dirtyPropertiesCount]
- -[ACProtobufCredentialItem dirtyProperties]
- -[ACProtobufCredentialItem expirationDate]
- -[ACProtobufCredentialItem hasExpirationDate]
- -[ACProtobufCredentialItem hasIsPersistent]
- -[ACProtobufCredentialItem hasObjectID]
- -[ACProtobufCredentialItem hash]
- -[ACProtobufCredentialItem isEqual:]
- -[ACProtobufCredentialItem isPersistent]
- -[ACProtobufCredentialItem mergeFrom:]
- -[ACProtobufCredentialItem objectID]
- -[ACProtobufCredentialItem readFrom:]
- -[ACProtobufCredentialItem serviceName]
- -[ACProtobufCredentialItem setAccountIdentifier:]
- -[ACProtobufCredentialItem setDirtyProperties:]
- -[ACProtobufCredentialItem setExpirationDate:]
- -[ACProtobufCredentialItem setHasIsPersistent:]
- -[ACProtobufCredentialItem setIsPersistent:]
- -[ACProtobufCredentialItem setObjectID:]
- -[ACProtobufCredentialItem setServiceName:]
- -[ACProtobufCredentialItem writeTo:]
- GCC_except_table21
- GCC_except_table239
- GCC_except_table242
- GCC_except_table251
- GCC_except_table255
- GCC_except_table260
- GCC_except_table265
- GCC_except_table272
- GCC_except_table277
- GCC_except_table281
- GCC_except_table284
- GCC_except_table287
- GCC_except_table290
- GCC_except_table296
- GCC_except_table313
- GCC_except_table317
- GCC_except_table320
- GCC_except_table323
- GCC_except_table328
- GCC_except_table332
- GCC_except_table336
- GCC_except_table342
- GCC_except_table347
- GCC_except_table354
- GCC_except_table360
- GCC_except_table371
- GCC_except_table378
- GCC_except_table400
- GCC_except_table404
- GCC_except_table410
- GCC_except_table415
- GCC_except_table421
- _ACProtobufCredentialItemReadFrom
- _OBJC_CLASS_$_ACProtobufCredentialItem
- _OBJC_IVAR_$_ACProtobufCredentialItem._accountIdentifier
- _OBJC_IVAR_$_ACProtobufCredentialItem._dirtyProperties
- _OBJC_IVAR_$_ACProtobufCredentialItem._expirationDate
- _OBJC_IVAR_$_ACProtobufCredentialItem._has
- _OBJC_IVAR_$_ACProtobufCredentialItem._isPersistent
- _OBJC_IVAR_$_ACProtobufCredentialItem._objectID
- _OBJC_IVAR_$_ACProtobufCredentialItem._serviceName
- _OBJC_METACLASS_$_ACProtobufCredentialItem
- _OUTLINED_FUNCTION_13
- __OBJC_$_CLASS_METHODS_ACProtobufCredentialItem
- __OBJC_$_INSTANCE_METHODS_ACProtobufCredentialItem
- __OBJC_$_INSTANCE_VARIABLES_ACProtobufCredentialItem
- __OBJC_$_PROP_LIST_ACProtobufCredentialItem
- __OBJC_CLASS_PROTOCOLS_$_ACProtobufCredentialItem
- __OBJC_CLASS_RO_$_ACProtobufCredentialItem
- __OBJC_METACLASS_RO_$_ACProtobufCredentialItem
- ___36-[ACAccountStore allCredentialItems]_block_invoke
- ___36-[ACAccountStore allCredentialItems]_block_invoke_2
- ___55-[ACAccountStore credentialItemForAccount:serviceName:]_block_invoke
- ___55-[ACAccountStore credentialItemForAccount:serviceName:]_block_invoke_2
- ___59-[ACAccountStore saveCredentialItem:withCompletionHandler:]_block_invoke
- ___59-[ACAccountStore saveCredentialItem:withCompletionHandler:]_block_invoke_2
- ___61-[ACAccountStore insertCredentialItem:withCompletionHandler:]_block_invoke
- ___61-[ACAccountStore insertCredentialItem:withCompletionHandler:]_block_invoke_2
- ___61-[ACAccountStore insertCredentialItem:withCompletionHandler:]_block_invoke_3
- ___61-[ACAccountStore removeCredentialItem:withCompletionHandler:]_block_invoke
- ___61-[ACAccountStore removeCredentialItem:withCompletionHandler:]_block_invoke_2
- ___block_descriptor_40_e8_32bs_e38_v24?0"ACCredentialItem"8"NSError"16ls32l8
- ___block_descriptor_48_e8_32s40r_e38_v24?0"ACCredentialItem"8"NSError"16lr40l8s32l8
- ___block_descriptor_72_e8_32s40s48bs_e27_v24?0"NSURL"8"NSError"16ls32l8s48l8s40l8
CStrings:
+ "com.apple.private.accounts.testing"
+ "trusted-device-id"
- "\"Calling daemon to save a credential item\""
- "\"Credential item %@ associated with store %@, inserting credential item on store %@\""
- "ACCredentialItem.m"
- "AllCredentialItems"
- "BEGIN [%lld]: AllCredentialItems "
- "BEGIN [%lld]: CredentialItemsForAccountWithServiceName %@ : %@"
- "BEGIN [%lld]: InsertCredentialItem %@"
- "BEGIN [%lld]: RemoveCredentialItem %@"
- "BEGIN [%lld]: SaveCredentialItem %@"
- "Credential item must be non-nil"
- "CredentialItemsForAccountWithServiceName"
- "END [%lld] %fs: AllCredentialItems %@%@"
- "END [%lld] %fs: CredentialItemsForAccountWithServiceName %@%@"
- "END [%lld] %fs: InsertCredentialItem %@%@"
- "END [%lld] %fs: RemoveCredentialItem %@%@"
- "END [%lld] %fs: RemoveCredentialItem %{public}@"
- "END [%lld] %fs: SaveCredentialItem %@%@"
- "END [%lld] %fs: SaveCredentialItem %{public}@"
- "InsertCredentialItem"
- "RemoveCredentialItem"
- "SaveCredentialItem"
- "accounts/all-credential-items"
- "accounts/credential-item-for-account"
- "accounts/insert-credential-item"
- "accounts/remove-credential-item"
- "accounts/save-credential-item"
- "isPersistent"
- "v24@?0@\"ACCredentialItem\"8@\"NSError\"16"
```
