## NanoControlCenter

> `/System/Library/PrivateFrameworks/NanoControlCenter.framework/NanoControlCenter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1f18` | `0xe25bc` | **`+0x6a4`** |
| `__AUTH_CONST.__cfstring` | `0xc0` | `0x120` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2b2e` | `0x2b6e` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x20e3` | `0x2123` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xce0` | `0xd18` | **`+0x38`** |
| `__TEXT.__const` | `0xc188` | `0xc158` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x14ac` | `0x14dc` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x6150` | `0x6170` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2ac9` | `0x2ae9` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x5c8` | `0x5b0` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1788` | `0x1798` | **`+0x10`** |
| `__DATA.__bss` | `0x8928` | `0x8938` | **`+0x10`** |
| `__DATA.__data` | `0x3758` | `0x3748` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2928` | `0x2934` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x7f6b` | `0x7f77` | **`+0xc`** |

### Other Changes

```diff

-95.1.0.0.0
+95.3.0.0.0

-  - /usr/lib/swift/libswiftCallKit.dylib

-  - /usr/lib/swift/libswiftMetalKit.dylib
-  - /usr/lib/swift/libswiftModelIO.dylib

-  Functions: 4715
-  Symbols:   2035
-  CStrings:  434
+  Functions: 4722
+  Symbols:   2039
+  CStrings:  438
Symbols:
+ +[NCCGlanceUtility _demoSettingsDefaults]
+ +[NCCGlanceUtility _isRunningInNanoPressDemoMode]
+ +[NCCGlanceUtility isRunningInDemoMode]
+ +[NCCGlanceUtility runningInDemoModeFProgramNumber]
+ ___41+[NCCGlanceUtility _demoSettingsDefaults]_block_invoke
+ ___swift_closure_destructor.78Tm
+ __demoSettingsDefaults.demoSettingsDefaults
+ __demoSettingsDefaults.onceToken
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _symbolic _____XDXMT 17NanoControlCenter16ButtonOrderModelC
- ___swift_closure_destructor.89Tm
- __swift_FORCE_LOAD_$_swiftCallKit
- __swift_FORCE_LOAD_$_swiftCallKit_$_NanoControlCenter
- __swift_FORCE_LOAD_$_swiftMetalKit
- __swift_FORCE_LOAD_$_swiftMetalKit_$_NanoControlCenter
- __swift_FORCE_LOAD_$_swiftModelIO
- __swift_FORCE_LOAD_$_swiftModelIO_$_NanoControlCenter
CStrings:
+ "%s inserting %s at index %ld in displayedButtonIDs of count %ld"
+ "FProgramNumber"
+ "NanoPressDemoMode"
+ "com.apple.demo-settings"
```
