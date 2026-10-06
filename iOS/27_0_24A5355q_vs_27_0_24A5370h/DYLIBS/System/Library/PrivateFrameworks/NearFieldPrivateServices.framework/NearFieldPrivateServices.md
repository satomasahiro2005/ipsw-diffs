## NearFieldPrivateServices

> `/System/Library/PrivateFrameworks/NearFieldPrivateServices.framework/NearFieldPrivateServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79e0` | `0x7dfc` | **`+0x41c`** |
| `__AUTH_CONST.__cfstring` | `0x820` | `0x900` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x173d` | `0x17d9` | **`+0x9c`** |
| `__AUTH_CONST.__objc_const` | `0x940` | `0x9a0` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x190` | `0x1e0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x540` | `0x568` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x61c` | `0x644` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b8` | `0x4d0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x30` | `0x2c` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-370.33.1.0.0
+370.37.0.0.0

-  Functions: 126
-  Symbols:   119
-  CStrings:  268
+  Functions: 129
+  Symbols:   121
+  CStrings:  274
Symbols:
+ _OBJC_CLASS_$_NFReportingService
+ _OBJC_METACLASS_$_NFReportingService
CStrings:
+ "%s:%i Endpoint error"
+ "%s:%i Endpoint=%{public}@, connection=%{public}@"
+ "%s:%i processNDEF error=%{public}@"
+ "%{public}s:%i Endpoint error"
+ "%{public}s:%i Endpoint=%{public}@, connection=%{public}@"
+ "%{public}s:%i processNDEF error=%{public}@"
+ "-[NFBSClient_BackgroundTagReading _onInvalidation:]"
+ "<BSServiceConnectionError, code=%ld>"
+ "BSServiceDispatchQueue"
+ "BSServiceInitiatingConnection"
+ "NFCUISceneService activate"
+ "com.apple.stockholm.services.NFReportingService"
+ "configureReporter"
+ "httpStatusCode"
+ "isProdSE"
+ "reportData"
+ "sendReport"
+ "v16@?0@\"<BSServiceInitiatingConnectionConfiguring>\"8"
+ "v16@?0@\"BSServiceInitiatingConnection<BSServiceConnectionContext>\"8"
- "%s:%i BSService endpoint error"
- "%s:%i BSServiceConnection=%@"
- "%s:%i BSServiceConnectionEndpoint=%@"
- "%s:%i processNDEF error=%@"
- "%{public}s:%i BSService endpoint error"
- "%{public}s:%i BSServiceConnection=%@"
- "%{public}s:%i BSServiceConnectionEndpoint=%@"
- "%{public}s:%i processNDEF error=%@"
- "-[NFBSClient_BackgroundTagReading _activate]_block_invoke_2"
- "BSServiceConnection"
- "BSServiceQuality"
- "v16@?0@\"<BSServiceConnectionConfiguring>\"8"
- "v16@?0@\"BSServiceConnection<BSServiceConnectionContext>\"8"
```
