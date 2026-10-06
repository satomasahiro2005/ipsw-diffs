## DiagnosticExtensionsDaemon

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/DiagnosticExtensionsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x9828` | `0x98e8` | **`+0xc0`** |
| `__TEXT.__text` | `0x75d10` | `0x75d0c` | **`-0x4`** |

### Other Changes

```diff

-222.0.0.0.0
+223.0.0.0.0

-  CStrings:  1789
+  CStrings:  1790
CStrings:
+ "could not match de directory [%{public}@] to known extensions. This is only an issue if file was triggered by DE flow."
+ "could not match de directory url [%{public}@] to known extensions. This is only an issue if file was triggered by DE flow"
- "could not match de directory [%{public}@] to known extensions"
```
