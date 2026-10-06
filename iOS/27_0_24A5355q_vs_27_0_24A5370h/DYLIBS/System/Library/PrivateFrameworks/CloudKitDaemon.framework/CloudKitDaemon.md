## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/CloudKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d7ec0` | `0x3da15c` | **`+0x229c`** |
| `__TEXT.__oslogstring` | `0x31b9a` | `0x3207f` | **`+0x4e5`** |
| `__TEXT.__cstring` | `0x2a8d4` | `0x2ab75` | **`+0x2a1`** |
| `__AUTH_CONST.__cfstring` | `0x233e0` | `0x23680` | **`+0x2a0`** |
| `__AUTH_CONST.__objc_const` | `0x4a740` | `0x4a9c0` | **`+0x280`** |
| `__TEXT.__objc_methlist` | `0x311f4` | `0x31434` | **`+0x240`** |
| `__TEXT.__unwind_info` | `0xcd78` | `0xce78` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x12e18` | `0x12f10` | **`+0xf8`** |
| `__DATA_CONST.__const` | `0x98d8` | `0x99b0` | **`+0xd8`** |
| `__AUTH.__objc_data` | `0x5990` | `0x5a30` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x58b0` | `0x5830` | **`-0x80`** |
| `__TEXT.__gcc_except_tab` | `0xc5b4` | `0xc62c` | **`+0x78`** |
| `__TEXT.__dlopen_cstrs` | `0x68` | `—` | **`-0x68`** |
| `__TEXT.__const` | `0x4d18` | `0x4cb8` | **`-0x60`** |
| `__DATA.__bss` | `0x31c0` | `0x31a0` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x1aa0` | `0x1a80` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0xb0c` | `0xb2c` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1126` | `0x1106` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1264` | `0x1248` | **`-0x1c`** |
| `__TEXT.__swift5_typeref` | `0x1f97` | `0x1f7d` | **`-0x1a`** |
| `__DATA.__objc_ivar` | `0x1a6c` | `0x1a84` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xc8` | `0xb4` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x14c0` | `0x14d0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x13a0` | `0x13b0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x198` | `0x1a8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2150` | `0x2158` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1dc0` | `0x1dc8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x3228` | `0x3230` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x138` | `0x134` | **`-0x4`** |

### Other Changes

