## Announce

> `/System/Library/PrivateFrameworks/Announce.framework/Announce`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e0c8` | `0x403e4` | **`+0x231c`** |
| `__DATA.__bss` | `0x2630` | `0x2e30` | **`+0x800`** |
| `__TEXT.__const` | `0x1ce4` | `0x20a4` | **`+0x3c0`** |
| `__TEXT.__cstring` | `0x4075` | `0x4255` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0x14c0` | `0x1668` | **`+0x1a8`** |
| `__TEXT.__eh_frame` | `0x7e8` | `0x950` | **`+0x168`** |
| `__TEXT.__unwind_info` | `0x1338` | `0x1458` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x916` | `0x9da` | **`+0xc4`** |
| `__DATA.__data` | `0x1258` | `0x12f0` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x3080` | `0x3100` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x820` | `0x8a0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x3240` | `0x32a0` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x698` | `0x6f0` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x840` | `0x890` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c58` | `0x1ca0` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0x128` | `0x168` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x5628` | `0x5660` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x8f7` | `0x927` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x400` | `0x428` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x1d8` | `0x1f0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4e8` | `0x4fc` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x1010` | `0x1020` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x78` | `0x88` | **`+0x10`** |

### Other Changes

```diff

+  - /System/Library/Frameworks/ActivityKit.framework/ActivityKit

-  Functions: 1673
-  Symbols:   2441
-  CStrings:  708
+  Functions: 1757
+  Symbols:   2474
+  CStrings:  717
Symbols:
+ +[ANDevice isHomeAccessory]
+ -[ANAnnounce dismissLiveActivityForAnnouncementIdentifiers:]
+ -[ANAnnounce dismissLiveActivityForAnnouncementIdentifiers:completionHandler:]
+ GCC_except_table68
+ _ANDefaultDisableSiriKitIntentHandlersOnHomeAccessory
+ _ANDefaultUseAlternativeAudioSessionModeOnHomeAccessory
+ ___60-[ANAnnounce dismissLiveActivityForAnnouncementIdentifiers:]_block_invoke
+ ___78-[ANAnnounce dismissLiveActivityForAnnouncementIdentifiers:completionHandler:]_block_invoke
+ ___kCFBooleanTrue
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_memcpy8_8
+ ___swift_project_boxed_opaque_existential_1
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV0D3Kit0dE0AA12ContentStateAdEP_SE
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV0D3Kit0dE0AA12ContentStateAdEP_SH
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV0D3Kit0dE0AA12ContentStateAdEP_Se
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV0D3Kit0dE0AASE
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV0D3Kit0dE0AASe
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV12ContentStateV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLOSHAASQ
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV12ContentStateV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV12ContentStateV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 8Announce30IntercomLiveActivityAttributesV12ContentStateVSHAASQ
+ _symbolic $s11ActivityKit0A10AttributesP
+ _symbolic _____ 8Announce30IntercomLiveActivityAttributesV
+ _symbolic _____ 8Announce30IntercomLiveActivityAttributesV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLO
+ _symbolic _____ 8Announce30IntercomLiveActivityAttributesV12ContentStateV
+ _symbolic _____ 8Announce30IntercomLiveActivityAttributesV12ContentStateV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLO
+ _symbolic _____ySSG s11_SetStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 8Announce30IntercomLiveActivityAttributesV12ContentStateV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8Announce30IntercomLiveActivityAttributesV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 8Announce30IntercomLiveActivityAttributesV12ContentStateV10CodingKeys33_AB963DE31D8BD3201F542F0C8F6D726ELLO
+ _type_layout_string 8Announce30IntercomLiveActivityAttributesV12ContentStateV
CStrings:
+ "-[ANAnnounce dismissLiveActivityForAnnouncementIdentifiers:]_block_invoke"
+ "-[ANAnnounce dismissLiveActivityForAnnouncementIdentifiers:completionHandler:]_block_invoke"
+ "AnnouncementIdentifiers="
+ "[BOOL] Disable SiriKit Intent Handlers on HomeAccessory"
+ "[BOOL] Use Alternative Audio Session Mode on HomeAccessory"
+ "announcementIdentifiers"
+ "disable_sirikit_intent_handlers_on_homeaccessory"
+ "launchLiveActivity"
+ "use_alternative_audio_mode_on_homeaccessory"
```
