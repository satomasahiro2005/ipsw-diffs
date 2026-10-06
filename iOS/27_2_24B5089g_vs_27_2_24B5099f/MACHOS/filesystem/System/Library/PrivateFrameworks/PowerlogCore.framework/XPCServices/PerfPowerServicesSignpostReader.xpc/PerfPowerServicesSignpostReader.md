## PerfPowerServicesSignpostReader

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/XPCServices/PerfPowerServicesSignpostReader.xpc/PerfPowerServicesSignpostReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e380` | `0x1eb54` | **`+0x7d4`** |
| `__TEXT.__oslogstring` | `0x12c1` | `0x1485` | **`+0x1c4`** |
| `__TEXT.__objc_methname` | `0x6026` | `0x6181` | **`+0x15b`** |
| `__TEXT.__objc_stubs` | `0x2fa0` | `0x30c0` | **`+0x120`** |
| `__DATA.__objc_selrefs` | `0x1510` | `0x1560` | **`+0x50`** |
| `__DATA.__objc_const` | `0x2818` | `0x2848` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x17e8` | `0x1810` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0xaab` | `0xabb` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x510` | `0x520` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x6e8` | `0x6f0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x294` | `0x298` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__cstring`

### Other Changes

```diff

-3486.40.98.0.0
+3486.40.112.0.0

-  Functions: 604
+  Functions: 611

-  CStrings:  1456
+  CStrings:  1473
CStrings:
+ "@\"NSMutableSet\""
+ "T@\"NSMutableSet\",&,V_bundleIDNegativeCache"
+ "_bundleIDNegativeCache"
+ "attributesOfItemAtPath:error:"
+ "bundleIDNegativeCache"
+ "contentsOfDirectoryAtPath:error:"
+ "distantPast"
+ "fileModificationDate"
+ "getBundleIDFromProcessImagePath: resolved bundleID=%@ via PLStateFilteringUtils fallback for processImagePath=%@"
+ "getBundleIDFromProcessImagePath: unable to resolve bundleID from processImagePath=%@ (bundlePath=%@)"
+ "getBundleIDFromRelocatedContainerForProcessImagePath:"
+ "getBundleIDFromRelocatedContainerForProcessImagePath: resolved bundleID=%@ for %@ under relocated container %@"
+ "lastPathComponent"
+ "processSignpostInterval: dropping %@ interval, unable to derive bundleID. endEvent.processName=%@ endEvent.processImagePath=%@"
+ "setBundleIDNegativeCache:"
+ "sortWithOptions:usingComparator:"
+ "stringByAppendingPathComponent:"
```
