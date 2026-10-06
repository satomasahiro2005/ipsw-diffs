## SESDiagnosticExtension

> `/System/Library/PrivateFrameworks/SEService.framework/PlugIns/SESDiagnosticExtension.appex/SESDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x854` | `0xa70` | **`+0x21c`** |
| `__DATA_CONST.__cfstring` | `0x120` | `0x2e0` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x86` | `0x188` | **`+0x102`** |
| `__DATA_CONST.__objc_dictobj` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x360` | `0x3e0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x292` | `0x308` | **`+0x76`** |
| `__TEXT.__oslogstring` | `0x15a` | `0x1bd` | **`+0x63`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x50` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0xe0` | `0x110` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x50` | `0x68` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x13` | `0x1e` | **`+0xb`** |
| `__DATA_CONST.__auth_got` | `0xd0` | `0xd8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-70.31.1.0.0
+70.34.0.0.0

-  Functions: 5
-  Symbols:   49
-  CStrings:  47
+  Functions: 7
+  Symbols:   53
+  CStrings:  70
Symbols:
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_CLASS_$_NSUserDefaults
+ ___kCFBooleanTrue
+ _objc_alloc
CStrings:
+ "EnableZoneLogging"
+ "Engineering"
+ "ExtraZoningLog"
+ "FWCoreDumpEnable"
+ "FWStreamLogging"
+ "FWStreamLoggingEnable"
+ "HCI"
+ "HCITraces"
+ "SESDiagnosticExtension: removing logging defaults"
+ "SESDiagnosticExtension: setting logging defaults"
+ "StackDebugEnabled"
+ "com.apple.MobileBluetooth.debug"
+ "com.apple.seserviced"
+ "debug.install.logging.applet"
+ "debug.logging.profile.to.install"
+ "initWithSuiteName:"
+ "lmpRouting"
+ "removeObjectForKey:"
+ "setBool:forKey:"
+ "setObject:forKey:"
+ "setupWithParameters:"
+ "teardownWithParameters:"
+ "v24@0:8@16"
```
