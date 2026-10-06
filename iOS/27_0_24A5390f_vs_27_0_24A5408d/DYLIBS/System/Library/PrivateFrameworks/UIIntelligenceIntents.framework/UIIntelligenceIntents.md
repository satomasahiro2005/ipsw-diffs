## UIIntelligenceIntents

> `/System/Library/PrivateFrameworks/UIIntelligenceIntents.framework/UIIntelligenceIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x30f8` | `0x43d8` | **`+0x12e0`** |
| `__TEXT.__text` | `0x2bce4` | `0x2cf04` | **`+0x1220`** |
| `__TEXT.__oslogstring` | `0x6aa` | `0x9ba` | **`+0x310`** |
| `__AUTH_CONST.__const` | `0x1470` | `0x13b0` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x13a5` | `0x1435` | **`+0x90`** |
| `__TEXT.__const` | `0x3b88` | `0x3bb8` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0xb0` | `0x80` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x600` | `0x628` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x82e` | `0x84e` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x9d8` | `0x9f0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x75c` | `0x774` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xe80` | `0xe68` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x764` | `0x774` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x1ba4` | `0x1bac` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x158` | `0x154` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0xbc` | `0xb8` | **`-0x4`** |

### Other Changes

```diff

-9127.0.78.0.0
+9127.0.84.0.0

-  Functions: 1075
-  Symbols:   680
-  CStrings:  133
+  Functions: 1072
+  Symbols:   683
+  CStrings:  141
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ ___swift_closure_destructor.5Tm
+ ___swift_memcpy56_8
+ _swift_retain_x25
+ _swift_unknownObjectRelease_n
- _swift_release_x22
- _swift_retain_x28
CStrings:
+ "Bounding frame of the target text field (scene-relative, points). Formatted as a CGRect string. When provided with Target Window Identifier, the intent focuses that field before presenting the result."
+ "Editing context request failed (hasTarget=%{bool,public}d): %{public}s"
+ "No editing context from %{public}s: isUITextView=%{bool,public}d, reconstruction=%{bool,public}d"
+ "Partial target (targetFrame=%{bool,public}d targetWindowIdentifier=%{bool,public}d) — both must be set for a valid target."
+ "Reconstruction: %{public}s returned neither attributed nor plain text"
+ "Reconstruction: %{public}s returned no document text range"
+ "Reconstruction: document (%{public}ld units) exceeds cap; truncating read to %{public}ld"
+ "Resolved text input %{public}s (viaTarget=%{bool,public}d)"
+ "Text-input reconstruction returned nil for %{public}s; falling back to coordinator/delegate paths"
+ "findTextInput missed target; falling back to %{public}s"
+ "resolved via target frame: %{public}s frame=%{public}s window=%{public}s"
+ "text-input reconstruction: selection not located in full document; falling back to caret"
- "Found editable range %{public}s via coordinator (document length: %{public}ld)"
- "Partial target (targetFrame=%{bool,public}d targetWindowIdentifier=%{bool,public}d) — both must be set"
- "editableRangeForResponder(_:)"
- "requestEditingContext(target:)"
```
