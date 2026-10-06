## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80968` | `0x85664` | **`+0x4cfc`** |
| `__TEXT.__cstring` | `0x113aa` | `0x120b3` | **`+0xd09`** |
| `__TEXT.__objc_methname` | `0x1220a` | `0x12795` | **`+0x58b`** |
| `__DATA_CONST.__cfstring` | `0x8480` | `0x8940` | **`+0x4c0`** |
| `__TEXT.__oslogstring` | `0xef5b` | `0xf36a` | **`+0x40f`** |
| `__DATA.__objc_const` | `0x9e20` | `0xa1b0` | **`+0x390`** |
| `__TEXT.__objc_stubs` | `0xaea0` | `0xb1c0` | **`+0x320`** |
| `__TEXT.__gcc_except_tab` | `0x2a9c` | `0x2d88` | **`+0x2ec`** |
| `__TEXT.__objc_methlist` | `0x50b4` | `0x52f4` | **`+0x240`** |
| `__DATA.__objc_selrefs` | `0x3488` | `0x35a8` | **`+0x120`** |
| `__DATA_CONST.__objc_arraydata` | `0x1550` | `0x1620` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x1890` | `0x1940` | **`+0xb0`** |
| `__DATA.__objc_data` | `0x12c0` | `0x1360` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x26f0` | `0x2788` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x430` | `0x4a8` | **`+0x78`** |
| `__TEXT.__objc_methtype` | `0x22b4` | `0x22f6` | **`+0x42`** |
| `__TEXT.__objc_classname` | `0x69c` | `0x6ce` | **`+0x32`** |
| `__DATA.__objc_ivar` | `0x6d8` | `0x708` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0x648` | `0x660` | **`+0x18`** |
| `__DATA.__bss` | `0x429` | `0x439` | **`+0x10`** |
| `__DATA.__data` | `0x720` | `0x730` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1640` | `0x1650` | **`+0x10`** |
| `__TEXT.__const` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xb30` | `0xb38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-906.0.0.0.0
+909.0.0.0.0

-  Functions: 2830
-  Symbols:   503
-  CStrings:  5608
+  Functions: 2918
+  Symbols:   505
+  CStrings:  5737
Symbols:
+ _NSClassFromString
+ _NSURLIsExcludedFromBackupKey
CStrings:
+ "%@, adminAuth: %lld, userAuth: %lld, authReason: %d, v=%llu"
+ "%s: managed override: %@ -> %@"
+ "%{public}s: No changed needed for %{public}@ NeedPrompt: %d"
+ "%{public}s: SQL Statement Exec Result %{public}@ NeedPrompt: %d"
+ "-[TCCDDirectoryManager checkIsPathInRootVolume:]"
+ "-[TCCDDisclosureCache recomputeForIdentifier:]"
+ "-[TCCDDisclosureCache recomputeForIdentifier:]_block_invoke"
+ "-[TCCDDisclosureCache recomputeForIdentifier:]_block_invoke_3"
+ "/private/var/mobile/Library/ManagedAppPrivacy"
+ "/private/var/mobile/Library/ManagedAppPrivacy/managed_disclosure_cache.plist"
+ "2G98R5QYU5/com.kingsoft.wpsoffice.mac.global"
+ "3E9E9FN277/com.graphisoft.archicad29"
+ "4788TTJ39Y/com.wiheads.paste"
+ "4EJSV8E65Y/com.druide.AgentAntidote"
+ "4SNPZZ27XN/eziowave"
+ "79RR9LPM2N/com.macitbetter.betterzip"
+ "829ZY6G65P/com.seclore.SecloreLite.InstallHelper"
+ "8S7YS6Z5ZQ/com.ametiq.simed"
+ "97GAAZ6CPX/com.renewedvision.propresenter"
+ "@\"TCCDDisclosureCache\""
+ "@\"TCCDManagedSettings\""
+ "A43FW9RYK2/com.mendeley.desktop"
+ "AU2ALARPUP/com.fasttracksoftware.adminbyrequest"
+ "B32@0:8@16@?24"
+ "BJ4HAAB9B3/us.zoom.pluginagent"
+ "D6XDM4N99E/com.mcneel.rhinoceros.8"
+ "DE8Y96K9QP/com.cisco.webex.pluginservice"
+ "DE8Y96K9QP/com.cisco.webexmeetingsapp"
+ "DELETE FROM access  WHERE service = ? AND client = ? AND client_type = ?"
+ "DELETE FROM managed_overrides  WHERE service = ? AND client = ? AND client_type = ?"
+ "DisclosureCache: failed to create %{public}@: %{public}@"
+ "DisclosureCache: predicate query failed for %{public}@: %d"
+ "DisclosureCache: rebuild query failed: %d"
+ "DisclosureCache: serialize failed: %{public}@"
+ "DisclosureCache: unable to exclude cache from backup for file"
+ "DisclosureCache: unable to exclude from backup (error: %@)"
+ "DisclosureCache: write failed to %{public}@: %{public}@"
+ "EEUF3NPG73/com.exclaimer.csua"
+ "Have %lu managed override actions from the database."
+ "HealthKit reminder: healthKitAPIOverride=ForceAvailable, simulating successful reset for %{public}@"
+ "HealthKit reminder: healthKitAPIOverride=ForceUnavailable, simulating framework-unavailable for %{private}@"
+ "INSERT INTO managed_overrides   (service, client, client_type, admin_auth_value, auth_value,    auth_reason, auth_version, flags, last_modified) VALUES (?, ?, ?, ?, ?, ?, ?, 0, CAST(strftime('%s','now') AS INTEGER)) ON CONFLICT(service, client, client_type, indirect_object_identifier) DO UPDATE SET   admin_auth_value = excluded.admin_auth_value,   auth_value       = excluded.auth_value,   auth_reason      = excluded.auth_reason,   auth_version     = excluded.auth_version,   last_modified    = CAST(strftime('%s','now') AS INTEGER)"
+ "LFNG3Q6WX2/net.nemetschek.vectorworks"
+ "NSSiriUsageDescription"
+ "QED4VVPZWA/com.logi.pluginservice"
+ "S5LKE7JNDX/com.roli.hub"
+ "S8EX82NJP6/com.macpaw.site.theunarchiver"
+ "SELECT 1 FROM managed_overrides WHERE client = ? AND NOT (flags & ?) AND NOT (flags & ?) LIMIT 1"
+ "SELECT 1 FROM managed_overrides WHERE service = ? AND client = ? AND client_type = ?"
+ "SELECT DISTINCT client FROM managed_overrides WHERE NOT (flags & ?) AND NOT (flags & ?)"
+ "SELECT admin_auth_value, auth_value, flags FROM managed_overrides WHERE service = ? AND client = ? AND client_type = ?"
+ "SELECT admin_auth_value, auth_version FROM managed_overrides WHERE service = ? AND client = ? AND client_type = ?"
+ "SELECT admin_auth_value, auth_version, auth_reason FROM managed_overrides WHERE service = ? AND client = ? AND client_type = ?"
+ "SELECT service, client, client_type FROM managed_overrides"
+ "SELECT service, client, client_type, auth_value, admin_auth_value, auth_reason, auth_version FROM managed_overrides WHERE NOT (flags & ?)"
+ "SetHealthKitAPIOverride"
+ "SetHealthKitAPIOverride: %{public}lld"
+ "Syncing managed override for newly installed WatchKit application: %@"
+ "T@\"NSMutableDictionary\",&,N,V_entries"
+ "T@\"NSObject<OS_dispatch_queue>\",&,N,V_queue"
+ "T@\"TCCDDisclosureCache\",R,N,V_disclosureCache"
+ "T@\"TCCDMainDatabase\",&,N,V_database"
+ "T@\"TCCDManagedSettings\",&,N,V_managedSettings"
+ "TB,N,V_directoryEnsured"
+ "TB,N,V_usageStringPolicyAuthorizedByForwarder"
+ "TCCDDisclosureCache"
+ "TCCDSyncManagedOverrideAction"
+ "TCCDSyncManagedOverrideAdminAuthValueKey"
+ "TCCDSyncManagedOverrideAuthReasonKey"
+ "TCCDSyncManagedOverrideAuthVersionKey"
+ "TCCDSyncManagedOverrideUserAuthValueKey"
+ "TCCD_MSG_MESSAGE_OPTION_USAGE_STRING_POLICY_AUTHORIZED_BY_FORWARDER_KEY"
+ "Ti,V_authReason"
+ "Tq,V_adminAuthValue"
+ "Tq,V_healthKitAPIOverride"
+ "Tq,V_userAuthValue"
+ "UPDATE managed_overrides    SET auth_value = ?,        flags = (flags | ?),        last_modified = CAST(strftime('%s','now') AS INTEGER)  WHERE service = ? AND client = ? AND client_type = ?"
+ "XXKJ396S2Y/com.autodesk.AutoCAD2024"
+ "XXKJ396S2Y/com.autodesk.AutoCAD2027"
+ "XXKJ396S2Y/com.autodesk.AutoCADLT2026_StandAlone"
+ "_adminAuthValue"
+ "_authReason"
+ "_directoryEnsured"
+ "_disclosureCache"
+ "_ensureDirectoryLocked"
+ "_entries"
+ "_healthKitAPIOverride"
+ "_managedSettings"
+ "_resetRemovedManagedTCCDefaultsWithPermissionsMap:"
+ "_setTestCacheDir:path:"
+ "_updateManagedTCCDefaultsWithPermissionsMap:"
+ "_usageStringPolicyAuthorizedByForwarder"
+ "_userAuthValue"
+ "_writeFileLocked"
+ "a781cb9f-7992-4ee7-a6ba-723b6fb0b65e"
+ "adminAuthValue"
+ "applying change: managed override: %@ -> %@"
+ "authReason"
+ "canOverridePromptPolicyForRequestor:withForwarderStamp:"
+ "checkIsPathInRootVolume:"
+ "checkLegacyDatabaseRegisteredAtPath:"
+ "com.apple.private.tcc.system-tccd-forwarder"
+ "com.apple.tccd.disclosure-cache"
+ "directoryEnsured"
+ "disclosureCache"
+ "entries"
+ "healthKitAPIOverride"
+ "internalQueue"
+ "isAuthSetViaDisclosurePrompt"
+ "launch_angel_full_sheet_prompt"
+ "managedSettings"
+ "peerSupportsManagedOverridesSync"
+ "permissionsMapFromTCCDefaults:"
+ "rebuildFromDatabase"
+ "recomputeForIdentifier:"
+ "registerNewDatabaseAtPath:"
+ "sendMessageAsyncToSystemTCCD:withReplyBlock:"
+ "sendMessageSyncToSystemTCCD:"
+ "setAdminAuthValue:"
+ "setAuthReason:"
+ "setDirectoryEnsured:"
+ "setEntries:"
+ "setHealthKitAPIOverride:"
+ "setManagedSettings:"
+ "setResourceValue:forKey:error:"
+ "setUsageStringPolicyAuthorizedByForwarder:"
+ "setUserAuthValue:"
+ "setValue:forKey:"
+ "string"
+ "tccd_replica_sync_update_from_ManagedOverrideAction: missing service or client identifier"
+ "usageStringPolicyAuthorizedByForwarder"
+ "userAuthValue"
+ "v32@0:8r*16r*24"
+ "validateExistingDatabaseAtPath:"
+ "writeToURL:options:error:"
- "-[TCCDDirectoryManager isPathInRootVolume:]"
- "SELECT admin_auth_value FROM managed_overrides WHERE service = ? AND client = ? AND client_type = ?"
- "_resetRemovedManagedTCCDefaults:"
- "_updateManagedTCCDefaults:"
- "c24@0:8@16"
- "isPathInRootVolume:"
```
