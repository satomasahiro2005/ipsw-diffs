## CoreServices

> `/System/Library/Frameworks/CoreServices.framework/CoreServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c52fc` | `0x1c63f8` | **`+0x10fc`** |
| `__TEXT.__gcc_except_tab` | `0x29128` | `0x29414` | **`+0x2ec`** |
| `__AUTH_CONST.__cfstring` | `0x178c0` | `0x179c0` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x155b8` | `0x15660` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0xb10` | `0xbb8` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x28bea` | `0x28c92` | **`+0xa8`** |
| `__DATA.__bss` | `0xfb0` | `0xf30` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x8c8` | `0x948` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x16208` | `0x16286` | **`+0x7e`** |
| `__AUTH.__objc_data` | `0x3430` | `0x33b8` | **`-0x78`** |
| `__DATA_DIRTY.__objc_data` | `0x18b0` | `0x1928` | **`+0x78`** |
| `__TEXT.__const` | `0x950` | `0x990` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xc560` | `0xc598` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xe13c` | `0xe16c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x73f0` | `0x7418` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x64f8` | `0x6510` | **`+0x18`** |
| `__AUTH.__data` | `0x328` | `0x318` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xbd8` | `0xbe8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA.__data` | `0x15c8` | `0x15c4` | **`-0x4`** |

### Other Changes

```diff

-1504.0.0.0.0
+1507.0.0.0.0

-  Functions: 9506
-  Symbols:   14204
-  CStrings:  6009
+  Functions: 9514
+  Symbols:   14216
+  CStrings:  6019
Symbols:
+ -[LSBundleRecordBuilder contentDescriptors]
+ -[LSBundleRecordBuilder secondaryGenreID]
+ -[LSiTunesMetadata contentDescriptors]
+ -[LSiTunesMetadata secondaryGenreIdentifier]
+ -[_LSCanOpenURLManager schemeQueryLimitForPlatform:linkingSDKVersion:]
+ GCC_except_table532
+ _OBJC_CLASS_$_MIStoreMetadataContentDescriptor
+ _OBJC_IVAR_$_LSBundleRecordBuilder._contentDescriptors
+ _OBJC_IVAR_$_LSBundleRecordBuilder._secondaryGenreID
+ _OBJC_IVAR_$_LSiTunesMetadata._contentDescriptors
+ _OBJC_IVAR_$_LSiTunesMetadata._secondaryGenreIdentifier
+ __LSDefaultAppCategoryIsValid
+ __LSPluginNotificationPayloadGetSessionKey
+ __LSPluginNotificationPayloadSetSessionKey
+ ___48-[LSiTunesMetadata _initWithContext:bundleData:]_block_invoke
+ ___block_descriptor_32_e385_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20l
+ ___block_descriptor_40_ea8_32s_e385_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20ls32l8
+ ___block_descriptor_40_ea8_32s_e385_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20ls32l8
+ ___block_descriptor_44_e385_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20l
+ ___block_descriptor_48_e8_32s40s_e385_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20ls32l8s40l8
+ ___block_descriptor_48_ea8_32bs_e382_v28?0"NSString"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20ls32l8
+ ___block_descriptor_52_e8_32s40n6_8_8_s0_e385_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20l
+ ___block_descriptor_56_ea8_32bs40bs_e372_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8s40l8
+ ___block_descriptor_56_ea8_32r40r_e372_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20lr32l8r40l8
+ ___block_descriptor_56_ea8_32s40bs_e372_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8s40l8
+ ___block_descriptor_624_ea8_32s_e19_v32?0I8r^v12I20*24ls32l8
+ ___block_descriptor_624_ea8_32s_e37_v40?0q8"NSString"16"NSString"24*32ls32l8
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_68_ea8_32s40s48s_e372_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32bs40r48r_e372_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8r40l8r48l8
+ ___block_descriptor_72_ea8_32s40s48r_e372_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8s40l8r48l8
+ ___block_descriptor_80_e8_32s40s48s56s64n6_8_8_s0_e385_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20l
- -[_LSCanOpenURLManager schemeQueryLimit]
- GCC_except_table155
- __OBJC_$_PROP_LIST__LSCanOpenURLManager
- ___LSApplicationWorkspacePluginsChangedCallback_block_invoke_2
- ___block_descriptor_32_e383_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20l
- ___block_descriptor_40_ea8_32s_e383_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20ls32l8
- ___block_descriptor_40_ea8_32s_e383_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20ls32l8
- ___block_descriptor_44_e383_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20l
- ___block_descriptor_48_e8_32s40s_e383_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20ls32l8s40l8
- ___block_descriptor_48_ea8_32bs_e380_v28?0"NSString"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20ls32l8
- ___block_descriptor_52_e8_32s40n6_8_8_s0_e383_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20l
- ___block_descriptor_52_ea8_32s_e370_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8
- ___block_descriptor_56_ea8_32bs40bs_e370_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8s40l8
- ___block_descriptor_56_ea8_32r40r_e370_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20lr32l8r40l8
- ___block_descriptor_56_ea8_32s40bs_e370_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8s40l8
- ___block_descriptor_612_ea8_32s_e19_v32?0I8r^v12I20*24ls32l8
- ___block_descriptor_612_ea8_32s_e37_v40?0q8"NSString"16"NSString"24*32ls32l8
- ___block_descriptor_72_e8_32bs40r48r_e370_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8r40l8r48l8
- ___block_descriptor_72_ea8_32s40s48r_e370_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20ls32l8s40l8r48l8
- ___block_descriptor_80_e8_32s40s48s56s64n6_8_8_s0_e383_v28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20l
CStrings:
+ "B28@?0@\"_LSDatabase\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20"
+ "B28@?0^{LSContext=@}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20"
+ "Could not determine local session for %@; processing anyway: %@"
+ "Ignoring %@ from session %@; this process reflects session %@"
+ "Invalid default app category"
+ "LSPluginNotificationSessionKey"
+ "contentDescriptors"
+ "isSystemSession"
+ "secondaryGenreID"
+ "secondaryGenreId"
+ "secondaryGenreIdentifier"
+ "uid"
+ "v28@?0@\"NSString\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20"
+ "v28@?0@\"_LSDatabase\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20"
+ "v28@?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20"
- "B28@?0@\"_LSDatabase\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20"
- "B28@?0^{LSContext=@}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20"
- "v28@?0@\"NSString\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20"
- "v28@?0@\"_LSDatabase\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}20"
- "v28@?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIIICCIII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIIC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}II{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IQQQIIIIIIIIIIQIIQQQQIQQIIIQIQIIQIIIIIIIIIIIIIIIICCC[1I]II{LSAppClipFields=I}iIIIIIIII}12*20"
```
