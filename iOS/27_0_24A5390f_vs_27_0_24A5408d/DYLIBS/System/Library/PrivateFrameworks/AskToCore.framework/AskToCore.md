## AskToCore

> `/System/Library/PrivateFrameworks/AskToCore.framework/AskToCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x943c4` | `0x99558` | **`+0x5194`** |
| `__DATA.__bss` | `0xe390` | `0xe710` | **`+0x380`** |
| `__AUTH_CONST.__const` | `0x5778` | `0x5a40` | **`+0x2c8`** |
| `__TEXT.__const` | `0x86d8` | `0x8928` | **`+0x250`** |
| `__TEXT.__cstring` | `0x33f3` | `0x3503` | **`+0x110`** |
| `__TEXT.__swift5_fieldmd` | `0x2400` | `0x24d8` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0x1dfc` | `0x1ecc` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x50c` | `0x45c` | **`-0xb0`** |
| `__TEXT.__eh_frame` | `0x31a0` | `0x3100` | **`-0xa0`** |
| `__TEXT.__unwind_info` | `0x2700` | `0x27a0` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x1ea4` | `0x1f3c` | **`+0x98`** |
| `__TEXT.__swift5_typeref` | `0x1ec0` | `0x1f44` | **`+0x84`** |
| `__DATA.__data` | `0x1d80` | `0x1e00` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0xdd8` | `0xe48` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x23da` | `0x243a` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x390` | `0x3d8` | **`+0x48`** |
| `__DATA.__common` | `0x168` | `0x1a8` | **`+0x40`** |
| `__AUTH.__data` | `0x288` | `0x2c0` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x2b60` | `0x2b88` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x760` | `0x780` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xc8` | **`-0x14`** |
| `__TEXT.__swift_as_cont` | `0x200` | `0x1ec` | **`-0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x758` | `0x768` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x11b0` | `0x11a0` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x264` | `0x274` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0xe20` | `0xe28` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xd8` | `0xd0` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0xd8` | `0xd0` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x54` | `0x58` | **`+0x4`** |

### Other Changes

```diff

-93.0.0.0.0
+96.0.0.0.0

