## sharereportingd

> `/usr/libexec/sharereportingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2867` | `0x2485` | **`-0x3e2`** |
| `__TEXT.__text` | `0x44bc8` | `0x44d80` | **`+0x1b8`** |
| `__TEXT.__eh_frame` | `0x3750` | `0x3648` | **`-0x108`** |
| `__DATA.__data` | `0x1830` | `0x17f8` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0xc0f` | `0xbde` | **`-0x31`** |
| `__TEXT.__const` | `0x3a48` | `0x3a1e` | **`-0x2a`** |
| `__TEXT.__unwind_info` | `0x1498` | `0x1478` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x8d3` | `0x8f1` | **`+0x1e`** |
| `__DATA_CONST.__const` | `0x28d0` | `0x28b8` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x424` | `0x40c` | **`-0x18`** |
| `__TEXT.__objc_methtype` | `0x307` | `0x2f2` | **`-0x15`** |
| `__DATA.__bss` | `0x5490` | `0x5480` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x290` | `0x280` | **`-0x10`** |
| `__DATA.__common` | `0xb0` | `0xb8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x340` | `0x338` | **`-0x8`** |
| `__TEXT.__objc_classname` | `0x1c0` | `0x1ba` | **`-0x6`** |
| `__TEXT.__swift_as_entry` | `0xe0` | `0xdc` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x1ac` | `0x1a8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-95.0.0.0.0
+104.0.0.0.0

+  - /usr/lib/libMobileGestalt.dylib

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 1401
-  Symbols:   503
-  CStrings:  383
+  Functions: 1400
+  Symbols:   501
+  CStrings:  390
Symbols:
+ _$s10Foundation3URLV17lastPathComponentSSvg
+ _$s10Foundation3URLV4host14percentEncodedSSSgSb_tF
+ _$s15Synchronization5MutexVMn
+ _$sSS10lowercasedSSyF
+ _$sSh10FoundationE36_unconditionallyBridgeFromObjectiveCyShyxGSo5NSSetCSgFZ
+ _$ss26DefaultStringInterpolationV06appendC0yyxlF
+ _CKValidSharingURLHostnames
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_internalBuild
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
- _$s17_StringProcessing14RegexComponentP5regexAA0C0Vy0C6OutputQzGvgTj
- _$s17_StringProcessing5RegexV06_regexA07versionACyxGSS_SitcfC
- _$s17_StringProcessing5RegexV10wholeMatch2inAC0E0Vyx_GSgSs_tKF
- _$s17_StringProcessing5RegexV5MatchV13dynamicMemberqd__s7KeyPathCyxqd__G_tcluig
- _$s17_StringProcessing5RegexV5MatchVMn
- _$s17_StringProcessing5RegexVMn
- _$s17_StringProcessing5RegexVyxGAA0C9ComponentAAMc
- _$sSS14_fromSubstringySSSshFZ
- _$sSSySsSnySS5IndexVGcig
- _$sSh11descriptionSSvg
- _$ss5print_9separator10terminatoryypd_S2StF
- _swift_getKeyPath
- _swift_retain_x25
CStrings:
+ " VARCHAR NOT NULL,\n    "
+ ")\nVALUES (?, ?, ?, ?, ?)\nON CONFLICT("
+ "DELETE FROM SRJunkReports WHERE token = ?"
+ "DELETE FROM SRRegistrations WHERE token = ?"
+ "Granted access to daemon container. { identifier="
+ "Rejecting share on an unrecognized sharing hostname. { share="
+ "Rejecting share with no token. { share="
+ "Share URL does not contain a token."
+ "Share URL hostname is not a valid iCloud sharing hostname."
+ "facetimemessagestored"
+ "sharereportingd/BackgroundActivityManager.swift"
+ "sharereportingd/CleanUpBackgroundActivity.swift"
+ "sharereportingd/ContainerManager.swift"
+ "sharereportingd/CoreAnalyticsManager.swift"
+ "sharereportingd/DeviceUtility.swift"
+ "sharereportingd/GenericSQLiteManager.swift"
+ "sharereportingd/SQLiteBindingHelpers.swift"
+ "sharereportingd/SQLiteColumnExtractor.swift"
+ "sharereportingd/Server.swift"
+ "sharereportingd/ServerProxy.swift"
+ "sharereportingd/ShareReportManager+Types.swift"
+ "sharereportingd/ShareReportManager.swift"
+ "sharereportingd/main.swift"
- "#/(?<base>https://www\\.icloud\\.com/[^/]+/[^#]+)(#.*)?/#"
- ")\nVALUES (?, ?, ?, ?)\nON CONFLICT("
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/TrustKit/Source/BackgroundActivityManager.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/TrustKit/Source/CoreAnalyticsManager.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/TrustKit/Source/GenericSQLiteManager.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/TrustKit/Source/SQLiteBindingHelpers.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/TrustKit/Source/SQLiteColumnExtractor.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/TrustKit/Source/Utility/ContainerManager.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/sharereportingd/CleanUpBackgroundActivity.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/sharereportingd/Server.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/sharereportingd/ServerProxy.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/sharereportingd/ShareReportManager+Types.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/sharereportingd/ShareReportManager.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TrustKit/sharereportingd/main.swift"
- "DELETE FROM SRJunkReports WHERE shareURL = ?"
- "DELETE FROM SRRegistrations WHERE shareURL = ?"
```