```diff

-2710.108.20.0.0
+2710.112.0.0.0

+  - /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration

-  Functions: 20611
-  Symbols:   2941
-  CStrings:  8381
+  Functions: 20670
+  Symbols:   2942
+  CStrings:  8407
Symbols:
+ _CKTestDeviceOptionConcurrentZoneReadingDisabled
+ _MarkForCounterSigning
+ _PCSNeedsRollAndCounterSign
+ _PCSObjectCreateFromExportedWithKeyedPCSAndOptionsWithTrusts
- _$ss6UInt32VMn
- _dlerror
- _dlsym
CStrings:
+ "\t\t%@ [%@] -> %@"
+ "Adding missing identity public keys for a different account. Current account: %@, new account: %@"
+ "Adding missing service identities for a different account. Current account: %@, new account: %@"
+ "Asset handles span multiple volumes"
+ "B16@?0@\"CKRecordZone\"8"
+ "Can't grant exclusive gate to waiter %@ because zone %@ is held"
+ "Can't grant shared gate to waiter %@ because zone %@ held exclusively"
+ "Can't immediately grant exclusive gate to %@ because zone %@ is held"
+ "Can't immediately grant shared gate to %@ because zone %@ held exclusively"
+ "CombinedPCSSizePerZone"
+ "CorruptRootZonePCSBeforeSave"
+ "Couldn't decrypt ancestor %@ for zone %@"
+ "Couldn't decrypt root share PCS while refreshing parent ancestry for stale cached child zone %@"
+ "Couldn't decrypt root share PCS while refreshing stale cached PCS for zone %@"
+ "Couldn't fetch server ancestry while refreshing stale cached PCS for zone %@"
+ "Couldn't refresh parent ancestry for stale cached child zone %@"
+ "Couldn't refresh parent ancestry for stale cached child zone %@ because fetched ancestry did not include parent %@"
+ "Couldn't refresh stale cached PCS for zone %@ because fetched ancestry was incomplete"
+ "Didn't get decrypted zoneish pcs to roll- soldiering on. We're probably using per-record PCS."
+ "Error initializing fake account with email %s, no error available"
+ "Expected 2 arguments for function distanceToLocation:fromLocation: %@"
+ "Failed to roll the identity for pcs %@ (type: %{public}@, identifier: %{public}@): %@"
+ "Fetched server ancestry for shared DB zone %@ after cached-parent PCS decrypt failure"
+ "Fetched shared DB parent ancestry for %@ while recovering stale child %@, but the parent was missing from the fetched ancestry: %@"
+ "Handling key rolling for zone %@. allowServiceIdentityRolling: %@. allowShareChangeRolling: %@"
+ "In-flight asset handles marked as interrupted during un/registering:%llu upload:%llu download:%llu item unregistered:%llu"
+ "MaxPCSSizeForMultiZoneKeyRoll"
+ "MaxPCSSizeForSingleZoneKeyRoll"
+ "Refusing to add an invited PCS to a nil zone PCS"
+ "Registering zone gate locks for IDs %@ waiter %@ accessMode %@"
+ "Rehydrated shared DB parent ancestry PCS cache for %@ after evicting stale child %@"
+ "Repair asset sub-operation <%{public}@: %p; %{public}@> for operation <%{public}@: %p; %{public}@> completed repair record update"
+ "Retrying shared DB zone PCS decrypt for %@ after refreshing server ancestry"
+ "Reusing already-rolled PCS for shared ancestor zone %@ (diamond dedup)"
+ "Rolled the identity for pcs %@ (type: %{public}@, identifier: %{public}@)"
+ "Shared DB cached-parent PCS recovery for zone %@ completed successfully"
+ "Shared DB cached-parent PCS recovery for zone %@ finished with error %@"
+ "Shared DB zone %@ failed to decrypt with cached parent %@ PCS. Fetching zone ancestry to refresh PCS cache. Error: %@"
+ "Test override: corrupted root zone %@ PCS bytes before save"
+ "We don't have a root share PCS to decrypt zone ancestry for zone %@"
+ "You can't add an invited PCS to a nil zone PCS"
+ "Zone %@ has parent %@. Attempting to recursively fetch ancestry from the cache."
+ "Zone %@ was not found during shared DB cached-parent PCS recovery. Evicting stale cached child PCS and refreshing parent %@ ancestry."
+ "Zone %@ was not found while refreshing stale cached PCS"
+ "Zone PCS recovery operation was cancelled while evicting stale cached PCS for zone %@"
+ "Zone PCS recovery operation was cancelled while refreshing stale cached PCS for zone %@"
+ "cache clone context for package item with signature %@"
+ "concurrentZoneReadingDisabled"
+ "exclusive"
+ "missing PCS"
+ "req: %{public}@, \"%@ Requires zone id gates, grabbing them from gatekeeper, expectDelay %{public}@ accessMode %{public}@\""
+ "req: %{public}@, \"Warn: Dropping protobuf result since we've already returned it to the client. This likely happened because of a request timeout.\""
+ "setTestingLeafZoneIDToAncestorChains is only available in testing"
+ "shared"
+ "waiter=%@, zoneIDs=%@, accessMode=%@"
- "\t\t%@ -> %@"
- "Asset handles span multiple volumnes"
- "CKMarkForCounterSigning"
- "CKMarkForCounterSigning is not defined. Skipping counterSignRecordPCS"
- "Can't grant gate to waiter %@ because zone %@ held by %@"
- "Can't immediately grant gate to %@ because zone %@ held by %@"
- "Couldn't clean up old private keys from PCS for zone %@: %@"
- "Didn't get decrypted zoneish pcs to roll- solidering on. We're probably using per-record PCS."
- "Error initializing fake account with email %s,  no error available"
- "Expected expected 2 arguments for function distanceToLocation:fromLocation: %@"
- "Failed to roll the identity for pcs %@: %@"
- "Handling key rolling for zone %@. allowServiceIdentityRolling: %@. allowShareChangeRolling: %@. allowRemovingOldZoneKeysForZoneish: %@"
- "In-flight asset handles marked as interrupted during un/registering:%llu upload:%llu download:%llu item unregistred:%llu"
- "MarkForCounterSigning"
- "PCSNeedsRollAndCounterSign"
- "PCSObjectCreateFromExportedWithKeyedPCSAndOptionsWithTrusts"
- "PCSShareProtectionRef CKPCSObjectCreateFromExportedWithKeyedPCSAndOptionsWithTrusts(PCSShareProtectionRef, NSDictionary<PCSFPOption,id> *__strong, CFDataRef, NSArray *__strong, CFErrorRef *)"
- "Registering zone gate locks for IDs %@ waiter %@"
- "Repair asset sub-operation <%{public}@: %p; %{public}@> for operaiton <%{public}@: %p; %{public}@> completed repair record update"
- "Rolled the identity for pcs %@"
- "Zone %@ has parent %@. Attempting to fetch recursively fetch ancestry from the cache."
- "_Bool CKMarkForCounterSigning(PCSShareProtectionRef, PCSShareProtectionRef)"
- "_Bool CKPCSNeedsRollAndCounterSign(CFDataRef, CFErrorRef *)"
- "cache clone context for pacakge item with signature %@"
- "req: %{public}@, \"%@ Requires zone id gates, grabbing them from gatekeeper, expectDelay %{public}@\""
- "req: %{public}@, \"Warn: Dropping protobuf result since we've alredy returned it to the client. This likely happened because of a request timeout.\""
- "softlink:r:path:/System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage"
- "void *ProtectedCloudStorageLibrary(void)"
- "waiter=%@, zoneIDs=%@"
```
