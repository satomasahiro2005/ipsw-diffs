## Email

> `/System/Library/PrivateFrameworks/Email.framework/Email`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xda6dc` | `0xd88b0` | **`-0x1e2c`** |
| `__AUTH_CONST.__objc_const` | `0x16f60` | `0x169e8` | **`-0x578`** |
| `__TEXT.__gcc_except_tab` | `0x1b088` | `0x1ac7c` | **`-0x40c`** |
| `__TEXT.__objc_methlist` | `0xd0ac` | `0xcd6c` | **`-0x340`** |
| `__DATA_CONST.__objc_selrefs` | `0x62b8` | `0x6108` | **`-0x1b0`** |
| `__DATA.__data` | `0x2a40` | `0x28c0` | **`-0x180`** |
| `__AUTH_CONST.__cfstring` | `0xa560` | `0xa400` | **`-0x160`** |
| `__TEXT.__unwind_info` | `0x81d0` | `0x8080` | **`-0x150`** |
| `__TEXT.__oslogstring` | `0x6913` | `0x67e3` | **`-0x130`** |
| `__DATA_DIRTY.__objc_data` | `0x3808` | `0x3718` | **`-0xf0`** |
| `__AUTH_CONST.__const` | `0x1ea0` | `0x1f40` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0xc98` | `0xc50` | **`-0x48`** |
| `__DATA_CONST.__const` | `0x4610` | `0x45e8` | **`-0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x340` | `0x320` | **`-0x20`** |
| `__TEXT.__const` | `0x18dc` | `0x18c2` | **`-0x1a`** |
| `__DATA.__objc_ivar` | `0xc4c` | `0xc34` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x590` | `0x578` | **`-0x18`** |
| `__TEXT.__cstring` | `0xc37f` | `0xc369` | **`-0x16`** |
| `__DATA_CONST.__objc_superrefs` | `0x480` | `0x470` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0xad0` | `0xac0` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x40f` | `0x41f` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x118` | `0x110` | **`-0x8`** |

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  Functions: 5173
-  Symbols:   8986
-  CStrings:  2166
+  Functions: 5140
+  Symbols:   8897
+  CStrings:  2151
Symbols:
+ +[EMListUnsubscribeCommand mailtoUnsubscribeCommandWithListID:address:sender:senderForUnsubscribeMessage:subject:body:accountObjectID:headerUnsubscribeTypes:]
+ -[EMListUnsubscribeMailtoValues accountObjectID]
+ -[EMListUnsubscribeMailtoValues initWithAddresss:subject:body:accountObjectID:]
+ -[EMMailboxCategoryCloudStorage test_drain]
+ -[EMMailboxScope initWithMailboxObjectIDs:forExclusion:]
+ -[EMUbiquitouslyPersistedDictionary test_drainDelegateNotifications]
+ -[EMUbiquitouslyPersistedDictionary test_drainMutations]
+ _OBJC_IVAR_$_EMListUnsubscribeMailtoValues._accountObjectID
+ __OBJC_$_CATEGORY_NSArray_$_EMSmartMailbox
+ __OBJC_$_INSTANCE_METHODS_NSArray(EMSmartMailbox|EMMessageListItem|EMSender)
+ ___43-[EMMailboxCategoryCloudStorage test_drain]_block_invoke
+ ___56-[EMUbiquitouslyPersistedDictionary test_drainMutations]_block_invoke
+ ___56-[EMUbiquitouslyPersistedDictionary test_drainMutations]_block_invoke_2
+ ___56-[EMUbiquitouslyPersistedDictionary test_drainMutations]_block_invoke_3
+ ___68-[EMUbiquitouslyPersistedDictionary test_drainDelegateNotifications]_block_invoke
+ ___68-[EMUbiquitouslyPersistedDictionary test_drainDelegateNotifications]_block_invoke_2
+ ___68-[EMUbiquitouslyPersistedDictionary test_drainDelegateNotifications]_block_invoke_3
+ ___68-[EMUbiquitouslyPersistedDictionary test_drainDelegateNotifications]_block_invoke_4
- +[EMAccountAuthentication log]
- +[EMListUnsubscribeCommand _accountWithIdentifier:]
- +[EMListUnsubscribeCommand accountFinderBlock]
- +[EMListUnsubscribeCommand mailtoUnsubscribeCommandWithListID:address:sender:senderForUnsubscribeMessage:subject:body:account:headerUnsubscribeTypes:]
- +[EMListUnsubscribeCommand setAccountFinderBlock:]
- +[EMListUnsubscribeDetector _validateHeaders:dkimVerified:]
- +[EMListUnsubscribeDetector receivingAccountFromMessage:]
- +[EMListUnsubscribeDetector unsubscribeTypeForHeader:]
- +[EMListUnsubscribeDetector validatedUnsubscribeTypeForHeader:dkimVerified:]
- -[EMAccountAuthentication .cxx_destruct]
- -[EMAccountAuthentication _hostnamesHaveSameTopLevelDomain:deliveryAccount:]
- -[EMAccountAuthentication _shouldAutoUpdateDeliveryAccount:forChangedReceivingAccount:]
- -[EMAccountAuthentication _updateDeliveryAccountCredentialIfNecessaryForAccountWithAccount:]
- -[EMAccountAuthentication _updateDeliveryAccountCredentialIfNecessaryForReceivingAccount:]
- -[EMAccountAuthentication accountFactory]
- -[EMAccountAuthentication initWithAccountFactory:]
- -[EMAccountAuthentication updateDeliveryAccountCredentialIfNecessaryForAccountWithIdentifier:]
- -[EMAccountAuthentication updateDeliveryAccountCredentialIfNecessaryForAccountWithSystemAccount:]
- -[EMHideMyEmail isConfiguredForAccountWithAltDSID:error:]
- -[EMListUnsubscribeDetector .cxx_destruct]
- -[EMListUnsubscribeDetector _listIDString:]
- -[EMListUnsubscribeDetector _normalizedAddress:]
- -[EMListUnsubscribeDetector _persistentKeyForHeaders:]
- -[EMListUnsubscribeDetector _senderString:]
- -[EMListUnsubscribeDetector acceptCommand:]
- -[EMListUnsubscribeDetector commandForMessage:dkimVerified:]
- -[EMListUnsubscribeDetector commandForMessage:mailToOnly:dkimVerified:]
- -[EMListUnsubscribeDetector ignoreCommand:]
- -[EMListUnsubscribeDetector initWithMutableDictionary:]
- -[EMListUnsubscribeDetector init]
- -[EMListUnsubscribeDetector removeAllPersistedCommands]
- -[EMListUnsubscribeDetector shouldIgnoreMessageWithHeaders:]
- -[EMListUnsubscribeMailtoValues account]
- -[EMListUnsubscribeMailtoValues initWithAddresss:subject:body:account:]
- -[EMMailDropMetadata isBannerWithMultiple]
- -[EMUbiquitouslyPersistedDictionary _waitForPendingMutationsForTesting]
- -[_EMUnsubscribeInfo .cxx_destruct]
- -[_EMUnsubscribeInfo initWithHeaders:]
- -[_EMUnsubscribeInfo setMailtoURL:]
- -[_EMUnsubscribeInfo setPostContent:]
- -[_EMUnsubscribeInfo setPostURL:]
- _ECMessageHeaderKeyListID
- _ECMessageHeaderKeyListUnsubscribe
- _ECMessageHeaderKeyListUnsubscribePost
- _OBJC_CLASS_$_ACAccountCredential
- _OBJC_CLASS_$_ECDKIMVerifier
- _OBJC_CLASS_$_EMAccountAuthentication
- _OBJC_CLASS_$_EMListUnsubscribeDetector
- _OBJC_CLASS_$__EMUnsubscribeInfo
- _OBJC_IVAR_$_EMAccountAuthentication._accountFactory
- _OBJC_IVAR_$_EMListUnsubscribeDetector._persistentDictionary
- _OBJC_IVAR_$_EMListUnsubscribeMailtoValues._account
- _OBJC_IVAR_$_EMListUnsubscribeMailtoValues._accountIdentifier
- _OBJC_IVAR_$__EMUnsubscribeInfo._mailtoURL
- _OBJC_IVAR_$__EMUnsubscribeInfo._postContent
- _OBJC_IVAR_$__EMUnsubscribeInfo._postURL
- _OBJC_METACLASS_$_EMAccountAuthentication
- _OBJC_METACLASS_$_EMListUnsubscribeDetector
- _OBJC_METACLASS_$__EMUnsubscribeInfo
- __OBJC_$_CATEGORY_NSArray_$_EMMessageListItem
- __OBJC_$_CLASS_METHODS_EMAccountAuthentication
- __OBJC_$_CLASS_METHODS_EMListUnsubscribeDetector
- __OBJC_$_INSTANCE_METHODS_EMAccountAuthentication
- __OBJC_$_INSTANCE_METHODS_EMListUnsubscribeDetector
- __OBJC_$_INSTANCE_METHODS_NSArray(EMMessageListItem|EMSender|EMSmartMailbox)
- __OBJC_$_INSTANCE_METHODS__EMUnsubscribeInfo
- __OBJC_$_INSTANCE_VARIABLES_EMAccountAuthentication
- __OBJC_$_INSTANCE_VARIABLES_EMListUnsubscribeDetector
- __OBJC_$_INSTANCE_VARIABLES__EMUnsubscribeInfo
- __OBJC_$_PROP_LIST_ECMailAccount
- __OBJC_$_PROP_LIST_EDAccount
- __OBJC_$_PROP_LIST_EDReceivingAccount
- __OBJC_$_PROP_LIST_EMAccountAuthentication
- __OBJC_$_PROP_LIST_NSArray_$_EMMessageListItem
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_ECAccountPropertyProviding
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_ECMailAccount
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_EDAccount
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_EDReceivingAccount
- __OBJC_$_PROTOCOL_METHOD_TYPES_ECAccountPropertyProviding
- __OBJC_$_PROTOCOL_METHOD_TYPES_ECMailAccount
- __OBJC_$_PROTOCOL_METHOD_TYPES_EDAccount
- __OBJC_$_PROTOCOL_METHOD_TYPES_EDReceivingAccount
- __OBJC_$_PROTOCOL_REFS_ECMailAccount
- __OBJC_$_PROTOCOL_REFS_EDAccount
- __OBJC_$_PROTOCOL_REFS_EDReceivingAccount
- __OBJC_CLASS_RO_$_EMAccountAuthentication
- __OBJC_CLASS_RO_$_EMListUnsubscribeDetector
- __OBJC_CLASS_RO_$__EMUnsubscribeInfo
- __OBJC_LABEL_PROTOCOL_$_ECAccountPropertyProviding
- __OBJC_LABEL_PROTOCOL_$_ECMailAccount
- __OBJC_LABEL_PROTOCOL_$_EDAccount
- __OBJC_LABEL_PROTOCOL_$_EDReceivingAccount
- __OBJC_METACLASS_RO_$_EMAccountAuthentication
- __OBJC_METACLASS_RO_$_EMListUnsubscribeDetector
- __OBJC_METACLASS_RO_$__EMUnsubscribeInfo
- __OBJC_PROTOCOL_$_ECAccountPropertyProviding
- __OBJC_PROTOCOL_$_ECMailAccount
- __OBJC_PROTOCOL_$_EDAccount
- __OBJC_PROTOCOL_$_EDReceivingAccount
- __OBJC_PROTOCOL_REFERENCE_$_EDReceivingAccount
- ___30+[EMAccountAuthentication log]_block_invoke
- ___71-[EMListUnsubscribeDetector commandForMessage:mailToOnly:dkimVerified:]_block_invoke
- ___71-[EMUbiquitouslyPersistedDictionary _waitForPendingMutationsForTesting]_block_invoke
- ___71-[EMUbiquitouslyPersistedDictionary _waitForPendingMutationsForTesting]_block_invoke_2
- ___71-[EMUbiquitouslyPersistedDictionary _waitForPendingMutationsForTesting]_block_invoke_3
- ___block_descriptor_48_ea8_32s_e9_16?0^8ls32l8
- _sAccountFinderBlock
CStrings:
+ "-[EMMailboxCategoryCloudStorage test_drain]"
+ "-[EMUbiquitouslyPersistedDictionary test_drainDelegateNotifications]"
+ "-[EMUbiquitouslyPersistedDictionary test_drainMutations]"
+ "EFPropertyKey_accountObjectID"
+ "EMMailboxCategoryCloudStorage.m"
+ "Hide My Email address %{public}@ is NOT available in the list of %lu HME addresses"
+ "Hide My Email address %{public}@ is available in the list of %lu HME addresses"
+ "The checking for HME address %{public}@ is valid failed (%lu HME addresses found): %{public}@, adding telemetry for isHideMyEmailAddressValid session"
- "$1$2"
- "<%{public}@> Timeout validating headers for: %@"
- "@16@?0^@8"
- "Account is not a receiving account. No delivery account to update: %@"
- "Attempt to update password if needed for delivery account %@"
- "EFPropertyKey_account.identifier"
- "EMListUnsubscribeDetector.m"
- "Hide My Email address is available: %{BOOL}d in the list of HME addresses"
- "L:%@"
- "No delivery account password found. Nothing to do"
- "Receiving account password changed: %@"
- "S:%@"
- "Should not try to update delivery account password"
- "The checking for HME address is valid failed:%{public}@, adding telemetry for isHideMyEmailAddressValid session"
- "Updating password for %@ did not work. Reverting password"
- "Updating password worked for delivery account: %@"
- "^[^<>]*<([^>]+)>\\s*$|^(.+)$"
- "accepted"
- "accountFinderBlock is not set"
- "com.apple.mail.listUnsubscribeInfo"
- "dictionary"
- "failed to find an account for identifier"
- "ignored"
```
