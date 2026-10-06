## seserviced

> `/usr/libexec/seserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47f7f8` | `0x4883f8` | **`+0x8c00`** |
| `__TEXT.__oslogstring` | `0x31761` | `0x31e42` | **`+0x6e1`** |
| `__TEXT.__eh_frame` | `0x15c20` | `0x16064` | **`+0x444`** |
| `__DATA_CONST.__const` | `0x158c8` | `0x15b38` | **`+0x270`** |
| `__DATA.__data` | `0xe2e4` | `0xe4c4` | **`+0x1e0`** |
| `__TEXT.__const` | `0x14c88` | `0x14e68` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0xa9d8` | `0xaba8` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0x2252c` | `0x226f9` | **`+0x1cd`** |
| `__DATA.__bss` | `0x13d80` | `0x13f00` | **`+0x180`** |
| `__TEXT.__objc_methname` | `0x1953d` | `0x1962d` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x640a` | `0x64fa` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x31fc` | `0x32dc` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x3318` | `0x33e8` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x19160` | `0x19228` | **`+0xc8`** |
| `__DATA_CONST.__cfstring` | `0x8800` | `0x88c0` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x6314` | `0x6390` | **`+0x7c`** |
| `__TEXT.__objc_stubs` | `0xe780` | `0xe7e0` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x58a2` | `0x58f2` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0xedc` | `0xf1c` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0xfb8` | `0xfd8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x5e2c` | `0x5e48` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x4ae8` | `0x4b00` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x828` | `0x840` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x3d4` | `0x3e8` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x4ec` | `0x500` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x5f0` | `0x604` | **`+0x14`** |
| `__DATA.__objc_data` | `0x6c00` | `0x6c10` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x5130` | `0x5120` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x3158` | `0x3168` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x7184` | `0x7194` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xacc` | `0xad8` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x28b0` | `0x28a8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x2110` | `0x2118` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0xc4` | `0xcc` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xcec` | `0xcf0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x654` | `0x658` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-70.35.1.0.0
+70.37.0.0.0

-  Functions: 13044
+  Functions: 13155

-  CStrings:  11558
+  CStrings:  11601
Symbols:
+ _$sScTss5NeverORszABRs_rlE11isCancelledSbvgZ
+ _CA_AvgConnectionDurationPerPeripheral
+ _CA_PassiveEntryRangingStatusURSKNotFound
+ _swift_release_x10
+ _swift_task_isCancelledWithFlags
- _$s9SEService10SESnapshotC6canFit11credentialsSbSayAA14CredentialTypeOG_tKF
- _$s9SEService17SERInternalClientC13getSESnapshot5tokens6ResultOyAA0E0CAA20SERXPCInternalErrorsOG10Foundation4DataVSg_tYaF
- _$s9SEService17SERInternalClientC13getSESnapshot5tokens6ResultOyAA0E0CAA20SERXPCInternalErrorsOG10Foundation4DataVSg_tYaFTu
- _$s9SEService17SERInternalClientC6sharedACvgZ
- _$s9SEService17SERInternalClientCMa
CStrings:
+ "%s : %i : Cannot delete duplicate endpoint: missing public key identifier"
+ "%s : %i : Pairing blocked on NFC-only device but no error was set; using default error"
+ "+[KmlEndpointManager getUntrackedEndpointForReaderIdentifier:session:seid:]"
+ "-[KmlDataExchangeManager initWithDelegate:isProbing:isUserInitiated:pairingPassword:transport:transportConfig:versionInformation:]"
+ "Cannot delete duplicate endpoint: missing public key identifier"
+ "Clearing discovery scan request for %{public}s"
+ "Endpoint does not exist %d, is not paired %d or not pending pairing %d for key identifier %@"
+ "Error: Secure Ranging Failed"
+ "Error: SubOptimal URSK Not Found"
+ "Failed pairing check 1 %d"
+ "Failed to acquire SE %@"
+ "Failed to deleteAllApplets"
+ "Failed to reclaim unused SE memory after installation failure: %{public}s"
+ "Falling back to Passbook as default due to ineligibility"
+ "Firing installation finished callback for %ld failed credential(s)"
+ "First Approach for %{public}s reached the attempt limit"
+ "Invalid reader ID"
+ "Launch event %s %{public}s configured with %{public}s"
+ "Not sending ranging not required because of express state %{public}s"
+ "Not starting DSK due to failure during applet preparation %@"
+ "Not starting DSK since not required (UWB supported %d)"
+ "Pairing not validated %d / %@"
+ "Pairing state (after) %{public}x / %{public}@"
+ "Pairing state (before) %{public}x / %{public}@"
+ "Passbook not installed -- invalidating default due to ineligibility"
+ "Passive Entry: Ranging Failed."
+ "Passive Entry: SubOptimal URSK Not Found."
+ "Q28@0:8B16^@20"
+ "Session %s: All getInstallationStatus calls failed; backing off polling to %fs"
+ "Session %s: Coalescing getInstallationStatus for credential %s"
+ "Session %s: Credential %s reported as installation failed by server"
+ "Session %s: Credential %s reported as installed by server"
+ "Session %s: Failed to get installation status for credential %s: %{public}s"
+ "Session %s: Failed to transition credentials to installationFailed: %{public}s"
+ "Session %s: Installation status polling already in flight"
+ "Session %s: No credentials remain in installationPending state; ending installation status polling"
+ "Session %s: Polling backoff reset to %fs after network recovery"
+ "Session %s: Starting installation status polling"
+ "Session %s: Stopping installation status polling"
+ "Setting discovery paired peripherals for %{public}s RSSI %hhd peripherals %{public}s"
+ "Setting discovery scan request for %{public}s service %{public}s RSSI %hhd filters %ld"
+ "Validate pairing re-paired with result %{public}d / %{public}@"
+ "Vv40@0:8@\"NSData\"16@\"NSString\"24@?<v@?@\"SESDataAttestation\"@\"NSError\">32"
+ "arrayByAddingObject:"
+ "ca.dsk.alisha.daily.connected.peripherals"
+ "dailyConnectionStartTime"
+ "deleteAllApplets:error:"
+ "failed_to_create"
+ "iOS (27.0) - SecureElementService-70.37"
+ "inFlightInstallationStatusQueries"
+ "installationStatusPollingTask"
+ "isDeviceIntentSent"
+ "maxFirstApproachAttempts"
+ "requestedFirstApproachKeyIdentifiersToAttempts"
+ "validatePairing"
+ "validatePairing:callback:"
+ "validatePairing:error:"
- "+[KmlEndpointManager getUnrevokedEndpointForReaderIdentifier:session:seid:withError:]"
- "-[KmlDataExchangeManager initWithDelegate:isProbing:pairingPassword:transport:transportConfig:versionInformation:]"
- "Configuring Passbook as default due to ineligibility"
- "Endpoint does not exist %d or is not paired %d for key identifier %@"
- "Launch event %s %s configured with %s"
- "Missing endpoint reader information %s"
- "Not starting DSK due to failed applet personalization %@"
- "Not starting DSK due to missing Sunsprite"
- "Q24@0:8^@16"
- "Valid key already exists for this reader identifier"
- "Vv40@0:8@\"NSData\"16@\"NSData\"24@?<v@?@\"SESDataAttestation\"@\"NSError\">32"
- "iOS (27.0) - SecureElementService-70.35.1"
- "requestedFirstApproachKeyIdentifiers"
- "validatePairing:"
```
