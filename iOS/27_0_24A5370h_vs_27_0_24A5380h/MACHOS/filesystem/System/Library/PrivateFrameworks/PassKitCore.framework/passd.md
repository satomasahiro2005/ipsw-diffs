## passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60e550` | `0x60eca8` | **`+0x758`** |
| `__DATA_CONST.__got` | `0x4378` | `0x4890` | **`+0x518`** |
| `__TEXT.__objc_methname` | `0xa835c` | `0xa84ac` | **`+0x150`** |
| `__TEXT.__oslogstring` | `0x5b92b` | `0x5ba2b` | **`+0x100`** |
| `__DATA.__objc_const` | `0x45070` | `0x450d8` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x354c0` | `0x35520` | **`+0x60`** |
| `__TEXT.__cstring` | `0x68b94` | `0x68bf4` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x77e60` | `0x77ea0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x32a58` | `0x32a78` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x14e42` | `0x14e22` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x7880` | `0x7890` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x36ecc` | `0x36edc` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2b1c` | `0x2b28` | **`+0xc`** |
| `__TEXT.__gcc_except_tab` | `0x90cc` | `0x90d8` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x20d88` | `0x20d90` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x3c50` | `0x3c58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x14568` | `0x14570` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1682.1.0.0.0
+1686.3.0.0.0

+  - /System/Library/PrivateFrameworks/CoreSuggestions.framework/CoreSuggestions

-  Functions: 29682
-  Symbols:   4319
-  CStrings:  36290
+  Functions: 29686
+  Symbols:   4317
+  CStrings:  36303
Symbols:
+ _CFPreferencesCopyAppValue
+ _PKAppleCardUpcomingTransactionsEnabled
- _OBJC_CLASS_$_FKTrillianTransactionImporter
- _OBJC_CLASS_$_PKContent
- _OBJC_CLASS_$_PKWebServiceDocumentDeliveryFeature
- _PKDocumentDeliveryEnabled
CStrings:
+ "AppCanShowSiriSuggestionsBlacklist"
+ "CONTINUITY_PROVISIONING_PROMPT_NOTIFICATION_BODY_DEVICE_NAME"
+ "Coalescing delivered-notifications completions: %lu pending"
+ "Migrating database from user_version 26061 to 26062"
+ "Synchronized delivered-notifications. Running %lu completions"
+ "Synchronizing delivered-notifications..."
+ "T@\"PKContinuityProximityCBAdvertisement\",R,N,V_advertisement"
+ "TB,N,V_useGenericMessaging"
+ "Updating past due notification (%@) Mini-Miranda generic messaging flag (from:%d to:%d)"
+ "_isEntitledForSiriSuggestions"
+ "_isSyncingDeliveredNotifications"
+ "_migrateFrom26061To26062:context:"
+ "_pendingDeliveredNotificationCompletions"
+ "_syncDeliveredNotificationsLock"
+ "com.apple.suggestions"
+ "existingPendingProvisioningAccess"
+ "initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:"
+ "posterGeneric"
+ "setSecureElementIdentifiers:"
+ "setUseGenericMessaging:"
+ "siriSuggestionsAccess"
+ "updatePastDueNotificationWithAccount:userNotification:"
+ "v20@?0B8@\"PKAccount\"12"
+ "\xc1"
- "-[PDPaymentService addPendingProvisioning:]"
- "DocumentDelivery"
- "Inserting pending transaction registration"
- "_insertPendingTransactionRegistration:"
- "addPendingProvisioning:"
- "createWithFileURL:dataTypeIdentifier:"
- "initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:"
- "isEnabledWithWebService:"
- "registerPaymentTransaction:"
- "second"
- "v24@0:8@\"PKPendingProvisioning\"16"
```
