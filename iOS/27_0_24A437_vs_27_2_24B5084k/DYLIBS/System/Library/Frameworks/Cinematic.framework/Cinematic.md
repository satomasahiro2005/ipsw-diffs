## Cinematic

> `/System/Library/Frameworks/Cinematic.framework/Cinematic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20dac` | `0x21064` | **`+0x2b8`** |
| `__TEXT.__oslogstring` | `0x1390` | `0x1447` | **`+0xb7`** |
| `__AUTH_CONST.__cfstring` | `0x1e0` | `0x240` | **`+0x60`** |
| `__TEXT.__cstring` | `0x5c1` | `0x5f1` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xab0` | `0xad8` | **`+0x28`** |

### Other Changes

```diff

-560.22.2.0.0
+560.40.3.0.0

-  Functions: 1020
-  Symbols:   1243
-  CStrings:  161
+  Functions: 1023
+  Symbols:   1244
+  CStrings:  168
Symbols:
+ -[CNAssetInfo initWithTracks:cinematicAssetInfo:]
+ ___block_descriptor_72_e8_32s40bs48r_e5_v8?0lr48l8s40l8s32l8
- -[CNAssetInfo initWithTracks:]
CStrings:
+ "Calling download on asset that does not need downloading. Returning self"
+ "Calling download on asset that is not supported (%@)."
+ "DisparitySettings returned nil"
+ "_loadFromAsset: Error %@"
+ "code: %li"
+ "unsupported asset"
+ "unsupported device"
```
