## VoiceControlSettings

> `/System/Library/PreferenceBundles/VoiceControlSettings.bundle/VoiceControlSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16614` | `0x16554` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x17d5` | `0x1805` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x3fdb` | `0x3fb6` | **`-0x25`** |
| `__DATA_CONST.__cfstring` | `0x16e0` | `0x16c0` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x11f4` | `0x11dc` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x580` | `0x588` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5a8` | `0x5a0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-179.0.0.0.0
+182.0.0.0.0

-  Functions: 485
-  Symbols:   375
-  CStrings:  1015
+  Functions: 483
+  Symbols:   376
+  CStrings:  1016
Symbols:
+ _OBJC_CLASS_$_CACMessageTracerUtilities
CStrings:
+ "PREFER_BLUETOOTH_HEADSET_FOOTER"
+ "PreferBluetoothLearnMore.BluettoothMic.Header"
+ "PreferBluetoothLearnMore.BluettoothMic.Item1"
+ "sendCoreAnalyticsForPreferBluetoothToggled:"
+ "setShowUserHints:"
+ "sharedCACMessageTracerUtilities"
+ "showUserHints"
- "PREFER_BLUETOOTH_HEADSET_FOOTER_IPAD"
- "PREFER_BLUETOOTH_HEADSET_FOOTER_IPHONE"
- "setUserHintsFeatures:"
- "setUserHintsForCommandSuggestionsEnabled:specifier:"
- "setUserHintsForNextStepSuggestionsEnabled:specifier:"
- "userHintsFeatures"
```
