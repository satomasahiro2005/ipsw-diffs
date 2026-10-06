## AskToDaemon

> `/System/Library/PrivateFrameworks/AskToDaemon.framework/AskToDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92b38` | `0x95828` | **`+0x2cf0`** |
| `__AUTH_CONST.__const` | `0x2960` | `0x2bc8` | **`+0x268`** |
| `__TEXT.__oslogstring` | `0x549e` | `0x56de` | **`+0x240`** |
| `__TEXT.__const` | `0x3318` | `0x34d8` | **`+0x1c0`** |
| `__DATA.__bss` | `0x2700` | `0x2880` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x4910` | `0x4a7c` | **`+0x16c`** |
| `__TEXT.__swift5_capture` | `0x6f0` | `0x798` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x17f0` | `0x1878` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x1a66` | `0x1ad8` | **`+0x72`** |
| `__TEXT.__cstring` | `0x2307` | `0x2367` | **`+0x60`** |
| `__DATA.__common` | `0x230` | `0x280` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0xee4` | `0xf34` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x10c4` | `0x1114` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1278` | `0x12bc` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x740` | `0x710` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1768` | `0x1790` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1338` | `0x1318` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x464` | `0x480` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x208` | `0x21c` | **`+0x14`** |
| `__DATA.__data` | `0x1000` | `0x1010` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x608` | `0x618` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1c4` | `0x1d4` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x194` | `0x1a4` | **`+0x10`** |
| `__AUTH.__data` | `0xf50` | `0xf58` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x120` | `0x128` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x88` | `0x8c` | **`+0x4`** |

### Other Changes

```diff

-90.1.0.0.0
+92.0.0.0.0

-  Functions: 1609
-  Symbols:   955
-  CStrings:  551
+  Functions: 1653
+  Symbols:   968
+  CStrings:  560
Symbols:
+ ___swift_closure_destructor.11Tm
+ ___swift_closure_destructor.16Tm
+ ___swift_closure_destructor.17Tm
+ ___swift_closure_destructor.27Tm
+ ___swift_closure_destructor.33Tm
+ ___swift_closure_destructor.51Tm
+ _associated conformance 11AskToDaemon29MessagesPayloadProvidingErrorOSHAASQ
+ _get_enum_tag_for_layout_string 11AskToDaemon24MessagesPayloadProviding_pSg
+ _swift_release_x9
+ _symbolic $s11AskToDaemon22MessagesBubbleUpdatingP
+ _symbolic ScCy_____Sg_____G 9AskToCore9ATPayloadC s5NeverO
+ _symbolic So8NSNumberCSg
+ _symbolic _____ 11AskToDaemon29MessagesPayloadProvidingErrorO
+ _symbolic _____ 9AskToCore25AcknowledgmentAlertActionO
+ _symbolic _____Sg 9AskToCore9ATPayloadC
+ _symbolic ______p 11AskToDaemon22MessagesBubbleUpdatingP
+ _symbolic ______pSg 11AskToDaemon24MessagesPayloadProvidingP
+ _type_layout_string 11AskToDaemon21MessagesBubbleUpdaterV
- ___swift_closure_destructor.25Tm
- ___swift_closure_destructor.31Tm
- ___swift_closure_destructor.34Tm
- ___swift_closure_destructor.7Tm
- _symbolic _____Sg 10Foundation20PersonNameComponentsV
CStrings:
+ "%s has no active IDS endpoints and will not be considered iMessage-capable."
+ "ATURL.create returned nil for payload %s; cannot forward URL to AskToExtension"
+ "Client has no response tasks"
+ "Could not parse ATPayload for message GUID %s: %@"
+ "Error calling acknowledgmentAlertButtonTapped on client with id %s: %@"
+ "No IMSPIMessage or extensionPayloadURL for GUID %s; stashedIcon recovery skipped"
+ "Resolved %ld iMessage-capable send destination(s) from %ld parent(s)/guardian(s)."
+ "Successfully called acknowledgmentAlertButtonTapped on client with id %s"
+ "The following family members have no iMessage-capable handles and will be dropped from the recipient group: %s"
+ "_acknowledgmentAlertButtonTapped(question:action:)"
+ "storedPayload(forMessageGUID:)"
- "Client is an AskTo-owned process. Returning no response tasks."
- "Failed to get the new Messages payload from the extension. error: %@"
```
