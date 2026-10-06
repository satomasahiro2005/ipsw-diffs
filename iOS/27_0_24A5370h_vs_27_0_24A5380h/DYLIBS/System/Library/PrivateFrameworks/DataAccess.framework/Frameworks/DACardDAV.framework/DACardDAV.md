## DACardDAV

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACardDAV.framework/DACardDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3c8` | `0xa9fc` | **`+0x634`** |
| `__AUTH_CONST.__objc_const` | `0x3130` | `0x31c0` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x520` | `0x5a0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0xee8` | `0xf50` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x230` | `0x280` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x6e8` | `0x72d` | **`+0x45`** |
| `__TEXT.__objc_methlist` | `0x143c` | `0x145c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x3d0` | `0x3e8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x320` | `0x330` | **`+0x10`** |
| `__TEXT.__cstring` | `0x62b` | `0x637` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-2704.0.0.0.0
+2706.0.0.0.0

+  - /System/Library/Frameworks/CFNetwork.framework/CFNetwork

-  Functions: 317
-  Symbols:   761
-  CStrings:  87
+  Functions: 322
+  Symbols:   776
+  CStrings:  92
Symbols:
+ +[DAURLSecurity hostSharesRegistrableDomain:with:]
+ +[DAURLSecurity photoURL:isAllowedForServerHost:]
+ _DAURLSecurityIsIPLiteral
+ _DAURLSecurityNormalize
+ _DAURLSecurityRegistrableDomain
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_DAURLSecurity
+ _OBJC_CLASS_$_NSURLComponents
+ _OBJC_METACLASS_$_DAURLSecurity
+ __CFHostGetTopLevelDomain
+ __OBJC_$_CLASS_METHODS_DAURLSecurity
+ __OBJC_CLASS_RO_$_DAURLSecurity
+ __OBJC_METACLASS_RO_$_DAURLSecurity
+ _inet_pton
+ _strlen
CStrings:
+ "%@.%@"
+ "."
+ "Refusing to fetch photo from %@; host does not match server host %@."
+ "["
+ "]"
```
