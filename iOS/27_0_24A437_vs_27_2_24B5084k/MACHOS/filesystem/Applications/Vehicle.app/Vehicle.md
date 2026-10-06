## Vehicle

> `/Applications/Vehicle.app/Vehicle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x222d8` | `0x22028` | **`-0x2b0`** |
| `__TEXT.__auth_stubs` | `0x1d90` | `0x1d80` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xed0` | `0xec8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4c0` | `0x4b8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-342.1.0.0.0
+351.2.0.0.0

+  - /System/Library/PrivateFrameworks/CarPlayAsset.framework/CarPlayAsset

-  Symbols:   779
+  Symbols:   777
Symbols:
+ _$s12CarPlayAsset4ZoneV0D6RegionO8rawValueSSvg
+ _$s13CarAssetUtils15CAUAssetLibraryC20featureConfigurationAA010CAUFeatureG0VyFTj
+ _$s5CAFUI26CAFNotificationDataSourcesC18notificationSource20settingsByIdentifier10zoneRegion11destination13actionHandlerAA0bF0CSDySSSo19CAFAutomakerSettingCGSg_12CarPlayAsset4ZoneV0tK0OAJ11DestinationOySSctFTj
+ _$sSq12CarPlayAssets23CustomStringConvertibleRzlE11descriptionSSvg
- _$s13CarAssetUtils15CAUAssetLibraryC10CAFCombineE20featureConfigurationAA010CAUFeatureH0VyF
- _$s14CarPlayAssetUI4ZoneV0E6RegionO5zone1yA2EmFWC
- _$s14CarPlayAssetUI4ZoneV0E6RegionO8rawValueSSvg
- _$s14CarPlayAssetUI4ZoneV0E6RegionOMa
- _$s5CAFUI26CAFNotificationDataSourcesC18notificationSource20settingsByIdentifier10zoneRegion11destination13actionHandlerAA0bF0CSDySSSo19CAFAutomakerSettingCGSg_14CarPlayAssetUI4ZoneV0uK0OAJ11DestinationOySSctFTj
- _$sSq14CarPlayAssetUIs23CustomStringConvertibleRzlE11descriptionSSvg
Functions:
~ sub_100008c44 -> sub_100008cac : 1860 -> 1644
~ sub_10001673c -> sub_1000166cc : 1256 -> 1020
~ sub_100016c24 -> sub_100016ac8 : 1256 -> 1020
```
