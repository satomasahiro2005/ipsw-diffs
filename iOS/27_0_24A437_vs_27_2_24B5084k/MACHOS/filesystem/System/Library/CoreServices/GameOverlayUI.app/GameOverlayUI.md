## GameOverlayUI

> `/System/Library/CoreServices/GameOverlayUI.app/GameOverlayUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf55fc` | `0xf5e60` | **`+0x864`** |
| `__TEXT.__cstring` | `0xe79` | `0xfa9` | **`+0x130`** |
| `__DATA_CONST.__const` | `0x50c0` | `0x5188` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0x1afc` | `0x1b4c` | **`+0x50`** |
| `__DATA.__common` | `0x168` | `0x188` | **`+0x20`** |
| `__DATA.__data` | `0x6b70` | `0x6b80` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1950e` | `0x1951e` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2c60` | `0x2c70` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x40a8` | `0x40b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3.0.41.2.1
+3.1.12.0.0

-  Functions: 3709
+  Functions: 3721

-  CStrings:  919
+  CStrings:  924
Symbols:
+ _$s7SwiftUI15ModifiedContentVA2A31AccessibilityAttachmentModifierVRs_rlE17accessibilityHintyACyxAEGqd__SyRd__lF
- _$s12GameStoreKit0abC16LocalizedStringsO15GAME_MODE_TITLESSyFZ
CStrings:
+ "APPLE_GAMES_BUTTON_AX_HINT"
+ "APPLE_GAMES_BUTTON_TITLE"
+ "Accessibility hint for the button in the overlay top bar that opens the Apple Games app"
+ "Accessibility label for the button in the overlay top bar that opens the Apple Games app"
+ "Open Apple Games"
```
