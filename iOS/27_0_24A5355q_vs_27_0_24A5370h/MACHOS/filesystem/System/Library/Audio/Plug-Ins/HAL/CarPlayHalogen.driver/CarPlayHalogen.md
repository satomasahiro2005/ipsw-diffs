## CarPlayHalogen

> `/System/Library/Audio/Plug-Ins/HAL/CarPlayHalogen.driver/CarPlayHalogen`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7210` | `0x7478` | **`+0x268`** |
| `__TEXT.__cstring` | `0x1235` | `0x132a` | **`+0xf5`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-980.58.1.11.1
+980.63.2.0.0

-  Functions: 153
+  Functions: 157

-  CStrings:  106
+  CStrings:  111
CStrings:
+ "HALCarAudio%sStream-%@ Started\n"
+ "HALCarAudio%sStream-%@ linked to audioSink %{ptr} \n"
+ "HALCarAudio%sStream-%@ linked to audioSource %{ptr}\n"
+ "HALCarAudioDevice-%@ Stopped HAL Audio; error %#m\n"
+ "HALCarAudioDevice-%@: startIO completed with error %#m \n"
```
