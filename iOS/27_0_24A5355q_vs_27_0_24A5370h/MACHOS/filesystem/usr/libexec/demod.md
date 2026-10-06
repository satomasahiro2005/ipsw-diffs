## demod

> `/usr/libexec/demod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf0e94` | `0xf3368` | **`+0x24d4`** |
| `__TEXT.__objc_methname` | `0x1fafb` | `0x2037d` | **`+0x882`** |
| `__TEXT.__objc_stubs` | `0x1ade0` | `0x1b360` | **`+0x580`** |
| `__DATA.__objc_const` | `0x19020` | `0x193e0` | **`+0x3c0`** |
| `__TEXT.__oslogstring` | `0x1c26c` | `0x1c58c` | **`+0x320`** |
| `__TEXT.__objc_methlist` | `0xd30c` | `0xd5ac` | **`+0x2a0`** |
| `__DATA.__objc_selrefs` | `0x7d08` | `0x7e88` | **`+0x180`** |
| `__TEXT.__cstring` | `0x109b2` | `0x10b22` | **`+0x170`** |
| `__DATA_CONST.__cfstring` | `0xea80` | `0xebe0` | **`+0x160`** |
| `__TEXT.__gcc_except_tab` | `0x4584` | `0x4680` | **`+0xfc`** |
| `__TEXT.__auth_stubs` | `0x2010` | `0x20a0` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x3978` | `0x39f0` | **`+0x78`** |
| `__DATA.__objc_data` | `0x4760` | `0x47b0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1018` | `0x1060` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0xae8` | `0xb28` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x182a` | `0x184a` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x498` | `0x4b0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xd80` | `0xd90` | **`+0x10`** |
| `__TEXT.__const` | `0x520` | `0x510` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x3d4b` | `0x3d5b` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x31b8` | `0x31c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x710` | `0x718` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x410` | `0x418` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1865.0.0.0.0
+1871.0.14.0.0

+  - /System/Library/Frameworks/Accessibility.framework/Accessibility

-  Functions: 5964
-  Symbols:   1036
-  CStrings:  10633
+  Functions: 6024
+  Symbols:   1047
+  CStrings:  10739
Symbols:
+ _CFPreferencesSetValue
+ _CONTAINER_PERSONA_ALL_AVAILABLE
+ _OBJC_CLASS_$_BMPublisherOptions
+ _container_error_get_type
+ _container_get_error_description
+ _container_query_count_results
+ _container_query_create
+ _container_query_free
+ _container_query_get_last_error
+ _container_query_iterate_results_sync
+ _container_query_set_class
+ _container_query_set_identifiers
+ _container_query_set_persona_unique_string
- _container_create_or_lookup_for_current_user
- _container_free_object
CStrings:
+ "%s: displacing active tracker for %{public}@ without finalization — marking as failed"
+ "%s: manifestInfo missing SubManifestType, skipping."
+ "%s: started tracking submanifest %{public}@"
+ "-[MSDProgressUpdater startSubManifestUpdateMonitor:withTotalComponents:manifestFilename:]"
+ "/var/mobile/Home/DemoContent/"
+ "@\"MSDSubManifestProgressTracker\""
+ "B16@?0^{container_object_s=}8"
+ "Beginning work for content update on worker!"
+ "Cannot remove data for container %{public}@(%{public}@), error is %s"
+ "ComponentsSuccessful"
+ "Content.SubManifests"
+ "Could not find resident device with Serial: %{public}@"
+ "Could not find serial number for current primary resident."
+ "Could not find serial number for intended primary resident."
+ "CurrentPrimaryResident"
+ "Device with serialNumber %{public}@ is already primary resident. Nothing to do."
+ "Failed to create container query for %{public}@(%{public}@)"
+ "Failed to set primary preferred hub for Serial: %{public}@"
+ "Found accessory with Serial: %{public}@ in non-primary home"
+ "Found accessory with Serial: %{public}@ in primary home"
+ "IDSIdentifier"
+ "InProgressManifestInfo"
+ "InstalledManifestFilename"
+ "InstalledManifestInfo"
+ "IntendedPrimaryResident"
+ "IntendedPrimaryResidentSerial"
+ "Loaded %lu submanifest tracker(s) from preferences."
+ "MSDDemoSubmanifestsStatus"
+ "MSDSubManifestProgressTracker"
+ "No primary home.  Will skip setting HS to %@."
+ "No primary resident found in home.  Likely home has just been created."
+ "No valid subManifestType was found for tracker"
+ "Primary preferred hub has been successfully set to device with Serial: %{public}@"
+ "Received an error of code %llu while running a query on container."
+ "Serial"
+ "Submanifest %{public}@ installation finished (success=%d)"
+ "Submanifest %{public}@ installation started, total components: %ld"
+ "Submanifest of filename %{public}@ is already installed.  Moving on."
+ "T@\"MSDPreferencesFile\",&,N,V_prefFile"
+ "T@\"MSDPreferencesFile\",R,D,N"
+ "T@\"MSDSubManifestProgressTracker\",&,V_activeSubManifestTracker"
+ "T@\"NSDate\",&,N,V_lastStoreClosedDate"
+ "T@\"NSDictionary\",C,N,V_inProgressManifestInfo"
+ "T@\"NSDictionary\",C,N,V_installedManifestInfo"
+ "T@\"NSMutableArray\",&,V_subManifestTrackers"
+ "T@\"NSString\",&,N,V_inProgressManifestFilename"
+ "T@\"NSString\",&,N,V_installedManifestFilename"
+ "T@\"NSString\",&,N,V_manifestFilename"
+ "T@\"NSString\",&,N,V_subManifestType"
+ "TC,N,V_installState"
+ "TC,N,V_installStatus"
+ "TQ,N,V_localBytesDownloaded"
+ "TQ,N,V_remoteBytesDownloaded"
+ "There was an error iterating results from container query."
+ "There were %lu containers found in the query."
+ "Tq,N,V_componentsSuccessful"
+ "Tq,N,V_totalComponents"
+ "Tracker isn't a valid dictionary, skipping"
+ "Unable to find accessory with Serial: %{public}@"
+ "_activeSubManifestTracker"
+ "_findInPrimaryHomeResident:withMatchingSN:"
+ "_inProgressManifestFilename"
+ "_inProgressManifestInfo"
+ "_installState"
+ "_installStatus"
+ "_installedManifestFilename"
+ "_installedManifestInfo"
+ "_lastStoreClosedDate"
+ "_localBytesDownloaded"
+ "_manifestFilename"
+ "_metaDictFromManifestInfo:"
+ "_prefFile"
+ "_remoteBytesDownloaded"
+ "_serialNumberForResident:"
+ "_subManifestTrackers"
+ "_subManifestType"
+ "activeSubManifestTracker"
+ "buildContentStatusForPing"
+ "com.apple.CompanionSetup.MainSetup"
+ "disableProximityPairingCard"
+ "disabledExtensions"
+ "enableWiFi retrying in %d seconds (attempt %lu of %d)..."
+ "exportToDict"
+ "finishInstallationWithSuccess:"
+ "handleHomeUpdateCommand:completion:"
+ "inProgressManifestFilename"
+ "inProgressManifestInfo"
+ "initWithManifestInfo:preferencesFile:"
+ "initWithStartDate:endDate:maxEvents:lastN:reversed:"
+ "initWithSubManifestType:"
+ "initWithSubManifestType:andTrackerDict:"
+ "installState"
+ "installStatus"
+ "installedManifestFilename"
+ "installedManifestInfo"
+ "isAlreadyInstalled"
+ "lastStoreClosedDate"
+ "loadFromPreferences"
+ "localBytesDownloaded"
+ "manifestFilename"
+ "markActiveSubManifestCompleted:"
+ "newDateBySubtractingOneDay"
+ "off"
+ "on"
+ "prefFile"
+ "publisherWithOptions:"
+ "recordComponentCompleted:"
+ "recordComponentCompleted:componentName:"
+ "recordDownloadedContent:fromSource:"
+ "remoteBytesDownloaded"
+ "saveTrackers:"
+ "serialNumber parameter is nil."
+ "setActiveSubManifestTracker:"
+ "setInProgressManifestFilename:"
+ "setInProgressManifestInfo:"
+ "setInstallState:"
+ "setInstallStatus:"
+ "setInstalledManifestFilename:"
+ "setInstalledManifestInfo:"
+ "setLastStoreClosedDate:"
+ "setLocalBytesDownloaded:"
+ "setManifestFilename:"
+ "setPrefFile:"
+ "setRemoteBytesDownloaded:"
+ "setSubManifestTrackers:"
+ "setSubManifestType:"
+ "startInstallationWithManifestInfo:totalComponents:manifestFilename:"
+ "startSubManifestUpdateMonitor:withTotalComponents:manifestFilename:"
+ "subManifestTrackers"
+ "subManifestType"
+ "unsignedCharValue"
+ "v40@0:8@16q24@32"
- "B48@0:8{?=@@}16{?=@@}32"
- "Beginning work for content update on manifest!"
- "Cannot create container object for %{public}@(%{public}@): %lld"
- "Cannot remove data for container %{public}@(%{public}@), error code is %lld"
- "Could not find resident device with UUID: %{public}@"
- "Device with UUID %{public}@ is already primary resident. Nothing to do."
- "Failed to set primary preferred hub for UUID: %{public}@"
- "Found accessory with UUID: %{public}@ in non-primary home"
- "Found accessory with UUID: %{public}@ in primary home"
- "Invalid UUID string: %{public}@"
- "Invalid accessory UUID string: %{public}@"
- "Primary preferred hub has been successfully set to device with UUID: %{public}@"
- "PrimaryHub"
- "PrimaryResident"
- "Subsumed  - start:  %{public}@ - end:  %{public}@"
- "Subsuming - start:  %{public}@ - end:  %{public}@"
- "UUID parameter is nil."
- "Unable to find accessory with UUID: %{public}@"
- "_findInPrimaryHomeResident:withMatchingUUID:"
- "currentPrimaryResident"
- "handleHomeUpdateCommand:"
- "intendedPrimaryResident"
- "isPrimaryResident"
- "publisher"
- "rval:  %{bool}d"
- "timeRange:subsumes:"
```
