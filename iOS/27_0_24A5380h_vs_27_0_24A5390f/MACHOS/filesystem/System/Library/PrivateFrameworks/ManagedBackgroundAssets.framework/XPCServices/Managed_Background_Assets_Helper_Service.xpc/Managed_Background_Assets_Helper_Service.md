## Managed Background Assets Helper Service

> `/System/Library/PrivateFrameworks/ManagedBackgroundAssets.framework/XPCServices/Managed Background Assets Helper Service.xpc/Managed Background Assets Helper Service`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7814` | `0x7994` | **`+0x180`** |
| `__DATA.__objc_const` | `0x2b0` | `0x368` | **`+0xb8`** |
| `__DATA.__data` | `0x4a0` | `0x548` | **`+0xa8`** |
| `__DATA.__bss` | `0x390` | `0x410` | **`+0x80`** |
| `__TEXT.__const` | `0x428` | `0x488` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x210` | `0x258` | **`+0x48`** |
| `__TEXT.__objc_classname` | `0x7d` | `0xc0` | **`+0x43`** |
| `__TEXT.__constg_swiftt` | `0x234` | `0x270` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x480` | `0x4a8` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x170` | `0x190` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xc20` | `0xc40` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x198` | `0x1b4` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x620` | `0x630` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x220` | `0x230` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x3fd` | `0x404` | **`+0x7`** |
| `__TEXT.__swift5_reflstr` | `0x176` | `0x17d` | **`+0x7`** |
| `__TEXT.__cstring` | `0x39c` | `0x397` | **`-0x5`** |
| `__TEXT.__swift5_proto` | `0x20` | `0x24` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x2fa` | `0x2f6` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2.0.30.0.0
+2.0.32.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 140
-  Symbols:   153
-  CStrings:  111
+  Functions: 144
+  Symbols:   154
+  CStrings:  113
Symbols:
+ _swift_deallocObject
+ _swift_retain_x19
- _swift_release_x9
CStrings:
+ "_TtC36ManagedBackgroundAssetsHelperService19ActorSystemDelegate"
+ "helper"
```
