## CoreODI

> `/System/Library/PrivateFrameworks/CoreODI.framework/CoreODI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53a9c` | `0x57248` | **`+0x37ac`** |
| `__TEXT.__eh_frame` | `0x4358` | `0x4820` | **`+0x4c8`** |
| `__AUTH_CONST.__const` | `0x2bd0` | `0x2dc8` | **`+0x1f8`** |
| `__TEXT.__const` | `0x7c42` | `0x7e02` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x1c34` | `0x1ae4` | **`-0x150`** |
| `__TEXT.__unwind_info` | `0x1b70` | `0x1cb0` | **`+0x140`** |
| `__DATA.__bss` | `0x9680` | `0x9780` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x1240` | `0x1320` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x138c` | `0x145c` | **`+0xd0`** |
| `__DATA.__data` | `0xc70` | `0xd10` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x1c5f` | `0x1cf5` | **`+0x96`** |
| `__TEXT.__swift5_capture` | `0x18c` | `0x220` | **`+0x94`** |
| `__TEXT.__swift5_fieldmd` | `0x1250` | `0x12dc` | **`+0x8c`** |
| `__AUTH_CONST.__objc_const` | `0xe68` | `0xef0` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0x971` | `0x9f1` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x756` | `0x796` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x5b8` | `0x5f0` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x2e8` | `0x320` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0xa48` | `0xa68` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x18c` | `0x1a0` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x278` | `0x288` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x13b8` | `0x13c0` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x520` | `0x528` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x5dc` | `0x5e4` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x19c` | `0x1a4` | **`+0x8`** |

### Other Changes

```diff

-27.0.52.0.0
+27.0.60.0.0

-  Functions: 2102
-  Symbols:   1068
-  CStrings:  256
+  Functions: 2168
+  Symbols:   1090
+  CStrings:  267
Symbols:
+ _ODIAttributeKeyDocumentCity
+ _ODIAttributeKeyDocumentCountryCode
+ _ODIAttributeKeyDocumentFirstName
+ _ODIAttributeKeyDocumentLastName
+ _ODIAttributeKeyDocumentPostalCode
+ _ODIAttributeKeyDocumentState
+ _ODIAttributeKeyDocumentStreet1
+ __IVARS__TtCC7CoreODI19ODIDaemonSPISessionP33_3B2C16813AE9E62F18A755D1B895387721ContinuationProcessor
+ ___swift_closure_destructor.76Tm
+ ___swift_memcpy25_8
+ ___swift_memcpy65_8
+ ___unnamed_25
+ _swift_release_x1
+ _swift_retain_x25
+ _swift_retain_x27
+ _symbolic SS______pIeghHrzo_ s5ErrorP
+ _symbolic Say_____GSSSgx______p_____Rz_____RzlIetMHgTgTgzo_ 7CoreODI13ConsentUpdateV s5ErrorP AA08OnDeviceC7ServiceP 11Distributed01_I9ActorStubP
+ _symbolic Say_____GSSSgx______p_____RzlIetWHgTgTgzo_ 7CoreODI13ConsentUpdateV s5ErrorP AA08OnDeviceC7ServiceP
+ _symbolic ScCySS______pGSg s5ErrorP
+ _symbolic ScCyx______pGSg s5ErrorP
+ _symbolic ScTyyt_____G s5NeverO
+ _symbolic ScTyyt______pG s5ErrorP
+ _symbolic _____ 7CoreODI19ODIDaemonSPISessionC18ODIMaxTimeoutError33_3B2C16813AE9E62F18A755D1B8953877LLV
+ _symbolic _____ 7CoreODI19ODIDaemonSPISessionC21ContinuationProcessor33_3B2C16813AE9E62F18A755D1B8953877LLC
+ _symbolic _____ s6UInt64V
+ _symbolic _____y_SSG 7CoreODI19ODIDaemonSPISessionC21ContinuationProcessor33_3B2C16813AE9E62F18A755D1B8953877LLC
+ _symbolic yyYbcSg
- ___swift_closure_destructor.75Tm
- _swift_initStackObject
- _swift_setDeallocating
- _symbolic Say_____Gx______p_____Rz_____RzlIetMHgTgzo_ 7CoreODI13ConsentUpdateV s5ErrorP AA08OnDeviceC7ServiceP 11Distributed01_I9ActorStubP
- _symbolic Say_____Gx______p_____RzlIetWHgTgzo_ 7CoreODI13ConsentUpdateV s5ErrorP AA08OnDeviceC7ServiceP
CStrings:
+ "Non-timeout error %@"
+ "Timeout error detected"
+ "document.city"
+ "document.countryCode"
+ "document.firstName"
+ "document.lastName"
+ "document.postalCode"
+ "document.state"
+ "document.street1"
+ "privacyTextVersion"
+ "timeoutTask(body:)"
+ "toggleUpdates(consentUpdates:privacyTextVersion:)"
+ "{\"sessionIdentifier\":\"-1\",\"assessment\":\""
+ "},\"additionalInfo\":{\"profileId\":\"UNKNOWN\",\"workflowId\":\""
- "\",\"idv_error\":-72780},\"additionalInfo\":{\"profileId\":\"UNKNOWN\",\"workflowId\":\""
- "toggleUpdates(consentUpdates:)"
- "{\"sessionIdentifier\":\"-1\",\"assessment\":\"eyJwcm9maWxlSWQiOiJVTktOT1dOIiwiYWRkaXRpb25hbEluZm8iOnsiaXNfZGV2aWNlX2xvY2tlZCI6dHJ1ZSwicGF5bG9hZF90ZW51cmUiOjAsInByb2ZpbGVfc2V0X29iamVjdF9pbmZvIjp7Im9yZGVyZWRQcm9maWxlQmFnSWQiOiJVTktOT1dOIiwiYXNzZXNzbWVudENvbmZpZ0lkIjoiVU5LTk9XTiIsInByb2ZpbGVTZXRPYmplY3RJZCI6IlVOS05PV04iLCJvcmRlcmVkUHJvZmlsZUJhZ05hbWUiOiJVTktOT1dOIiwicHJvZmlsZUJhZ1NldElkIjoiVU5LTk9XTiJ9LCJ3b3JrZmxvd19pZCI6ImNvbS5hcHBsZS5hbXAucGFpZEJ1eS5mdWxsLnZfMC4wLjEifSwiZXJyb3JJbmZvIjp7Imlkdl9lcnJvciI6LTcyNzgwLCJ3b3JrZmxvd19pZCI6ImNvbS5hcHBsZS5hbXAucGFpZEJ1eS5mdWxsLnZfMC4wLjEifX0=\"}"
```
