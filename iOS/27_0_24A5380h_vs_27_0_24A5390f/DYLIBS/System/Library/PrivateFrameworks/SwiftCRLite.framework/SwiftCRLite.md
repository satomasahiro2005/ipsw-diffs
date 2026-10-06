## SwiftCRLite

> `/System/Library/PrivateFrameworks/SwiftCRLite.framework/SwiftCRLite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb57c4` | `0xb646c` | **`+0xca8`** |
| `__AUTH_CONST.__objc_const` | `0x1820` | `0x19e0` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x4bc` | `0x53c` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x90` | `0xe0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x458` | `0x4a0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x40bc` | `0x40fc` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x17fe` | `0x181e` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1208` | `0x1220` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x10` | `0x28` | **`+0x18`** |
| `__DATA.__common` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA.__data` | `0x11b8` | `0x11c8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x568` | `0x578` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2638` | `0x2648` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xb0` | `0xb8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x690` | `0x698` | **`+0x8`** |
| `__TEXT.__const` | `0x9254` | `0x924c` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1be4` | `0x1bec` | **`+0x8`** |

### Other Changes

```diff

-134.0.15.0.0
+134.0.18.0.0

-  Functions: 3384
-  Symbols:   1327
-  CStrings:  539
+  Functions: 3400
+  Symbols:   1353
+  CStrings:  543
Symbols:
+ -[SwiftCRLiteClient findValidInfoForCertificate:issuer:]
+ -[SwiftValidInfo .cxx_destruct]
+ -[SwiftValidInfo flags]
+ -[SwiftValidInfo format]
+ -[SwiftValidInfo initWithFormat:flags:matched:notBeforeDate:notAfterDate:policyConstraints:]
+ -[SwiftValidInfo matched]
+ -[SwiftValidInfo notAfterDate]
+ -[SwiftValidInfo notBeforeDate]
+ -[SwiftValidInfo policyConstraints]
+ _CFBooleanGetTypeID
+ _CFGetTypeID
+ _OBJC_CLASS_$_SwiftValidInfo
+ _OBJC_IVAR_$_SwiftValidInfo._flags
+ _OBJC_IVAR_$_SwiftValidInfo._format
+ _OBJC_IVAR_$_SwiftValidInfo._matched
+ _OBJC_IVAR_$_SwiftValidInfo._notAfterDate
+ _OBJC_IVAR_$_SwiftValidInfo._notBeforeDate
+ _OBJC_IVAR_$_SwiftValidInfo._policyConstraints
+ _OBJC_METACLASS_$_SwiftValidInfo
+ __OBJC_$_INSTANCE_METHODS_SwiftValidInfo
+ __OBJC_$_INSTANCE_VARIABLES_SwiftValidInfo
+ __OBJC_$_PROP_LIST_SwiftValidInfo
+ __OBJC_CLASS_RO_$_SwiftValidInfo
+ __OBJC_METACLASS_RO_$_SwiftValidInfo
+ _kCFPreferencesCurrentHost
+ _swift_unknownObjectRelease_n
CStrings:
+ "3"
+ "ValidUpdateBackground"
+ "chmod 0o644 %s failed: %s"
+ "com.apple.security"
```
