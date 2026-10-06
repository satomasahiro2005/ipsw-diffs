## PassbookStubAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/PassbookStubAppIntentsExtension.appex/PassbookStubAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3358` | `0x3fdc` | **`+0xc84`** |
| `__DATA.__bss` | `0x880` | `0xd00` | **`+0x480`** |
| `__TEXT.__const` | `0x570` | `0x820` | **`+0x2b0`** |
| `__TEXT.__auth_stubs` | `0x4b0` | `0x630` | **`+0x180`** |
| `__DATA_CONST.__auth_ptr` | `0x2d8` | `0x3b0` | **`+0xd8`** |
| `__DATA_CONST.__auth_got` | `0x260` | `0x320` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x27a` | `0x33a` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x173` | `0x1f3` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x60` | `0xe0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x2e1` | `0x359` | **`+0x78`** |
| `__DATA.__data` | `0x138` | `0x1a0` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x94` | `0xf8` | **`+0x64`** |
| `__TEXT.__swift5_reflstr` | `0x171` | `0x1d3` | **`+0x62`** |
| `__TEXT.__objc_methname` | `0x90` | `0xea` | **`+0x5a`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1f0` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0x90` | `0xd8` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x80` | `0xc0` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xb4` | `0xe8` | **`+0x34`** |
| `__TEXT.__swift5_proto` | `0x44` | `0x68` | **`+0x24`** |
| `__DATA.__objc_selrefs` | `0x18` | `0x38` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0xc` | `0x14` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1677.4.0.0.0
+1682.1.0.0.0

+  - /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication

-  Functions: 101
-  Symbols:   78
-  CStrings:  16
+  Functions: 138
+  Symbols:   95
+  CStrings:  24
Symbols:
+ _LAErrorDomain
+ _OBJC_CLASS_$_LAContext
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_PKPaymentWebService
+ _OBJC_CLASS_$_PKWebServiceRemoteNetworkPaymentFeature
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_opt_self
+ _objc_release_x20
+ _objc_release_x23
+ _objc_release_x27
+ _objc_release_x8
+ _objc_retain
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x21
+ _swift_getForeignTypeMetadata
+ _swift_getObjCClassMetadata
CStrings:
+ "Biometrics Locked Out"
+ "Feature Not Supported"
+ "biometricsLockedOut"
+ "canEvaluatePolicy:error:"
+ "enabled"
+ "featureNotSupported"
+ "remoteNetworkPaymentFeatureWithWebService:"
+ "sharedService"
```
