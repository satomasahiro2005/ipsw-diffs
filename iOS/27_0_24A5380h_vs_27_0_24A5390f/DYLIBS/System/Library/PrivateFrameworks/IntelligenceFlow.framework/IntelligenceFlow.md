## IntelligenceFlow

> `/System/Library/PrivateFrameworks/IntelligenceFlow.framework/IntelligenceFlow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a5854` | `0x3ac8ac` | **`+0x7058`** |
| `__TEXT.__const` | `0x9bd5c` | `0x9de5c` | **`+0x2100`** |
| `__DATA.__bss` | `0xce6a0` | `0xcf7a0` | **`+0x1100`** |
| `__AUTH_CONST.__const` | `0x41418` | `0x41918` | **`+0x500`** |
| `__TEXT.__unwind_info` | `0x190c8` | `0x194c8` | **`+0x400`** |
| `__TEXT.__swift5_reflstr` | `0xc79b` | `0xcb6b` | **`+0x3d0`** |
| `__TEXT.__cstring` | `0xbcf6` | `0xc046` | **`+0x350`** |
| `__TEXT.__swift5_fieldmd` | `0x196cc` | `0x19a10` | **`+0x344`** |
| `__DATA_DIRTY.__common` | `0x2cd8` | `0x2fa0` | **`+0x2c8`** |
| `__TEXT.__swift5_typeref` | `0x19901` | `0x19b2d` | **`+0x22c`** |
| `__TEXT.__constg_swiftt` | `0x147c8` | `0x149e8` | **`+0x220`** |
| `__DATA.__data` | `0xea50` | `0xec50` | **`+0x200`** |
| `__TEXT.__eh_frame` | `0x1db88` | `0x1dd60` | **`+0x1d8`** |
| `__AUTH_CONST.__auth_got` | `0x1890` | `0x1950` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0xfe8` | `0x10a8` | **`+0xc0`** |
| `__DATA_DIRTY.__data` | `0x11ed8` | `0x11f98` | **`+0xc0`** |
| `__TEXT.__swift5_proto` | `0x9058` | `0x90e4` | **`+0x8c`** |
| `__AUTH_CONST.__objc_const` | `0x2f88` | `0x3008` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x860` | `0x8b8` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x154f` | `0x158f` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x2320` | `0x2348` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x7ec` | `0x7d4` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0xf10` | `0xf28` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x704` | `0x710` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x608` | `0x610` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x88` | `0x8c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x510` | `0x514` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x558` | `0x55c` | **`+0x4`** |

### Other Changes

```diff

-3600.147.12.501.3
+3600.151.4.501.6

+  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 42519
-  Symbols:   277
-  CStrings:  1454
+  Functions: 42838
+  Symbols:   282
+  CStrings:  1475
Symbols:
+ _OBJC_CLASS_$_AFConnection
+ _OBJC_CLASS_$_OS_dispatch_queue_serial
+ _swift_getFunctionTypeMetadata1
+ _swift_release_n
+ _swift_retain_n
CStrings:
+ "#IFToolbox: Database readiness unchanged (%s) after check from %s"
+ "#IFToolbox: Failed to check readiness via XPC: %s code: %ld"
+ "#IFToolbox: Toolbox status changed to %s for locale: %s, triggered by: %s"
+ "ContextMenuScrapeDelayMs"
+ "ContextRetrievalElementHierarchyDebugLog"
+ "DefaultMultiAgentConfiguration - Primary=Skimmer, all other agents are guests (Remote, Network: %s)"
+ "PlatformInstructionCarPlayUltraForceOverride"
+ "PlatformInstructionChineseLanguageGamesForceOverride"
+ "PlatformInstructionChineseMainlandLanguageGamesForceOverride"
+ "PlatformInstructionJapaneseLanguageGamesForceOverride"
+ "PlatformInstructionKoreanLanguageGamesForceOverride"
+ "PlatformInstructionMitigationForceOverride"
+ "PlatformInstructionWritingToolForceOverride"
+ "SearchForMessages#NoResultsResponse"
+ "com.apple.intelligenceflow.toolbox.readiness"
+ "companionIDSIdentifier"
+ "companionSharedUserId"
+ "isVisualIntelligenceEnabled"
+ "noResultsResponse"
+ "notReady"
+ "onDeviceRoutingPluginEnabled"
+ "on_with_fallback"
+ "personalRequestHandled"
+ "ready"
+ "simulateUnlockedDevice"
- "#IFToolbox: All databases are ready for locale: %s"
- "#IFToolbox: Failed to check readiness via XPC: %s"
- "#IFToolbox: Not all databases are ready for locale: %s"
- "#IFToolbox: Status change notification received, source: %s, name: %s"
```
