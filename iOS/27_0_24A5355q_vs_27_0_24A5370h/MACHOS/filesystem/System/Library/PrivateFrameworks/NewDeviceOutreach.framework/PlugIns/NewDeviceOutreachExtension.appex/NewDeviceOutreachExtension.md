## NewDeviceOutreachExtension

> `/System/Library/PrivateFrameworks/NewDeviceOutreach.framework/PlugIns/NewDeviceOutreachExtension.appex/NewDeviceOutreachExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fa4` | `0x1d90` | **`-0x214`** |
| `__DATA.__data` | `0x120` | `0x1b8` | **`+0x98`** |
| `__DATA.__objc_const` | `0x2b0` | `0x340` | **`+0x90`** |
| `__TEXT.__objc_classname` | `0x6b` | `0xca` | **`+0x5f`** |
| `__TEXT.__cstring` | `0x48c` | `0x463` | **`-0x29`** |
| `__TEXT.__constg_swiftt` | `0x28` | `0x50` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x2e0` | `0x2c0` | **`-0x20`** |
| `__DATA.__common` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x108` | `0xf0` | **`-0x18`** |
| `__TEXT.__const` | `0x74` | `0x86` | **`+0x12`** |
| `__DATA_CONST.__auth_got` | `0x180` | `0x170` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x218` | `0x208` | **`-0x10`** |
| `__DATA.__bss` | `0x8` | `—` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-602.0.0.0.0
+616.0.0.0.0

+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib

+  - /usr/lib/swift/libswiftXPC.dylib

-  Functions: 49
-  Symbols:   74
+  Functions: 43
+  Symbols:   81
Symbols:
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftXPC
+ _objc_opt_self
+ _swift_deallocClassInstance
+ _swift_deletedMethodError
- _swift_once
- _swift_slowAlloc
CStrings:
+ "_TtC26NewDeviceOutreachExtensionP33_ABBBA6D02977386B13B5BBD4094E6D9D19ResourceBundleClass"
- "com.apple.NewDeviceOutreach"
```
