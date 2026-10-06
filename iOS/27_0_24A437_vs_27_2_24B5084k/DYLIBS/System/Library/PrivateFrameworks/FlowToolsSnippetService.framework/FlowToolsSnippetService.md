## FlowToolsSnippetService

> `/System/Library/PrivateFrameworks/FlowToolsSnippetService.framework/FlowToolsSnippetService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x107958` | `0x11aa8c` | **`+0x13134`** |
| `__AUTH_CONST.__const` | `0xafd8` | `0xb778` | **`+0x7a0`** |
| `__TEXT.__oslogstring` | `0x6bb6` | `0x72e6` | **`+0x730`** |
| `__TEXT.__eh_frame` | `0x7960` | `0x8058` | **`+0x6f8`** |
| `__TEXT.__const` | `0xde96` | `0xe4e6` | **`+0x650`** |
| `__AUTH.__data` | `0x4d0` | `0x8b8` | **`+0x3e8`** |
| `__DATA.__bss` | `0x109e0` | `0x10d90` | **`+0x3b0`** |
| `__TEXT.__cstring` | `0x202d` | `0x23dd` | **`+0x3b0`** |
| `__TEXT.__unwind_info` | `0x4348` | `0x4618` | **`+0x2d0`** |
| `__AUTH_CONST.__objc_const` | `0x1718` | `0x19b8` | **`+0x2a0`** |
| `__TEXT.__swift5_fieldmd` | `0x2a40` | `0x2ca8` | **`+0x268`** |
| `__TEXT.__swift5_typeref` | `0x3613` | `0x3852` | **`+0x23f`** |
| `__TEXT.__constg_swiftt` | `0x24fc` | `0x271c` | **`+0x220`** |
| `__TEXT.__swift5_capture` | `0x1a7c` | `0x1c6c` | **`+0x1f0`** |
| `__TEXT.__swift5_reflstr` | `0x15d6` | `0x17b6` | **`+0x1e0`** |
| `__AUTH_CONST.__auth_got` | `0x1bb8` | `0x1d30` | **`+0x178`** |
| `__DATA.__data` | `0x1030` | `0x1150` | **`+0x120`** |
| `__DATA_DIRTY.__bss` | `0x70f0` | `0x7170` | **`+0x80`** |
| `__DATA_DIRTY.__data` | `0x2290` | `0x2238` | **`-0x58`** |
| `__AUTH.__objc_data` | `0xd8` | `0x128` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x408` | `0x454` | **`+0x4c`** |
| `__TEXT.__swift_as_entry` | `0x374` | `0x3c0` | **`+0x4c`** |
| `__TEXT.__swift_as_ret` | `0x3ac` | `0x3f4` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0xba0` | `0xbdc` | **`+0x3c`** |
| `__TEXT.__swift5_assocty` | `0x3e0` | `0x410` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x3a8` | `0x3c8` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xb0` | `0xc8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x890` | `0x8a8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x240` | `0x230` | **`-0x10`** |
| `__TEXT.__swift5_protos` | `0x48` | `0x54` | **`+0xc`** |

### Other Changes

