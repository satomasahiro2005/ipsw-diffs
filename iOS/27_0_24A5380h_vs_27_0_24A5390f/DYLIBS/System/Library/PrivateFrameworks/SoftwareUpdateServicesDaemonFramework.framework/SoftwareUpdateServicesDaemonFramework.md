## SoftwareUpdateServicesDaemonFramework

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesDaemonFramework.framework/SoftwareUpdateServicesDaemonFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x625b0` | `0x62df4` | **`+0x844`** |
| `__TEXT.__cstring` | `0x10a01` | `0x110f8` | **`+0x6f7`** |
| `__AUTH_CONST.__cfstring` | `0x89a0` | `0x8c80` | **`+0x2e0`** |
| `__AUTH_CONST.__objc_const` | `0x81a8` | `0x83d0` | **`+0x228`** |
| `__TEXT.__objc_methlist` | `0x505c` | `0x51a4` | **`+0x148`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d68` | `0x3e38` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x1340` | `0x13f8` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x190` | `0x230` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x19e0` | `0x1a60` | **`+0x80`** |
| `__DATA.__data` | `0x7e0` | `0x840` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x760` | `0x7a8` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x340` | `0x360` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xab0` | `0xad0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x340` | `0x354` | **`+0x14`** |
| `__DATA.__bss` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x138` | `0x148` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xf0` | `0x100` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0x90` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__const` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-1107.0.0.0.0
+1112.0.1.0.0

+  - /System/Library/PrivateFrameworks/LowPowerMode.framework/LowPowerMode

