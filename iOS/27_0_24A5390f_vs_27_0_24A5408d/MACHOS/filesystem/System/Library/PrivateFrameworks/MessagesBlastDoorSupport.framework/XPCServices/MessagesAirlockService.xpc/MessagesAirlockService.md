## MessagesAirlockService

> `/System/Library/PrivateFrameworks/MessagesBlastDoorSupport.framework/XPCServices/MessagesAirlockService.xpc/MessagesAirlockService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xae1` | `0xa81` | **`-0x60`** |
| `__TEXT.__eh_frame` | `0xe48` | `0xe20` | **`-0x28`** |
| `__TEXT.__oslogstring` | `0x87e` | `0x85e` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x1bd0` | `0x1bc0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x7a8` | `0x798` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xdf0` | `0xde8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-327.100.2.0.0
+331.100.1.0.0

-  Functions: 618
+  Functions: 615

-  CStrings:  540
+  CStrings:  538
Symbols:
+ _swift_bridgeObjectRetain_n
- __swift_stdlib_strtod_clocale
CStrings:
+ "File transfer has no attachment info yet -- building non-final placeholder transfer."
- "File transfer attribute is missing attachment info (URL, etc) -- ignoring file transfer, but processing textual content."
- "MissingAttachment"
- "com.apple.BlastDoor.TextMessage.FileTransferAttribute.ImageInfo"
```
