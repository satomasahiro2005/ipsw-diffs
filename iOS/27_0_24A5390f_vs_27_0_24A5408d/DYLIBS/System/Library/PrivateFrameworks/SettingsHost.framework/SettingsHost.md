## SettingsHost

> `/System/Library/PrivateFrameworks/SettingsHost.framework/SettingsHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93320` | `0x95ed8` | **`+0x2bb8`** |
| `__TEXT.__oslogstring` | `0x2564` | `0x2884` | **`+0x320`** |
| `__AUTH_CONST.__const` | `0x50e0` | `0x52c0` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `0x2848` | `0x29d0` | **`+0x188`** |
| `__DATA.__bss` | `0x6a50` | `0x6bd0` | **`+0x180`** |
| `__TEXT.__const` | `0x6878` | `0x69e8` | **`+0x170`** |
| `__TEXT.__swift5_typeref` | `0x1b84` | `0x1cc4` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0x189e` | `0x197e` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x3c58` | `0x3d08` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x1bc4` | `0x1c70` | **`+0xac`** |
| `__TEXT.__constg_swiftt` | `0x18a0` | `0x1918` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x1bd8` | `0x1c50` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x1110` | `0x1140` | **`+0x30`** |
| `__DATA.__data` | `0xcc0` | `0xcf0` | **`+0x30`** |
| `__TEXT.__swift5_mpenum` | `0x68` | `0x94` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d0` | `0x3f0` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x1880` | `0x1890` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x474` | `0x484` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x498` | `0x4a4` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x1c0` | `0x1cc` | **`+0xc`** |

### Other Changes

```diff

-2027.0.5.0.0
+2027.0.7.0.0

-  Functions: 2591
-  Symbols:   977
-  CStrings:  590
+  Functions: 2652
+  Symbols:   996
+  CStrings:  600
Symbols:
+ _MobileGestalt_get_internalBuild
+ ___swift_memcpy129_8
+ ___swift_memcpy130_8
+ ___swift_memcpy17_8
+ ___swift_memcpy65_8
+ _associated conformance 12SettingsHost0A24SearchIndexingSimulationO14SimulatedFaultOSHAASQ
+ _objc_retain_x28
+ _swift_release_x1
+ _symbolic SDySSSo16LNActionMetadataCGIgo_
+ _symbolic SS16bundleIdentifier_SS06actionB0So16LNActionMetadataC5valuet
+ _symbolic Sd5width_Sd6heightt
+ _symbolic SdSg
+ _symbolic Si15domainsToDelete_Si3capt
+ _symbolic _____ 12SettingsHost0A18IconRepresentationV14SizingBehaviorV
+ _symbolic _____ 12SettingsHost0A18IconRepresentationV14SizingBehaviorV0eF4TypeO
+ _symbolic _____ 12SettingsHost0A24SearchIndexingSimulationO
+ _symbolic _____ 12SettingsHost0A24SearchIndexingSimulationO14SimulatedFaultO
+ _symbolic _____ySS16bundleIdentifier_SS06actionB0So16LNActionMetadataC5valuetG s23_ContiguousArrayStorageC
+ _symbolic _____ySSSDySSSo16LNActionMetadataCGG s18_DictionaryStorageC
+ _symbolic _____ySSSo16LNActionMetadataCG s18_DictionaryStorageC
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
+ _type_layout_string 12SettingsHost0A18IconRepresentationV14SizingBehaviorV
- ___swift_memcpy72_8
- ___swift_memcpy97_8
- _associated conformance 12SettingsHost08InternalA18SearchIndexerErrorOSHAASQ
CStrings:
+ "Invalidated %{public}ld lastIndexed_ record(s) after full index deletion."
+ "LNMetadataProvider.waitForInitialIndexing() failed: %{public}@. Skipping enumeration and leaving the index untouched this pass."
+ "Refusing stale-domain sweep: %{public}ld domains would be deleted, exceeding the safety cap of %{public}ld. Enumeration likely incomplete; leaving index intact."
+ "Retaining %{public}ld domain(s) absent from this pass's enumeration but already indexed for the current build/locale/generation — treating as transient Link Services incompleteness rather than stale removal."
+ "SettingsSearchSimulateDropLastIntentsCount"
+ "SettingsSearchSimulateWaitFailure"
+ "SettingsSearchSimulateZeroOpenIntents"
+ "com.apple.preference.extensions"
+ "⚠️ SIMULATION %{public}s: overriding %{public}ld OpenIntent(s) with an empty result."
+ "⚠️ SIMULATION %{public}s=%{public}ld: dropping %{public}ld of %{public}ld OpenIntent(s)."
```
