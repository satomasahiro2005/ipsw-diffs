## MFAANetwork

> `/System/Library/PrivateFrameworks/MFAAuthentication.framework/XPCServices/MFAANetwork.xpc/MFAANetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b43f0` | `0x1b44c4` | **`+0xd4`** |
| `__TEXT.__oslogstring` | `0x19f8` | `0x1a32` | **`+0x3a`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 622
+  Functions: 623

-  CStrings:  645
+  CStrings:  646
Functions:
~ -[MFAANetwork _verifyFairPlaySignatureSync:forData:timedOut:error:] : 604 -> 720
~ -[FairPlaySAPSession initWithDelegate:] : 496 -> 492
~ _systemInfo_copyProductType : 72 -> 96
~ _systemInfo_copyProductVersion : 72 -> 96
+ -[MFAANetwork _requestMetadataForToken:withUUID:requestedLocale:requestInfo:withReply:].cold.15
CStrings:
+ "Cannot verify FairPlay SAP signature with nil parameters!"
```
