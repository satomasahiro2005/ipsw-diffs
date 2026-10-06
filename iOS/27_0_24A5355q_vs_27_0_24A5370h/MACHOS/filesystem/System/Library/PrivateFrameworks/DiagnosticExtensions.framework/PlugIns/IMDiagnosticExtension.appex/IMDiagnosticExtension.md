## IMDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/IMDiagnosticExtension.appex/IMDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a48` | `0x1e78` | **`+0x430`** |
| `__TEXT.__objc_stubs` | `0x600` | `0x740` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x57b` | `0x67e` | **`+0x103`** |
| `__TEXT.__cstring` | `0x1bf` | `0x28f` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0x120` | `0x1e0` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x190` | `0x1e0` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x430` | `0x480` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x98` | `0xd0` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x228` | `0x250` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x154` | `0x16c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x110` | `0x120` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Functions: 52
-  Symbols:   113
-  CStrings:  98
+  Functions: 56
+  Symbols:   125
+  CStrings:  114
Symbols:
+ _IMDIndexingThrottleHistoryFilePath
+ _IMDPreviousClientStateDataGet
+ _OBJC_CLASS_$_IMSpotlightClientState
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSKeyedUnarchiver
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_CLASS_$_NSSet
+ _objc_alloc
+ _objc_opt_class
+ _objc_opt_isKindOfClass
CStrings:
+ "IMCSPreviousClientStateData"
+ "IMCSPreviousClientStateData_decodeError"
+ "IMCSPreviousClientStateData_decoded"
+ "_collectIndexingKVStoreContents"
+ "_collectThrottleHistorySidePlist"
+ "com.apple.IMCoreSpotlight.IMDKV.plist"
+ "com.apple.imdpersistence.IMDIndexingThrottleHistory.plist"
+ "dataWithContentsOfURL:options:error:"
+ "dictionary"
+ "fileExistsAtPath:"
+ "initWithData:error:"
+ "localizedDescription"
+ "setObject:forKeyedSubscript:"
+ "setWithObjects:"
+ "unarchivedObjectOfClasses:fromData:error:"
+ "unknown"
```
