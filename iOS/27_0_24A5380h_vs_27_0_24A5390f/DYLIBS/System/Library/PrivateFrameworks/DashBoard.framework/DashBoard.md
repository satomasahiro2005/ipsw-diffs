## DashBoard

> `/System/Library/PrivateFrameworks/DashBoard.framework/DashBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f6d78` | `0x2fc43c` | **`+0x56c4`** |
| `__DATA.__bss` | `0x8b48` | `0x9468` | **`+0x920`** |
| `__TEXT.__const` | `0xd014` | `0xd644` | **`+0x630`** |
| `__AUTH_CONST.__const` | `0xc730` | `0xcac0` | **`+0x390`** |
| `__AUTH_CONST.__objc_const` | `0x52bf0` | `0x52e18` | **`+0x228`** |
| `__TEXT.__constg_swiftt` | `0x7074` | `0x724c` | **`+0x1d8`** |
| `__TEXT.__swift5_typeref` | `0xb8f6` | `0xba88` | **`+0x192`** |
| `__DATA_CONST.__got` | `0x2d98` | `0x2eb0` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0x97b8` | `0x98c0` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0x1782c` | `0x1791c` | **`+0xf0`** |
| `__TEXT.__cstring` | `0xda57` | `0xdb27` | **`+0xd0`** |
| `__DATA.__data` | `0xa450` | `0xa510` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x1792c` | `0x179dc` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0xcff8` | `0xd090` | **`+0x98`** |
| `__TEXT.__swift5_proto` | `0x430` | `0x4c4` | **`+0x94`** |
| `__TEXT.__swift5_reflstr` | `0x5437` | `0x54c7` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x43d4` | `0x4454` | **`+0x80`** |
| `__AUTH.__objc_data` | `0xea80` | `0xeaf0` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x910` | `0x970` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x2f1c` | `0x2f5c` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x36a0` | `0x36d8` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x469c` | `0x46cc` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1a2c` | `0x1a5c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3828` | `0x3850` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x348` | `0x370` | **`+0x28`** |
| `__DATA.__common` | `0x390` | `0x3b0` | **`+0x20`** |
| `__AUTH.__data` | `0x3708` | `0x3718` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x44` | `0x50` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x648` | `0x654` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x12a4` | `0x12a8` | **`+0x4`** |

### Other Changes

