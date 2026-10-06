## FocusEngine

> `/System/Library/SubFrameworks/FocusEngine.framework/FocusEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30214` | `0x306f0` | **`+0x4dc`** |
| `__TEXT.__ustring` | `0x35c` | `0x414` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x6e80` | `0x6ee8` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x2860` | `0x28a0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3920` | `0x3950` | **`+0x30`** |
| `__TEXT.__cstring` | `0x3c70` | `0x3c9b` | **`+0x2b`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c60` | `0x1c88` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xd68` | `0xd80` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x448` | `0x454` | **`+0xc`** |

### Other Changes

```diff

-9127.0.66.1.105
+9127.0.71.1.102

-  Functions: 1221
-  Symbols:   2356
-  CStrings:  444
+  Functions: 1224
+  Symbols:   2362
+  CStrings:  447
Symbols:
+ -[_UIFocusGuideImpl startFocusUpdate]
+ -[_UIFocusGuideImpl stopFocusUpdate]
+ -[_UIFocusMapSnapshot addFocusGuideContainers:]
+ _OBJC_IVAR_$__UIFocusGuideImpl._focusUpdateCount
+ _OBJC_IVAR_$__UIFocusGuideImpl._retainedDelegate
+ _OBJC_IVAR_$__UIFocusMapSnapshot._activeFocusGuideImpls
CStrings:
+ "B"
+ "Unbalanced stopFocusUpdate call on %@"
+ "startFocusUpdate called on %@ with a nil delegate — the owning UIFocusGuide was deallocated"
+ "\xe2!"
- "\xd2!"
```
