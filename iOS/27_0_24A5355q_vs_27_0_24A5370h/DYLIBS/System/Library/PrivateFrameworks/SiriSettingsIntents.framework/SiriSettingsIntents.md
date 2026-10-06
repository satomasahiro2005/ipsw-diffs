## SiriSettingsIntents

> `/System/Library/PrivateFrameworks/SiriSettingsIntents.framework/SiriSettingsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xfb4` | `0xfa4` | **`-0x10`** |
| `__TEXT.__text` | `0x2c5910` | `0x2c5900` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x4610` | `0x4620` | **`+0x10`** |

### Other Changes

```diff

-3600.29.3.1.1
+3600.35.2.0.0
Functions:
~ sub_2a17cf3d4 -> sub_2a2d723d4 : 468 -> 460
~ sub_2a185b99c -> sub_2a2dfe994 : 404 -> 428
~ sub_2a191ad40 -> sub_2a2ebdd50 : 472 -> 484
~ sub_2a197c8e8 -> sub_2a2f1f904 : 460 -> 456
~ sub_2a19b4630 -> sub_2a2f57648 : 464 -> 460
~ sub_2a19cf730 -> sub_2a2f72744 : 496 -> 484
~ sub_2a19cfab8 -> sub_2a2f72ac0 : 480 -> 484
~ sub_2a1a00fc0 -> sub_2a2fa3fcc : 500 -> 476
~ sub_2a1a013f4 -> sub_2a2fa43e8 : 480 -> 488
~ sub_2a1a01744 -> sub_2a2fa4740 : 492 -> 484
~ sub_2a1a2cdf4 -> sub_2a2fcfde8 : 468 -> 464
CStrings:
+ "Confirmation Check: Checking if utterance is rewritten %{bool}d"
- "Confirmation Check: Checking if utterance is rewrittern %{bool}d"
```
