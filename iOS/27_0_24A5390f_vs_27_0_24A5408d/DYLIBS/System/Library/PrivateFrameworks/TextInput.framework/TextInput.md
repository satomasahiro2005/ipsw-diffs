## TextInput

> `/System/Library/PrivateFrameworks/TextInput.framework/TextInput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80850` | `0x80960` | **`+0x110`** |
| `__AUTH_CONST.__objc_const` | `0x11b70` | `0x11bd0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xb600` | `0xb660` | **`+0x60`** |
| `__TEXT.__cstring` | `0x495e6` | `0x49636` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x255ce0` | `0x255d20` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x56a0` | `0x56c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2490` | `0x24a0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x20a0` | `0x20b0` | **`+0x10`** |

### Other Changes

```diff

-3562.0.0.0.0
+3567.0.0.0.0

-  Functions: 4007
-  Symbols:   7649
-  CStrings:  76802
+  Functions: 4011
+  Symbols:   7655
+  CStrings:  76804
Symbols:
+ -[TIPreferencesController setShouldSplitInDefaultContext:]
+ -[TIPreferencesController setShouldSplitInSplitPreferringContext:]
+ -[TIPreferencesController shouldSplitInDefaultContext]
+ -[TIPreferencesController shouldSplitInSplitPreferringContext]
+ _TIKeyboardShouldSplitInDefaultContextPreference
+ _TIKeyboardShouldSplitInSplitPreferringContextPreference
CStrings:
+ "KeyboardShouldSplitInDefaultContext"
+ "KeyboardShouldSplitInSplitPreferringContext"
```
