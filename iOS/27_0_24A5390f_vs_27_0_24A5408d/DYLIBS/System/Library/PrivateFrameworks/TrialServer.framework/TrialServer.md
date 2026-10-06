## TrialServer

> `/System/Library/PrivateFrameworks/TrialServer.framework/TrialServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x151768` | `0x1518cc` | **`+0x164`** |
| `__TEXT.__oslogstring` | `0x1de95` | `0x1def5` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x7ee8` | `0x7f28` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x4378` | `0x43a8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xc7b4` | `0xc7ac` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-508.0.0.0.0
+511.0.0.0.0

-  CStrings:  4226
+  CStrings:  4227
Symbols:
+ +[TRITaskUtils prevTelemetryFieldsFromActivationEventDatabase:deactivatedRecord:]
- +[TRIDeactivateTreatmentTask prevTelemetryFieldsFromActivationEventDatabase:deactivatedRecord:]
CStrings:
+ "Aug  4 2026"
+ "Failed to log deactivation post-launch event for outgoing treatment %@ of experiment %{public}@"
+ "TrialXP-511"
- "Jul 10 2026"
- "TrialXP-508"
```
