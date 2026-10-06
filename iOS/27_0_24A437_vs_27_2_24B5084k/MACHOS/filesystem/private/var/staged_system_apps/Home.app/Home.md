## Home

> `/private/var/staged_system_apps/Home.app/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc04d8` | `0xc0b34` | **`+0x65c`** |
| `__TEXT.__objc_methname` | `0x13151` | `0x13241` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x5008` | `0x505e` | **`+0x56`** |
| `__TEXT.__oslogstring` | `0x7163` | `0x7119` | **`-0x4a`** |
| `__DATA.__data` | `0x53e4` | `0x542c` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0xbac0` | `0xbb00` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x4d2d` | `0x4d60` | **`+0x33`** |
| `__DATA.__objc_selrefs` | `0x44e8` | `0x4518` | **`+0x30`** |
| `__TEXT.__const` | `0x3354` | `0x3384` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x1256` | `0x1286` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x5944` | `0x596c` | **`+0x28`** |
| `__DATA.__objc_const` | `0x77a0` | `0x77c0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x33e0` | `0x3400` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2aa8` | `0x2ac8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x70c2` | `0x70d5` | **`+0x13`** |
| `__DATA_CONST.__auth_got` | `0x1a00` | `0x1a10` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x12a0` | `0x12b0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x16e9` | `0x16f9` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1354` | `0x1360` | **`+0xc`** |
| `__DATA.__objc_data` | `0x1520` | `0x1528` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x7128` | `0x7120` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x12a8` | `0x12b0` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x2950` | `0x2958` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
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
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1241.1.7.1.3
+1263.1.0.1.2

+  - /System/Library/PrivateFrameworks/AsyncAlgorithmsInternal.framework/AsyncAlgorithmsInternal

-  - /usr/lib/swift/libswiftCallKit.dylib

-  Functions: 3949
-  Symbols:   1790
-  CStrings:  4460
+  Functions: 3950
+  Symbols:   1792
+  CStrings:  4466
Symbols:
+ _$s13HomeDataModel06StaticA0V2id10Foundation4UUIDVvg
+ _$s13HomeDataModel0bC0C22homesToMatterSnapshotsSDy10Foundation4UUIDVAA0F13StateSnapshotVGvgTj
+ _$s13HomeDataModel17AccessoryProtocolPAAE3pIDs6UInt64VSgvg
+ _$s13HomeDataModel17AccessoryProtocolPAAE3vIDs6UInt64VSgvg
+ _$s6HomeUI24SidebarTabElementBuilderV16createCategories4with4home14matterSnapshotSayACG0A9DataModel05StateL0VSg_So6HMHomeCAI06MatteroL0VSgtFZ
+ _$s6HomeUI24SidebarTabElementBuilderV4from4with14matterSnapshotACSg0A9DataModel16UmbrellaCategoryO_AH05StateJ0VAH06MatteroJ0VSgtcfC
+ _$sSo11HMAccessoryC13HomeDataModel17AccessoryProtocolACMc
- _$s6HomeUI24SidebarTabElementBuilderV16createCategories4with4homeSayACG0A9DataModel13StateSnapshotVSg_So6HMHomeCtFZ
- _$s6HomeUI24SidebarTabElementBuilderV4from4withACSg0A9DataModel16UmbrellaCategoryO_AG13StateSnapshotVtcfC
- _$s6HomeUI28AccessorySetupOnboardingFlowC15prewarmIfNeeded3forySo11HMAccessoryC_tFZ
- _$s6HomeUI28AccessorySetupOnboardingFlowCMa
- __swift_FORCE_LOAD_$_swiftCallKit
CStrings:
+ "accessory:didUpdateMatterNodeID:"
+ "accessoryDidUpdateSupportsRTAPATAudio:"
+ "accessoryDidUpdateSupportsRegulatoryErase:"
+ "homeManager:didRemoveCurrentAccessoryWithRegulatoryEraseRequired:"
+ "initWithUnsignedLongLong:"
+ "presentAccessoryControlsSheet(from:animated:)"
+ "presentCategorySheet(from:animated:)"
+ "setBottomAccessory:animated:"
+ "v32@0:8@\"HMAccessory\"16@\"NSNumber\"24"
- "HOME_SUPPORTS_ACTIVITY_STATE compiled in. HOME_ENABLE_ACTIVITY_STATE = %{BOOL}d"
- "presentAccessoryControlsSheet(from:)"
- "presentCategorySheet(from:)"
```
