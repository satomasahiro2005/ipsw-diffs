## MusicScriptUpdateService

> `/private/var/staged_system_apps/Music.app/Frameworks/MusicApplication.framework/XPCServices/MusicScriptUpdateService.xpc/MusicScriptUpdateService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e8518` | `0x4ecd0c` | **`+0x47f4`** |
| `__DATA_CONST.__const` | `0x31528` | `0x31958` | **`+0x430`** |
| `__DATA.__bss` | `0x29060` | `0x29470` | **`+0x410`** |
| `__TEXT.__swift5_typeref` | `0x1acbc` | `0x1afe0` | **`+0x324`** |
| `__TEXT.__const` | `0x29d40` | `0x29fc0` | **`+0x280`** |
| `__DATA.__data` | `0x17a28` | `0x17bb8` | **`+0x190`** |
| `__TEXT.__swift5_reflstr` | `0xc562` | `0xc6d2` | **`+0x170`** |
| `__TEXT.__constg_swiftt` | `0x10fac` | `0x110c0` | **`+0x114`** |
| `__TEXT.__unwind_info` | `0x10788` | `0x10878` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0xdc60` | `0xdd38` | **`+0xd8`** |
| `__DATA.__objc_data` | `0x81d8` | `0x8298` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x90d8` | `0x9188` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0xce60` | `0xcf00` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xdc24` | `0xdca4` | **`+0x80`** |
| `__DATA.__objc_const` | `0x161d0` | `0x16248` | **`+0x78`** |
| `__TEXT.__objc_methname` | `0x10f45` | `0x10fb5` | **`+0x70`** |
| `__DATA.__common` | `0x44a0` | `0x44e0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3d64` | `0x3d9c` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x98c0` | `0x98f0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x26d8` | `0x2708` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x3fc8` | `0x3ff0` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x3fc8` | `0x3fe8` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x162d4` | `0x162b4` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x2db8` | `0x2d98` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x1898` | `0x18b8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x4c68` | `0x4c80` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3618` | `0x3628` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x9010` | `0x9000` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0xfc0` | `0xfcc` | **`+0xc`** |

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

-  Functions: 23810
-  Symbols:   1169
-  CStrings:  5337
+  Functions: 23862
+  Symbols:   1171
+  CStrings:  5350
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
