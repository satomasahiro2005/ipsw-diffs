## AccessibilitySettingsLoader

> `/System/Library/AccessibilityBundles/AccessibilitySettingsLoader.bundle/AccessibilitySettingsLoader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x113fc` | `0x11c64` | **`+0x868`** |
| `__TEXT.__oslogstring` | `0x651` | `0x8aa` | **`+0x259`** |
| `__AUTH_CONST.__cfstring` | `0x1500` | `0x1540` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xdb8` | `0xdf0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x11cc` | `0x1204` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x23d0` | `0x2400` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2036` | `0x2065` | **`+0x2f`** |
| `__AUTH_CONST.__const` | `0x5e0` | `0x600` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x528` | `0x548` | **`+0x20`** |
| `__TEXT.__const` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x730` | `0x738` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x38` | `0x3c` | **`+0x4`** |

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Functions: 399
-  Symbols:   1014
-  CStrings:  324
+  Functions: 405
+  Symbols:   1027
+  CStrings:  336
Symbols:
+ -[AccessibilityFloatingUIKeyboardHelper _handleFirstResponderDidChangeNotification:]
+ -[AccessibilityFloatingUIKeyboardHelper _startObservingTextInput]
+ -[AccessibilityFloatingUIKeyboardHelper _stopObservingTextInput]
+ -[AccessibilityFloatingUIKeyboardHelper observingTextInput]
+ -[AccessibilityFloatingUIKeyboardHelper setObservingTextInput:]
+ GCC_except_table292
+ GCC_except_table293
+ GCC_except_table305
+ GCC_except_table312
+ GCC_except_table324
+ GCC_except_table338
+ GCC_except_table343
+ GCC_except_table348
+ GCC_except_table359
+ GCC_except_table361
+ GCC_except_table369
+ GCC_except_table399
+ _LiveSpeechLogCommon
+ _NSStringFromClass
+ _OBJC_CLASS_$_UIWindow
+ _OBJC_IVAR_$_AccessibilityFloatingUIKeyboardHelper._observingTextInput
+ ___84-[AccessibilityFloatingUIKeyboardHelper _handleFirstResponderDidChangeNotification:]_block_invoke
+ ___block_descriptor_32_e34_v24?0"NSDictionary"8"NSError"16l
+ _objc_release_x27
+ _objc_release_x28
- GCC_except_table289
- GCC_except_table290
- GCC_except_table303
- GCC_except_table310
- GCC_except_table318
- GCC_except_table320
- GCC_except_table336
- GCC_except_table337
- GCC_except_table353
- GCC_except_table355
- GCC_except_table363
- GCC_except_table393
CStrings:
+ "FloatingUIKB: first responder changed responder=%{public}@ isTextInput=%d scene=%{public}@ activationState=%ld"
+ "FloatingUIKB: ignoring, scene is not foreground active"
+ "FloatingUIKB: listener state update, liveSpeechEnabled=%d observing=%d"
+ "FloatingUIKB: observing first responder changes in %{public}@"
+ "FloatingUIKB: reporting text input to AXUIServer, scene %{public}@"
+ "FloatingUIKB: skipping monitoring in %{public}@ (pid %d)"
+ "FloatingUIKB: starting monitoring in %{public}@ (pid %d)"
+ "FloatingUIKB: stopped observing first responder changes in %{public}@"
+ "FloatingUIKB: text input report failed: %{public}@"
+ "nil"
+ "sceneID"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
```
