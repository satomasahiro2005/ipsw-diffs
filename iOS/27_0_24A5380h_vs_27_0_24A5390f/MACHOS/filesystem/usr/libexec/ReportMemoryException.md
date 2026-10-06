## ReportMemoryException

> `/usr/libexec/ReportMemoryException`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93ac` | `0x9254` | **`-0x158`** |
| `__DATA.__objc_const` | `0x90` | `0x168` | **`+0xd8`** |
| `__DATA.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x6d0` | `0x710` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1040` | `0x1000` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x378` | `0x398` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x31` | `0x4f` | **`+0x1e`** |
| `__TEXT.__objc_methlist` | `0x14` | `0x2c` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0xb83` | `0xb72` | **`-0x11`** |
| `__TEXT.__cstring` | `0xf4a` | `0xf56` | **`+0xc`** |
| `__TEXT.__objc_classname` | `0xd` | `0x18` | **`+0xb`** |
| `__DATA.__objc_ivar` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__const` | `0xf0` | `0xe8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x170` | `0x178` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-360.0.0.0.0
+364.0.0.0.0

-  Functions: 63
-  Symbols:   488
-  CStrings:  406
+  Functions: 64
+  Symbols:   499
+  CStrings:  412
Symbols:
+ -[RMELogPath .cxx_destruct]
+ OBJC_IVAR_$_RMELogPath._fileCreationDate
+ OBJC_IVAR_$_RMELogPath._filePath
+ _OBJC_CLASS_$_RMELogPath
+ _OBJC_METACLASS_$_RMELogPath
+ _RMEGetTimeOrderedLogPaths
+ __OBJC_$_INSTANCE_METHODS_RMELogPath
+ __OBJC_$_INSTANCE_VARIABLES_RMELogPath
+ __OBJC_CLASS_RO_$_RMELogPath
+ __OBJC_METACLASS_RO_$_RMELogPath
+ ___RMEGetTimeOrderedLogPaths_block_invoke
+ ___block_descriptor_32_e35_q24?0"RMELogPath"8"RMELogPath"16l
+ _objc_getProperty
+ _objc_msgSendSuper2
+ _objc_retain_x28
+ _objc_storeStrong
- _RMEGetTimeOrderedLogPathsMatchingPrefs
- ___RMEGetTimeOrderedLogPathsMatchingPrefs_block_invoke
- ___block_descriptor_32_e25_q24?0"NSURL"8"NSURL"16l
- _objc_msgSend$dateWithTimeIntervalSinceNow:
- _objc_msgSend$keysSortedByValueUsingComparator:
CStrings:
+ ".cxx_destruct"
+ "@\"NSDate\""
+ "@\"NSString\""
+ "RMELogPath"
+ "_fileCreationDate"
+ "_filePath"
+ "init"
+ "q24@?0@\"RMELogPath\"8@\"RMELogPath\"16"
+ "v16@0:8"
- "dateWithTimeIntervalSinceNow:"
- "keysSortedByValueUsingComparator:"
- "q24@?0@\"NSURL\"8@\"NSURL\"16"
```
