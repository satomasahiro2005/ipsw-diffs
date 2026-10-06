## UIKitCore

> `/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bcb194` | `0x1bcb43c` | **`+0x2a8`** |
| `__TEXT.__oslogstring` | `0x54b26` | `0x54c32` | **`+0x10c`** |
| `__DATA_CONST.__objc_selrefs` | `0x95c28` | `0x95c30` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x19fa40` | `0x19fa48` | **`+0x8`** |

### Other Changes

```diff

-9127.0.84.1.902
+9127.0.84.1.115

-  Functions: 181271
-  Symbols:   228738
-  CStrings:  33767
+  Functions: 181272
+  Symbols:   228739
+  CStrings:  33771
Symbols:
+ -[_UIKeyboardFocusAssistant _shouldCancelDeferralPolicyTask:forRunnableTaskWithResponder:needsFocus:isReentrant:]
Functions:
~ -[UIKeyboardSceneDelegate _setKeyWindowSceneInputViews:animationStyle:] : 3336 -> 3564
~ -[_UIKeyboardFocusAssistant performWhenReadyForResponder:needsFocus:precedence:reason:readyTask:meanwhileTask:] : 2716 -> 2796
+ -[_UIKeyboardFocusAssistant _shouldCancelDeferralPolicyTask:forRunnableTaskWithResponder:needsFocus:isReentrant:]
CStrings:
+ "Do not cancel deferralPolicyTask: running task for snapshotting (responder:%{public}@)"
+ "Set key window scene input views for snapshotting"
+ "_setKeyWindowSceneInputViews: preparing input views for TEW"
+ "_setKeyWindowSceneInputViews: preparing input views for keyboardWindow"
```
