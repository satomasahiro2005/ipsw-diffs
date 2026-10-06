## ProxCardKit

> `/System/Library/PrivateFrameworks/ProxCardKit.framework/ProxCardKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e39c` | `0x1e684` | **`+0x2e8`** |
| `__AUTH_CONST.__cfstring` | `0x5c0` | `0x6a0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x74d` | `0x7f6` | **`+0xa9`** |
| `__DATA_CONST.__objc_selrefs` | `0x2008` | `0x2040` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x2df0` | `0x2e20` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x830` | `0x848` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x400` | `0x408` | **`+0x8`** |

### Other Changes

```diff

-2131.20.71.0.0
+2131.21.21.0.0

-  Functions: 728
-  Symbols:   1754
-  CStrings:  94
+  Functions: 733
+  Symbols:   1760
+  CStrings:  101
Symbols:
+ -[PRXPasscodeEntryView accessibilityActivate]
+ -[PRXPasscodeEntryView accessibilityAttributedValue]
+ -[PRXPasscodeEntryView accessibilityHint]
+ -[PRXPasscodeEntryView accessibilityValue]
+ _PRXPasscodeEntryLocalizedString
+ _UIAccessibilitySpeechAttributeSpellOut
CStrings:
+ "Empty"
+ "Enter a %ld-digit code"
+ "PASSCODE_ENTRY_ACCESSIBILITY_HINT"
+ "PASSCODE_ENTRY_ACCESSIBILITY_LABEL"
+ "PASSCODE_ENTRY_ACCESSIBILITY_VALUE_EMPTY"
+ "PRXPasscodeEntryView"
+ "Passcode"
```
