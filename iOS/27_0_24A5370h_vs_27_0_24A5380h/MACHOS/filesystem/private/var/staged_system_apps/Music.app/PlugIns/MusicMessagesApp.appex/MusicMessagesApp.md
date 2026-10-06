## MusicMessagesApp

> `/private/var/staged_system_apps/Music.app/PlugIns/MusicMessagesApp.appex/MusicMessagesApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5087ec` | `0x50d0ac` | **`+0x48c0`** |
| `__DATA_CONST.__const` | `0x326a8` | `0x32ad8` | **`+0x430`** |
| `__DATA.__bss` | `0x29d90` | `0x2a1a0` | **`+0x410`** |
| `__TEXT.__swift5_typeref` | `0x1b83c` | `0x1bb60` | **`+0x324`** |
| `__TEXT.__const` | `0x2af60` | `0x2b1e0` | **`+0x280`** |
| `__DATA.__data` | `0x18d08` | `0x18e98` | **`+0x190`** |
| `__TEXT.__swift5_reflstr` | `0xd052` | `0xd1c2` | **`+0x170`** |
| `__TEXT.__constg_swiftt` | `0x12094` | `0x121a8` | **`+0x114`** |
| `__TEXT.__unwind_info` | `0x10cc8` | `0x10dc0` | **`+0xf8`** |
| `__TEXT.__swift5_fieldmd` | `0xe318` | `0xe3f0` | **`+0xd8`** |
| `__DATA.__objc_data` | `0x90d0` | `0x9190` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x13255` | `0x13305` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x9198` | `0x9248` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0xd940` | `0xd9e0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xe5a4` | `0xe624` | **`+0x80`** |
| `__DATA.__objc_const` | `0x178a0` | `0x17918` | **`+0x78`** |
| `__DATA.__common` | `0x45e0` | `0x4620` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x4654` | `0x468c` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x9ab0` | `0x9ae0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x2840` | `0x2870` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x4330` | `0x4358` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x4488` | `0x44a8` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x1628c` | `0x1626c` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x3a78` | `0x3a58` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x1904` | `0x1924` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x4d60` | `0x4d78` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3788` | `0x3798` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x943c` | `0x942c` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x1024` | `0x1030` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.100.69.0.0
+4026.100.73.0.0

-  Functions: 24364
-  Symbols:   1231
-  CStrings:  5696
+  Functions: 24445
+  Symbols:   1233
+  CStrings:  5709
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
