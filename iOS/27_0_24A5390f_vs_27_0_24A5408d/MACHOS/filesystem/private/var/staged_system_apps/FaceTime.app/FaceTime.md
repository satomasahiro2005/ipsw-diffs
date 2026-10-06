## FaceTime

> `/private/var/staged_system_apps/FaceTime.app/FaceTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc56b8` | `0xc54b8` | **`-0x200`** |
| `__DATA.__bss` | `0x20b0` | `0x21b0` | **`+0x100`** |
| `__TEXT.__const` | `0x3304` | `0x3394` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x10c3d` | `0x10cbd` | **`+0x80`** |
| `__DATA.__data` | `0x33d0` | `0x3380` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x40a8` | `0x40e8` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xaca0` | `0xacc0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x1380` | `0x1360` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x1548` | `0x1564` | **`+0x1c`** |
| `__TEXT.__gcc_except_tab` | `0x3c8` | `0x3ac` | **`-0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0xf44` | `0xf60` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x1bde` | `0x1bc4` | **`-0x1a`** |
| `__DATA.__objc_selrefs` | `0x3d88` | `0x3da0` | **`+0x18`** |
| `__DATA.__objc_const` | `0x9490` | `0x9480` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x898` | `0x8a8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2fc0` | `0x2fd0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xfb2` | `0xfa2` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2e40` | `0x2e50` | **`+0x10`** |
| `__DATA.__objc_data` | `0x2878` | `0x2870` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x17f0` | `0x17f8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5c14` | `0x5c1c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x11c` | `0x120` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3068.100.3.0.0
+3072.100.1.2.2

-  Functions: 3678
-  Symbols:   1494
-  CStrings:  3766
+  Functions: 3684
+  Symbols:   1497
+  CStrings:  3769
Symbols:
+ _$s15ConversationKit34ButtonsStackViewControllerDelegateP07regularcE0So6UIViewCSgvMTq
+ _$s15ConversationKit34ButtonsStackViewControllerDelegateP07regularcE0So6UIViewCSgvgTq
+ _$s15ConversationKit34ButtonsStackViewControllerDelegateP07regularcE0So6UIViewCSgvsTq
+ _$s15ConversationKit8FeaturesC40isFaceTimeLandingPageThreeColumnsEnabledSbvg
- _$s15ConversationKit26ButtonsStackViewControllerCMn
CStrings:
+ "T@\"UIViewController\",&,V_buttonViewController"
+ "callControlsPlacement"
+ "canEnableThumperCalling"
+ "regularButtonsView"
+ "setButtonViewController:"
+ "setNavigationBarHidden:animated:"
+ "setRightBarButtonItems:"
+ "setSharesBackground:"
- "buttonsViewController"
- "isFrontFacingCheck"
- "readableContentGuide"
- "supportsThumperCalling"
- "updateVideoLayers"
```
