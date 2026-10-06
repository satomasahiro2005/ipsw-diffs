## swtransparencyd

> `/usr/libexec/swtransparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf95f4` | `0xfde8c` | **`+0x4898`** |
| `__DATA.__objc_const` | `0xf358` | `0xe830` | **`-0xb28`** |
| `__TEXT.__objc_stubs` | `0x6b40` | `0x65c0` | **`-0x580`** |
| `__DATA.__bss` | `0x7548` | `0x7118` | **`-0x430`** |
| `__TEXT.__objc_methname` | `0x7b9d` | `0x77cd` | **`-0x3d0`** |
| `__TEXT.__objc_methlist` | `0x73ac` | `0x709c` | **`-0x310`** |
| `__TEXT.__eh_frame` | `0x67f4` | `0x69dc` | **`+0x1e8`** |
| `__DATA.__objc_selrefs` | `0x22d8` | `0x2148` | **`-0x190`** |
| `__TEXT.__objc_methtype` | `0x21f9` | `0x20a5` | **`-0x154`** |
| `__TEXT.__const` | `0x6000` | `0x5ed0` | **`-0x130`** |
| `__DATA_CONST.__cfstring` | `0x3180` | `0x3060` | **`-0x120`** |
| `__TEXT.__swift5_fieldmd` | `0x19a0` | `0x1a64` | **`+0xc4`** |
| `__DATA.__data` | `0x4980` | `0x48c0` | **`-0xc0`** |
| `__TEXT.__oslogstring` | `0x361d` | `0x36bd` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x11cb` | `0x1261` | **`+0x96`** |
| `__DATA_CONST.__const` | `0x5f58` | `0x5fc8` | **`+0x70`** |
| `__DATA_CONST.__auth_ptr` | `0x570` | `0x508` | **`-0x68`** |
| `__TEXT.__objc_classname` | `0x1a84` | `0x1a24` | **`-0x60`** |
| `__TEXT.__auth_stubs` | `0x2790` | `0x27e0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x650` | `0x698` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x1c8` | `0x180` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0x47c0` | `0x4800` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x13d8` | `0x1400` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x74c` | `0x724` | **`-0x28`** |
| `__TEXT.__cstring` | `0x4dc9` | `0x4da9` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x38c` | `0x36c` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x1af0` | `0x1ad4` | **`-0x1c`** |
| `__DATA.__objc_ivar` | `0x47c` | `0x464` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x660` | `0x648` | **`-0x18`** |
| `__DATA_CONST.__objc_protolist` | `0xe0` | `0xd0` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x308` | `0x2f8` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x1425` | `0x141b` | **`-0xa`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x48` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x74` | `0x7c` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x5bc` | `0x5c4` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x34` | `0x38` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1b8` | `0x1b4` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x390` | `0x394` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x368` | `0x36c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-1766.0.13.0.0
+1766.0.27.0.0

