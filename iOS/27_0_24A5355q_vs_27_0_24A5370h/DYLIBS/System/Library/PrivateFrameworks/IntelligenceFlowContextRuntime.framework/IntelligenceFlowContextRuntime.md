## IntelligenceFlowContextRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/IntelligenceFlowContextRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfc3f4` | `0x1022e0` | **`+0x5eec`** |
| `__TEXT.__eh_frame` | `0x7f78` | `0x8270` | **`+0x2f8`** |
| `__TEXT.__const` | `0x4830` | `0x4a90` | **`+0x260`** |
| `__AUTH_CONST.__objc_const` | `0x1b90` | `0x1d80` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0x32c2` | `0x3457` | **`+0x195`** |
| `__DATA.__bss` | `0x14e0` | `0x1670` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0x29b0` | `0x2b2c` | **`+0x17c`** |
| `__AUTH_CONST.__const` | `0x4f50` | `0x50a0` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x58c` | `0x6cc` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x2db8` | `0x2ef0` | **`+0x138`** |
| `__DATA.__data` | `0xd40` | `0xe70` | **`+0x130`** |
| `__DATA_CONST.__objc_selrefs` | `0x9a8` | `0xab8` | **`+0x110`** |
| `__TEXT.__cstring` | `0x1bbc` | `0x1ccc` | **`+0x110`** |
| `__AUTH.__data` | `0x578` | `0x640` | **`+0xc8`** |
| `__AUTH.__objc_data` | `0x2d8` | `0x398` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x24f0` | `0x25b0` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x19e8` | `0x1a9c` | **`+0xb4`** |
| `__TEXT.__swift5_fieldmd` | `0x11a0` | `0x124c` | **`+0xac`** |
| `__TEXT.__swift5_reflstr` | `0xcfa` | `0xd8a` | **`+0x90`** |
| `__DATA_CONST.__got` | `0xf80` | `0xfd0` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x15e0` | `0x162c` | **`+0x4c`** |
| `__DATA_CONST.__objc_classlist` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0x98` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x3a4` | `0x3b4` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1dc` | `0x1e8` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x640` | `0x64c` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1fc` | `0x204` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x384` | `0x38c` | **`+0x8`** |

### Other Changes

```diff

-3600.138.6.501.17
+3600.144.5.501.3

-  Functions: 4682
-  Symbols:   322
-  CStrings:  360
+  Functions: 4780
+  Symbols:   327
+  CStrings:  369
Symbols:
+ _OBJC_CLASS_$_LNActionExecutorOptions
+ _OBJC_CLASS_$_LNActionOutput
+ _OBJC_CLASS_$_LNConnectionPolicySignals
+ _OBJC_CLASS_$_LNIntentsValueType
+ _OBJC_CLASS_$_LNProperty
CStrings:
+ "EditingContextFetcher.getResult"
+ "RequestEditingContext"
+ "WritingToolsCanPerformIntent"
+ "[EditingContextFetcher] cursor=%{public}ld preservedRanges=%{public}ld hasMarkdown=%{bool,public}d"
+ "[EditingContextFetcher] unexpected result type: %{public}s"
+ "[UserContextFetcher] Editing context fetched for %{sensitive}s but no matching focused OnScreenText entity found to stitch into — editing context discarded"
+ "[UserContextFetcher] Filtered 3P transient entity from %s"
+ "[UserContextFetcher] Filtered non-schematized 3P entity: %s from %s"
+ "[UserContextFetcher] Filtered non-schematized 3P foreign entity: %s from %s"
+ "[UserContextFetcher] Stitched editing context (cursor=%{public}ld, preservedCount=%{public}ld, hasMarkdown=%{bool,public}d) into focused entity in %{sensitive}s"
+ "[UserContextFetcher] ToolDatabase unavailable — blocking 3P entity %s from %s"
+ "[UserContextFetcher] snapshotImage nil for %s"
+ "[UserContextFetcher] snapshotImage present for %s, extracted %ld bytes"
+ "[fetchLocalLiveEntities] Failed to resolve LNEntity for bundle %s: %@ — falling back to entityIdentifier"
+ "[fetchLocalLiveEntities] No container for bundle: %s — falling back to entityIdentifier"
+ "com.apple.CameraOverlayAngel"
+ "com.apple.CampoRemoteService"
+ "com.apple.UIKitCore"
+ "execute(frameworkIdentifier:actionIdentifier:targetAppBundleIdentifier:parameters:timeout:)"
+ "preserved_ranges"
- "[fetchLocalLiveEntities] Failed to resolve LNEntity for bundle %s: %@"
- "[fetchLocalLiveEntities] No container for bundle: %s"
- "[liveCameraFeed] Camera.app foregrounded — building entity for %s"
- "[liveCameraFeed] Camera.app not foregrounded; skipping entity for %s"
- "[liveCameraFeed] Failed to create temporary IntelligenceFile: %s"
- "[liveCameraFeed] Failed to get snapshot image data: %s"
- "[liveCameraFeed] Snapshot file attached — yielding full entity for %s"
- "[liveCameraFeed] Snapshot file unavailable — yielding entity identifier for %s. VI requests will not have image data."
- "[liveCameraFeed] Unable to get UI hierarchy for %s. VI requests will not have image data."
- "com.apple.camera"
- "fetchPassthroughCameraEntities"
```
