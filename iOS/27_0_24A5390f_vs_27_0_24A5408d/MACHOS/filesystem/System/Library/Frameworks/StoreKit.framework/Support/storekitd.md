## storekitd

> `/System/Library/Frameworks/StoreKit.framework/Support/storekitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b362c` | `0x5d0478` | **`+0x1ce4c`** |
| `__DATA_CONST.__const` | `0x6d538` | `0x709f8` | **`+0x34c0`** |
| `__TEXT.__swift5_capture` | `0x1d93c` | `0x1ed54` | **`+0x1418`** |
| `__TEXT.__eh_frame` | `0x36350` | `0x37028` | **`+0xcd8`** |
| `__DATA.__bss` | `0x562e8` | `0x56d68` | **`+0xa80`** |
| `__TEXT.__const` | `0x3f0d0` | `0x3f690` | **`+0x5c0`** |
| `__TEXT.__unwind_info` | `0x16010` | `0x16348` | **`+0x338`** |
| `__TEXT.__cstring` | `0x1e445` | `0x1e6b5` | **`+0x270`** |
| `__DATA.__data` | `0x132c0` | `0x13450` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0xbc9a` | `0xbe24` | **`+0x18a`** |
| `__TEXT.__swift_as_cont` | `0x2d4c` | `0x2e68` | **`+0x11c`** |
| `__TEXT.__constg_swiftt` | `0x9300` | `0x9408` | **`+0x108`** |
| `__DATA.__objc_const` | `0x1c9d8` | `0x1cad8` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0xc500` | `0xc600` | **`+0x100`** |
| `__DATA.__objc_data` | `0x5148` | `0x5210` | **`+0xc8`** |
| `__TEXT.__objc_methname` | `0x115b9` | `0x11679` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0xcacc` | `0xcb80` | **`+0xb4`** |
| `__TEXT.__objc_methlist` | `0x78ac` | `0x7944` | **`+0x98`** |
| `__TEXT.__swift_as_ret` | `0x1dd0` | `0x1e68` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x738f` | `0x73ff` | **`+0x70`** |
| `__TEXT.__objc_classname` | `0x25ff` | `0x265f` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x2cfc` | `0x2d50` | **`+0x54`** |
| `__DATA.__objc_selrefs` | `0x4390` | `0x43d8` | **`+0x48`** |
| `__DATA_CONST.__auth_ptr` | `0x18a8` | `0x18e0` | **`+0x38`** |
| `__TEXT.__swift_as_entry` | `0xfb0` | `0xfe8` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x4ea0` | `0x4ec0` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0xd88` | `0xda0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x320` | `0x334` | **`+0x14`** |
| `__DATA.__common` | `0x10a0` | `0x10b0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4250` | `0x4260` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x7c` | `0x8c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1094` | `0x10a0` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x2138` | `0x2140` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x618` | `0x620` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-816.0.41.0.0
+816.0.47.2.2

-  Functions: 36989
-  Symbols:   1788
-  CStrings:  7097
+  Functions: 37803
+  Symbols:   1792
+  CStrings:  7126
Symbols:
+ _$sSh11descriptionSSvg
+ _$ss25LosslessStringConvertibleMp
+ _$ss25LosslessStringConvertiblePs06CustombC0Tb
+ _$ss25LosslessStringConvertiblePyxSgSScfCTq
+ _NSSelectorFromString
- _swift_unknownObjectRetain_n
CStrings:
+ " INTEGER,\n\nPRIMARY KEY ("
+ " app transaction sync task already in progress."
+ " app transaction sync task with lower priority."
+ " app transaction. forceAuth: "
+ " is not supported for StoreKit Testing"
+ " is using Octane per forced overrides, skipping signature check"
+ ". Returning cached value."
+ "19:59:14"
+ "Aug  6 2026"
+ "Authenticating account for request parameters."
+ "Backing off for sync error "
+ "Busting AMSBagCache for "
+ "Deleting all transactions and data for "
+ "Encoded request parameters (Never) is not valid JSON"
+ "Error recording app transaction sync failure: "
+ "Error while syncing revoked AppTransaction: "
+ "Failed to get last sync error: "
+ "T@\"<AMSBagProtocol>\",N,R"
+ "T@\"NSData\",N,C"
+ "Updating AppTransaction for "
+ "Updating revoked AppTransaction"
+ "_TtC9storekitdP33_7F93F1DD2C0429010C2756FB991A282531AppTransactionSyncFailureEntity"
+ "app-transaction-disable-managed-account"
+ "app-transaction-sync-backoff-interval"
+ "app-transaction-sync-extended-backoff-errors"
+ "app-transaction-sync-extended-backoff-interval"
+ "appTransactionDisableManagedAccount"
+ "appTransactionSyncBackOffInterval"
+ "appTransactionSyncExtendedBackOffErrors"
+ "appTransactionSyncExtendedBackOffInterval"
+ "app_transaction_sync_failures"
+ "auditTokenData"
+ "bagForProfile:profileVersion:processInfo:account:"
+ "cacheQueryInterval"
+ "cacheQueryInterval(reply:)"
+ "cacheQueryIntervalWithReply:"
+ "developerErrorCode"
+ "developerErrorMessage"
+ "dialog"
+ "hostAuditTokenData"
+ "initWithPurchase:"
+ "setHostAuditTokenData:"
+ "setPurchaseInfo:"
+ "storekit-cache-query-interval"
- "05:56:33"
- "Awaiting app transaction sync task already in progress."
- "Deleting all transactions for "
- "Invalid device serial number for AppTransaction request."
- "Jul 11 2026"
- "Missing account token for AppTransaction request."
- "Replacing app transaction sync task with lower priority."
- "Syncing app transaction. forceAuth: "
- "T@\"<AMSBagProtocol>\",N,&"
- "Updating AppTransaction to "
- "dialog.developerErrorCode"
- "dialog.developerErrorMessage"
- "setDefaultBag:"
- "setSandboxBag:"
- "setTestflightBag:"
```
