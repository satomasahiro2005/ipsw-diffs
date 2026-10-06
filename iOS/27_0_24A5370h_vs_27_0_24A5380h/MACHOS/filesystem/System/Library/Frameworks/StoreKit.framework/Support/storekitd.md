## storekitd

> `/System/Library/Frameworks/StoreKit.framework/Support/storekitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c95ec` | `0x5bb420` | **`-0xe1cc`** |
| `__TEXT.__eh_frame` | `0x3743c` | `0x364e0` | **`-0xf5c`** |
| `__TEXT.__cstring` | `0x1ef05` | `0x1e885` | **`-0x680`** |
| `__DATA_CONST.__const` | `0x6d358` | `0x6d908` | **`+0x5b0`** |
| `__DATA.__objc_const` | `0x1d0c0` | `0x1cd68` | **`-0x358`** |
| `__TEXT.__swift5_capture` | `0x1d74c` | `0x1da18` | **`+0x2cc`** |
| `__TEXT.__unwind_info` | `0x15eb0` | `0x16158` | **`+0x2a8`** |
| `__TEXT.__objc_stubs` | `0xcc60` | `0xca00` | **`-0x260`** |
| `__TEXT.__const` | `0x3f410` | `0x3f250` | **`-0x1c0`** |
| `__TEXT.__oslogstring` | `0x70c2` | `0x6f22` | **`-0x1a0`** |
| `__DATA.__bss` | `0x567e8` | `0x56668` | **`-0x180`** |
| `__TEXT.__swift_as_cont` | `0x2ec8` | `0x2d80` | **`-0x148`** |
| `__TEXT.__swift_as_ret` | `0x1ec4` | `0x1df4` | **`-0xd0`** |
| `__TEXT.__swift_as_entry` | `0x1048` | `0xfd0` | **`-0x78`** |
| `__DATA.__data` | `0x13290` | `0x13300` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x5000` | `0x4fc0` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x1038` | `0x1068` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x737f` | `0x734f` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x4280` | `0x4260` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x11e49` | `0x11e29` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x42f8` | `0x42d8` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0xbd5e` | `0xbd40` | **`-0x1e`** |
| `__TEXT.__swift5_fieldmd` | `0xcae4` | `0xcacc` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x2150` | `0x2140` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1880` | `0x1890` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4578` | `0x4570` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x1e8` | `0x1e0` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x9328` | `0x932c` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x115c` | `0x1158` | **`-0x4`** |
| `__TEXT.__swift5_protos` | `0x78` | `0x7c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xd8c` | `0xd88` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-816.0.34.0.0
+816.0.38.0.0

-  Functions: 37514
-  Symbols:   1792
-  CStrings:  7274
+  Functions: 37215
+  Symbols:   1789
+  CStrings:  7228
Symbols:
+ _$s15Synchronization5MutexVMn
- _$s15Synchronization5MutexVMa
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlF
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlFTu
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "23:28:24"
+ "Active simulated error for manage subscriptions request: "
+ "Active simulated error for offer code redeem request: "
+ "Active simulated error for refund request: "
+ "Allowing server-driven silent authentication request without a UI context"
+ "Fetching the Octane server port is no longer supported"
+ "Ignoring legacy Octane server push action "
+ "Jun 27 2026"
+ "Listening for Octane server events is no longer supported"
+ "Updating the Octane server port is no longer supported"
+ "authenticationType"
- " because the app is not installed for development"
- " because the app was uninstalled"
- " for Octane server transaction "
- " from Octane server"
- " on Octane server for "
- " on the Octane server"
- " using Octane server"
- "\" on Octane server transaction "
- ", device is using Octane 2."
- "10:10:01"
- "Completing ask to buy request for Octane server transaction "
- "Deleting all Octane server transactions for "
- "Error looking up app with bundleID "
- "Expiring subscription "
- "Failed to change auto renew status on Octane server: "
- "Failed to complete ask to buy in Octane server: "
- "Failed to delete transactions: "
- "Failed to encode purchase configuration request: "
- "Failed to perform transaction action in Octane server: "
- "Force renewing subscription "
- "Ignoring Octane server push action "
- "Jun 13 2026"
- "No context available to handle forced Xcode authentication"
- "No message available for "
- "No storefront response from Octane server"
- "Octane server didn't return any transaction data"
- "Octane server failed to expire subscription: "
- "Octane server failed to remove overrides: "
- "Octane server failed to renew subscription: "
- "Octane server is not active, device is using Octane 2"
- "Octane server is not enabled, device is using Octane 2"
- "Performing action \""
- "Port updated to %ld"
- "Registering for event type %{public}ld with filter %{public}@"
- "Registering observation id %{public}@ to %{public}ld client(s)"
- "Removing Octane data for "
- "Removing octane server overrides for "
- "Requesting integer value "
- "Requesting string value "
- "Setting auto renew status to "
- "Unregistering observation id %{public}@ with %{public}ld clients for %{public}@"
- "Unregistering observation id %{public}@ with XPC service"
- "UseOctane2"
- "[%s] Missing developer control in server response: %{private}s"
- "[%s] Missing message parameters in server response: %{private}s"
- "[%s] Missing message type in server response: %{private}s"
- "[AccountManager] Dialogs disabled for Xcode environment. Skipping authentication."
- "[AccountManager] Simulated authentication completed with action id: "
- "[AccountManager] Simulated authentication dialog request failed: "
- "[AccountManager] Simulated authentication did complete"
- "[AccountManager] Starting Xcode authentication"
- "ams_dictionaryByAddingEntriesFromDictionary:"
- "appRemovedWithBundleID:"
- "storekitd/AccountManager.swift"
- "storekitd/InAppTransactionTask+Swift.swift"
- "storekitd/OfferEligibilityManager.swift"
- "v24@?0@\"NSError\"8@\"NSString\"16"
```
