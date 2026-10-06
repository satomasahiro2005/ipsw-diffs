## SiriPlaybackControlSupport

> `/System/Library/PrivateFrameworks/SiriPlaybackControlSupport.framework/SiriPlaybackControlSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8394c` | `0x83730` | **`-0x21c`** |
| `__TEXT.__cstring` | `0x2727` | `0x2697` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x603c` | `0x5fac` | **`-0x90`** |
| `__TEXT.__unwind_info` | `0x1e90` | `0x1e80` | **`-0x10`** |
| `__AUTH_CONST.__const` | `0x80d0` | `0x80c8` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1dc8` | `0x1dc0` | **`-0x8`** |

### Other Changes

```diff

-3600.26.5.0.0
+3600.26.17.0.0

-  Functions: 4284
-  Symbols:   1116
-  CStrings:  695
+  Functions: 4277
+  Symbols:   1115
+  CStrings:  691
Symbols:
+ ___swift_closure_destructor.202Tm
- _OUTLINED_FUNCTION_177
- ___swift_closure_destructor.203Tm
CStrings:
- "FeatureFlagProvider#shouldSuppressSnippetIfNeeded skipping on xr"
- "FeatureFlagProvider#shouldSuppressSnippetIfNeeded: %{bool}d"
- "PlaybackControlsCommandProviding#shouldSuppressSnippetIfNeeded default implementation should not be used"
- "suppress_snippet"
```
