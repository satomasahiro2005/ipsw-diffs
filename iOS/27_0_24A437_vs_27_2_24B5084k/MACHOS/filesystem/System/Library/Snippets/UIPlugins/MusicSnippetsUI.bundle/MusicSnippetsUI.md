## MusicSnippetsUI

> `/System/Library/Snippets/UIPlugins/MusicSnippetsUI.bundle/MusicSnippetsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3af6c` | `0x43dc4` | **`+0x8e58`** |
| `__TEXT.__swift5_typeref` | `0x6cd6` | `0x856a` | **`+0x1894`** |
| `__TEXT.__eh_frame` | `0x1a44` | `0x1fb4` | **`+0x570`** |
| `__TEXT.__auth_stubs` | `0x2110` | `0x23f0` | **`+0x2e0`** |
| `__TEXT.__oslogstring` | `0x938` | `0xb88` | **`+0x250`** |
| `__DATA.__data` | `0x2328` | `0x2548` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0xef8` | `0x1110` | **`+0x218`** |
| `__TEXT.__const` | `0x2b58` | `0x2cf8` | **`+0x1a0`** |
| `__DATA_CONST.__const` | `0x19f8` | `0x1b70` | **`+0x178`** |
| `__DATA_CONST.__auth_got` | `0x1090` | `0x1200` | **`+0x170`** |
| `__TEXT.__cstring` | `0x3c4` | `0x524` | **`+0x160`** |
| `__TEXT.__constg_swiftt` | `0xa5c` | `0xb48` | **`+0xec`** |
| `__DATA_CONST.__got` | `0x7d8` | `0x8c0` | **`+0xe8`** |
| `__TEXT.__swift5_reflstr` | `0x6f4` | `0x7c4` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x960` | `0x9e4` | **`+0x84`** |
| `__DATA.__common` | `0x71` | `0xf1` | **`+0x80`** |
| `__DATA_CONST.__auth_ptr` | `0x828` | `0x8a8` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x390` | `0x3d8` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x118` | `0x14c` | **`+0x34`** |
| `__TEXT.__swift_as_entry` | `0x5c` | `0x90` | **`+0x34`** |
| `__TEXT.__swift_as_ret` | `0x80` | `0xac` | **`+0x2c`** |
| `__TEXT.__objc_methname` | `0x1ac` | `0x1c9` | **`+0x1d`** |
| `__DATA.__bss` | `0x2bb8` | `0x2ba8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x16c` | `0x174` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc4` | `0xcc` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `0x8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-4026.110.3.0.0
+4026.210.18.1.0

-  - /System/Library/PrivateFrameworks/IconServices.framework/IconServices
+  - /System/Library/PrivateFrameworks/FlowToolsSnippetService.framework/FlowToolsSnippetService

-  - /System/Library/PrivateFrameworks/_IconServices_SwiftUI.framework/_IconServices_SwiftUI

+  - /System/Library/PrivateFrameworks/iTunesCloud.framework/iTunesCloud

-  Functions: 1582
-  Symbols:   171
-  CStrings:  91
+  Functions: 1752
+  Symbols:   170
+  CStrings:  108
Symbols:
+ _OBJC_CLASS_$_ICPrivacyInfo
+ _swift_bridgeObjectRelease_n
+ _swift_retain_x9
- _OBJC_CLASS_$_ISIcon
- _OBJC_CLASS_$_ISImageDescriptor
- _swift_getAtKeyPath
- _swift_getObjCClassFromMetadata
CStrings:
+ "%{public}s could not open url: %{public}s; falling back to open intent"
+ "%{public}s error occurred while attempting to play music item: %{public}s, error: %{public}@"
+ "%{public}s found no open tool for %{public}s; the system asked for a launch of %{public}s"
+ "%{public}s no url for item: %{public}s; falling back to open intent"
+ "%{public}s opened %{public}s %{public}s"
+ "%{public}s opened url: %{public}s"
+ "%{public}s play intent error: %{public}s"
+ "%{public}s playing item: %{public}s"
+ "%{public}s received an unhandled outcome: %{public}s"
+ "%{public}s resolved nothing for %{public}s %{public}s"
+ "%{public}s resuming playback error: %{public}s"
+ "%{public}s unable to open item with no Siri entity type: %{public}s"
+ "%{public}s unknown status: %{public}s, treating as not playing"
+ "An error occurred, please try again later."
+ "MusicSnippetsUI/MusicItemCell.swift"
+ "Open the Apple Music app and review the privacy information to play."
+ "Subscribe to Apple Music to play."
+ "Unexpected explicit content treatment: "
+ "View.task @ MusicSnippetsUI/MusicItemCell.swift:"
+ "dot.radiowaves.left.and.right"
+ "preflightDisclosureRequiredForMusic"
+ "privacyAcknowledgementRequiredForMusic"
- "%{public}s failed to play/pause music item %{public}s: %{public}@"
- "%{public}s starting new playback of %{public}s"
- "Accessing Environment<%s>'s value outside of being installed on a View. This will always read the default value and will not update."
- "initWithBundleIdentifier:"
- "initWithSize:scale:"
```
