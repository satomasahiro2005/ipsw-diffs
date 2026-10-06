## MediaControl

> `/System/Library/PrivateFrameworks/MediaControl.framework/MediaControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x185e` | `0x196e` | **`+0x110`** |
| `__TEXT.__text` | `0xba8bc` | `0xba804` | **`-0xb8`** |
| `__TEXT.__const` | `0x17650` | `0x17680` | **`+0x30`** |

### Other Changes

```diff

-4026.110.75.1.0
+4026.100.79.0.0

-  Functions: 8595
+  Functions: 8600

-  CStrings:  290
+  CStrings:  292
CStrings:
+ "[%{public}s] updatePendingItems - value: %{public}s"
+ "[%{public}s] updateSnapshot - value: %{public}s"
+ "[%{public}s] updateSnapshot - value: nil"
+ "[%{public}s]<%{public}s> beginInteractionWithControl<%{public}s> - control: %{public}s"
+ "[%{public}s]<%{public}s> beginInteractionWithControl<%{public}s> - control: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> connect - failed with error: %{public}@."
+ "[%{public}s]<%{public}s> deinit"
+ "[%{public}s]<%{public}s> endContinuousInteraction<%{public}s> missing finalizer. Was this interaction ended multiple times?"
+ "[%{public}s]<%{public}s> endContinuousInteractionWithControl<%{public}s> - control: %{public}s"
+ "[%{public}s]<%{public}s> endContinuousInteractionWithControl<%{public}s> - control: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> flushPendingVolumeControls - failed with error: %{public}@"
+ "[%{public}s]<%{public}s> handleAbsoluteVolumeControl - control: %{public}s value adjusted from: %{public}f to: %{public}f"
+ "[%{public}s]<%{public}s> handleAbsoluteVolumeControl - deferred control: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> handleInteractWithControlResult - deferred control: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> handleInteractWithControlResult - processed control: %{public}s, dispatch pending control: %{public}s"
+ "[%{public}s]<%{public}s> init"
+ "[%{public}s]<%{public}s> interactWithAction - action: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> interactWithControl - control: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> interactWithItem - item: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> interactWithSession - session: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> updateServiceExpandedSessionIdentifiers - value: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> updateServiceRoutingMode - value: %{public}s failed with error: %{public}@"
+ "[%{public}s]<%{public}s> updateServiceUIPresented - value: %{bool,public}d failed with error: %{public}@"
- "[%s] updatePendingItems - value: %{public}s"
- "[%s] updateSnapshot - value: %s"
- "[%s] updateSnapshot - value: nil"
- "[%s]<%s> interactWithControl - control: %{public}s failed with error: %{public}@"
- "[%s]<%s> updateServiceRoutingMode - value: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> beginInteractionWithControl<%{public}s> - control: %{public}s"
- "[%s]<%{public}s> beginInteractionWithControl<%{public}s> - control: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> connect - failed with error: %{public}@."
- "[%s]<%{public}s> endContinuousInteraction<%{public}s> missing finalizer. Was this interaction ended multiple times?"
- "[%s]<%{public}s> endContinuousInteractionWithControl<%{public}s> - control: %{public}s"
- "[%s]<%{public}s> endContinuousInteractionWithControl<%{public}s> - control: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> flushPendingVolumeControls - failed with error: %{public}@"
- "[%s]<%{public}s> handleAbsoluteVolumeControl - control: %{public}s value adjusted from: %{public}f to: %{public}f"
- "[%s]<%{public}s> handleAbsoluteVolumeControl - deferred control: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> handleInteractWithControlResult - deferred control: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> handleInteractWithControlResult - processed control: %{public}s, dispatch pending control: %{public}s"
- "[%s]<%{public}s> interactWithAction - action: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> interactWithItem - item: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> interactWithSession - session: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> updateServiceExpandedSessionIdentifiers - value: %{public}s failed with error: %{public}@"
- "[%s]<%{public}s> updateServiceUIPresented - value: %{bool,public}d failed with error: %{public}@"
```
