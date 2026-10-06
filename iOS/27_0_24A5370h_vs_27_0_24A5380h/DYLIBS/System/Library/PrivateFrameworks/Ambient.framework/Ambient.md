## Ambient

> `/System/Library/PrivateFrameworks/Ambient.framework/Ambient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cb0` | `0x5d2c` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x5ab` | `0x5f2` | **`+0x47`** |
| `__TEXT.__unwind_info` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xd4` | `0xd8` | **`+0x4`** |

### Other Changes

```diff

-104.0.0.0.0
+107.0.0.0.0

-  Functions: 212
+  Functions: 213

-  CStrings:  109
+  CStrings:  110
Functions:
~ ___63-[AMAmbientIlluminationTrigger initWithBrightnessSystemClient:]_block_invoke : 300 -> 364
~ ___63-[AMAmbientIlluminationTrigger initWithBrightnessSystemClient:]_block_invoke_2 : 56 -> 16
~ -[AMAmbientIlluminationTrigger initWithBrightnessSystemClient:] : 328 -> 348
+ ___63-[AMAmbientIlluminationTrigger initWithBrightnessSystemClient:]_block_invoke.cold.1
CStrings:
+ "Ignoring invalid trustedLux from BrightnessSystemClient: %{public}0.4f"
```
