## CoreMedia

> `/System/Library/Frameworks/CoreMedia.framework/CoreMedia`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20ad8c` | `0x20aecc` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x1c4c0` | `0x1c500` | **`+0x40`** |
| `__TEXT.__cstring` | `0x22b6a` | `0x22b9a` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x6cb4` | `0x6cd4` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xba28` | `0xba38` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x73b8` | `0x73c8` | **`+0x10`** |

### Other Changes

```diff

-3350.75.2.0.0
+3350.77.1.6.0

-  Functions: 14932
-  Symbols:   12500
-  CStrings:  6046
+  Functions: 14934
+  Symbols:   12504
+  CStrings:  6049
Symbols:
+ _connectionEstablisher_handleDeadServerConnection
+ _connectionEstablisher_removeAndDestroyClientInfoWhileLocked
+ _kFigReportingEventKey_MusicExperimentID
+ _kFigReportingEventKey_MusicTreatmentID
CStrings:
+ "<< FigXPC >> %s: Unexpected type '%{public}s' in server reply; connection %p %{public}s"
+ "<< FigXPC >> %s: xpc error in server reply; connection %p %{public}s: %{public}s"
+ "<unknown>"
+ "msc_experimentID"
+ "msc_treatmentID"
- "<< FigXPC >> %s: Unexpected type '%s' in server reply; connection %p %s"
- "<< FigXPC >> %s: xpc error in server reply; connection %p %s: %s"
```