```diff

-3600.65.34.0.0
+3605.23.1.1.1

+  - /System/Library/Frameworks/Network.framework/Network

+  - /System/Library/PrivateFrameworks/LinkServices.framework/LinkServices

-  - /usr/lib/swift/libswiftGLKit.dylib

-  - /usr/lib/swift/libswiftSceneKit.dylib

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 7320
-  Symbols:   358
-  CStrings:  528
+  Functions: 7650
+  Symbols:   356
+  CStrings:  562
Symbols:
+ _OBJC_CLASS_$_LNEnvironment
- _OBJC_CLASS_$_NSCache
- __swift_FORCE_LOAD_$_swiftGLKit
- __swift_FORCE_LOAD_$_swiftSceneKit
CStrings:
+ "#EntityOpener: executed tool=%s identifierKind=%s preferredStable=%{bool}d didRunOpensIntent=%{bool}d"
+ "#EntityOpener: execution cancelled tool=%s identifierKind=%s preferredStable=%{bool}d"
+ "#EntityOpener: execution failed tool=%s identifierKind=%s preferredStable=%{bool}d domain=%s code=%ld"
+ "#EntityOpener: open tool execution cancelled; noOp"
+ "#EntityOpener: open tool failed to execute and no launchable bundle; noOp"
+ "#EntityOpener: open tool failed to execute; falling back to launch bundleId=%s"
+ "#SnippetService InAppResponseUtilities: No entities found in displayItem type"
+ "%s Display items: %s"
+ "CompanionRegistryCache: Could not set up remote dispatcher errorDomain=%s errorCode=%ld"
+ "CompanionRegistryCache: companion discovery exceeded its deadline, continuing without a companion registry"
+ "DefaultMessagesHandler: handle missing draft body responseId=%{sensitive}s"
+ "DefaultMessagesHandler: rendering Apple TV draft confirmation body as plaintext responseId=%{sensitive}s"
+ "Displayed as the value of a boolean result field that is off / unset / no."
+ "Displayed as the value of a boolean result field that is on / set / yes."
+ "DraftMessageEntity"
+ "ExcludedAppsAttributionViewProviding: rejected isAppExclusionReminderNeeded=%{bool}d responseContextIsNil=%{bool}d deviceIdiom=%s responseId=%{sensitive}s"
+ "ExcludedAppsAttributionViewProviding: rejected within turnDebounceInterval elapsed=%f responseId=%{sensitive}s"
+ "ExcludedAppsAttributionViewProviding: skipped for inline-entity rendering responseId=%{sensitive}s"
+ "PluginHandler.awaitPluginPreload"
+ "PluginHandler.invokeHandler"
+ "PluginHandler.probeHandlers"
+ "SnippetService: airplane mode is on but a network path is satisfied — using the network error dialog rather than the airplane mode dialog"
+ "SnippetService: substituting valid-but-empty inline-entity snippet for hidden resultModel bundle=%{public}s responseId=%{sensitive}s"
+ "SnippetServiceNetworkReachabilityQueue"
+ "StreamingHandler: Found visual update for for entity tag=%{sensitive}s responseId=%{sensitive}s"
+ "StreamingHandler: enrichUpdate encoded TypedValue metadata sidecar for entity tag=%{sensitive}s responseId=%{sensitive}s"
+ "StreamingHandler: enrichUpdateWithArtifactFileTags rewrote <key_entity> as <file> tag for entity tag=%{sensitive}s responseId=%{sensitive}s"
+ "This does not include results from apps you’ve locked or excluded. You can manage excluded apps in Siri Settings."
+ "[ShowMoreTruncated] group exceeds preview limit with no Show More affordance: idiom=%s count=%ld limit=%ld dropped=%ld"
+ "com.apple.siri.messages.SiriMessagesAppIntentsExtension"
+ "context(inlineEntityRendering:totalItemCount:)"
+ "createItem(_:bundleIdentifier:entityIdentifier:entityType:openAction:entityURL:entityInstanceIdentifier:)"
+ "createItem(_:identifier:type:bundleIdentifierOverride:openAction:entityURL:instanceIdentifier:)"
+ "enrichUpdateWithInlineEntitySnippets(_:entities:systemResponse:)"
+ "entityInstanceIdentifier"
+ "excludedAppsDisclaimerLastResponseId"
+ "excludedAppsDisclaimerLastShownDate"
+ "firstToLand(deadline:resolver:)"
+ "personaInfo"
+ "settings-navigation://com.apple.Settings.Siri/RESTRICT_ACCESS_ID"
+ "tapURL"
+ "titleLineLimit"
- "#EntityOpener: executed tool=%s"
- "#EntityOpener: execution failed tool=%s domain=%s code=%ld"
- "SiriCompanion"
- "StreamingHandler: enrichUpdate encoded TypedValue metadata sidecar for entity tag=%{sensitive}s entryCount=%ld responseId=%{sensitive}s"
- "StreamingHandler: enrichUpdate skipping sentinel for entity tag=%{sensitive}s — plugin declares snippetHidden responseId=%{sensitive}s"
- "context(totalItemCount:)"
- "createItem(_:bundleIdentifier:entityIdentifier:entityType:openAction:entityURL:)"
- "createItem(_:identifier:type:bundleIdentifierOverride:openAction:entityURL:)"
```
