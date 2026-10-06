## mapspushd

> `/System/Library/PrivateFrameworks/MapsSupport.framework/mapspushd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e9b4` | `0x1f144` | **`+0x790`** |
| `__DATA_CONST.__const` | `0x10c8` | `0x1228` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x6c17` | `0x6cfa` | **`+0xe3`** |
| `__TEXT.__objc_stubs` | `0x54a0` | `0x5580` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x2f88` | `0x3018` | **`+0x90`** |
| `__TEXT.__cstring` | `0x22f3` | `0x2372` | **`+0x7f`** |
| `__DATA.__objc_data` | `0x870` | `0x8c0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x418` | `0x458` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x19d7` | `0x1a11` | **`+0x3a`** |
| `__DATA.__objc_selrefs` | `0x1b50` | `0x1b88` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x1f74` | `0x1f9c` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x22a0` | `0x22c0` | **`+0x20`** |
| `__DATA_CONST.__objc_doubleobj` | `0x380` | `0x3a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x750` | `0x768` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x54b` | `0x560` | **`+0x15`** |
| `__DATA.__bss` | `0xd0` | `0xe0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x1cfd` | `0x1cf5` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2970.30.6.5.7
+2972.30.6.12.16

-  Functions: 627
-  Symbols:   288
-  CStrings:  1738
+  Functions: 638
+  Symbols:   291
+  CStrings:  1750
Symbols:
+ _OBJC_CLASS_$_MSPAuthFeedbackReportTicket
+ _OBJC_CLASS_$_MSPUnauthFeedbackReportTicket
+ ___NSArray0__struct
CStrings:
+ "@\"MSPBaseFeedbackReportTicket\""
+ "Failed to look up RAP records for report ids %@: %@"
+ "RAPCommunityIDLookup"
+ "Submitting query request"
+ "UGCShouldSendBAACertificatesForCommunityIDWriteRequests"
+ "_submitLogEventWithRequestParams:rapId:completion:"
+ "_submitTicket:completion:"
+ "communityIDForReportIds:completion:"
+ "initWithFeedbackRequestParameters:traits:userInfoType:"
+ "setAnonymousUserId:"
+ "setWillSubmitRequestBlock:"
+ "tdmUserInfo"
+ "v16@?0@\"GEORPFeedbackRequest\"8"
+ "v16@?0@\"NSString\"8"
- "@\"<GEOMapServiceFeedbackReportTicket>\""
- "Created request %@"
```
