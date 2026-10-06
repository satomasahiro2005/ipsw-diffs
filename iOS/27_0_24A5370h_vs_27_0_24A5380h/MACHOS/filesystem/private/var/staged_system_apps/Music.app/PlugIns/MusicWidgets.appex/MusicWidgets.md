## MusicWidgets

> `/private/var/staged_system_apps/Music.app/PlugIns/MusicWidgets.appex/MusicWidgets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x593b34` | `0x598668` | **`+0x4b34`** |
| `__DATA_CONST.__const` | `0x33278` | `0x336a8` | **`+0x430`** |
| `__DATA.__bss` | `0x2f600` | `0x2fa10` | **`+0x410`** |
| `__TEXT.__swift5_typeref` | `0x2bd1c` | `0x2c040` | **`+0x324`** |
| `__TEXT.__const` | `0x30490` | `0x30710` | **`+0x280`** |
| `__DATA.__data` | `0x1c228` | `0x1c3b8` | **`+0x190`** |
| `__TEXT.__swift5_reflstr` | `0xd362` | `0xd4d2` | **`+0x170`** |
| `__TEXT.__constg_swiftt` | `0x127ec` | `0x12900` | **`+0x114`** |
| `__TEXT.__unwind_info` | `0x12620` | `0x12718` | **`+0xf8`** |
| `__TEXT.__swift5_fieldmd` | `0xeff0` | `0xf0c8` | **`+0xd8`** |
| `__DATA.__objc_data` | `0x81e8` | `0x82a8` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0xa018` | `0xa0c8` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0xce00` | `0xcea0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xec24` | `0xeca4` | **`+0x80`** |
| `__DATA.__objc_const` | `0x166c0` | `0x16738` | **`+0x78`** |
| `__TEXT.__objc_methname` | `0x11015` | `0x11085` | **`+0x70`** |
| `__DATA.__common` | `0x4820` | `0x4860` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3c8c` | `0x3cc4` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x2dd8` | `0x2e08` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x4e60` | `0x4e88` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x3f78` | `0x3f98` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xa800` | `0xa820` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x19cb4` | `0x19c94` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x2d48` | `0x2d28` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x1bc4` | `0x1be4` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x5408` | `0x5418` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3a10` | `0x3a20` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x9378` | `0x9368` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x1128` | `0x1134` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.100.69.0.0
+4026.100.73.0.0

-  Functions: 26001
-  Symbols:   1153
-  CStrings:  5512
+  Functions: 26081
+  Symbols:   1155
+  CStrings:  5525
Symbols:
+ _OBJC_CLASS_$_CAPortalLayer
+ _OBJC_CLASS_$_UIGlassEffect
CStrings:
+ "Attempted to present %{public}s, but needs to wait for the ongoing transition from %{public}s to %s to complete first"
+ "Intent id=%{public}s) — Queue contains no playable content"
+ "MusicCoreUI.LayerView"
+ "MusicCoreUI/LayerView.swift"
+ "NPAV_LAYOUT_DEBUG_OVERLAY"
+ "TransitionCoordinator %{public}s completed ongoing animations. Now attempting to re-present %{public}s from %{public}s"
+ "_hasMaterial"
+ "microphoneConstraints"
+ "microphoneGlassCompositingView"
+ "microphoneView"
+ "music.nullOverflow"
+ "setInteractive:"
+ "setMatchesOpacity:"
+ "setMatchesPosition:"
+ "setMatchesTransform:"
+ "setSourceLayer:"
+ "visualStyle"
+ "╰ ❌ Intent id=%{public}s) — Could not playback, content unavailable"
- "Attempted to present %{public}s, but needs to wait for the ongoing transition %{public}s to complete first"
- "TransitionCoordinator %{public}s completed ongoing animations. Now attemptying to re-present %{public}s"
- "blurEffect"
- "packageView"
- "viewWillLayoutSubviews"
```
