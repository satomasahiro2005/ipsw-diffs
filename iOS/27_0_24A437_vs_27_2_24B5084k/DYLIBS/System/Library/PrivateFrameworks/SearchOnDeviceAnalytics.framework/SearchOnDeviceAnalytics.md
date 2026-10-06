## SearchOnDeviceAnalytics

> `/System/Library/PrivateFrameworks/SearchOnDeviceAnalytics.framework/SearchOnDeviceAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x171604` | `0x1773c0` | **`+0x5dbc`** |
| `__TEXT.__eh_frame` | `0xd264` | `0xd60c` | **`+0x3a8`** |
| `__TEXT.__oslogstring` | `0xb71` | `0xdf1` | **`+0x280`** |
| `__TEXT.__const` | `0x28210` | `0x28430` | **`+0x220`** |
| `__DATA.__bss` | `0x272c0` | `0x27440` | **`+0x180`** |
| `__AUTH.__data` | `0x9640` | `0x9780` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x5a78` | `0x5b90` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0x88e0` | `0x89f8` | **`+0x118`** |
| `__AUTH_CONST.__const` | `0xc708` | `0xc818` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x4219` | `0x42db` | **`+0xc2`** |
| `__TEXT.__swift5_reflstr` | `0xaf22` | `0xafc2` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x91f4` | `0x9290` | **`+0x9c`** |
| `__TEXT.__constg_swiftt` | `0x6da4` | `0x6e24` | **`+0x80`** |
| `__TEXT.__cstring` | `0x5f54` | `0x5fd4` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x1890` | `0x18e8` | **`+0x58`** |
| `__DATA.__data` | `0x5940` | `0x5990` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1dc0` | `0x1df8` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0xabc` | `0xaec` | **`+0x30`** |
| `__DATA.__common` | `0x259` | `0x269` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xb08` | `0xb18` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x14c0` | `0x14cc` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x534` | `0x540` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x6c` | `0x78` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x44` | `0x50` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x40` | `0x4c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x198` | `0x1a0` | **`+0x8`** |

### Other Changes

```diff

-3600.56.26.11.2
+3605.21.1.1.1

+  - /System/Library/PrivateFrameworks/PoirotAnalytics.framework/PoirotAnalytics

-  - /usr/lib/libMobileGestalt.dylib

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftMetal.dylib

+  - /usr/lib/swift/libswiftQuartzCore.dylib

+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib

-  Functions: 15405
-  Symbols:   3407
-  CStrings:  629
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 15515
+  Symbols:   3430
+  CStrings:  637
Symbols:
+ __DATA__TtC23SearchOnDeviceAnalytics21SAWTimeWindowBookmark
+ __IVARS__TtC23SearchOnDeviceAnalytics21SAWTimeWindowBookmark
+ __METACLASS_DATA__TtC23SearchOnDeviceAnalytics21SAWTimeWindowBookmark
+ ___swift_closure_destructor.6Tm
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftAccelerate_$_SearchOnDeviceAnalytics
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftMetal_$_SearchOnDeviceAnalytics
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftQuartzCore_$_SearchOnDeviceAnalytics
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers_$_SearchOnDeviceAnalytics
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_SearchOnDeviceAnalytics
+ _associated conformance 23SearchOnDeviceAnalytics12BlockFactoryC12PoirotBlocks013TableProducerF0AaD04UsereF0
+ _objc_retain_x27
+ _symbolic SS6source_SS4name_____5fieldt 17PoirotSchematizer13FieldManifestV
+ _symbolic Si6offset_SS6source_SS4name_____5fieldt7elementt 17PoirotSchematizer13FieldManifestV
+ _symbolic _____ 23SearchOnDeviceAnalytics11MetricStoreC11MetricsViewV
+ _symbolic _____ 23SearchOnDeviceAnalytics15SAWAssetsConfigV
+ _symbolic _____ 23SearchOnDeviceAnalytics21SAWTimeWindowBookmarkC
+ _symbolic _____Sg 12PoirotBlocks14DatabaseConfigV
+ _symbolic _____ySS3key______5valuetG s23_ContiguousArrayStorageC 17PoirotSchematizer13FieldManifestV
+ _symbolic _____ySS6source_SS4name_____5fieldtG s23_ContiguousArrayStorageC 17PoirotSchematizer13FieldManifestV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12PoirotBlocks10DataSourceV
- _MGCopyAnswer
- ___swift_closure_destructor.14Tm
CStrings:
+ "    SELECT\n        "
+ "Asset selection for %s: UAF content version %lu vs OS installed %lu -> %s wins"
+ "Failed to load Pegasus config from %{sensitive}s. File exists: %{bool}d. Callers that gate on config default to the disabled behavior."
+ "OTA recipe lookup DISABLED because the Pegasus config failed to load. Look for \"Failed to load Pegasus config\" or \"Could not read config plist\" earlier in the log, and confirm config.plist exists in the PegasusConfiguration container."
+ "OTA recipe lookup by config: %s=%{bool}d"
+ "SPOTLIGHT_METRIC_SEARCH_SIRI_ENGAGED"
+ "SPOTLIGHT_METRIC_ZKW_SIRI_ENGAGED"
+ "Skipping UAF asset lookup for %s because OTA recipe lookup is disabled. Only the OS installed recipe will be considered."
+ "pegasusKitDictionarySearch"
+ "webContentFilter"
- " AS\n    SELECT\n        "
- "RegulatoryModelNumber"
```
