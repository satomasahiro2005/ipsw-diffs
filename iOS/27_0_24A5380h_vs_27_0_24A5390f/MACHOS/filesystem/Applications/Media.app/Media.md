## Media

> `/Applications/Media.app/Media`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc5ed4` | `0xc69e0` | **`+0xb0c`** |
| `__TEXT.__objc_methname` | `0x8145` | `0x8205` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x4020` | `0x40e0` | **`+0xc0`** |
| `__TEXT.__const` | `0x7334` | `0x73e4` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x756a` | `0x75f0` | **`+0x86`** |
| `__DATA.__data` | `0x4f40` | `0x4f80` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x31a0` | `0x31e0` | **`+0x40`** |
| `__DATA.__objc_const` | `0x4460` | `0x4498` | **`+0x38`** |
| `__DATA.__objc_data` | `0x36c0` | `0x36f0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1b28` | `0x1b58` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x37ac` | `0x37d8` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0x2018` | `0x2040` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x18e0` | `0x1900` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1a5a` | `0x1a7a` | **`+0x20`** |
| `__DATA.__common` | `0x270` | `0x280` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb08` | `0xb18` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x216c` | `0x217c` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x2d31` | `0x2d21` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x192c` | `0x1938` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-337.2.0.0.0
+340.0.0.0.0

-  Functions: 3395
-  Symbols:   1482
-  CStrings:  1939
+  Functions: 3405
+  Symbols:   1488
+  CStrings:  1946
Symbols:
+ _$s5CAFUI23CAFUITileViewControllerC10carSession19prominentCategories9listItems16settingsSections0K5Cache12assetManager014requestContentO025preventVolumeNotification15sharedAudioLogoACSo10CARSessionC_SaySo19CAFSettingsCategoryVGSayAA17CAFUIDataListItemCGSayAA29CAFUIAutomakerSettingsSectionVGAA013CAFUISettingsM0VSg13CarAssetUtils015CAUAssetLibraryO0CAA012CAFUIRequestqO0CSgS2b9isVisible_So15UIBarButtonItemCSg4itemtSgtcfCTq
+ _$s5CAFUI23CAFUITileViewControllerC10carSession19prominentCategories9listItems16settingsSections0K5Cache12assetManager014requestContentO025preventVolumeNotification15sharedAudioLogoACSo10CARSessionC_SaySo19CAFSettingsCategoryVGSayAA17CAFUIDataListItemCGSayAA29CAFUIAutomakerSettingsSectionVGAA013CAFUISettingsM0VSg13CarAssetUtils015CAUAssetLibraryO0CAA012CAFUIRequestqO0CSgS2b9isVisible_So15UIBarButtonItemCSg4itemtSgtcfc
+ _$sSo13UIFocusSystemC5UIKitE05focusB03forABSgSo0A11Environment_p_tFZ
+ _$sSqMa
+ _OBJC_CLASS_$_UIFocusSystem
+ _OBJC_CLASS_$__UIFocusUpdateRequest
+ _swift_release_x11
+ _swift_release_x2
- _$s5CAFUI23CAFUITileViewControllerC10carSession19prominentCategories9listItems16settingsSections0K5Cache12assetManager014requestContentO025preventVolumeNotification014rightBarButtonJ0ACSo10CARSessionC_SaySo19CAFSettingsCategoryVGSayAA17CAFUIDataListItemCGSayAA29CAFUIAutomakerSettingsSectionVGAA013CAFUISettingsM0VSg13CarAssetUtils015CAUAssetLibraryO0CAA012CAFUIRequestqO0CSgSbSaySo05UIBarW4ItemCGSgtcfCTq
- _$s5CAFUI23CAFUITileViewControllerC10carSession19prominentCategories9listItems16settingsSections0K5Cache12assetManager014requestContentO025preventVolumeNotification014rightBarButtonJ0ACSo10CARSessionC_SaySo19CAFSettingsCategoryVGSayAA17CAFUIDataListItemCGSayAA29CAFUIAutomakerSettingsSectionVGAA013CAFUISettingsM0VSg13CarAssetUtils015CAUAssetLibraryO0CAA012CAFUIRequestqO0CSgSbSaySo05UIBarW4ItemCGSgtcfc
CStrings:
+ "_requestFocusUpdate:"
+ "init(carSession:prominentCategories:listItems:settingsSections:settingsCache:assetManager:requestContentManager:preventVolumeNotification:sharedAudioLogo:)"
+ "initWithEnvironment:"
+ "leftAnchor"
+ "rightAnchor"
+ "savedFocusedIndexPath"
+ "setAllowsDeferral:"
+ "setSemanticContentAttribute:"
- "init(carSession:prominentCategories:listItems:settingsSections:settingsCache:assetManager:requestContentManager:preventVolumeNotification:rightBarButtonItems:)"
```