-  Functions: 3535
-  Symbols:   1349
-  CStrings:  501
+  Functions: 3584
+  Symbols:   1361
+  CStrings:  514
Symbols:
+ _CGContextAddPath
+ _CGPathCreateWithContinuousRoundedRect
+ __OBJC_$_CLASS_METHODS__TtC9AskToCore9ATPayload(AskToCore|AskToCore1|AskToCore2|AskToCore3|AskToCore4|AskToCore5)
+ __OBJC_$_INSTANCE_METHODS__TtC9AskToCore9ATPayload(AskToCore|AskToCore1|AskToCore2|AskToCore3|AskToCore4|AskToCore5)
+ __OBJC_CLASS_PROTOCOLS_$__TtC9AskToCore9ATPayload(AskToCore|AskToCore1|AskToCore2|AskToCore3|AskToCore4|AskToCore5)
+ ___swift_closure_destructor.47Tm
+ _associated conformance 9AskToCore28iMessageAccountMismatchEventV5FieldOSHAASQ
+ _associated conformance 9AskToCore28iMessageAccountMismatchEventVAA07MetricsG0AA5FieldAaDP_SH
+ _associated conformance 9AskToCore28iMessageAccountMismatchEventVAA07MetricsG0AA5FieldAaDP_SY
+ _associated conformance 9AskToCore29iMessageAccountMismatchReasonOSHAASQ
+ _swift_retain_x28
+ _symbolic $s9AskToCore17AnalyticsReporterP
+ _symbolic SDy_____ypG 9AskToCore28iMessageAccountMismatchEventV5FieldO
+ _symbolic Say_____G 9AskToCore23ATCommunicationMetadataC13LenientAction33_018464744FB3D64D90F2041DA3514459LLV
+ _symbolic ShySSG
+ _symbolic _____ 9AskToCore23ATCommunicationMetadataC13LenientAction33_018464744FB3D64D90F2041DA3514459LLV
+ _symbolic _____ 9AskToCore28iMessageAccountMismatchEventV
+ _symbolic _____ 9AskToCore28iMessageAccountMismatchEventV5FieldO
+ _symbolic _____ 9AskToCore29iMessageAccountMismatchReasonO
+ _symbolic _____ 9AskToCore29iMessageAccountMismatchStatusO
+ _symbolic _____Sg 9AskToCore23ATCommunicationMetadataC6ActionO
+ _symbolic _____Sg s17CodingUserInfoKeyV
+ _symbolic ______p 9AskToCore16ContactResolvingP
+ _symbolic ______ypt 9AskToCore28iMessageAccountMismatchEventV5FieldO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 9AskToCore23ATCommunicationMetadataC6ActionO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 9AskToCore24ATRegistrationCapabilityO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 9AskToCore7ATColorV
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC 9AskToCore28iMessageAccountMismatchEventV5FieldO
+ _symbolic _____y_____ypG s18_DictionaryStorageC 9AskToCore28iMessageAccountMismatchEventV5FieldO
+ _symbolic _____y_____ypG s18_DictionaryStorageC s17CodingUserInfoKeyV
+ _type_layout_string 9AskToCore23ATCommunicationMetadataC13LenientAction33_018464744FB3D64D90F2041DA3514459LLV
+ _type_layout_string 9AskToCore28iMessageAccountMismatchEventV
- __OBJC_$_CLASS_METHODS__TtC9AskToCore9ATPayload(AskToCore|AskToCore1|AskToCore2|AskToCore3|AskToCore4)
- __OBJC_$_INSTANCE_METHODS__TtC9AskToCore9ATPayload(AskToCore|AskToCore1|AskToCore2|AskToCore3|AskToCore4)
- __OBJC_CLASS_PROTOCOLS_$__TtC9AskToCore9ATPayload(AskToCore|AskToCore1|AskToCore2|AskToCore3|AskToCore4)
- ___swift_closure_destructor.64Tm
- _associated conformance 9AskToCore25AcknowledgmentAlertActionOSHAASQ
- _get_enum_tag_for_layout_string 9AskToCore25AcknowledgmentAlertActionOIeghy_Sg
- _kCGImageMetadataShouldExcludeGPS
- _kCGImagePropertyDPIHeight
- _kCGImagePropertyDPIWidth
- _kCGImagePropertyPixelHeight
- _kCGImagePropertyPixelWidth
- _swift_retain_x26
- _symbolic ScCySaySSGSg______pG s5ErrorP
- _symbolic _____ 9AskToCore25AcknowledgmentAlertActionO
- _symbolic _____Ieghy_ 9AskToCore25AcknowledgmentAlertActionO
- _symbolic ______ypt So11CFStringRefa
- _symbolic _____y______yptG s23_ContiguousArrayStorageC So11CFStringRefa
- _symbolic _____y_____ypG s18_DictionaryStorageC So11CFStringRefa
- _symbolic _____ytIeghnr_ 9AskToCore25AcknowledgmentAlertActionO
- _symbolic y_____YbcSg 9AskToCore25AcknowledgmentAlertActionO
CStrings:
+ "\nclientIconData: "
+ "ATURL.create returned nil"
+ "Compressing the resized image failed: "
+ "Image compression failed. Error: %@"
+ "Invalid ATURL string"
+ "Logging iMessageAccountMismatchEvent metric (reason: %{public}s)"
+ "Resized and downsampled image data was nil"
+ "Resizing and downsampling the image produced no data"
+ "accountNotInFamily"
+ "actions"
+ "com.apple.AskPermission.AskToBuy"
+ "com.apple.askto.ATPayload.encodingForStaging"
+ "com.apple.family.AskTo.iMessageAccountMismatch"
+ "exclamationmark.shield.fill"
+ "iMessageNotEnabled"
+ "reason"
+ "reportAccountMismatchIfNeeded()"
+ "requiredRegistrationCapabilitiesV2"
+ "stageQuestionInMessages(_:recipientGroup:)"
- "CGImageDestination could not be created for type "
- "Error notifying client of acknowledgment alert button tapped: %@"
- "Resulting encoded Data for type "
- "_acknowledgmentAlertButtonTapped(question:action:)"
- "acknowledgmentAlertButtonTapped(question:action:)"
- "send(question:to:)"
```