```diff

-577.2.0.0.0
+580.0.0.0.0

-  Functions: 15396
-  Symbols:   14407
-  CStrings:  3604
+  Functions: 15528
+  Symbols:   14447
+  CStrings:  3617
Symbols:
+ -[DBLockOutController environmentConfiguration:appearanceStyleDidChange:fence:]
+ -[DBLockOutViewController _updateAdditionalSafeAreaInsets]
+ -[DBLockOutViewController environmentConfiguration:viewAreaDidChangeFromViewAreaFrame:safeAreaInsets:toViewAreaFrame:safeAreaInsets:duration:transitionControlType:]
+ -[DBStatusBarViewController punchthroughLauncher]
+ -[DBStatusBarViewController setActionForPartWithIdentifier:]
+ -[DBStatusBarViewController setPunchthroughLauncher:]
+ _OBJC_CLASS_$_STUIStatusBarAction
+ _OBJC_CLASS_$_STUIStatusBarCarPlayWirelessChargerIdentifier
+ _OBJC_CLASS_$__TtC9DashBoard22DBPunchthroughLauncher
+ _OBJC_IVAR_$_DBStatusBarViewController._punchthroughLauncher
+ _OBJC_METACLASS_$__TtC9DashBoard22DBPunchthroughLauncher
+ _STUIStatusBarCarPlayPartIdentifierSuffix
+ _STUIStatusBarMakeCarPlayPartIdentifier
+ _STUIStatusBarPartIdentifierCarPlayAutomakerStatusItem
+ _STUIStatusBarPartIdentifierCarPlayBluetooth
+ _STUIStatusBarPartIdentifierCarPlayCellular
+ _STUIStatusBarPartIdentifierCarPlayCurrentUser
+ _STUIStatusBarPartIdentifierCarPlayWifi
+ _STUIStatusBarPartIdentifierCarPlayWirelessCharger
+ __DATA__TtC9DashBoard22DBPunchthroughLauncher
+ __INSTANCE_METHODS__TtC9DashBoard22DBPunchthroughLauncher
+ __IVARS__TtC9DashBoard22DBPunchthroughLauncher
+ __METACLASS_DATA__TtC9DashBoard22DBPunchthroughLauncher
+ ___164-[DBLockOutViewController environmentConfiguration:viewAreaDidChangeFromViewAreaFrame:safeAreaInsets:toViewAreaFrame:safeAreaInsets:duration:transitionControlType:]_block_invoke
+ ___60-[DBStatusBarViewController setActionForPartWithIdentifier:]_block_invoke
+ ___61-[DBUISyncLockOutView initWithMode:environmentConfiguration:]_block_invoke
+ ___79-[DBLockOutController environmentConfiguration:appearanceStyleDidChange:fence:]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e23_B16?0"STUIStatusBar"8lw40l8s32l8
+ _associated conformance So23STStatusBarDataEntryKeyaSHSCSQ
+ _associated conformance So23STStatusBarDataEntryKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So23STStatusBarDataEntryKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _associated conformance So27STUIStatusBarPartIdentifieraSHSCSQ
+ _associated conformance So27STUIStatusBarPartIdentifieras20_SwiftNewtypeWrapperSCSY
+ _associated conformance So27STUIStatusBarPartIdentifieras20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _symbolic $s9DashBoard16ActionableStatus33_8EB36A9F2F430E517D3CE1869704A923LLP
+ _symbolic $s9DashBoard17ActionableService33_8EB36A9F2F430E517D3CE1869704A923LLP
+ _symbolic $s9DashBoard28VehicleStatusBarEntryService33_8EB36A9F2F430E517D3CE1869704A923LLP
+ _symbolic SDySSSaySo24CAFWirelessChargerStatusCGGSg
+ _symbolic So10CAFServiceC
+ _symbolic _____ 9DashBoard22DBPunchthroughLauncherC
+ _symbolic _____ So23STStatusBarDataEntryKeya
+ _symbolic _____ So27STUIStatusBarPartIdentifiera
+ _symbolic _____Sg 14CarPlayAssetUI23VisibilityConfigurationV
+ _symbolic _____ySDyS2SGG 9DashBoard7DefaultC
+ _symbolic _____ySSSaySo24CAFWirelessChargerStatusCGG s18_DictionaryStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So27STUIStatusBarPartIdentifiera
+ _symbolic _____y______y_____y_____SSGSg_GG 7Combine10PublishersO4DropV AA9PublishedV9PublisherV 14CarPlayAssetUI11TaggedValueV AJ9ComponentV
+ _symbolic _____y_____y_____SSGSg_G 7Combine9PublishedV9PublisherV 14CarPlayAssetUI11TaggedValueV AF9ComponentV
+ _type_layout_string So27STUIStatusBarPartIdentifiera
- _OBJC_CLASS_$__TtC9DashBoard29DBAppLinkPunchthroughLauncher
- _OBJC_METACLASS_$__TtC9DashBoard29DBAppLinkPunchthroughLauncher
- __DATA__TtC9DashBoard29DBAppLinkPunchthroughLauncher
- __INSTANCE_METHODS__TtC9DashBoard29DBAppLinkPunchthroughLauncher
- __IVARS__TtC9DashBoard29DBAppLinkPunchthroughLauncher
- __METACLASS_DATA__TtC9DashBoard29DBAppLinkPunchthroughLauncher
- _symbolic _____ 9DashBoard29DBAppLinkPunchthroughLauncherC
- _symbolic _____Sg3key_SaySo24CAFWirelessChargerStatusCG5valuet 13CarAssetUtils19CAUVehicleLayoutKeyO
- _symbolic _____y_____SgSaySo24CAFWirelessChargerStatusCGG s18_DictionaryStorageC 13CarAssetUtils19CAUVehicleLayoutKeyO
CStrings:
+ "%s key=%s"
+ "%s(%@) action fired for %@ contentURLAction=%@"
+ "%s(%@) action fired for %@ with no scene"
+ "%s(%@) no action for %@"
+ "%s(%@) setting action for %@"
+ "-[DBStatusBarViewController setActionForPartWithIdentifier:]"
+ "-[DBStatusBarViewController setActionForPartWithIdentifier:]_block_invoke"
+ "B16@?0@\"STUIStatusBar\"8"
+ "DashBoard.DBPunchthroughLauncher"
+ "Did present: %s"
+ "Failed to present: %s"
+ "Will present: %s"
+ "lastActiveMapsMediaByVehicleID"
+ "removeEntry(forKey:)"
- "DashBoard.DBAppLinkPunchthroughLauncher"
```
