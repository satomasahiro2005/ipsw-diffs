## AlwaysOnExclavesDaemon

> `/System/Library/PrivateFrameworks/AlwaysOnExclavesDaemon.framework/AlwaysOnExclavesDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e54` | `0x97b4` | **`+0x960`** |
| `__DATA.__bss` | `0x480` | `0x700` | **`+0x280`** |
| `__TEXT.__const` | `0x5c0` | `0x7b0` | **`+0x1f0`** |
| `__TEXT.__swift5_typeref` | `0x13a` | `0x1c4` | **`+0x8a`** |
| `__AUTH_CONST.__const` | `0x380` | `0x400` | **`+0x80`** |
| `__TEXT.__cstring` | `0x707` | `0x767` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `—` | `0x60` | **`+0x60`** |
| `__DATA.__data` | `0x1f0` | `0x230` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x182` | `0x1c2` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x220` | `0x258` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x64f` | `0x67f` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x568` | `0x590` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x23c` | `0x264` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x5e0` | `0x600` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x388` | `0x3a4` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x28` | `0x3c` | **`+0x14`** |
| `__AUTH.__data` | `0x238` | `0x248` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x2c` | `0x30` | **`+0x4`** |

### Other Changes

```diff

-66.0.6.0.0
+66.40.14.0.0

+  - /usr/lib/swift/libswift_DarwinFoundation1.dylib

-  Functions: 160
-  Symbols:   224
-  CStrings:  75
+  Functions: 203
+  Symbols:   240
+  CStrings:  78
Symbols:
+ ___swift_memcpy8_8
+ _associated conformance 22AlwaysOnExclavesDaemon31CrossConclaveIpcReceiverOptionsVs10SetAlgebraAASQ
+ _associated conformance 22AlwaysOnExclavesDaemon31CrossConclaveIpcReceiverOptionsVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 22AlwaysOnExclavesDaemon31CrossConclaveIpcReceiverOptionsVs9OptionSetAASY
+ _associated conformance 22AlwaysOnExclavesDaemon31CrossConclaveIpcReceiverOptionsVs9OptionSetAAs0K7Algebra
+ _os_workgroup_attr_set_flags
+ _os_workgroup_create
+ _pthread_create_with_workgroup_np
+ _symbolic $sSY
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic So15OS_os_workgroupCSg
+ _symbolic Su
+ _symbolic _____ 22AlwaysOnExclavesDaemon31CrossConclaveIpcReceiverOptionsV
+ _type_layout_string 22AlwaysOnExclavesDaemon31CrossConclaveIpcReceiverOptionsV
CStrings:
+ "%s: created dedicated workgroup '%s_c2cc'"
+ "): failed to create workgroup for "
+ "): failed to set workgroup attributes for "
```
