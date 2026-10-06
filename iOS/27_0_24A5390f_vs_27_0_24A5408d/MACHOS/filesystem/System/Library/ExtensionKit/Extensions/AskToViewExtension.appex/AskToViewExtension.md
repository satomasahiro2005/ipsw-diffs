## AskToViewExtension

> `/System/Library/ExtensionKit/Extensions/AskToViewExtension.appex/AskToViewExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11b98` | `0x19ca0` | **`+0x8108`** |
| `__DATA_CONST.__const` | `0x538` | `0xc48` | **`+0x710`** |
| `__TEXT.__const` | `0x6c2` | `0xa58` | **`+0x396`** |
| `__TEXT.__swift5_capture` | `0x1e8` | `0x4f4` | **`+0x30c`** |
| `__DATA.__data` | `0x530` | `0x6f0` | **`+0x1c0`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x540` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0x864` | `0x9b4` | **`+0x150`** |
| `__TEXT.__swift5_reflstr` | `0x1df` | `0x32f` | **`+0x150`** |
| `__TEXT.__swift5_typeref` | `0x753` | `0x8a2` | **`+0x14f`** |
| `__DATA.__bss` | `0x3d0` | `0x4f0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x388` | `0x487` | **`+0xff`** |
| `__TEXT.__swift5_fieldmd` | `0x15c` | `0x258` | **`+0xfc`** |
| `__TEXT.__oslogstring` | `0x4af` | `0x58f` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x401` | `0x4a1` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x26c` | `0x2f0` | **`+0x84`** |
| `__TEXT.__auth_stubs` | `0x1060` | `0x10e0` | **`+0x80`** |
| `__TEXT.__objc_methtype` | `0x1a9` | `0x149` | **`-0x60`** |
| `__DATA_CONST.__got` | `0x298` | `0x2e8` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x838` | `0x878` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0x90` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x54` | `0x74` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1a0` | `0x184` | **`-0x1c`** |
| `__DATA.__objc_const` | `0x3a0` | `0x3b8` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x34` | `0x48` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x18` | `0x24` | **`+0xc`** |
| `__DATA.__objc_data` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x150` | `0x148` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x1c` | `0x24` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-93.0.0.0.0
+96.0.0.0.0

-  Functions: 245
-  Symbols:   170
-  CStrings:  130
+  Functions: 357
+  Symbols:   173
+  CStrings:  135
Symbols:
+ _objc_retain_x25
+ _objc_retain_x26
+ _objc_retain_x27
+ _swift_release_x27
+ _swift_retain_x19
+ _swift_retain_x22
+ _swift_retain_x25
+ _swift_retain_x26
- _objc_retain_x28
- _swift_cvw_allocateGenericValueMetadataWithLayoutString
- _swift_getExistentialTypeMetadata
- _swift_getGenericMetadata
- _swift_retain_x27
CStrings:
+ "%s Could not construct URL to launch Messages"
+ "%s didLaunchApp %{bool}d"
+ "Approve in person flow completed with answerChoice == %s. error: %s"
+ "AskToViewExtension/ApproveInPersonFlowView.swift"
+ "AskToViewExtension/AskFlowCoordinator.swift"
+ "AskToViewExtension/AskToApproveFlowView.swift"
+ "Attempting to open url to launch Messages %{private}s"
+ "Direct Approve in person flow completed with answerChoice == %s. error: %s"
+ "Error broadcasting messagesComposeDidFinish: %@"
+ "Error finishing AskToViewExtension with result: %@"
+ "Failed to launch Messages with error: %@"
+ "Presenting direct approve in person"
+ "Presenting direct ask to approve"
+ "View.task @ AskToViewExtension/ApproveInPersonFlowView.swift:"
+ "View.task @ AskToViewExtension/AskToApproveFlowView.swift:"
+ "launchMessagesAndStagePayload(result:)"
+ "messagesComposeDidFinish"
+ "presentMessageCompose(result:delegateBinding:withCurrentHostingController:)"
- "%s Error calling acknowledgmentAlertButtonTapped: %@"
- "%s Error calling messagesComposeDidFinish: %@"
- "Approve in person flow completed with success == %@. error: %@"
- "Attempting to open url to launch Messages %s"
- "Failed to launch Messages on macOS with error: %@"
- "_launchMessagesAndStagePayload(result:)"
- "_presentMessageCompose(result:)"
- "acknowledgmentAlertButtonTappedWithQuestion:action:reply:"
- "messageComposeViewController(_:didFinishWith:)"
- "notifyDaemonOfAlertAction(_:)"
- "presentMessageCompose didLaunchApp %{bool}d"
- "v40@0:8@\"_TtC5AskTo10ATQuestion\"16q24@?<v@?@\"NSError\">32"
- "v40@0:8@16q24@?32"
```
