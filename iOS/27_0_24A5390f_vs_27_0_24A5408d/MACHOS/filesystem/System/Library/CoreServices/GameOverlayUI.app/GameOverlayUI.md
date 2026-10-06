## GameOverlayUI

> `/System/Library/CoreServices/GameOverlayUI.app/GameOverlayUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf550c` | `0xf55e4` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0x4118` | `0x40a8` | **`-0x70`** |
| `__TEXT.__swift5_typeref` | `0x194a2` | `0x1950e` | **`+0x6c`** |
| `__TEXT.__cstring` | `0xed9` | `0xe79` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x5110` | `0x50c0` | **`-0x50`** |
| `__TEXT.__swift5_capture` | `0x1b28` | `0x1afc` | **`-0x2c`** |
| `__TEXT.__auth_stubs` | `0x4e30` | `0x4e10` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x2720` | `0x2710` | **`-0x10`** |
| `__TEXT.__const` | `0x7b74` | `0x7b84` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x34dd` | `0x34ed` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x21de` | `0x21ce` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2c70` | `0x2c60` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x20b0` | `0x20a4` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x1198` | `0x1190` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1420` | `0x1418` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3.0.35.0.0
+3.0.41.2.1

-  - /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices

-  Functions: 3710
-  Symbols:   2323
-  CStrings:  920
+  Functions: 3709
+  Symbols:   2319
+  CStrings:  919
Symbols:
+ _$s12GameStoreKit20OverlayLayoutMetricsO24overlayTabBarItemSpacing12CoreGraphics7CGFloatVvgZ
- _$s12GameStoreKit19LocalPlayerProviderCMn
- _$ss9_typeName_9qualifiedSSypXp_SbtF
- _OBJC_CLASS_$_AMSFeatureFlagITFE
- _swift_task_getMainExecutor
- _swift_task_isCurrentExecutor
CStrings:
+ "gc-access-point:"
+ "setAccessibilityIdentifier:"
- "GameOverlayUI/DefaultOverlayJetView.swift"
- "Incorrect actor executor assumption; Expected same executor as "
- "setMutableFeatureName:toValue:"
```
