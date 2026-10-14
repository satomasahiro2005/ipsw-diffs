## MusicSnippetsUI

> `/System/Library/Snippets/UIPlugins/MusicSnippetsUI.bundle/MusicSnippetsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4559c` | `0x4f7cc` | **`+0xa230`** |
| `__TEXT.__eh_frame` | `0x1fb4` | `0x259c` | **`+0x5e8`** |
| `__TEXT.__swift5_typeref` | `0x8be4` | `0x908a` | **`+0x4a6`** |
| `__DATA.__data` | `0x24a8` | `0x28f0` | **`+0x448`** |
| `__TEXT.__const` | `0x2c98` | `0x2fc8` | **`+0x330`** |
| `__TEXT.__oslogstring` | `0xb88` | `0xea8` | **`+0x320`** |
| `__TEXT.__unwind_info` | `0x1128` | `0x1368` | **`+0x240`** |
| `__TEXT.__swift5_reflstr` | `0x804` | `0x9d4` | **`+0x1d0`** |
| `__TEXT.__swift5_fieldmd` | `0xa20` | `0xba8` | **`+0x188`** |
| `__DATA.__bss` | `0x2b98` | `0x2d18` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x1cc0` | `0x1e18` | **`+0x158`** |
| `__TEXT.__auth_stubs` | `0x2530` | `0x2680` | **`+0x150`** |
| `__DATA_CONST.__got` | `0x910` | `0xa58` | **`+0x148`** |
| `__TEXT.__constg_swiftt` | `0xb24` | `0xc38` | **`+0x114`** |
| `__DATA_CONST.__auth_got` | `0x12a0` | `0x1348` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x3f8` | `0x458` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x8f8` | `0x948` | **`+0x50`** |
| `__TEXT.__cstring` | `0x584` | `0x5d4` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x14c` | `0x190` | **`+0x44`** |
| `__TEXT.__swift5_assocty` | `0x228` | `0x258` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0xac` | `0xd0` | **`+0x24`** |
| `__TEXT.__swift_as_entry` | `0x90` | `0xa8` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xcc` | `0xe0` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x178` | `0x184` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-4026.200.27.0.0
+4026.210.2.0.0

-  Functions: 1780
-  Symbols:   170
-  CStrings:  111
+  Functions: 1948
+  Symbols:   172
+  CStrings:  121
Symbols:
+ _objc_release_x27
+ _swift_willThrow
CStrings:
+ "%{public}s Failed to library map item with ID = \"%{public}s\"; using the unmapped item. %{public}@."
+ "%{public}s Library mapped item with ID = \"%{public}s\"; hasLibraryID = %{bool,public}d."
+ "%{public}s Returning playback mode %{public}s for item: %{public}s."
+ "%{public}s error occurred while attempting to preview song: %{public}s, error: %{public}@"
+ "%{public}s unable to determine playability of item: %{public}s, falling back to subscription status. error: %{public}@"
+ "%{public}s unable to determine subscription status, hiding playback. error: %{public}@"
+ "%{public}s unable to preview song: %{public}s"
+ "%{public}s unknown UserInterfaceIdiom: %s, using default"
+ "%{public}s unknown playability status: %{public}s, hiding playback"
+ "View.task @ MusicSnippetsUI/PlayPauseButton.swift:"
+ "View.task @ MusicSnippetsUI/PlayPreviewButton.swift:"
- "Subscribe to Apple Music to play."
```
