## AskPermissionUI

> `/Applications/AskPermissionUI.app/AskPermissionUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe0e4` | `0xe65c` | **`+0x578`** |
| `__TEXT.__objc_stubs` | `0x2540` | `0x2640` | **`+0x100`** |
| `__DATA.__objc_const` | `0x2610` | `0x26f8` | **`+0xe8`** |
| `__TEXT.__objc_methname` | `0x4178` | `0x424f` | **`+0xd7`** |
| `__DATA_CONST.__cfstring` | `0x1500` | `0x1580` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x1424` | `0x1480` | **`+0x5c`** |
| `__DATA.__objc_selrefs` | `0xf18` | `0xf60` | **`+0x48`** |
| `__TEXT.__cstring` | `0xa96` | `0xad8` | **`+0x42`** |
| `__DATA_CONST.__const` | `0x3b8` | `0x3d8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x260` | `0x280` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2f0` | `0x308` | **`+0x18`** |
| `__DATA.__bss` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x16c` | `0x17c` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x18cf` | `0x18d2` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-130.1.4.0.0
+130.1.6.0.0

-  Functions: 267
-  Symbols:   170
-  CStrings:  1029
+  Functions: 276
+  Symbols:   173
+  CStrings:  1044
Symbols:
+ _AMSAccountMediaTypeAppStoreSandbox
+ _OBJC_CLASS_$_AMSProcessInfo
+ _OBJC_CLASS_$_NSISO8601DateFormatter
CStrings:
+ "@76@0:8@16@24@32B40@44@52@60q68"
+ "ISO8601DateFormatter"
+ "TB,R,N"
+ "TB,R,N,V_isSandbox"
+ "_isSandbox"
+ "bagForProfile:profileVersion:processInfo:"
+ "createdDateISO8601"
+ "currentProcess"
+ "dateFormatter"
+ "initWithDate:requestIdentifier:uniqueIdentifier:isSandbox:itemIdentifier:localizations:offerName:status:"
+ "isSandbox"
+ "isSandboxRequest"
+ "modifiedDateISO8601"
+ "sandboxBag"
+ "setAccountMediaType:"
+ "setFormatOptions:"
+ "stringFromDate:"
- "@72@0:8@16@24@32@40@48@56q64"
- "initWithDate:requestIdentifier:uniqueIdentifier:itemIdentifier:localizations:offerName:status:"
```
