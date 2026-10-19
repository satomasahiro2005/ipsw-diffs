## callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x547100` | `0x54a594` | **`+0x3494`** |
| `__TEXT.__objc_methname` | `0x71447` | `0x71747` | **`+0x300`** |
| `__DATA.__data` | `0x10dc0` | `0x10fe0` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x54413` | `0x54263` | **`-0x1b0`** |
| `__TEXT.__objc_methtype` | `0x13564` | `0x136e4` | **`+0x180`** |
| `__DATA.__objc_const` | `0x40cc8` | `0x40e38` | **`+0x170`** |
| `__TEXT.__objc_stubs` | `0x3dd40` | `0x3de80` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x29108` | `0x29240` | **`+0x138`** |
| `__TEXT.__constg_swiftt` | `0x9d70` | `0x9e98` | **`+0x128`** |
| `__DATA.__objc_data` | `0xe708` | `0xe828` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x29e98` | `0x29fb0` | **`+0x118`** |
| `__TEXT.__const` | `0x10530` | `0x10620` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x1c6fc` | `0x1c7cc` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x13ba0` | `0x13c58` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x9b2c` | `0x9bde` | **`+0xb2`** |
| `__TEXT.__unwind_info` | `0xf4d8` | `0xf580` | **`+0xa8`** |
| `__TEXT.__objc_classname` | `0x5bf2` | `0x5c92` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x5f60` | `0x5fc0` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x7338` | `0x738c` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0x8d60` | `0x8db0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x29d8` | `0x2a18` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x2fc0` | `0x2ff0` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0xae8` | `0xb18` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x9c54` | `0x9c84` | **`+0x30`** |
| `__DATA_CONST.__objc_protorefs` | `0x448` | `0x460` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1628` | `0x1638` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0xba00` | `0xba10` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x99c` | `0x9a8` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xd08` | `0xd10` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x704` | `0x708` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

+  - /System/Library/Frameworks/HomeKit.framework/HomeKit

+  - /System/Library/PrivateFrameworks/HMFoundation.framework/HMFoundation

-  Functions: 29337
-  Symbols:   3081
-  CStrings:  24709
+  Functions: 29406
+  Symbols:   3095
+  CStrings:  24744
Symbols:
+ _$s12HMFoundation2ggopySSxlF
+ _$s5IndexSlTl
+ _$sSa22_allocateUninitializedySayxG_SpyxGtSiFZ
+ _$sSl10startIndex0B0QzvgTj
+ _$sSl5countSivgTj
+ _$sSl9formIndex5aftery0B0Qzz_tFTj
+ _$sSlTL
+ _$sSly7ElementQz5IndexQzcirTj
+ _$ss15ContiguousArrayV15reserveCapacityyySiF
+ _OBJC_CLASS_$_HMAccessory
+ _OBJC_CLASS_$_HMHome
+ _OBJC_CLASS_$_HMHomeManager
+ _OBJC_CLASS_$_HMMediaGroup
+ _OBJC_CLASS_$_HMSurroundSystem
+ _OBJC_CLASS_$_RPCompanionLinkDevice
- _TUMinimumSupportedSharePlayProtocolVersion
CStrings:
+ "HMHomeManagerDelegate"
+ "HMMediaGroupsControllerDelegate"
+ "HMMediaGroupsControllerDelegate_Deprecated"
+ "Re-sweeping active devices to filter to eligible nearby devices: %@"
+ "_TtC13callservicesd18HomeTheaterManager"
+ "_homeTheaterDataSource"
+ "accessories"
+ "activeDevices"
+ "audioDestinationIdentifier"
+ "audioGroupsController"
+ "callservicesd.HomeTheaterManager"
+ "frontLeftDestinationIdentifier"
+ "frontRightDestinationIdentifier"
+ "groups"
+ "handleGroupsUpdated()"
+ "handleHomesUpdated()"
+ "homeManager:didAddHome:"
+ "homeManager:didReceiveAddAccessoryRequest:"
+ "homeManager:didRemoveHome:"
+ "homeManager:didUpdateAuthorizationStatus:"
+ "homeManagerDidUpdateHomes:"
+ "homeManagerDidUpdatePrimaryHome:"
+ "homeTheaterDataSourceFactory"
+ "homes"
+ "mediaGroupsController:didCreateGroup:"
+ "mediaGroupsController:didReceiveGroup:"
+ "mediaGroupsController:didReceiveGroup:destination:"
+ "mediaGroupsController:didRemoveGroup:"
+ "mediaGroupsController:didUpdateGroup:"
+ "mediaGroupsController:didUpdateSettings:group:"
+ "rearLeftDestinationIdentifier"
+ "rearRightDestinationIdentifier"
+ "subscribeToAllGroups"
+ "v24@0:8@\"HMHomeManager\"16"
+ "v32@0:8@\"HMHomeManager\"16@\"HMAddAccessoryRequest\"24"
+ "v32@0:8@\"HMHomeManager\"16@\"HMHome\"24"
+ "v32@0:8@\"HMHomeManager\"16Q24"
+ "v32@0:8@\"HMMediaGroupsController\"16@\"HMMediaGroup\"24"
+ "v40@0:8@\"HMMediaGroupsController\"16@\"HMAccessorySettings\"24@\"HMMediaGroup\"32"
+ "v40@0:8@\"HMMediaGroupsController\"16@\"HMMediaGroup\"24@\"<HMMediaDestination>\"32"
- "At least one participant in conversation %@ does not support SharePlay. Invalidating session %@"
- "Not adding activity session, as not all participants are on the latest SharePlay version"
- "Not enforcing shareplay version check due to server over-ride"
- "[WARN] All active participants in the call are not on minimum supported shareplay version"
- "[WARN] One or more participant on %@ is on an older share play protocol %@ version %@"
```
