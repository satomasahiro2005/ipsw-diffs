## AskPermissionAskToResponseExtension

> `/System/Library/ExtensionKit/Extensions/AskPermissionAskToResponseExtension.appex/AskPermissionAskToResponseExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1540c` | `0x15808` | **`+0x3fc`** |
| `__TEXT.__objc_stubs` | `0x1e60` | `0x1f60` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x29a5` | `0x2a65` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0x1220` | `0x12a0` | **`+0x80`** |
| `__DATA.__objc_const` | `0x1438` | `0x1490` | **`+0x58`** |
| `__TEXT.__cstring` | `0x11dd` | `0x122d` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0xa80` | `0xac8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xb1c` | `0xb50` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x578` | `0x598` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2c8` | `0x2e0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4a8` | `0x4c0` | **`+0x18`** |
| `__DATA.__bss` | `0x3d8` | `0x3e8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xd4` | `0xd8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-130.1.4.0.0
+130.1.6.0.0

-  Functions: 360
-  Symbols:   245
-  CStrings:  778
+  Functions: 366
+  Symbols:   248
+  CStrings:  793
Symbols:
+ _AMSAccountMediaTypeAppStoreSandbox
+ _OBJC_CLASS_$_AMSProcessInfo
+ _OBJC_CLASS_$_NSISO8601DateFormatter
CStrings:
+ "ISO8601DateFormatter"
+ "TB,R,N"
+ "TB,R,N,V_isSandbox"
+ "_isSandbox"
+ "bagForProfile:profileVersion:processInfo:"
+ "createdDateISO8601"
+ "currentProcess"
+ "dateFormatter"
+ "isSandbox"
+ "isSandboxRequest"
+ "modifiedDateISO8601"
+ "sandboxBag"
+ "setAccountMediaType:"
+ "setFormatOptions:"
+ "stringFromDate:"
```
