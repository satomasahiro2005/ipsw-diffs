## SiriMessagesUI

> `/System/Library/PrivateFrameworks/SiriMessagesUI.framework/SiriMessagesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc80c8` | `0xc85ac` | **`+0x4e4`** |
| `__TEXT.__oslogstring` | `0x439a` | `0x446a` | **`+0xd0`** |
| `__AUTH_CONST.__auth_got` | `0x2280` | `0x22a8` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x27ac` | `0x27d4` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2b30` | `0x2b08` | **`-0x28`** |
| `__DATA.__data` | `0x3480` | `0x3470` | **`-0x10`** |
| `__TEXT.__const` | `0x7c54` | `0x7c44` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1d15` | `0x1d25` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1e1c` | `0x1e28` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x10f60` | `0x10f54` | **`-0xc`** |

### Other Changes

```diff

-3600.47.13.0.0
+3600.47.22.11.2

-  Functions: 4710
-  Symbols:   2114
-  CStrings:  387
+  Functions: 4711
+  Symbols:   2115
+  CStrings:  389
Symbols:
+ _OUTLINED_FUNCTION_170
+ _OUTLINED_FUNCTION_171
- _symbolic _____Sg_ABt 16IntelligenceFlow26PrescribedActionDescriptorV
CStrings:
+ "#AutoSendableCompactCarPlayButtonView .dismissed received sendOnDismissCommand=%s shouldAutoSend=true"
+ "#AutoSendableCompactCarPlayButtonView dismiss ignored: shouldAutoSend is false"
+ "#AutoSendableCompactCarPlayButtonView dispatching sendOnDismissCommand=%s via context.perform(aceCommand:)"
+ "#AutoSendableCompactCarPlayButtonView no sendOnDismissCommand to fire"
- "#AutoSendableCompactCarPlayButtonView fire PrescribedActionDescriptor on dismissal"
- "#AutoSendableCompactCarPlayButtonView no PrescribedActionDescriptor to fire"
```
