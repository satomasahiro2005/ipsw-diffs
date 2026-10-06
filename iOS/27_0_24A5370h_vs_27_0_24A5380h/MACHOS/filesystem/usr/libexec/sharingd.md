## sharingd

> `/usr/libexec/sharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6950a4` | `0x696ca0` | **`+0x1bfc`** |
| `__TEXT.__unwind_info` | `0x14268` | `0x14728` | **`+0x4c0`** |
| `__TEXT.__oslogstring` | `0x3c963` | `0x3cb33` | **`+0x1d0`** |
| `__TEXT.__eh_frame` | `0x2406c` | `0x24214` | **`+0x1a8`** |
| `__TEXT.__swift_as_cont` | `0x229c` | `0x21e0` | **`-0xbc`** |
| `__DATA_CONST.__got` | `0x38e0` | `0x3998` | **`+0xb8`** |
| `__DATA.__objc_const` | `0x38200` | `0x382b0` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x3eb61` | `0x3ec11` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x1e4a4` | `0x1e52c` | **`+0x88`** |
| `__TEXT.__objc_stubs` | `0x373c0` | `0x37440` | **`+0x80`** |
| `__DATA.__data` | `0x148c8` | `0x14858` | **`-0x70`** |
| `__TEXT.__objc_methname` | `0x4e735` | `0x4e7a5` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x1ca40` | `0x1c9e8` | **`-0x58`** |
| `__TEXT.__swift_as_ret` | `0xef8` | `0xf44` | **`+0x4c`** |
| `__TEXT.__gcc_except_tab` | `0x67f8` | `0x6840` | **`+0x48`** |
| `__TEXT.__const` | `0x15a88` | `0x15ac8` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x5188` | `0x5150` | **`-0x38`** |
| `__TEXT.__swift5_reflstr` | `0x5919` | `0x58f9` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x11020` | `0x11038` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x5e30` | `0x5e18` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x2900` | `0x2914` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x7f84` | `0x7f70` | **`-0x14`** |
| `__TEXT.__auth_stubs` | `0xa960` | `0xa970` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xe18` | `0xe28` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x54c0` | `0x54c8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x42e0` | `0x42d8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2122.10.2.2.1
+2124.10.2.2.2

-  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 26227
-  Symbols:   4885
-  CStrings:  27467
+  Functions: 26245
+  Symbols:   4886
+  CStrings:  27476
Symbols:
+ _$sSq7SharingE13tryUnwrapLazy_4file4linexSSyXK_SSSitKF
CStrings:
+ "BLE NearbyInfo airDropUsable %d -> %d (screenStateSupportsAirDrop=%d, currentConsoleUser=%d, discoverableLevel=%ld, wirelessEnabled=%d)\n"
+ "Dropping duplicate duet suggestion for conversation %{public}@"
+ "Failed to register wifi monitor %@. Retrying in 5 seconds"
+ "FindNearbyLocalFindableAccessoryExtendedRange"
+ "Installing wifi interface monitor"
+ "Replaced appsvc endpoint %s: AU %{bool}d->%{bool}d"
+ "Wifi interface monitor installed, monitoring power/BSSID/mode changes"
+ "Wifi interface monitor invalidated. Retrying in 5 seconds"
+ "_cwfInterfaceQueue"
+ "createAttachmentsForURLsBeingShared:typeIdentifiersBeingShared:photosAssetIDs:processedImageResultsData:sandboxExtensionsByfileURLPath:"
+ "dropping endpoint - isAirDropable=false and no delegate override: %s"
+ "predictionContextAttachments"
+ "retryInstallWifiInterfaceMonitor"
+ "updateServerState canRun(appService=%{bool}d, bonjour=%{bool}d, nearField=%{bool}d) inputs(screenStateSupportsAirDrop=%{bool}d, isAirDropDiscoverable=%{bool}d, isNearbySharingEnabled=%{bool}d, wirelessEnabled=%{bool}d, bluetoothEnabledIncludingRestricted=%{bool}d)"
+ "wifiMonitorInvalidated"
- "Failed to register wifi monitor %@\n"
- "Pairable: %s adding application service endpoint"
- "Person: %s adding application service endpoint"
- "Person: %s adding bonjour endpoint"
- "Removing existing endpoint to insert new: %s"
- "_createAttachmentsForURLsBeingShared:typeIdentifiersBeingShared:photosAssetIDs:processedImageResultsData:sandboxExtensionsByfileURLPath:"
```
