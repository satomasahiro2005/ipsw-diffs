## CoreRoutineDiagnostics

> `/System/Library/PrivateFrameworks/CoreRoutineDiagnostics.framework/CoreRoutineDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe808` | `0xe910` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0x1b2c` | `0x1b79` | **`+0x4d`** |
| `__TEXT.__const` | `0x168` | `0x170` | **`+0x8`** |

### Other Changes

```diff

-1117.0.0.0.0
+1119.0.0.0.0

-  CStrings:  359
+  CStrings:  360
Functions:
~ -[RTTransactionManager endProfilingForTransaction:] : 592 -> 856
CStrings:
+ "Profiling completed for %{public}@, durationMs, %.3f, identifier, %{public}@"
```
