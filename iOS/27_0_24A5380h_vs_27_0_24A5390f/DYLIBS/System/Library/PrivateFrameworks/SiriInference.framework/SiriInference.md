## SiriInference

> `/System/Library/PrivateFrameworks/SiriInference.framework/SiriInference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30ae4c` | `0x30b19c` | **`+0x350`** |
| `__AUTH_CONST.__const` | `0x28090` | `0x28018` | **`-0x78`** |
| `__TEXT.__oslogstring` | `0x12fc0` | `0x12f60` | **`-0x60`** |
| `__TEXT.__swift5_reflstr` | `0x100db` | `0x1010b` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xffb4` | `0xffc0` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0xa6e0` | `0xa6d8` | **`-0x8`** |

### Other Changes

```diff

-3600.34.11.0.0
+3600.34.15.0.0

-  Functions: 19905
+  Functions: 19903

-  CStrings:  3179
+  CStrings:  3178
CStrings:
+ "ModelAppPredictor predict: all candidate apps excluded; no app available"
- "CommsAppResolutionTrainingLogEmitter: event: %@"
- "ModelAppPredictor predict should not have reached here due to %ld candidate apps, will skip experimentation trigger"
```