-  Functions: 6028
-  Symbols:   965
-  CStrings:  2970
+  Functions: 6029
+  Symbols:   957
+  CStrings:  2890
Symbols:
+ _$s10Foundation3URLV34withUnsafeFileSystemRepresentationyxxSPys4Int8VGSgKXEKlF
+ _$s10Foundation4DateV026timeIntervalSinceReferenceB0ACSd_tcfC
+ _$s10Foundation4DateV026timeIntervalSinceReferenceB0Sdvg
+ _$sBpWV
+ _$sSD15reserveCapacityyySiF
+ _$sSPyxGs7CVarArgsMc
+ _$sSS7cStringSSSPys4Int8VG_tcfC
+ _$sSS7cStringSSSPys5UInt8VG_tcfC
+ _$ss13OpaquePointerVMn
+ _$ss15__VaListBuilderC7va_lists03CVaB7PointerVyF
+ _$ss15__VaListBuilderCMa
+ _$ss4Int8VMn
+ _$ss5ErrorP10FoundationE20localizedDescriptionSSvg
+ _$ss6HasherV5_hash4seed_S2i_s6UInt64VtFZ
+ _$ss7CVarArgMp
+ _$ss7CVarArgP05_cVarB8EncodingSaySiGvgTj
+ _sqlite3_free
+ _sqlite3_get_autocommit
+ _sqlite3_vmprintf
- _$s10Foundation18_ErrorCodeProtocolMp
- _$s10Foundation18_ErrorCodeProtocolP01_B4TypeAC_AA21_BridgedStoredNSErrorTn
- _$s10Foundation18_ErrorCodeProtocolPSQTb
- _$s10Foundation21_BridgedStoredNSErrorMp
- _$s10Foundation21_BridgedStoredNSErrorP4CodeAC_8RawValueSYs17FixedWidthIntegerTn
- _$s10Foundation21_BridgedStoredNSErrorP4CodeAC_AA06_ErrorE8ProtocolTn
- _$s10Foundation21_BridgedStoredNSErrorP4CodeAC_SYTn
- _$s10Foundation21_BridgedStoredNSErrorP8_nsErrorSo0D0CvgTq
- _$s10Foundation21_BridgedStoredNSErrorP8_nsErrorxSo0D0C_tcfCTq
- _$s10Foundation21_BridgedStoredNSErrorPAA06CustomD0Tb
- _$s10Foundation21_BridgedStoredNSErrorPAA26_ObjectiveCBridgeableErrorTb
- _$s10Foundation21_BridgedStoredNSErrorPAAE012_getEmbeddedD0yXlSgyF
- _$s10Foundation21_BridgedStoredNSErrorPAAE08_bridgedD0xSgSo0D0C_tcfC
- _$s10Foundation21_BridgedStoredNSErrorPAAE13errorUserInfoSDySSypGvg
- _$s10Foundation21_BridgedStoredNSErrorPAAE2eeoiySbx_xtFZ
- _$s10Foundation21_BridgedStoredNSErrorPAAE4code4CodeQzvg
- _$s10Foundation21_BridgedStoredNSErrorPAAE4hash4intoys6HasherVz_tF
- _$s10Foundation21_BridgedStoredNSErrorPAAE9errorCodeSivg
- _$s10Foundation21_BridgedStoredNSErrorPSHTb
- _$s10Foundation26_ObjectiveCBridgeableErrorMp
- _$s10Foundation26_ObjectiveCBridgeableErrorP15_bridgedNSErrorxSgSo0F0Ch_tcfCTq
- _$s10Foundation26_ObjectiveCBridgeableErrorPs0D0Tb
- _$s10_ErrorType10Foundation01_A12CodeProtocolPTl
- _$s4Code10Foundation21_BridgedStoredNSErrorPTl
- _$sSo8NSObjectC10ObjectiveCE9hashValueSivg
- _NSLocalizedDescriptionKey
- _objc_retainAutoreleaseReturnValue
CStrings:
+ "%Q"
+ "%s: sqlite3_exec: %s[%d]"
+ "Failed to quote SQL string"
+ "KTSwiftDBStmt prepare: %s"
+ "PRAGMA auto_vacuum = incremental"
+ "PRAGMA journal_mode = WAL"
+ "_TtC15swtransparencyd13KTSwiftDBStmt"
+ "sqlite3_bind_blob(rawbuffer): %d"
+ "sqlite3_bind_null: %d"
+ "stepWithError %d error: %s"
- "%@: %s"
- "@\"KTSDBObjc\""
- "@\"NSArray\"16@0:8"
- "@\"NSDate\"24@0:8Q16"
- "@\"NSDictionary\"16@0:8"
- "@\"NSObject<OS_os_log>\""
- "B16@?0@\"<KTSDBRow>\"8"
- "B32@0:8@16*24"
- "B32@0:8@?16^@24"
- "KTSDBObjc"
- "KTSDBObjcError"
- "KTSDBRow"
- "KTSDBStmt"
- "KTSDBStmt prepare: %@"
- "Q24@0:8@\"NSString\"16"
- "T@\"KTSDBObjc\",&,V_db"
- "T@\"NSDictionary\",&,N,V_indexesByColumnName"
- "T@\"NSObject<OS_os_log>\",&,V_log"
- "TB,V_needReset"
- "T^{sqlite3=},V_db"
- "T^{sqlite3_stmt=},V_stmt"
- "VACUUM"
- "^{sqlite3=}"
- "^{sqlite3=}16@0:8"
- "^{sqlite3_stmt=}"
- "^{sqlite3_stmt=}16@0:8"
- "_TtCC15swtransparencyd9KTSwiftDB12SQLStatement"
- "_TtCC15swtransparencyd9KTSwiftDB6SQLRow"
- "_db"
- "_indexesByColumnName"
- "_log"
- "_needReset"
- "_stmt"
- "allObjects"
- "allObjectsByColumnName"
- "autoVacuumSetting"
- "bindData:column:"
- "bindDate:column:"
- "bindDouble:column:"
- "bindInt64:column:"
- "bindInt:column:"
- "bindNullAtColumn:"
- "bindString:column:"
- "blobAtColumn:"
- "clearBindings"
- "columnCount"
- "columnNameAtColumn:"
- "columnTypeAtColumn:"
- "dateAtColumn:"
- "dictionaryWithCapacity:"
- "doubleAtColumn:"
- "enumerateColumnsUsingBlock:"
- "executeSQL:"
- "executeSQL:arguments:"
- "executeSQLStmt:"
- "generateDone"
- "generateError:method:"
- "indexForColumnName:"
- "initDatabaseWithURL:"
- "initWithFormat:arguments:"
- "initWithStatement:db:error:"
- "int64AtColumn:"
- "intAtColumn:"
- "null"
- "numberWithUnsignedInteger:"
- "objectAtColumn:"
- "pragma auto_vacuum = incremental"
- "pragma journal_mode = WAL"
- "prepareStatement:error:"
- "reset"
- "row"
- "setDb:"
- "setIndexesByColumnName:"
- "setLog:"
- "setNeedReset:"
- "setObject:atIndexedSubscript:"
- "setStmt:"
- "sqlite3_exec: %s[%d]"
- "sqliteCode"
- "step"
- "stepWithError %d error: %@"
- "stepWithError:"
- "steps"
- "steps: %@"
- "steps:error:"
- "textAtColumn:"
- "timeIntervalSinceReferenceDate"
- "v24@0:8^{sqlite3=}16"
- "v24@0:8^{sqlite3_stmt=}16"
- "v24@?0Q8@\"NSString\"16"
```
