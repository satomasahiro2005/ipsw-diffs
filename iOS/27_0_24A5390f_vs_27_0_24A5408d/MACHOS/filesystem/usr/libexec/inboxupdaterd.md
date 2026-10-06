## inboxupdaterd

> `/usr/libexec/inboxupdaterd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0xcee3` | `0x11573` | **`+0x4690`** |
| `__TEXT.__text` | `0x8c1f8` | `0x8cd98` | **`+0xba0`** |
| `__DATA_CONST.__const` | `0xedc0` | `0xf2d0` | **`+0x510`** |
| `__DATA.__objc_const` | `0x9610` | `0x9a28` | **`+0x418`** |
| `__TEXT.__objc_methname` | `0x8ed6` | `0x90c2` | **`+0x1ec`** |
| `__TEXT.__cstring` | `0x5394` | `0x5510` | **`+0x17c`** |
| `__TEXT.__objc_stubs` | `0x8860` | `0x89a0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x409c` | `0x4184` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0xa7fc` | `0xa882` | **`+0x86`** |
| `__DATA_CONST.__cfstring` | `0x4c40` | `0x4cc0` | **`+0x80`** |
| `__DATA.__data` | `0x2568` | `0x25c8` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x17d4` | `0x1778` | **`-0x5c`** |
| `__DATA.__objc_selrefs` | `0x2708` | `0x2760` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x5d8` | `0x598` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1f68` | `0x1f98` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x1779` | `0x1795` | **`+0x1c`** |
| `__TEXT.__objc_classname` | `0x670` | `0x687` | **`+0x17`** |
| `__DATA.__objc_ivar` | `0x444` | `0x454` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1530` | `0x1520` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xaa8` | `0xaa0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xd0` | `0xd8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-274.0.9.0.0
+274.2.1.0.0

-  Functions: 4243
-  Symbols:   519
-  CStrings:  3741
+  Functions: 4272
+  Symbols:   510
+  CStrings:  3766
Symbols:
- _SecItemDelete
- _kMAOptionsBAAIgnoreExistingKeychainItems
- _kMAOptionsBAAKeychainAccessGroup
- _kMAOptionsBAAKeychainLabel
- _kSecAttrAccessGroup
- _kSecAttrLabel
- _kSecClass
- _kSecClassCertificate
- _kSecClassKey
CStrings:
+ "&A"
+ "@\"<MIBUWiFiHelperDelegate>\""
+ "BAA credential fetch failed after %lu attempt(s)"
+ "BAA credentials obtained on attempt %lu"
+ "BAA fetch aborted before attempt %lu: reporter invalidated"
+ "Dropping status report: reporter invalidated"
+ "Failed to create SecAccessControl on attempt %lu: %{public}@"
+ "Failed to generate BAA nonce on attempt %lu; aborting"
+ "Failed to obtain BAA certificates: %{public}@"
+ "MIBUWiFiHelperDelegate"
+ "Network dropped after going online; arming network-loss watchdog"
+ "Network lost for more than %d seconds after going online"
+ "Network restored; cancelling network-loss watchdog"
+ "Personalization network-loss watchdog timer fired!"
+ "Requesting BAA certs (attempt %lu/%lu)"
+ "Starting personalization network-loss watchdog timer with %ds timeout..."
+ "Stopping personalization network-loss watchdog timer..."
+ "Stopping status POST retries: reporter invalidated"
+ "T@\"<MIBUWiFiHelperDelegate>\",W,N,V_delegate"
+ "T@\"PCPersistentTimer\",&,N,V_networkLossWatchdogTimer"
+ "TB,N,V_lastNetworkAvailable"
+ "_fireWatchdogTimeoutWithError:"
+ "_invalidated"
+ "_isInvalidated"
+ "_lastNetworkAvailable"
+ "_networkLossWatchdogTimer"
+ "_startNetworkLossWatchdogTimer"
+ "_stopAllWatchdogTimers"
+ "_stopNetworkLossWatchdogTimer"
+ "com.apple.mobileinboxupdater.personalizationnetworkwatchdog"
+ "handleNetworkLossWatchdogTimer:"
+ "https://product-personalization-coreos.ext.pos.apple.com"
+ "lastNetworkAvailable"
+ "networkConnectivityDidDrop"
+ "networkConnectivityDidRestore"
+ "networkLossWatchdogTimer"
+ "setLastNetworkAvailable:"
+ "setNetworkLossWatchdogTimer:"
+ "wifiHelperDidLoseNetwork"
+ "wifiHelperDidRegainNetwork"
- "BAA cert request finished"
- "BAA credential fetch timed out after %d seconds"
- "Failed to create SecAccessControl: %{public}@"
- "Failed to delete BAA %{public}@ from keychain: %d"
- "Failed to fetch. err: %@"
- "Failed to generate BAA nonce; aborting credential fetch"
- "Failed to obtain BAA certificates: %@"
- "Requesting BAA certs"
- "_deleteBAAKeychainItems"
- "certificate"
- "dictionaryWithDictionary:"
- "https://production-personalization-coreos.ext.pos.apple.com"
- "inboxupdaterd"
- "initWithArray:"
- "key"
```