-  Functions: 2106
-  Symbols:   3370
-  CStrings:  1480
+  Functions: 2142
+  Symbols:   3435
+  CStrings:  1507
Symbols:
+ +[SUCSPNMonitor sharedMonitor]
+ +[SUDaemonHelper shared]
+ -[SUCSPNMonitor .cxx_destruct]
+ -[SUCSPNMonitor SUCSPNStateToString:]
+ -[SUCSPNMonitor _handleCSPNStateChange:]
+ -[SUCSPNMonitor bucketTimestampIn10Minutes:]
+ -[SUCSPNMonitor init]
+ -[SUCSPNMonitor queue]
+ -[SUCSPNMonitor setQueue:]
+ -[SUCSPNMonitor startMonitoring]
+ -[SUCSPNMonitor stateHistory]
+ -[SUCSPNMonitor stopMonitoring]
+ -[SUCSPNMonitor telemetryDictionary]
+ -[SUDaemonHelper .cxx_destruct]
+ -[SUDaemonHelper connectionEnsured]
+ -[SUDaemonHelper connectionQueue]
+ -[SUDaemonHelper connection]
+ -[SUDaemonHelper dealloc]
+ -[SUDaemonHelper init]
+ -[SUDaemonHelper setConnection:]
+ -[SUDaemonHelper trialBGSTAutoUpdateEnabledWithError:]
+ -[SUManagerCore powerNapMonitor]
+ -[SUScanner hasAlternateUpdateFallbackWindowElapsedForPreferred:alternate:]
+ GCC_except_table4
+ GCC_except_table77
+ GCC_except_table89
+ _OBJC_CLASS_$_SUCSPNMonitor
+ _OBJC_CLASS_$_SUDaemonHelper
+ _OBJC_CLASS_$__PMCoreSmartPowerNap
+ _OBJC_IVAR_$_SUCSPNMonitor._cspn
+ _OBJC_IVAR_$_SUCSPNMonitor._queue
+ _OBJC_IVAR_$_SUDaemonHelper._connection
+ _OBJC_IVAR_$_SUDaemonHelper._connectionQueue
+ _OBJC_IVAR_$_SUManagerCore._powerNapMonitor
+ _OBJC_METACLASS_$_SUCSPNMonitor
+ _OBJC_METACLASS_$_SUDaemonHelper
+ __OBJC_$_CLASS_METHODS_SUCSPNMonitor
+ __OBJC_$_CLASS_METHODS_SUDaemonHelper
+ __OBJC_$_INSTANCE_METHODS_SUCSPNMonitor
+ __OBJC_$_INSTANCE_METHODS_SUDaemonHelper
+ __OBJC_$_INSTANCE_VARIABLES_SUCSPNMonitor
+ __OBJC_$_INSTANCE_VARIABLES_SUDaemonHelper
+ __OBJC_$_PROP_LIST_SUCSPNMonitor
+ __OBJC_$_PROP_LIST_SUDaemonHelper
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SUDaemonHelperServiceProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SUDaemonHelperServiceProtocol
+ __OBJC_CLASS_RO_$_SUCSPNMonitor
+ __OBJC_CLASS_RO_$_SUDaemonHelper
+ __OBJC_LABEL_PROTOCOL_$_SUDaemonHelperServiceProtocol
+ __OBJC_METACLASS_RO_$_SUCSPNMonitor
+ __OBJC_METACLASS_RO_$_SUDaemonHelper
+ __OBJC_PROTOCOL_$_SUDaemonHelperServiceProtocol
+ __OBJC_PROTOCOL_REFERENCE_$_SUDaemonHelperServiceProtocol
+ ___24+[SUDaemonHelper shared]_block_invoke
+ ___29-[SUCSPNMonitor stateHistory]_block_invoke
+ ___30+[SUCSPNMonitor sharedMonitor]_block_invoke
+ ___31-[SUCSPNMonitor stopMonitoring]_block_invoke
+ ___32-[SUCSPNMonitor startMonitoring]_block_invoke
+ ___32-[SUCSPNMonitor startMonitoring]_block_invoke_2
+ ___35-[SUDaemonHelper connectionEnsured]_block_invoke
+ ___54-[SUDaemonHelper trialBGSTAutoUpdateEnabledWithError:]_block_invoke
+ ___54-[SUDaemonHelper trialBGSTAutoUpdateEnabledWithError:]_block_invoke_2
+ ___NSArray0__struct
+ ___block_descriptor_40_e8_32r_e17_v16?0"NSError"8lr32l8
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___block_descriptor_40_e8_32w_e8_v12?0C8lw32l8
+ ___block_descriptor_48_e8_32r40r_e20_v20?0B8"NSError"12lr32l8r40l8
+ _shared.__helper
+ _shared.onceToken
- -[SUManagerCore isDescriptorAutoUpdatable:]
- GCC_except_table76
- GCC_except_table85
- GCC_except_table88
CStrings:
+ "%s - Cannot compute fallback window: preferred releaseDate=%@, alternate releaseDate=%@"
+ "%s - Fallback window elapsed, auto-downloading older update %@"
+ "%s - One or both updates are still ramped (preferred=%d, alternate=%d)"
+ "%s - Using override fallback interval: %f seconds"
+ "%s - Window start: %@, elapsed: %.0f seconds, fallback interval: %.0f seconds, elapsed=%@"
+ "%s: Failed to get data from Trial: %@"
+ "%s: Using BGST because it's enabled by Trial"
+ "-[SUScanner hasAlternateUpdateFallbackWindowElapsedForPreferred:alternate:]"
+ "0:00"
+ "CSPN monitor already active, do nothing"
+ "CSPN monitoring started"
+ "CSPN monitoring stopped"
+ "CSPN state changed to %u"
+ "CSPN state history: %@"
+ "CoolOff"
+ "Failed to create _PMCoreSmartPowerNap instance"
+ "Off"
+ "On"
+ "Unknown(%u)"
+ "[DDM] %s: About to cancel the declaration for key: %@"
+ "[DDM] %s: Cancel scheduled download retry for reason: %@"
+ "[DDM] %s: Canceling the current download to download %@ [%p]"
+ "[DDM] %s: Cannot cancel: key is nil"
+ "[DDM] %s: Cannot cancel: key is unknown"
+ "[DDM] %s: Current active declaration = %@; current download = \n%@"
+ "[DDM] %s: Current declaration changed from %@ to %@"
+ "[DDM] %s: Current declaration is good and the new declaration isn't more urgent. Don't evaluate this time."
+ "[DDM] %s: Current declaration is good, nothing to do here"
+ "[DDM] %s: Current download is what is encforced"
+ "[DDM] %s: Current network: %@"
+ "[DDM] %s: Declaration invalidated!"
+ "[DDM] %s: Device is up-to-date; don't retry"
+ "[DDM] %s: Don't scan for a null declaration"
+ "[DDM] %s: Download %@ to start. Error: %@"
+ "[DDM] %s: Download already exists: %ld"
+ "[DDM] %s: Download policy doesn't allow downloading over cellular; try again later..."
+ "[DDM] %s: Download was purged (result: %d; error: %@)"
+ "[DDM] %s: Downloading: %@ [%p]"
+ "[DDM] %s: Failed to find any updates for declarations; will re-evaluate later"
+ "[DDM] %s: Failed to get a valid ddm manager..."
+ "[DDM] %s: Failed to remove declaration for key %@ from %@"
+ "[DDM] %s: Failed to set %@ as active; it must not be valid!!!"
+ "[DDM] %s: Failed to set global settings from %@ to %@, error: %@"
+ "[DDM] %s: Found declaration %@ and corresponding update %@ from state"
+ "[DDM] %s: Getting DDM status"
+ "[DDM] %s: Handled declaration %@: %@"
+ "[DDM] %s: Let's evaluate all declaraions!"
+ "[DDM] %s: MDM command conflicts with DDM"
+ "[DDM] %s: No declarations available, nothing to do here"
+ "[DDM] %s: No declarations in configuration %@"
+ "[DDM] %s: No descriptors available"
+ "[DDM] %s: No download"
+ "[DDM] %s: No handler given"
+ "[DDM] %s: No network connection; try again later..."
+ "[DDM] %s: No reply handler provided"
+ "[DDM] %s: No target update; not handling the download"
+ "[DDM] %s: No target versions changed; no need to re-evaluate"
+ "[DDM] %s: No update found for DDM declaration %@ with error %@"
+ "[DDM] %s: No updates found... Let's skip %@"
+ "[DDM] %s: Non-fatal scan error %@, will not report"
+ "[DDM] %s: Nothing found for the new declaration %@; let's keep the original one."
+ "[DDM] %s: Nothing relevant found..."
+ "[DDM] %s: Our download was killed; it's time to re-evaluate the declarations"
+ "[DDM] %s: Picked alternate descriptor from scan results"
+ "[DDM] %s: Picked preferred descriptor from scan results"
+ "[DDM] %s: Purging download with options %@"
+ "[DDM] %s: Reporting active declaration to client: %@"
+ "[DDM] %s: SUDDMManager failed to initiate as first call to sharedManager was made without a server delegate"
+ "[DDM] %s: Scan didn't find anything relevant; don't retry"
+ "[DDM] %s: Scan failed with error %@"
+ "[DDM] %s: Scan hit an error %@, retrying in 5s: %d"
+ "[DDM] %s: Scan triggered by ddm, nothing to do here"
+ "[DDM] %s: Scanning for update for DDM declaration %@"
+ "[DDM] %s: Schedule to retry downloading on %@ for reason: %@"
+ "[DDM] %s: Sending %@ to UI"
+ "[DDM] %s: Software Update not allowed because RRTS is on"
+ "[DDM] %s: Successfully set global settings from %@ to %@"
+ "[DDM] %s: The current active declaration was canceled, re-evaluate the declarations"
+ "[DDM] %s: The current download is relevant to the canceled declaration; purge it"
+ "[DDM] %s: The enforced update successfully finished; invalidating the declaration ..."
+ "[DDM] %s: The last scan error %@ is fatal, notifying the status channel."
+ "[DDM] %s: Unable to handle null declaration"
+ "[DDM] %s: Update found for DDM declaration %@: %@ [%p]"
+ "[DDM] %s: Update found for declaration: %@ [%p], %@"
+ "[DDM] %s: Update found for the new declaration %@; let's enforce it!"
+ "[DDM] %s: Update found! Let's enforce %@"
+ "[DDM] %s: [ANOMALY] shouldn't have any previously scheduled activity!"
+ "[DDM] %s: _ddmConfiguration persistence path: %@"
+ "[DDM] %s: alwaysEnableAutoDownload: %@"
+ "[DDM] %s: alwaysEnableAutoInstallOSUpdates: %@"
+ "[DDM] %s: alwaysEnableAutoInstallRapidSecurityResponse: %@"
+ "[DDM] %s: current global settings = %@"
+ "[DDM] %s: declarationToEnforce = %@, updateForDeclaration = %@ [%p]"
+ "[DDM] %s: declarations = %@"
+ "[DDM] %s: download did fail: %@, error: %@"
+ "[DDM] %s: download did finish: %@, install policy: %@"
+ "[DDM] %s: download did start: %@"
+ "[DDM] %s: download was killed: %@"
+ "[DDM] %s: enableGlobalNotifications: %d"
+ "[DDM] %s: enableRapidSecurityResponse: %d"
+ "[DDM] %s: enableRapidSecurityResponseRollback: %d"
+ "[DDM] %s: getDDMGlobalSettingsWithHandler - globalSettings = %@, error = %@"
+ "[DDM] %s: in SUManagerServer"
+ "[DDM] %s: recommendedCadence: %@"
+ "[DDM] %s: setDDMGlobalSettings - result = %d, error = %@"
+ "[DDM] %s: update was successfully installed: %@"
+ "[DDM] %s: updateDeferralPeriod: %lu"
+ "[DDM] %s: was called"
+ "com.apple.sus.SUDaemonHelperService"
+ "com.apple.sus.cspnmonitor.q"
+ "com.apple.susd.helper.connection"
+ "powerNapCount"
+ "powerNapDate%lu"
+ "powerNapState%lu"
+ "state"
+ "timestamp"
+ "v12@?0C8"
- "About to cancel the declaration for key: %@"
- "Cancel scheduled download retry for reason: %@"
- "Canceling the current download to download %@ [%p]"
- "Cannot cancel: key is nil"
- "Cannot cancel: key is unknown"
- "Current active declaration = %@; current download = \n%@"
- "Current declaration changed from %@ to %@"
- "Current declaration is good and the new declaration isn't more urgent. Don't evaluate this time."
- "Current declaration is good, nothing to do here"
- "Current download is what is encforced"
- "Current network: %@"
- "Declaration invalidated!"
- "Device is up-to-date; don't retry"
- "Don't scan for a null declaration"
- "Download %@ to start. Error: %@"
- "Download already exists: %ld"
- "Download policy doesn't allow downloading over cellular; try again later..."
- "Download was purged (result: %d; error: %@)"
- "Downloading: %@ [%p]"
- "Failed to find any updates for declarations; will re-evaluate later"
- "Failed to get a valid ddm manager..."
- "Failed to remove declaration for key %@ from %@"
- "Failed to set %@ as active; it must not be valid!!!"
- "Failed to set global settings from %@ to %@, error: %@"
- "Found declaration %@ and corresponding update %@ from state"
- "Getting DDM status"
- "Handled declaration %@: %@"
- "Let's evaluate all declaraions!"
- "MDM command conflicts with DDM"
- "No declarations available, nothing to do here"
- "No declarations in configuration %@"
- "No descriptors available"
- "No download"
- "No handler given"
- "No network connection; try again later..."
- "No reply handler provided"
- "No target update; not handling the download"
- "No target versions changed; no need to re-evaluate"
- "No update found for DDM declaration %@ with error %@"
- "No updates found... Let's skip %@"
- "Non-fatal scan error %@, will not report"
- "Nothing found for the new declaration %@; let's keep the original one."
- "Nothing relevant found..."
- "Our download was killed; it's time to re-evaluate the declarations"
- "Picked alternate descriptor from scan results"
- "Picked preferred descriptor from scan results"
- "Purging download with options %@"
- "Reporting active declaration to client: %@"
- "SUDDMManager failed to initiate as first call to sharedManager was made without a server delegate"
- "Scan didn't find anything relevant; don't retry"
- "Scan failed with error %@"
- "Scan hit an error %@, retrying in 5s: %d"
- "Scan triggered by ddm, nothing to do here"
- "Scanning for update for DDM declaration %@"
- "Schedule to retry downloading on %@ for reason: %@"
- "Sending %@ to UI"
- "Software Update not allowed because RRTS is on"
- "Successfully set global settings from %@ to %@"
- "The current active declaration was canceled, re-evaluate the declarations"
- "The current download is relevant to the canceled declaration; purge it"
- "The enforced update successfully finished; invalidating the declaration ..."
- "The last scan error %@ is fatal, notifying the status channel."
- "Unable to handle null declaration"
- "Update found for DDM declaration %@: %@ [%p]"
- "Update found for declaration: %@ [%p], %@"
- "Update found for the new declaration %@; let's enforce it!"
- "Update found! Let's enforce %@"
- "[ANOMALY] shouldn't have any previously scheduled activity!"
- "[DDM] %s: %@"
- "_ddmConfiguration persistence path: %@"
- "alwaysEnableAutoDownload: %@"
- "alwaysEnableAutoInstallOSUpdates: %@"
- "alwaysEnableAutoInstallRapidSecurityResponse: %@"
- "current global settings = %@"
- "declarationToEnforce = %@, updateForDeclaration = %@ [%p]"
- "declarations = %@"
- "download did fail: %@, error: %@"
- "download did finish: %@, install policy: %@"
- "download did start: %@"
- "download was killed: %@"
- "enableGlobalNotifications: %d"
- "enableRapidSecurityResponse: %d"
- "enableRapidSecurityResponseRollback: %d"
- "getDDMGlobalSettingsWithHandler - globalSettings = %@, error = %@"
- "in SUManagerServer"
- "recommendedCadence: %@"
- "setDDMGlobalSettings - result = %d, error = %@"
- "update was successfully installed: %@"
- "updateDeferralPeriod: %lu"
- "was called"
```
