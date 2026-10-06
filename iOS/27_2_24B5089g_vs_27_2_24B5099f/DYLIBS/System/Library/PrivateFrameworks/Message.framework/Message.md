## Message

> `/System/Library/PrivateFrameworks/Message.framework/Message`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb02e8c` | `0xb00814` | **`-0x2678`** |
| `__AUTH.__objc_data` | `0x6418` | `0x5e28` | **`-0x5f0`** |
| `__DATA_DIRTY.__objc_data` | `0xa50` | `0x1040` | **`+0x5f0`** |
| `__TEXT.__eh_frame` | `0x18a74` | `0x18b44` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x314d6` | `0x31576` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0xacce0` | `0xacc68` | **`-0x78`** |
| `__DATA_CONST.__const` | `0x154c8` | `0x15470` | **`-0x58`** |
| `__TEXT.__oslogstring` | `0x27ed0` | `0x27e80` | **`-0x50`** |
| `__DATA.__data` | `0xe978` | `0xe9b8` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x33968` | `0x33938` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x10d48` | `0x10d2c` | **`-0x1c`** |
| `__TEXT.__gcc_except_tab` | `0x370d4` | `0x370c0` | **`-0x14`** |
| `__AUTH_CONST.__objc_const` | `0x23118` | `0x23108` | **`-0x10`** |
| `__DATA.__bss` | `0x53a50` | `0x53a60` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x540` | `0x530` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xf380` | `0xf390` | **`+0x10`** |
| `__AUTH.__data` | `0xb5c8` | `0xb5d0` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0x4090` | `0x4098` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x1b8` | `0x1b0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb8c8` | `0xb8c0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x144bc` | `0x144c4` | **`+0x8`** |

### Other Changes

```diff

-3901.200.41.0.0
+3901.200.66.2.1

-  Functions: 48719
-  Symbols:   21368
-  CStrings:  8548
+  Functions: 48711
+  Symbols:   21355
+  CStrings:  8551
Symbols:
+ +[MFMessageKeychainManager _addAllIdentitiesToArray:matchingPolicy:fromSyncableKeychain:withError:]
+ +[MFMessageKeychainManager _copyAllIdentitiesMatchingPolicy:error:]
+ +[MFMessageKeychainManager _logIdentityCount:purpose:address:]
+ -[MFMessageChangeManager_iOS hasCompletedInitialSyncForMailboxURL:]
+ _kSecMatchPolicy
+ _symbolic So20EFProcessTransactionC
- +[MFMessageKeychainManager _addAllIdentitiesToArray:fromSyncableKeychain:withError:usingBlock:]
- +[MFMessageKeychainManager _copyAllIdentitiesWithError:usingBlock:]
- +[MFMessageKeychainManager _validateIdentity:forAddress:policy:usage:error:]
- +[MFMessageKeychainManager validateEncryptionIdentity:forAddress:error:]
- +[MFMessageKeychainManager validateSigningIdentity:forAddress:error:]
- _MFMessageKeychainManagerCertificateDeniedDomain
- _OBJC_CLASS_$_EDAccountDeletionDiagnostics
- __OBJC_$_PROTOCOL_REFS_OS_os_transaction
- __OBJC_LABEL_PROTOCOL_$_OS_os_transaction
- __OBJC_PROTOCOL_$_OS_os_transaction
- ___67+[MFMessageKeychainManager _copyAllIdentitiesWithError:usingBlock:]_block_invoke
- ___67+[MFMessageKeychainManager _copyAllIdentitiesWithError:usingBlock:]_block_invoke_2
- ___69+[MFMessageKeychainManager copyAllSigningIdentitiesForAddress:error:]_block_invoke
- ___72+[MFMessageKeychainManager copyAllEncryptionIdentitiesForAddress:error:]_block_invoke
- ___block_descriptor_40_e8_32b_e24_B16?0^{__SecIdentity=}8ls32l8
- ___block_descriptor_56_e8_32o40o48r_e24_B16?0^{__SecIdentity=}8lr48l8s32l8s40l8
- _flat unique So17OS_os_transaction_p
- _symbolic Spy_____SgG 9IMAP2MIME8BoundaryV
- _symbolic ______p So17OS_os_transactionP
CStrings:
+ "#SMIMEErrors Found %lu usable %{public}s identities for \"%@\""
+ "DELETE FROM properties WHERE key = 'com.apple.mail.searchableIndex.lastProcessedAttachmentIDKey';"
+ "RaveBBaseline"
+ "RaveResetBackFillMessageBodiesStages2"
+ "Resetting lastProcessedAttachmentID for attachment re-donation."
+ "encryption"
+ "signing"
- "#SMIMEErrors Found %lu (out of %lu) matching encryption identities for \"%@\""
- "#SMIMEErrors Found %lu (out of %lu) matching signing identities for \"%@\""
- "B16@?0^{__SecIdentity=}8"
- "MFMessageKeychainManagerCertificateDeniedDomain"
```
