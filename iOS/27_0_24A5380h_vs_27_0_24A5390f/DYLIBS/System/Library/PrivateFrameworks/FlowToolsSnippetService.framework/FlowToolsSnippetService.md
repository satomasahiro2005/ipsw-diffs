## FlowToolsSnippetService

> `/System/Library/PrivateFrameworks/FlowToolsSnippetService.framework/FlowToolsSnippetService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf0b74` | `0xf82d0` | **`+0x775c`** |
| `__AUTH_CONST.__const` | `0x9e98` | `0xa830` | **`+0x998`** |
| `__DATA.__bss` | `0x10200` | `0x10780` | **`+0x580`** |
| `__TEXT.__const` | `0xd626` | `0xdb06` | **`+0x4e0`** |
| `__TEXT.__swift5_capture` | `0x16f8` | `0x1950` | **`+0x258`** |
| `__TEXT.__eh_frame` | `0x754c` | `0x7704` | **`+0x1b8`** |
| `__TEXT.__unwind_info` | `0x3d50` | `0x3ee0` | **`+0x190`** |
| `__TEXT.__swift5_fieldmd` | `0x2798` | `0x28b8` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x6056` | `0x6146` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x3429` | `0x3519` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x1436` | `0x1516` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x226c` | `0x2348` | **`+0xdc`** |
| `__DATA.__data` | `0xee8` | `0xf78` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x7c0` | `0x848` | **`+0x88`** |
| `__AUTH_CONST.__auth_got` | `0x1a78` | `0x1ad0` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x1620` | `0x1660` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x2248` | `0x2278` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1fbd` | `0x1fed` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x3b0` | `0x3e0` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0xb60` | `0xb8c` | **`+0x2c`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xb4` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x364` | `0x380` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x220` | `0x230` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x3e0` | `0x3ec` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x394` | `0x3a0` | **`+0xc`** |
| `__TEXT.__swift5_mpenum` | `0x2c` | `0x34` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x360` | `0x368` | **`+0x8`** |

### Other Changes

```diff

-3600.65.18.1.1
+3600.65.26.1.1

+  - /System/Library/Frameworks/Photos.framework/Photos

+  - /usr/lib/swift/libswiftGLKit.dylib

+  - /usr/lib/swift/libswiftSceneKit.dylib

-  Functions: 6795
-  Symbols:   334
-  CStrings:  488
+  Functions: 7036
+  Symbols:   343
+  CStrings:  493
Symbols:
+ _OBJC_CLASS_$_PHAsset
+ _OBJC_CLASS_$_PHCloudIdentifier
+ _OBJC_CLASS_$_PHPhotoLibrary
+ _OBJC_CLASS_$_PHPhotoLibraryIdentifier
+ _OBJC_CLASS_$_PHPhotoLibraryManager
+ _OBJC_CLASS_$_PHPhotoLibraryOpenOptions
+ __swift_FORCE_LOAD_$_swiftGLKit
+ __swift_FORCE_LOAD_$_swiftSceneKit
+ _memset
+ _swift_release_x9
- _OBJC_CLASS_$_SAUIAssistantNoticeView
CStrings:
+ "DefaultPhotosHandler: encoded syncable identifiers cloud=%ld syndication=%ld local=%ld"
+ "DismissToolSheetNotification"
+ "HandlerOutput: dropping content-empty result model so the dialog still prints responseId=%{sensitive}s"
+ "NoticeHandler: missing entitySnippetRenderer, returning EmptyOutput responseId=%{sensitive}s"
+ "NoticeHandler: rendering notice as inform responseId=%{sensitive}s"
+ "PhotoAssetUtils: Photos not authorized (auth=%ld); passing local ids through unchanged"
+ "PhotoAssetUtils: syncable encode incomplete resolved=%ld total=%ld systemAssets=%ld syndicationAssets=%ld"
+ "SnippetServicePhotosModel: cloud identifier not found in mappings"
+ "SnippetServicePhotosModel: failed to resolve cloud identifier domain=%s code=%ld"
+ "SnippetServicePhotosModel: resolved cloud identifiers resolved=%ld requested=%ld"
+ "SnippetServicePhotosModel: resolved syndication identifiers resolved=%ld requested=%ld"
+ "com.apple.siri.SearchAgent"
+ "identifierKinds"
- "#modes: NoticeHandler.handle makeUtteranceView responseMode=%s responseId=%{sensitive}s"
- "AssistantNoticeView"
- "NoticeHandler: no SAUIAddViews in AceOutput commands, returning empty view responseId=%{sensitive}s"
- "NoticeHandler: no dialog provided, returning EmptyOutput responseId=%{sensitive}s"
- "NoticeHandler: output not of expected AceOutput type, returning empty view actualType=%s responseId=%{sensitive}s"
- "NoticeHandler: unable to create notice utterance view, returning EmptyOutput responseId=%{sensitive}s"
- "SAUIAssistantUtteranceView: building notice view from utterance view bundleId=%s"
- "SAUIAssistantUtteranceView: unable to build notice view from utterance view"
```
