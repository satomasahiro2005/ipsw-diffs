## RCS

> `/System/Library/Messages/PlugIns/RCS.imservice/RCS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x110908` | `0x111938` | **`+0x1030`** |
| `__TEXT.__oslogstring` | `0x69f8` | `0x6a98` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x28a3` | `0x2913` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0xa978` | `0xa9d8` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x5920` | `0x5980` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x21e7` | `0x2243` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x5090` | `0x50e0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x6123` | `0x6163` | **`+0x40`** |
| `__DATA.__objc_const` | `0x2398` | `0x23b8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x16a4` | `0x16c4` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xcac` | `0xcc8` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x1940` | `0x1958` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3c10` | `0x3c28` | **`+0x18`** |
| `__DATA.__data` | `0x3cc8` | `0x3cd8` | **`+0x10`** |
| `__TEXT.__const` | `0x6438` | `0x6448` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1a44` | `0x1a50` | **`+0xc`** |
| `__DATA.__objc_data` | `0x6a0` | `0x6a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x9c8` | `0x9d0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x9a8` | `0x9b0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x33c` | `0x340` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-1487.100.6.2.2
+1491.100.1.2.11

-  Functions: 3888
-  Symbols:   492
-  CStrings:  1686
+  Functions: 3898
+  Symbols:   493
+  CStrings:  1693
Symbols:
+ _OBJC_CLASS_$_CTLazuliOperationError
CStrings:
+ "Clearing stale send error %u on successfully sent message %s"
+ "Not doing reachability request for %s for a Google RBM chatbot the user has not messaged (isForPendingConversation: %{bool}d, hasNotRepliedToChat: %{bool}d), assume it's reachable"
+ "cachedCapabilitiesQueue"
+ "com.apple.Messages.RCSCachedCapabilitiesQueue"
+ "discoverCapabilities(for:cached:context:operationID:)"
+ "errorCode"
+ "hasNotRepliedToChat"
+ "setErrorCode:"
- "Not doing reachability request for %s for a new compose to a Google RBM, assume it's reachable"
```
